# PDF Scout

**A small, portable PDF reader for Windows 10 and 11** that can find and copy text and rearrange pages — one file, nothing to install.
By Dialsoft LLC.

## Download

**[Download PDFScout.exe](https://github.com/Dialsoft/pdfscout-releases/raw/main/PDFScout.exe)** (version 1.5.0, 4.5 MB)

Put it somewhere like your Desktop, Downloads or `C:\Tools` (not Program Files, so it can keep itself up to date) and double-click it.
Windows may show a blue "Windows protected your PC" box the first time: click **More info**, then **Run anyway**.

## What it does

- Opens PDFs with its own built-in engine (PDFium, the engine Google Chrome uses), packed inside the one EXE
- Find: Ctrl+F highlights every match in the document and steps through them
- Select and copy text; right-click menu with Copy, Select All and Find
- Clickable links (web links show the real address and ask first) and a Bookmarks list for PDFs that have a table of contents
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

## What's new in 1.5.0

- PDF Scout now has its own PDF engine built in: PDFium, the open-source engine Google Chrome uses. Pages, page-panel pictures and printouts are drawn by it, so PDF Scout no longer depends on the PDF engine inside Windows and looks the same on every PC. It is still one portable EXE (now about 4.7 MB); the first time it runs it unpacks the engine into your user profile.
- New: Find (Home tab, or Ctrl+F). Type a word or phrase and every match in the document is highlighted; Next and Previous (F3 / Shift+F3, or Enter / Shift+Enter) step through them.
- New: select and copy text. Drag across text to select it, double-click to select a word, Ctrl+A to select everything, Ctrl+C to copy. Right-click a page for a menu with Copy, Select All and Find.
- New: links work. Click a link inside a PDF to jump to the page it points to. A link to a web address shows you the real address and asks before opening your browser.
- New: bookmarks. If a PDF has its own table of contents, click Bookmarks at the top of the side panel and click an entry to jump there. The part you're reading is highlighted.
- The Page Panel button moved from the Home tab to the Organize tab to make room for Find (F4 still shows and hides the panel).
- PDFium needs 64-bit Windows 10 or 11. On Windows 8.1, or if the engine can't be unpacked, PDF Scout uses the Windows engine as before: pages show and print, but Find, copy, links and bookmarks are off. Help > Diagnostic Report says which engine is in use.
- Scanned documents are pictures of text, so there is nothing to find or copy in them unless they were saved as "searchable".

See [CHANGELOG.md](CHANGELOG.md) for every version.

**Checksum (SHA-256):** `9385a01729440270648721fb9bb91052d050d7cc76b1b277d2363a9666382468`

## Open-source notice

PDF Scout includes the PDFium library (© The PDFium Authors and others), which draws the pages and reads their text.
PDFium and the components inside it are open-source software; their license notices are in
[THIRD-PARTY-NOTICES.txt](THIRD-PARTY-NOTICES.txt). Those licenses cover PDFium only, not the rest of PDF Scout.

---
© 2026 Dialsoft LLC — Marc Frega, Wharton NJ. All rights reserved.
