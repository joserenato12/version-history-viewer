# Version History Viewer

A lightweight web application to parse and display version history files with support for hierarchy, filtering and search.

## 🌐 Live Demo

👉 https://joserenato12.github.io/version-history-viewer/

---

## 🚀 Features

- Parse markdown-like version files
- Nested hierarchy support (sub-items)
- Version filtering
- Full-text search
- Configurable via JSON (theme, data source, branding)
- Responsive layout (mobile, tablet, desktop)

---

## ⚙️ Configuration

The application is driven by a `config.json` file:

```json
{
  "appName": "Version History Viewer",
  "primaryColor": "#005B96",
  "secondaryColor": "#707A8A",
  "tertiaryColor": "#00AEEF",
  "logo": "logo.png",
  "dataFile": "Historico.txt"
}
```

---

## 📄 Example input format

```md
## Version 1.0.0
**Release date:** 01/01/2026

### Improvements
- New feature
  - Sub-item

### Fixes
- Bug fix in rendering
```

---

## 🛠️ Tech Stack

- HTML
- CSS
- Vanilla JavaScript

---

## 📌 Purpose

This project provides a simple and reusable way to visualize version history across different environments, with minimal setup and no dependencies.

---

## 📦 How to use

- Clone the repository
- Edit the `config.json` file
- Customize your `Historico.txt`
- Open with a local server (e.g., Live Server)

---

## 📄 License

This project is open-source and available under the MIT License.
