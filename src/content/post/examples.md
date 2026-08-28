---
title: "格式文档"
publishDate: 2026-09-01
description: "演示该网站所支持的文本样式。"
draft: true
---

用于预览该网站支持的文本样式的演示文档。

## Frontmatter shape

```yaml
---
title: "文章标题"
publishDate: 2026-01-01
description: "用于卡片、社交预览和元标签的一句摘要。"
tags: [ tag-one, tag-two ]
# updatedDate: 2026-02-01      # 可选 - 更新日期
# draft: true                  # 不在构建显示的草稿
# coverImage:                  # 可选 - 文章封面在标题与正文之间出现
#   src: ./_assets/cover.png
#   alt: "Description for screen readers"
---
```

## 行内代码 & 强调

You can mix `inline code`, *italics*, **bold**, and ***both*** in the same line. ~~Strikethrough~~ works too. <ins>下划线文本</ins> <font color="red">红色文字</font>  

这是一个[Google](https://www.google.com "可选的浮现文本")链接。

[这是一段隐藏的注释]: # 

<p style="text-align:center">这段文字居中显示。</p>

>  A blockquote sits with a left rule, in italics, slightly muted.

## 分隔线

---

## 列表

1. a
2. b
3. c

- 1
- 2
- 3

## 表格

| Syntax      | Description |
| ----------- | ----------- |
| Header      | Title       |
| Paragraph   | Text        |

## 任务列表

- [x] Write the press release
- [ ] Update the website

## 图片

![background](./_assets/color-fields.jpg)

## 代码

```java
public class HelloWorld {
    public static void main(String[] args) {
        System.out.println("Hello, World!");
    }
}
```

```bash
sudo pacman -Syu
sudo pacman -S ffmpeg cargo git
```

## LaTeX

$$
\int_{-\infty}^{\infty} e^{-x^2}\,dx = \sqrt{\pi}
$$

## 脚注

Footnotes work via remark-gfm[^1]. They render at the bottom of the post and are linked back to the reference.

[^1]: Like this. Click the back-arrow to return to the citation.

## 自定义容器

Three styled containers ship for asides:

:::note
A neutral note. Use this for clarifying context.
:::

:::tip
Tips for the reader. Use sparingly.
:::

:::caution
Heads-up — something to watch for.
:::
