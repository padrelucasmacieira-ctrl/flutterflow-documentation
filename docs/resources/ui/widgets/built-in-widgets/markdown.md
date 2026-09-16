---
slug: markdown
title: Markdown
description: Learn how to display and customize Markdown content in your FlutterFlow app.
tags: [Base Elements]
keywords: [Markdown, Widget, Formatted Text, Dynamic Content]
---

# Markdown

The **Markdown** widget renders formatted content written using [Markdown syntax](https://www.markdownguide.org/basic-syntax/). It supports content such as headings, emphasized text, lists, links, quotes, and code without requiring HTML.

Use this widget to display notes, documentation, forum posts, release notes, help content, or other formatted text in your app.

## Adding a Markdown Widget

1. Open the [Widget Palette](../../../../intro/ff-ui/widget-palette.md) and add the **Markdown** widget from **Base Elements**.
2. Select the widget and open the [Properties Panel](../../../../intro/ff-ui/builder.md#properties-panel).
3. Under **Data**, enter fixed Markdown content or set the value from a variable. Dynamic content is useful for displaying formatted text from a database, an API response, or generated app content.

For example, you can use Markdown to display a privacy policy:

```md
# Privacy Policy

**Last updated:** September 16, 2026

We use your information to provide and improve our services.

## Information we collect

- Account information
- App usage data

[Contact our privacy team](mailto:privacy@example.com)
```

<div style={{
    position: 'relative',
    paddingBottom: 'calc(56.67989417989418% + 41px)', // Keeps the aspect ratio and additional padding
    height: 0,
    width: '100%'}}>
    <iframe
        src="https://demo.arcade.software/PZ0RUIsNIpBhyLIXqVEz?embed&show_copy_link=true"
        title="Adding and configuring a Markdown widget"
        style={{
            position: 'absolute',
            top: 0,
            left: 0,
            width: '100%',
            height: '100%',
            colorScheme: 'light'
        }}
        frameborder="0"
        loading="lazy"
        webkitAllowFullScreen
        mozAllowFullScreen
        allowFullScreen
        allow="clipboard-write">
    </iframe>
</div>

## Customizing the Markdown Widget

### Making Content Selectable

Enable **Selectable** to allow users to select and copy text from the rendered Markdown content.

## Best Practices

- Use a consistent heading hierarchy to keep long content easy to scan.
- Test long and dynamic content on different screen sizes to prevent clipping or unexpected overflow.
- Review Markdown received from external sources before displaying it, especially links.
- Use descriptive link text and verify that links work on every target platform.
