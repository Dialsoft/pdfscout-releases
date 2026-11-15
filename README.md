# PDF Scout

**A tiny, portable PDF viewer for Windows 10 and 11** that can also rearrange pages — one small file, nothing to install.
By Dialsoft LLC.

## Download

**[Download PDFScout.exe](https://github.com/Dialsoft/pdfscout-releases/raw/main/PDFScout.exe)** (version 1.4.2, 764 KB)

Put it somewhere like your Desktop, Downloads or `C:\Tools` (not Program Files, so it can keep itself up to date) and double-click it.
Windows may show a blue "Windows protected your PC" box the first time: click **More info**, then **Run anyway**.

## What it does

- Opens PDFs instantly using the PDF engine built into Windows (that's why it's so small)
- Ribbon with Home, Organize, Settings, Share and Help tabs, with color icons and detailed tooltips
- Page panel: a small picture of every page down the right side; click one to jump to it
- Rearrange pages: drag a page up or down in the page panel, then Save (or Save As to keep the original)
- Continuous scrolling, zoom, Fit Width, Fit Page, Actual Size, Go to page
- Rotate sideways scans left or right
- Print all pages, the current page or a range, fit to paper or actual size
- Password-protected PDFs
- Can be your default PDF app: Settings tab > Set as default PDF app
- Send the PDF to someone by email (straight through your own mail server, attached), or a note by text message, WhatsApp, Messenger or Teams
- Keeps itself up to date automatically (checks at start and every 6 hours; you choose when to install)

## What's new in 1.4.2

- New: Help tab > Diagnostic Report. If something doesn't work on your PC, do the thing that fails and then click it. PDF Scout saves a text file on your Desktop (and copies it to the clipboard) describing what it has been doing, so the problem can be tracked down. It contains nothing from inside your documents.
- The page panel can no longer be left waiting behind the big pages: after each big page is drawn, a page-panel picture gets its turn.
- While a page-panel picture is still being drawn, the panel shows a shrunken copy of the big page if that has already been drawn, instead of a blank box.
- PDF Scout now decides whether a page picture is up to date from the size it asked Windows for, so a picture that comes back a pixel off is never redrawn over and over.

See [CHANGELOG.md](CHANGELOG.md) for every version.

**Checksum (SHA-256):** `4babfab6ec9533fced9d93f17b05998530ee75439fcc8e08975c5cc831b4d48f`

---
© 2026 Dialsoft LLC — Marc Frega, Wharton NJ. All rights reserved.
