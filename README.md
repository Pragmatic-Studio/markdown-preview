# Markdown Preview

A real-time Markdown editor with instant preview, built with native web technologies.

## 🚀 Features

- ✅ **Real-time preview** - Changes are reflected instantly
- ✅ **Full Markdown support** - Including tables, code, lists, and more
- ✅ **Copy functionality** - Copy rendered HTML to clipboard
- ✅ **Responsive design** - Works perfectly on mobile and desktop devices
- ✅ **Modern interface** - Clean and professional design with Montserrat typography
- ✅ **No external dependencies** - 100% native code (HTML5, CSS3, JavaScript ES6+)

## 🛠️ Technologies Used

- **HTML5** - Semantic structure
- **CSS3** - Modern styles with Flexbox and responsive design
- **JavaScript ES6+** - Application logic
- **Marked.js** - Markdown rendering library (CDN)

## 📁 Project Structure

```
marwdown-preview/
├── index.html          # Main application file
├── AGENTS.md           # Development rules and principles
└── README.md           # Project documentation
```

## 🎯 Functionality

### Markdown Editor
- Text area with visual syntax highlighting
- Informative placeholder
- Automatic textarea resizing

### Preview Panel
- Instant Markdown to HTML rendering
- Support for all standard Markdown elements:
  - Headers (H1-H6)
  - Bold and italic text
  - Ordered and unordered lists
  - Blockquotes
  - Inline code and code blocks
  - Tables
  - Links
  - Task lists (checkboxes)

### Copy Functionality
- Button to copy rendered HTML
- Success and error messages
- Compatibility with modern and legacy browsers

## 🚀 Usage

1. **Open the application**: Simply open `index.html` in your web browser
2. **Write Markdown**: Use the left panel to write your Markdown content
3. **View preview**: The right panel shows the rendered result in real-time
4. **Copy HTML**: Use the "Copy to Clipboard" button to get the generated HTML

## 📝 Supported Syntax Examples

```markdown
# Main Header
## Secondary Header

**Bold text** and *italic text*

> This is a quote

- Unordered list
- Second item

1. Ordered list
2. Second item

`inline code`

```javascript
// Code block
function example() {
    return "Hello world";
}
```

| Column 1 | Column 2 |
|----------|----------|
| Cell 1   | Cell 2   |

- [x] Completed task
- [ ] Pending task
```

## 🎨 Customization

The project uses CSS variables that can be easily modified for customization:

- **Colors**: Consistent color palette with CSS variables
- **Typography**: Montserrat font from Google Fonts
- **Spacing**: Uniform spacing system
- **Responsive**: Breakpoints for different screen sizes

## 🔧 Development

### Development Principles

This project follows SOLID principles and development best practices:

- **Single Responsibility**: Each function has a specific responsibility
- **Open/Closed**: Code open for extension, closed for modification
- **Liskov Substitution**: Consistent and reusable interfaces
- **Interface Segregation**: Specific and non-overloaded interfaces
- **Dependency Inversion**: Dependencies through abstractions

### Code Conventions

- **JavaScript**: camelCase for variables and functions
- **CSS**: kebab-case for classes
- **Comments**: Clear documentation in complex functions
- **Structure**: Modular and well-organized code

## 📱 Compatibility

- ✅ Chrome 60+
- ✅ Firefox 55+
- ✅ Safari 12+
- ✅ Edge 79+
- ✅ Mobile devices (iOS/Android)

## 🤝 Contributing

Contributions are welcome. Please:

1. Follow the development principles established in `AGENTS.md`
2. Keep the code 100% native (no external libraries)
3. Ensure the design is responsive
4. Test on multiple browsers

## 📄 License

This project is part of Pragmatic Studio and is intended for internal use.

---

**Developed by**: Rafael Reyna  
**Organization**: Pragmatic Studio  
**Email**: rreyna@pragmaticstudio.dev
