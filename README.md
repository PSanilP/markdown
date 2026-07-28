# Markdown to Rich Text Converter ✍️

A lightweight, single-file web application that instantly converts raw Markdown into polished Rich Text. Designed for quick drafting, visual editing, and seamlessly copying formatted text into emails, word processors, or CMS platforms.

## 🌟 Features

* **Live Dual-Pane Preview:** Type raw markdown on the left and see the rendered rich text instantly on the right.
* **Visual Edit Mode:** Toggle the visual editor to go full-screen and edit your text using a traditional WYSIWYG toolbar—no markdown knowledge required!
* **Format Painter:** Easily copy block formatting (like Headings or Quotes) and inline styles (like Bold or Italics) from one element and apply it to another with a single click.
* **Clear Formatting:** Instantly strip away inline styles and reset blocks back to normal text.
* **Drag and Drop:** Drop any `.md` or `.txt` file directly into the browser to load its contents.
* **Smart Copy & Paste:** Copy the raw markdown, or copy the rendered Rich Text to paste perfectly formatted content into Gmail, Outlook, Word, or Notion.
* **Zero Build Step:** Entirely built with Vanilla JavaScript, HTML, and CSS in a single file. No frameworks, no bundlers, no heavy `node_modules`.

## 🛠️ Built With

* **HTML, CSS, & Vanilla JavaScript**
* **[Marked.js](https://marked.js.org/)** - For robust parsing of Markdown into HTML.
* **[Turndown.js](https://github.com/mixmark-io/turndown)** - For converting visually edited HTML back into clean Markdown.

## How to Use

Since this is a client-side only application, there is no installation required!

**Option 1: Live Demo**
Check out the live application hosted on GitHub pages here: 
> *👉 https://psanilp.github.io/markdown*

**Option 2: Run Locally**
1. Clone this repository or download the `index.html` file.
2. Double-click the `index.html` file to open it in any modern web browser.
3. Start typing, or drag and drop a markdown file onto the screen to begin!

## 💡 Keyboard Shortcuts & Tips

* **Copying for Emails:** Use the "Copy as Rich Text" button in the right-pane header to copy the exact visual formatting.
* **Format Painter:** Click the paintbrush icon in Edit Mode, select the text with the formatting you want, then click your target text to apply it.
* **Responsive Panels:** Drag the center dotted divider to adjust the width of the raw markdown input versus the visual output. 

## 📝 License

This project is open-source and available for anyone to use, modify, or distribute.
