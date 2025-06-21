# Responsive HTML Table Generator

A powerful, customizable HTML table generator that supports live editing, color customization, DOCX uploads, and responsive formatting — all in a user-friendly drag-and-drop interface.

---

## ✨ Features

- ✅ **Live Table Editing** (add/remove rows & columns)
- 🎨 **Customize** header & row colors, text color, border color, and font
- 📄 **DOCX Upload Support** to convert tables from `.docx` into HTML
- ⚡ **Real-Time Preview** of HTML with syntax highlighting
- 📋 **Copy to Clipboard** and 💾 **Download** the generated HTML
- 📱 **Responsive Output** with mobile-friendly layout

---

## 🚀 Getting Started

1. **Clone this repo** or [Download ZIP](https://github.com/CoderYukti/ResponsiveTableGen/archive/refs/heads/main.zip)

2. **Open `index.html`** in your browser

3. Start building your table:
   - Create a table from scratch or
   - Drag and drop a `.docx` file with a table

4. Customize your styles using the sidebar:
   - Font family
   - Header and row background/text colors
   - Border color

5. Use the buttons:
   - `Generate HTML` to see the output
   - `Copy HTML` to clipboard
   - `Download HTML` as a file

---

## 📦 Dependencies

- [Mammoth.js](https://github.com/mwilliamson/mammoth.js) – for DOCX to HTML conversion
- [Prism.js](https://prismjs.com/) – for HTML syntax highlighting
- Optional: [html-beautify](https://beautifier.io/) – for nicely formatted HTML output

All libraries are loaded via CDN in the `index.html`.

---

## 🔧 Customization Tips

- Modify table default styles in `style.css` or inline `<style>` tag
- Add more fonts or styles to the dropdown in HTML
- Extend support for additional file types or formats if needed

---

## 🧩 Contribution

Pull requests are welcome! If you have suggestions or improvements (like better formatting or features like CSV upload), feel free to open an issue or submit a PR.

---

## 📄 License

This project is open-sourced under the [MIT License](LICENSE).

---

## 🙌 Acknowledgements

Thanks to the open-source community for tools like:
- Mammoth.js
- Prism.js
- html-beautify
