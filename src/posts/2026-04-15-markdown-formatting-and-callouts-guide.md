---
title: "Markdown formatting, callouts, and code blocks"
date: 2026-04-15
permalink: "/markdown-formatting-and-callouts-guide/"
layout: layouts/post.njk
tags: ["Coding", "Design"]
description: "Live showcase of every callout box, syntax-highlighted code block, spoiler, and typography element included in Eleventy Silicon."
---

Eleventy Silicon includes custom Markdown containers, automatic copy buttons on fenced code blocks, and collapsible spoilers without loading heavy client-side frameworks.

## Callout containers

::: info
Use `::: info` for background context or hardware specs that complement the main steps.
:::

::: caution
Use `::: caution` when readers should double-check pinouts, paths, or backups before proceeding.
:::

::: warning
Use `::: warning` for destructive actions like formatting drives or changing voltage levels.
:::

## Syntax highlighting with one-click copy

```python
def calculate_crc(data: bytes) -> int:
    crc = 0xFFFF
    for byte in data:
        crc ^= byte
    return crc
```

## Collapsible spoilers

<details class="spoiler-block">
<summary>Reveal benchmark notes</summary>

Pure static HTML + self-hosted WOFF2 fonts + AVIF/WebP image transforms deliver sub-50ms load times with zero third-party requests.

</details>
