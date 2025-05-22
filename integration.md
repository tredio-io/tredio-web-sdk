# Player Integration Documentation

This guide outlines the steps for integrating the Tredio Player into a webpage, along with guidance on how to configure and manage it.

## Overview
This document provides instructions for integrating the Tredio player into your web application. Depending on your application architecture, you can choose to insert the provided script into either:

- The `<head>` tag on all necessary pages for a multi-page application.
- The main `<head>` tag for a single-page application.

## Script for Integration
To integrate the Tredio player, use the following script:

```html
<script>
  (() => {
    var script = document.createElement("script");
    script.src = `https://player.tredio.io/tredio-dist2.js`;
    document.head.appendChild(script);
  })();
</script>
```
## 🎧 Demo Example
To see the Tredio audio player in action, check out our live demo:

👉 [Tredio Player Demo](https://footballco-demo.web.app)

You can use this demo to explore how the player looks and behaves when integrated into a web page. It’s a great reference to verify the script integration and playback functionality.

## Instructions

### For Multi-Page Applications
1. **Direct Integration:**
   - Open the HTML file for each page where the player will be displayed.
   - Locate the `<head>` tag in the HTML file.
   - Paste the provided script inside the `<head>` tag.

2. **Using WordPress Admin:**
   - If you're using WordPress, you can integrate the script through the admin panel.
   - Install a plugin that allows you to add scripts, such as **Insert Headers and Footers**.
   - Go to the plugin settings and paste the provided script into the appropriate section for header scripts.

### For Single-Page Applications
1. Open the main HTML file (usually `index.html`).
2. Find the main `<head>` tag.
3. Insert the provided script within the `<head>` tag.

## Conclusion
By following these instructions, you will successfully integrate the Tredio player into your web application. If you encounter any issues, please contact Tredio support for assistance.
