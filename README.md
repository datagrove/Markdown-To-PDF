# Markdown-To-PDF
Dart package for transforming markdown files to HTML and HTML to PDF.

Project Goal:
A package to convert markdown to html and the resulting html to PDF.

Leverage the following packages:
- [markdown](https://pub.dev/packages/markdown)
- [html](https://pub.dev/packages/html)
- [pdf](https://pub.dev/packages/pdf)

Requirements:
- Pure dart
- Works on all dart platforms including all flutter platforms
- Accepts box constraint
  - Returns amount of html rendered such that rendering can resume on a subsequent page
- Follow standards and requirements for publication on pub.dev
- Support enough html to support basic markdown

Additional Features:
- Support for additional html embedded into markdown
  - Reference the [flutter_html](https://pub.dev/packages/flutter_html) as an example of a package that implements growing and extendible subset of html
- Be able to create a PDF of marp-style slide decks
  - [Marp Markdown](https://marp.app)

Additional References:
- [Python Solution](https://weasyprint.org)
