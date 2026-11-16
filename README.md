# PDF Scout

**A small, portable PDF reader for Windows 10 and 11** that can find and copy text and rearrange pages — one file, nothing to install.
By Dialsoft LLC.

## Download

PDF Scout 1.6.0 comes two ways. Both are the same program.

- **[PDFScout-Setup.exe](https://github.com/Dialsoft/pdfscout-releases/raw/main/PDFScout-Setup.exe)** — the installer (7.1 MB). Adds PDF Scout to the Start menu and to Windows "Installed apps", with an uninstaller. It asks whether to install for **just you** (no administrator needed) or for **everyone who uses the PC** (asks for an administrator).
- **[PDFScout.exe](https://github.com/Dialsoft/pdfscout-releases/raw/main/PDFScout.exe)** — the portable copy (4.6 MB). Nothing to install: put it somewhere like your Desktop, Downloads or `C:\Tools` (not Program Files, so it can keep itself up to date) and double-click it.

Windows may show a blue "Windows protected your PC" box the first time: click **More info**, then **Run anyway**.

**For IT / remote deployment:** `PDFScout-Setup.exe /S` installs silently for the account running it; add `/ALLUSERS` (run as administrator) to install for everyone, `/DESKTOP` for a Desktop shortcut, and `/NOUPDATES` to switch off automatic update checks. `"C:\Program Files\PDF Scout\Uninstall.exe" /S` removes it silently.

## What it does

- Opens PDFs with its own built-in engine (PDFium, the engine Google Chrome uses), packed inside the one EXE
- Find: Ctrl+F highlights every match in the document and steps through them
- Select and copy text; right-click menu with Copy, Select All and Find
- Clickable links (web links show the real address and ask first) and a Bookmarks list for PDFs that have a table of contents
- Ribbon with Home, Organize, Settings, Share and Help tabs, with color icons and detailed tooltips
- Page panel: a small picture of every page down the right side; click one to jump to it
- Rearrange pages: drag a page up or down in the page panel, then Save (or Save As to keep the original)
- Delete pages: select a page and press Del, or right-click it in the page panel
- Combine PDFs: open two PDFs in two PDF Scout windows and drag pages from one page panel into the other (drag copies, Shift+drag moves)
- Continuous scrolling, zoom, Fit Width, Fit Page, Actual Size, Go to page
- Rotate sideways scans left or right
- Print all pages, the current page or a range, fit to paper or actual size
- Password-protected PDFs
- Can be your default PDF app: Settings tab > Set as default PDF app
- Send the PDF to someone by email (straight through your own mail server, attached), or a note by text message, WhatsApp, Messenger or Teams
- Keeps itself up to date automatically (checks at start and every 6 hours; you choose when to install)

## What's new in 1.6.0

- New: take pages from one PDF into another. Open each PDF in its own PDF Scout window (Organize tab > Second PDF opens another PDF beside the one you have and puts the two windows side by side). Then drag a page from one window's page panel and let go over the other window's page panel. A blue bar shows where it will land. It works in both directions.
- Dragging a page across copies it: it stays in the PDF it came from. Hold Shift while you let go to move it instead (it is added there and deleted here).
- New: Delete Page. Select a page and click Delete Page on the Organize tab, press Del, or right-click the page in the page panel. A PDF always keeps at least one page.
- New: right-click a page in the page panel for a menu with Delete, the Move commands and Undo.
- Undo (Ctrl+Z) now takes back deleted and brought-in pages as well as moves, one change at a time.
- Nothing changes in a PDF file until you click Save in that window. When pages were deleted or brought in, the file is written out fresh, so a deleted page is really gone from the saved file, not just hidden. Use Save As if you want to keep the original too.
- The PDF's own bookmarks and form fields are kept when you save. Pages that come from another PDF bring their pictures, text and links, but not that PDF's bookmarks or fillable-form behavior. Password-protected PDFs can't be changed or used as a source, as before.

See [CHANGELOG.md](CHANGELOG.md) for every version.

**Checksums (SHA-256):**

- PDFScout-Setup.exe: `62fc0c1a291097230b6b794f195fc9fb7374a3b0d543e160b81b0efb3c37f1cd`
- PDFScout.exe: `60726b9ae45df552c0f6f16d4b00a75c299873e1fbacfa3dbbd1eea3e33a2db2`

## Open-source notice

PDF Scout includes the PDFium library (© The PDFium Authors and others), which draws the pages and reads their text.
PDFium and the components inside it are open-source software; their license notices are in
[THIRD-PARTY-NOTICES.txt](THIRD-PARTY-NOTICES.txt). Those licenses cover PDFium only, not the rest of PDF Scout.

---
© 2026 Dialsoft LLC — Marc Frega, Wharton NJ. All rights reserved.
