# Documentation -- Markdown Editor Lite

This document explains the usage, features, and shortcuts available in
**Markdown Editor Lite**.

------------------------------------------------------------------------

## 📝 Overview

Markdown Editor Lite is a **single-file HTML application** that allows
you to write, preview, and export Markdown documents directly in your
browser.\
No installation or server setup is required -- just open
`markdown_editor_lite.html`.

------------------------------------------------------------------------

## 📂 File Management

-   **New File** -- clears the editor to start a fresh document.
-   **Open File** -- load a `.md`, `.markdown`, or `.txt` file from your
    computer.
-   **Auto-save** -- editor content is automatically saved to your
    browser's local storage.
-   **Recent Files** -- access the 5 most recent files opened.
-   **Save** -- download the current document as a Markdown file
    (`.md`).

------------------------------------------------------------------------

## 👀 Editor Modes

-   **Split View** -- editor + live preview side by side.\
-   **Editor Only** -- focus only on the Markdown code.\
-   **Table Converter** -- convert tab-separated data (e.g., from
    Excel/Google Sheets) into Markdown tables.

------------------------------------------------------------------------

## 🎨 Appearance

-   **Dark/Light Theme Toggle** -- switch between modes.\
-   **Focus Mode** -- dim all lines except the current editing line.\
-   **Full Screen** -- distraction-free editing view.

------------------------------------------------------------------------

## 🛠️ Toolbar Features

### Text Formatting

-   **Bold** → `**text**`\
-   **Italic** → `*text*`\
-   **Strikethrough** → `~~text~~`\
-   **Inline Code** → `` `code` ``

### Headings

-   H1 → `# Heading`\
-   H2 → `## Heading`\
-   H3 → `### Heading`

### Lists & Quotes

-   Bulleted list → `- item`\
-   Numbered list → `1. item`\
-   Blockquote → `> text`

### Links & Media

-   Link → `[title](url)`\
-   Image → Upload or drag & drop → `![alt](base64data)`\
-   Horizontal Rule → `---`

### Advanced Inserts

-   Table → Insert default Markdown table template\

-   Code Block →

    ``` markdown
    ```

    code here

-   Table of Contents → `[TOC]` (automatically replaced by a generated
    TOC)

------------------------------------------------------------------------

## 📊 Tools & Utilities

-   **Date / Time Insert** -- insert current date or time.\
-   **Search & Replace** -- quick find/replace within the document.\
-   **Statistics** -- word/character counts, reading time, advanced
    document stats.\
-   **Word Goal** -- set a custom writing goal and track progress.\
-   **Document Outline** -- overview of document structure via headings.

------------------------------------------------------------------------

## 📤 Export & Copy Options

-   **Copy Markdown** -- copy raw Markdown to clipboard.\
-   **Copy HTML** -- copy rendered HTML preview.\
-   **Export as HTML** -- save the preview as a standalone `.html`
    file.\
-   **Export as HTML (Custom CSS)** -- same as above, but with your own
    CSS inserted.\
-   **Export as PDF** -- generate a PDF version via
    [html2pdf.js](https://github.com/eKoopmans/html2pdf).

------------------------------------------------------------------------

## ⌨️ Keyboard Shortcuts

  Shortcut             Action
  -------------------- ---------------------
  **Ctrl+S / Cmd+S**   Save document
  **Ctrl+O / Cmd+O**   Open file
  **Ctrl+F**           Search
  **Ctrl+H**           Search & Replace
  **Ctrl+Shift+T**     Insert template
  **Ctrl+Shift+O**     Document outline
  **Ctrl+Shift+S**     Advanced statistics
  **Ctrl+G**           Set word goal
  **F11**              Toggle full screen

------------------------------------------------------------------------

## 🔗 Templates Included

-   **Blog Post** -- starter for articles.\
-   **Documentation** -- API or project docs format.\
-   **Meeting Notes** -- structured meeting minutes.\
-   **Readme** -- GitHub README starter.

------------------------------------------------------------------------

## ⚠️ Notes & Limitations

-   Images are stored as **base64 data URIs** inside the Markdown.\
-   Local storage may be cleared by your browser -- always save
    important files manually.\
-   PDF export depends on browser capabilities and html2pdf.js.

------------------------------------------------------------------------

## 🤝 Contribution Guide

If you want to add new features or fix bugs:

1.  Fork this repository.\
2.  Make your changes in a new branch.\
3.  Document your changes in `DOCUMENTATION.md`.\
4.  Submit a Pull Request.

------------------------------------------------------------------------
