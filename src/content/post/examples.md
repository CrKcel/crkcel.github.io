---
title: "格式文档"
publishDate: 2026-01-01
description: "演示该网站支持的文本样式。"
draft: true
---

预览网站支持的文本样式。

## 前置信息

```yaml
---
title: "文章标题"
publishDate: 2026-01-01
description: "用于卡片、社交预览和元标签的一句摘要。"
# tags: [ tag-one, tag-two ]
# updatedDate: 2026-02-01      # 可选 - 更新日期
# draft: true                  # 不在构建显示的草稿
# coverImage:                  # 可选 - 文章封面在标题与正文之间出现
#   src: ./_assets/cover.png
#   alt: "Description for screen readers"
---
```

## 文本

可以使用 *斜体*, **粗体**, ***粗斜体***, `行内代码`, ~~删除线~~, <ins>下划线</ins>, <font color="red">颜色</font> [链接](https://www.google.com "浮现文本") 等文字。

<p style="text-align:center">居中显示的文字。</p>

>  引用块文字。

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

渲染在文章底部, 通过 remark-gfm[^1] 实现。

[^1]: 点击后退箭头可以返回引用位置。

## 自定义容器

:::note
A neutral note. Use this for clarifying context.
:::

:::tip
Tips for the reader. Use sparingly.
:::

:::caution
Heads-up — something to watch for.
:::
