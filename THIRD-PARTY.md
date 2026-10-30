# Third-party components

| Component | Version | License | Use |
|---|---|---|---|
| [pdf-lib](https://github.com/Hopding/pdf-lib) | 1.17.1 | MIT | Merge, split, rotate, watermark, page numbers, metadata |
| [pdfjs-dist](https://github.com/mozilla/pdf.js) | 6.4.299 | Apache-2.0 | Local page thumbnails and text extraction |

The PDF.js runtime and worker are vendored into `public/vendor` at install time; no CDN is used.
Fonts are system families (Georgia/Palatino + Consolas).

Folio is not affiliated with Stirling PDF or Adobe.
