# Version History Viewer

A lightweight web application to parse and display version history files with support for hierarchy, filtering and search.

## 🚀 Features

- Parse markdown-like version files
- Nested hierarchy support (sub-items)
- Version filtering
- Full-text search
- Configurable via JSON (theme, data source, branding)
- Responsive layout (mobile, tablet, desktop)

## ⚙️ Configuration

The application is driven by a `config.json` file:

```json
{
  "appName": "Version History Viewer",
  "primaryColor": "#2563eb",
  "secondaryColor": "#f59e0b",
  "logo": "logo.svg",
  "dataFile": "Historico.txt"
}