# Whitespace Cleaner

A modern, responsive web application that transforms messy text into clean, readable content by removing excessive whitespace while preserving the structure and meaning of your text.

## 🚀 Live Demo

**[Try it now →](https://jason-mendes.github.io/Empty-White-Space-Cleaner/)**

## 📋 Overview

The Whitespace Cleaner is a powerful yet simple tool designed to help you clean up text that contains multiple consecutive whitespace characters (spaces, tabs, newlines). It's perfect for cleaning up copied text from PDFs, websites, or documents that have formatting issues.

### What it does

- **Removes excessive whitespace**: Converts multiple consecutive whitespace characters into single spaces
- **Preserves text structure**: Maintains the content and meaning while improving readability
- **Trims boundaries**: Removes leading and trailing whitespace
- **Real-time processing**: Instantly shows cleaned results as you type

## ✨ Features

### 🔧 Core Functionality

- **Intelligent whitespace removal**
- **Real-time text cleaning**
- **Preserve content integrity**

### 📊 Text Analytics

- Character count (before & after)
- Word count tracker
- Token count with breakdown
- Live-updating statistics

### 🎨 User Experience

- Dark theme
- Responsive across devices
- Smooth UI animations
- Keyboard + screen reader accessible

### ⚡ Productivity Features

- One-click copy
- Smart visual feedback
- Undo last clear
- Clear all with confirmation

### 🧭 Safari Compatibility

- Fully tested on Safari
- Uses backdrop filters with fallbacks

## 📖 Usage

1. Paste or type text in the **Original Text** panel
2. View the **Cleaned Text** on the right
3. Check **live stats** for characters, words, and tokens
4. Click **Copy** to save cleaned text
5. Use **Clear All** to reset

#### Example Transformation

**Before:**

```
This    text   has   multiple       spaces   and
weird formatting.
```

**After:**

```
This text has multiple spaces and weird formatting.
```

## 🛠️ Technical Details

### Built With

- **React 18**
- **Vanilla CSS** (Grid & Flexbox)
- **Babel Standalone** (in-browser JSX)
- No build tools required — single `index.html` file

### Browser Support

- ✅ Chrome (latest)
- ✅ Firefox (latest)
- ✅ Safari 9+
- ✅ Edge
- ✅ Mobile

### Performance Optimizations

- Memoized calculations (`useMemo`)
- Debounced input handler
- Lightweight (only React CDN used)

## 📁 Project Structure

```
Empty-White-Space-Cleaner/
├── index.html         # Main single-page app
├── README.md          # This documentation
└── .git/              # Git data
```

## 🚀 Local Development

```bash
git clone https://github.com/Jason-Mendes/Empty-White-Space-Cleaner.git
cd Empty-White-Space-Cleaner
```

Then just open `index.html` in your browser, or use:

```bash
python -m http.server 8000
```

## 🌐 Deployment

### GitHub Pages (Recommended)

1. Push code to GitHub
2. Go to **Settings → Pages**
3. Choose "Deploy from a branch" → `main` → `/ (root)`
4. Access your app at:
   `https://yourusername.github.io/Empty-White-Space-Cleaner/`

### Other Options

- **Netlify**: drag & drop `index.html`
- **Vercel**: connect your GitHub repo
- **Any Web Server**: upload the `index.html` file

## 💡 Use Cases

### Content Creation

- Clean up copied text from PDFs
- Format text for blogs, docs, social posts

### Development

- Clean config files or documentation
- Format output logs or code comments

### Academic & Professional

- Clean research notes
- Format citations
- Prep manuscripts for submission

## 🤝 Contributing

1. Fork this repo
2. Create a feature branch:

   ```bash
   git checkout -b feature/amazing-feature
   ```

3. Edit `index.html`, test changes
4. Commit with a clear message:

   ```bash
   git commit -m 'Add amazing feature'
   ```

5. Push and open a pull request

### Dev Guidelines

- Stick to the single-file approach
- Keep styling consistent
- Test on all modern browsers
- Update the README if needed

## 📄 License

Licensed under the [MIT License](LICENSE).

## 🐛 Issues & Support

Found a bug or have a feature request? [Open an issue](https://github.com/Jason-Mendes/Empty-White-Space-Cleaner/issues)

## 🗺️ Roadmap

- [ ] Custom whitespace pattern options
- [ ] Export to `.txt`, `.md`, and more
- [ ] Batch processing
- [ ] Side-by-side comparison mode
- [ ] Keyboard shortcuts
- [ ] Save custom cleaning presets

---

**Made with ❤️ by [Jason Mendes](https://github.com/Jason-Mendes)**

*Transform messy text into clean, readable content with just one click!*

### ✅ Tips

- Make sure the file is saved with the **.md** extension — _not_ `.txt`.
- Do **not** wrap the whole thing in \`\`\`markdown — only use those for actual code blocks.
- GitHub will automatically render titles, bullet points, and links.


