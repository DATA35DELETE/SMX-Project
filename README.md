# Stored Memory X (SMX)

## About

The SMX project offers a web-based electronic notebook. Instead of writing a traditional book with headings, texts, lists, and tables, authors can create a more modern and dynamic book. Additionally, since SMX is primarily designed for writing tutorial books for programming languages, it supports `pre` + `code` with syntax highlighting via Hljs, making code snippets colorful and visually appealing. This allows for more vibrant and engaging books.

## Features

The standout features of the SMX project include:

- Web-based, ensuring seamless operation on all devices with an internet browser
- Syntax highlighting for programming languages using Hljs
- Provides a ready-to-use template
- Supports adding background images/videos
- Offers an organized working environment
- Easy project forking with `forker.exe`

## Installation

```bash
git clone https://github.com/DATA35DELETE/SMX-Project.git
```

## Structure

```stylus
SMX
│   hljsLICENSE // Hljs's LICENSE
│   LICENSE // LICENSE
│   main.css // Main stylesheet file
│   main.js // Main JavaScript file for adding background videos
│   README.md // Main Markdown file
│   READMEtr.md // Turkish Markdown file
│   X.roadMap.md // Roadmap for the electronic book
│   SMXForker.exe // Tool for automatically creating electronic books
│
├───hljs // Highlight files
│       highlight.min.js
│       number.min.js
│       vs2015.min.css
│
└───Subjects // Lessons/Pages
    │   demo.html // Page template
    │
    ├───img // Images used for pages
    │   │   pp.png // Page header image
    │   │   example.png // Sample image, AI-generated
    │   │
    │   └───wallpapers // Wallpapers
    │           exapmle.png // Page background image, AI-generated
    │
    └───vid // Page background videos
            example.mp4 // Sample video
```
