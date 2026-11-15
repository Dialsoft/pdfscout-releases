# PDF Scout

**A tiny, portable PDF viewer for Windows 10 and 11** that can also rearrange pages — one small file, nothing to install.
By Dialsoft LLC.

## Download

**[Download PDFScout.exe](https://github.com/Dialsoft/pdfscout-releases/raw/main/PDFScout.exe)** (version 1.4.0, 744 KB)

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

## What's new in 1.4.0

- New page panel: a strip down the right side of the window shows a small picture of every page. Click a page to jump to it. Hide or show the panel with Page Panel on the Home or Organize tab, or press F4.
- Rearrange pages: drag a page up or down in the page panel and drop it where you want it. A blue bar shows where it will land, the list scrolls by itself near the top and bottom, and Esc cancels.
- New Organize tab: Move Up, Move Down, Move to Front and Move to Back for the selected page (Alt+Up, Alt+Down, Alt+Home, Alt+End), and Undo Move (Ctrl+Z) to take moves back one at a time.
- Save (Ctrl+S) writes the new page order into the PDF; Save As (Ctrl+Shift+S) writes a new file and leaves the original alone. A * in the title bar means the new order hasn't been saved, and PDF Scout asks before closing, opening another PDF, sending or updating with unsaved changes.
- Saving is careful: PDF Scout writes the new file next to the old one, has Windows read it back to check every page, and only then replaces the old file. Pictures, text, bookmarks and form fields stay exactly as they were. Only the order of the pages changes.
- Printing follows the order on screen, including moves you haven't saved yet.
- Password-protected PDFs can still be read and printed, but their pages can't be rearranged.

See [CHANGELOG.md](CHANGELOG.md) for every version.

**Checksum (SHA-256):** `9508fe586e3f3a444c383a64710f3fd505418bbfc6918081997536860ed3b2ea`

---
© 2026 Dialsoft LLC — Marc Frega, Wharton NJ. All rights reserved.
