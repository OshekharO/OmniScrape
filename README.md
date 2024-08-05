# 🌐 OmniScrape

<p align="center">
  <strong>Search across multiple websites simultaneously with ease!</strong>
</p>

<p align="center">
  <a href="#features">Features</a> •
  <a href="#demo">Demo</a> •
  <a href="#usage">Usage</a> •
  <a href="#configuration">Configuration</a> •
  <a href="#contributing">Contributing</a>
</p>

<p align="center">
  <img src="https://img.shields.io/github/license/OshekharO/OmniScrape" alt="License">
  <img src="https://img.shields.io/github/stars/OshekharO/OmniScrape" alt="Stars">
  <img src="https://img.shields.io/github/forks/OshekharO/OmniScrape" alt="Forks">
</p>

## 🚀 Features

- 🔍 Search across multiple websites simultaneously
- 🗂️ Categorized search for targeted results
- 🖼️ Display results with images and titles
- 🔗 Direct links to original content
- 🛠️ Easy configuration for adding new websites
- 🌐 CORS-friendly with integrated bypasser

## 🎬 Demo

Try out the live demo [here](https://badoo.eu.org/)!

## 🖥️ Usage

1. Select a category from the dropdown menu.
2. Enter your search term in the input field.
3. Click the "Search" button.
4. View the results from multiple websites, categorized and displayed with images and titles.

## ⚙️ Configuration

Add or modify websites in the `sites.json` file:

```json
{
  "category_name": {
 "provider_name": {
   "name": "Display Name",
   "url": "https://search-url.com/?q=",
   "main": "main-container-selector",
   "title": "title-selector",
   "img": "image-selector",
   "href": "link-selector"
 }
  }
}
```

## 🤝 Contributing

Contributions, issues, and feature requests are welcome! Feel free to check [issues page](https://github.com/OshekharO/OmniScrape/issues).
