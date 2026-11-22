---
layout: layouts/base.njk
title: "Formatting Reference"
eleventyExcludeFromCollections: true
description: "Markdown formatting and callout reference."
noindex: true
---

# Formatting Reference

## Headings
Front matter handles the H1. Using H2 for main sections.

```markdown
## Step-by-Step Instructions
```

Example:

## Step-by-Step Instructions
Use a standard bullet '-' point list with bold text for the step title.

```markdown
- **Install the required packages:**
```

Example:

- **Install the required packages:**

## Tip Callout Box
Use the custom container syntax to generate an orange tip box.

```markdown
::: tip
Always create a backup of your configuration file before running the script.
:::
```

Example:

::: tip
Always create a backup of your configuration file before running the script.
:::

## Links

Creating a link is easy.

```markdown
[description](url)
```

Example:

[Link to this blog](https://example.com)

## Highlighting words

To highlight anything use backticks.

```markdown
Locate the `fastcgi_pass`
```

Example:

Locate the `fastcgi_pass`

## Blockquote

Quotes

```markdown
> "Everything proceeds mathematically... if someone could have a sufficient insight into the inner parts of things, he would be a prophet and would see the future in the present as in a mirror."
>
> &mdash; **Gottfried Wilhelm Leibniz**
```

Example:

> "Everything proceeds mathematically... if someone could have a sufficient insight into the inner parts of things, he would be a prophet and would see the future in the present as in a mirror."
>
> &mdash; **Gottfried Wilhelm Leibniz**

## Bold Text

```markdown
**Raport Repair**
```

Example:

**Raport Repair**

## Notification boxes

```markdown
::: info
Standard informational note. Useful for extra context or hardware specs without interrupting the main steps.
:::

::: caution
Semi-scary heads-up: double-check pinouts, backups, or target paths before running the next command.
:::

::: warning
Warning: wrong selection or voltage here can brick the device, overwrite live data, or cause downtime.
:::
```

Example:

::: info
Standard informational note. Useful for extra context or hardware specs without interrupting the main steps.
:::

::: caution
Semi-scary heads-up: double-check pinouts, backups, or target paths before running the next command.
:::

::: warning
Warning: wrong selection or voltage here can brick the device, overwrite live data, or cause downtime.
:::