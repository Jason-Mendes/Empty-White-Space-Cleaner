```markdown
# Whitespace Cleaner

A modern, responsive web application that transforms messy text into clean, readable content by removing excessive whitespace while preserving the structure and meaning of your text.

## 🚀 Live Demo

**[Try it now →](https://jason-mendes.github.io/Empty-White-Space-Cleaner/)**

---

## 📋 Overview

The Whitespace Cleaner is a powerful yet simple tool designed to help you clean up text that contains multiple consecutive whitespace characters (spaces, tabs, newlines). It's perfect for cleaning up copied text from PDFs, websites, or documents that have formatting issues.

### What it does

- **Removes excessive whitespace**: Converts multiple consecutive whitespace characters into single spaces  
- **Preserves text structure**: Maintains the content and meaning while improving readability  
- **Trims boundaries**: Removes leading and trailing whitespace  
- **Real-time processing**: Instantly shows cleaned results as you type  

---

## ✨ Features

### 🔧 Core Functionality

- Replaces 2+ consecutive whitespace characters with a single space  
- Instant preview of cleaned text  
- Maintains word boundaries and text meaning  

### 📊 Text Analytics

- Character count: Before and after comparison  
- Word count: Track word changes during cleaning  
- Token count: Advanced token breakdown  
- Live statistics: Real-time updates as you edit  

### 🎨 User Experience

- Modern dark theme  
- Fully responsive design  
- Smooth interface animations  
- Keyboard navigation and screen reader support  

### ⚡ Productivity Features

- One-click copy to clipboard  
- Visual feedback for copy and clear actions  
- Undo previously cleared text  
- Clear all button for new content  

### 🧭 Safari Compatibility

- Works on all modern browsers, including Safari  
- Backdrop filter effects with proper fallbacks  

---

## 📖 Usage

1. Paste or type your text in the left panel labeled **"Original Text"**  
2. View the cleaned result instantly in the right panel labeled **"Cleaned Text"**  
3. Monitor live statistics for both input and cleaned text  
4. Use the **Copy to Clipboard** button to export your cleaned content  
5. Use **Clear All** to reset the input (with Undo available)

### Example Transformation

**Before (Original Text):**

```

This    text   has   multiple   spaces     and    weird   formatting.

```

**After (Cleaned Text):**

```

This text has multiple spaces and weird formatting.

```

---

## 🛠️ Technical Details

### Built With

- **React 18** – UI rendering  
- **Vanilla CSS** – Grid & Flexbox styling  
- **Babel Standalone** – In-browser JSX compilation  
- **No build tools** – Runs entirely in the browser from a single HTML file  

### Browser Support

- ✔️ Chrome (latest)  
- ✔️ Firefox (latest)  
- ✔️ Safari 9+  
- ✔️ Edge (latest)  
- ✔️ Mobile browsers  

### Performance Features

- `React.useMemo` for memoized calculations  
- Debounced updates for large input performance  
- Lightweight – No third-party libraries except React  

---

## 📁 Project Structure

```

Empty-White-Space-Cleaner/
├── index.html        # Complete single-page application
├── README.md         # Project documentation
└── .git/             # Git repository metadata

````

---

## 🚀 Local Development

1. Clone the repository:
    ```bash
    git clone https://github.com/Jason-Mendes/Empty-White-Space-Cleaner.git
    cd Empty-White-Space-Cleaner
    ```

2. Open in browser:
    - Just open `index.html` in any modern browser  
    - Or run a local server:
      ```bash
      python -m http.server 8000
      ```

3. Make changes:
    - Edit `index.html` directly  
    - Refresh your browser to test changes  

---

## 🌐 Deployment

### GitHub Pages (Recommended)

1. Push to your GitHub repository  
2. Go to: **Repository → Settings → Pages**  
3. Select:
    - **Branch**: `main`
    - **Folder**: `/ (root)`  
4. Your site will be live at:  
   `https://yourusername.github.io/Empty-White-Space-Cleaner/`

### Other Options

- **Netlify** – Drag and drop the `index.html` file  
- **Vercel** – Connect your GitHub repo  
- **Any hosting** – Upload `index.html` to your server  

---

## 💡 Use Cases

### 📝 Content Creation

- Clean up pasted text from PDFs or websites  
- Prepare blog, article, or social media content  
- Format messy input for consistency  

### 👨‍💻 Development

- Sanitize comments or code snippets  
- Clean up configuration files  
- Format JSON, XML, or plain text  

### 📚 Academic & Professional

- Tidy up research notes  
- Format essays and reports  
- Fix citations and references  

---

## 🤝 Contributing

Contributions are welcome!

1. **Fork the repository**  
2. **Create a feature branch**:
    ```bash
    git checkout -b feature/your-feature
    ```
3. **Make your changes** to `index.html`  
4. **Test thoroughly**  
5. **Commit your changes**:
    ```bash
    git commit -m "Add: your feature"
    ```
6. **Push your branch**:
    ```bash
    git push origin feature/your-feature
    ```
7. **Open a Pull Request**

### Guidelines

- Stick to single-file architecture  
- Ensure mobile and cross-browser compatibility  
- Follow code style and UI patterns  
- Update README for new features  

---

## 📄 License

This project is open source under the [MIT License](LICENSE).

---

## 🐛 Issues & Support

Found a bug? Have a feature request?  
[Open an issue here →](https://github.com/Jason-Mendes/Empty-White-Space-Cleaner/issues)

---

## 🗺️ Roadmap

- [ ] Support custom whitespace patterns  
- [ ] Export cleaned text to TXT, MD, etc.  
- [ ] Batch process multiple inputs  
- [ ] Text diff & comparison mode  
- [ ] Keyboard shortcuts  
- [ ] Custom cleaning presets  

---

**Made with ❤️ by [Jason Mendes](https://github.com/Jason-Mendes)**  
*Transform messy text into clean, readable content with just one click!*
````

---

### ✅ Instructions:

* **Paste** the entire content above into your `README.md` file.
* **GitHub** will render it correctly with headers, links, and formatting.
* The file is optimized for clarity, usability, and professional presentation.
