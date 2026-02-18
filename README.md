Whitespace Cleaner

A responsive web app that transforms messy text into clean, readable content by stripping out excessive whitespace while preserving
structure and meaning.

**[Try it now →](https://jason-mendes.github.io/Empty-White-Space-Cleaner/)** 

Overview

Whitespace Cleaner handles text that's full of extra spaces, tabs, and newlines — the kind you get from copying out of PDFs, websites, or poorly formatted documents.

What it does

Collapses excessive whitespace — multiple consecutive spaces, tabs, and newlines become single spaces
Preserves your content — the meaning and structure stay intact
Trims boundaries — strips leading and trailing whitespace
Works in real-time — results update as you type
Example

Before: This text has multiple spaces and weird formatting.

After: This text has multiple spaces and weird formatting.

Features

Core Functionality

Real-time whitespace cleaning
Content integrity preserved through processing
Handles spaces, tabs, and newline characters
Text Analytics

Character count (before and after)
Word count tracker
Token count with breakdown
All stats update live as you type
User Experience

Dark theme throughout
Responsive layout across devices
Smooth animations and transitions
Accessible via keyboard and screen readers
Productivity

One-click copy to clipboard
Visual feedback on actions
Undo last clear
Clear all with confirmation step
Safari Compatibility

Fully tested on Safari
Backdrop filters with proper fallbacks
Usage

Paste or type text in the Original Text panel
View the Cleaned Text on the right
Check the live stats for characters, words, and tokens
Click Copy to save the cleaned text
Use Clear All to reset everything
Technical Details

Built With

React 18
Vanilla CSS (Grid + Flexbox)
Babel Standalone for in-browser JSX
No build tools needed — it's a single index.html file
Browser Support

Chrome (latest)
Firefox (latest)
Safari 9+
Edge
Mobile browsers
Performance

Memoized calculations with useMemo
Debounced input handling
Lightweight — only React CDN dependency
Project Structure

Empty-White-Space-Cleaner/ ├── index.html # The entire app ├── README.md # This file └── .git/

Local Development

git clone https://github.com/Jason-Mendes/Empty-White-Space-Cleaner.git cd Empty-White-Space-Cleaner

Open index.html directly in your browser, or spin up a local server:

python -m http.server 8000

Deployment

GitHub Pages (simplest option)

Push code to GitHub
Go to Settings → Pages
Choose "Deploy from a branch" → main → / (root)
Your app will be at: https://yourusername.github.io/Empty-White-Space-Cleaner/
Other options

Netlify — drag and drop index.html
Vercel — connect your GitHub repo
Any web server — just host the single HTML file
Use Cases

Content Work

Clean up text copied from PDFs
Format content for blogs, docs, or social posts
Development

Tidy up config files or documentation
Clean output logs or code comments
Academic / Professional

Format research notes and citations
Prep manuscripts for submission
Contributing

Fork the repo
Create a feature branch: git checkout -b feature/your-feature
Make your changes in index.html and test them
Commit with a clear message: git commit -m 'Add your feature'
Push and open a pull request
Guidelines

Keep the single-file approach
Stay consistent with existing styles
Test across modern browsers
Update the README if your change warrants it
License

Licensed under the LICENSE.

Issues & Support

Found a bug or have a feature request? [Open an issue](https://github.com/Jason-Mendes/Empty-White-Space-Cleaner/issues)  

Roadmap

Custom whitespace pattern options
Export to .txt, .md, and more
Batch processing
Side-by-side comparison mode
Keyboard shortcuts
Saveable cleaning presets
**Made with ❤️  by [Jason Mendes](https://github.com/Jason-Mendes)**

Clean up messy text with one click.
