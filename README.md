# Magic Markdown Editor ✨

## Overview

Magic Markdown Editor is a simple, elegant, and powerful web-based markdown editing tool that allows users to write markdown text and instantly see the rendered HTML preview. It provides a clean, user-friendly interface with real-time markdown rendering and convenient formatting options.

## Features

### 1. Real-Time Markdown Rendering
- Type or paste markdown text in the left panel
- Instantly see the rendered HTML output in the right panel
- Supports full markdown syntax, including:
  - Headings
  - Bold and italic text
  - Code blocks
  - Lists
  - Tables

### 2. Text Formatting Toolbar
The editor provides quick formatting buttons for:
- **Bold**: Wraps selected text in `**`
- *Italic*: Wraps selected text in `*`
- Headings: Insert H1, H2, and H3 headers
- Table: Insert a pre-formatted markdown table

### 3. Clipboard Integration
- **Paste Markdown**: Click the "Paste Markdown Text" button to quickly paste text from your clipboard
- **Copy Rendered Text**: Click the "Copy Rendered Text" button to quickly copy the rendered HTML to your clipboard in both HTML and plain text formats

  *- for easily pasting text, from e.g. AI generated content, into the Markdown Editor, and copying it right back into the clipboard as formatted text, for using in Word, Powerpoint, etc.*

## How to Use

### Saving the Magic Markdown Editor to your desktop
- Save the "magic-markdown-editor.html" file to your desktop

### Writing Markdown
- Open the Magic Markdown Editor (the "magic-markdown-editor.html" file, saved to your desktop)
- Click the blue "Paste Markdown Text" button, or start typing in the left text area
- See your markdown instantly rendered in the right panel

### Formatting or Adding Text
- Select text and click formatting buttons
- Keyboard shortcuts work as standard markdown syntax

### Copying Content
- Click the green "Copy Rendered Text" button
- The text is automatically copied to your clipboard, as formatted text (for inserting into e.g. Word, Powerpoint, etc.)
- A green checkmark confirms successful copying

## Supported Markdown Elements

### Text Formatting
- **Bold text**: `**bold**`
- *Italic text*: `*italic*`
- ***Bold and Italic***: `***bold and italic***`

### Headings
```markdown
# H1 Heading
## H2 Heading
### H3 Heading
```

### Code
- Inline code: ``code``
- Code blocks:
```markdown
    ``python
    print("Hello, World!")
    ``
```

### Lists
- Unordered list:
  ```markdown
  - Item 1
  - Item 2
    - Nested item
  ```

- Ordered list:
  ```markdown
  1. First item
  2. Second item
     1. Nested ordered item
  ```

### Tables
```markdown
| Header 1 | Header 2 | Header 3 |
|----------|----------|----------|
| Cell 1   | Cell 2   | Cell 3   |
```

## Technical Details
- Uses `marked.js` for markdown parsing
- Integrates `highlight.js` for code syntax highlighting
- Built with Tailwind CSS for responsive design
- Modern web technologies for smooth user experience

## Browser Compatibility
Compatible with modern web browsers that support:
- Clipboard API
- ES6 JavaScript
- Flexbox and Grid layouts

## Limitations
- Requires a modern web browser
- Temporary markdown rendering (not saved between sessions)
- No file import/export functionality

## Contributing
Feel free to fork the project, submit pull requests, or report issues on the project's repository.

## License
MIT License

## Contact
✨ Magic Markdown Editor Team
