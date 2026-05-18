# ⚡ Page Exporter

Export any webpage into clean, structured knowledge files.

Page Exporter is a lightweight Chrome extension that converts webpages into beautifully formatted:

- TXT
- Markdown (`.md`)
- DOCX (`.docx`)

Perfect for:
- ChatGPT uploads
- Claude uploads
- research workflows
- documentation
- note-taking
- internal dashboards
- authenticated webpages

---

# ✨ Features

## 📄 Clean Formatting

Automatically preserves:
- headings
- paragraphs
- bullet lists
- tables

while removing:
- scripts
- ads
- navigation clutter
- noisy UI elements

---

## 🔒 Works on Logged-In Pages

Export content from:
- Notion
- Jira
- dashboards
- internal tools
- CRM systems
- documentation portals

Because extraction happens directly in your browser.

---

## ⚡ Multiple Export Formats

One-click export to:

| Format | Use Case |
|---|---|
| TXT | Simple AI uploads |
| Markdown | Obsidian / Notion / RAG |
| DOCX | Microsoft Word / sharing |

---

## 🎨 Modern UI

- glassmorphism design
- lightweight popup
- fast exports
- minimal UX

---

# 📂 Project Structure

```text
page-exporter/
├── manifest.json
├── popup.html
├── popup.js
├── styles.css
├── docx.min.js
└── icon.png
```

---

# 🚀 Installation

## 1. Download the project

Clone or download the repository.

---

## 2. Download DOCX library

Download:

https://unpkg.com/docx@8.5.0/build/index.umd.js

Save as:

```text
docx.min.js
```

inside the extension folder.

---

## 3. Open Chrome Extensions

Go to:

```text
chrome://extensions
```

---

## 4. Enable Developer Mode

Toggle:

```text
Developer mode
```

(top-right corner)

---

## 5. Load Extension

Click:

```text
Load unpacked
```

Then select:

```text
page-exporter/
```

---

# 🖥️ Usage

1. Open any webpage
2. Click the extension icon
3. Choose export format:
   - Copy Text
   - TXT
   - Markdown
   - DOCX

Done.

---

# 🧠 How It Works

The extension:

```text
Webpage
→ semantic extraction
→ cleanup
→ structured formatting
→ export
```

It:
- clones the DOM safely
- extracts semantic content
- preserves structure
- never modifies the original page

---

# 🔐 Privacy

Everything runs locally in your browser.

No:
- AI APIs
- tracking
- analytics
- external servers

Your data never leaves your device.

---

# 📌 Supported Content

✅ Headings  
✅ Paragraphs  
✅ Lists  
✅ Tables  

---

# 🛠️ Built With

- Chrome Extensions Manifest V3
- Vanilla JavaScript
- docx.js

---

# 📈 Future Improvements

Planned features:

- image export
- PDF export
- code block detection
- article mode
- multi-page export
- ZIP packaging
- better table rendering

---

# 📄 License

MIT License

---

# ⚡ Why This Exists

Most AI tools cannot access:
- authenticated pages
- internal dashboards
- logged-in content

Page Exporter bridges that gap by turning webpages into portable knowledge files ready for AI workflows.
