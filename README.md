# PDF Scout

**A small, portable PDF reader for Windows 10 and 11** that can find and copy text and rearrange pages — one file, nothing to install.
By Dialsoft LLC.

## Download

PDF Scout 1.6.2 comes two ways. Both are the same program.

- **[PDFScout-Setup.exe](https://github.com/Dialsoft/pdfscout-releases/raw/main/PDFScout-Setup.exe)** — the installer (7.1 MB). Adds PDF Scout to the Start menu and to Windows "Installed apps", with an uninstaller. It asks whether to install for **just you** (no administrator needed) or for **everyone who uses the PC** (asks for an administrator).
- **[PDFScout.exe](https://github.com/Dialsoft/pdfscout-releases/raw/main/PDFScout.exe)** — the portable copy (4.6 MB). Nothing to install: put it somewhere like your Desktop, Downloads or `C:\Tools` (not Program Files, so it can keep itself up to date) and double-click it.

Windows may show a blue "Windows protected your PC" box the first time: click **More info**, then **Run anyway**.

**For IT / remote deployment:** `PDFScout-Setup.exe /S` installs silently for the account running it; add `/ALLUSERS` (run as administrator) to install for everyone, `/DESKTOP` for a Desktop shortcut, and `/NOUPDATES` to switch off automatic update checks. `"C:\Program Files\PDF Scout\Uninstall.exe" /S` removes it silently.

## Learn PDF Scout

- **[Video tour](https://dialsoft.com/pdf-scout/#video)** — three minutes, narrated, with an animated demonstration of dragging a page from one PDF into another and saving the result as a new PDF. Plays on dialsoft.com; also here as an [MP4 download](https://github.com/Dialsoft/pdfscout-releases/raw/main/PDFScout-Tour.mp4).
- **[User Guide](https://dialsoft.com/pdf-scout/manual/)** — the full manual, with a picture for every step. Also [on this page](GUIDE.md) and as a printable [PDF](https://github.com/Dialsoft/pdfscout-releases/raw/main/PDF-Scout-User-Guide.pdf).

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

## What's new in 1.6.2

- Dragging a page to a second PDF Scout window: the page's picture now travels with the mouse all the way across, so you can see what you are carrying.
- Help tab > User Guide now opens the guide on dialsoft.com, where the video tour plays right on the page.

See [CHANGELOG.md](CHANGELOG.md) for every version.

**Checksums (SHA-256):**

- PDFScout-Setup.exe: `70a1d948c5019b98d21ba4725f3d2b6c816e1d1bd0efe1462e9d2891cb42e5d2`
- PDFScout.exe: `7d63ac2abca3af9b3969fc5716f7c2ba7b9a851dd967ece6cb5e0ddce57187a6`

## Open-source notice

PDF Scout includes the PDFium library (© The PDFium Authors and others), which draws the pages and reads their text.
PDFium and the components inside it are open-source software; their license notices are in
[THIRD-PARTY-NOTICES.txt](THIRD-PARTY-NOTICES.txt). Those licenses cover PDFium only, not the rest of PDF Scout.

---
© 2026 Dialsoft LLC — Marc Frega, Wharton NJ. All rights reserved.
