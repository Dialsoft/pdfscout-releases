# PDF Scout

**A small, portable PDF reader for Windows 10 and 11** that can find and copy text and rearrange pages — one file, nothing to install.
By Dialsoft LLC.

## Download

PDF Scout 1.5.1 comes two ways. Both are the same program.

- **[PDFScout-Setup.exe](https://github.com/Dialsoft/pdfscout-releases/raw/main/PDFScout-Setup.exe)** — the installer (7.0 MB). Adds PDF Scout to the Start menu and to Windows "Installed apps", with an uninstaller. It asks whether to install for **just you** (no administrator needed) or for **everyone who uses the PC** (asks for an administrator).
- **[PDFScout.exe](https://github.com/Dialsoft/pdfscout-releases/raw/main/PDFScout.exe)** — the portable copy (4.5 MB). Nothing to install: put it somewhere like your Desktop, Downloads or `C:\Tools` (not Program Files, so it can keep itself up to date) and double-click it.

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
- Continuous scrolling, zoom, Fit Width, Fit Page, Actual Size, Go to page
- Rotate sideways scans left or right
- Print all pages, the current page or a range, fit to paper or actual size
- Password-protected PDFs
- Can be your default PDF app: Settings tab > Set as default PDF app
- Send the PDF to someone by email (straight through your own mail server, attached), or a note by text message, WhatsApp, Messenger or Teams
- Keeps itself up to date automatically (checks at start and every 6 hours; you choose when to install)

## What's new in 1.5.1

- New: PDF Scout now comes two ways. PDFScout.exe is the portable copy, as before. PDFScout-Setup.exe is an installer: it adds PDF Scout to the Start menu (and the Desktop if you like), lists it under Windows "Installed apps" with an uninstaller, and adds it to "Open with" for PDFs.
- The installer asks who PDF Scout is for. "Just me" needs no administrator password. "Everyone who uses this PC" installs into Program Files and asks Windows for an administrator's permission.
- Installed copies keep themselves up to date too: Update now downloads the new installer, checks it, and runs it quietly. A copy installed for everyone asks for an administrator's permission each time it updates.
- For IT: PDFScout-Setup.exe /S installs without showing anything (/ALLUSERS for everyone, /DESKTOP for a Desktop shortcut, /NOUPDATES to switch off automatic update checks on PCs you update yourself). Uninstall.exe /S removes it the same way.
- An installed copy uses the PDF engine the installer put next to it, so nothing has to be unpacked the first time it runs.
- Help > Diagnostic Report now says whether the copy is portable or installed.
- If you use the portable copy, nothing changes for you.

See [CHANGELOG.md](CHANGELOG.md) for every version.

**Checksums (SHA-256):**

- PDFScout-Setup.exe: `6967b7756fbdaeec6b53cfe36750d1cf785d800ce3e9d81215ebdf374a92ff49`
- PDFScout.exe: `313547ee4f370176dd269b280df81c1ccd0db3a0a7231a7fc0b20c3038d43b75`

## Open-source notice

PDF Scout includes the PDFium library (© The PDFium Authors and others), which draws the pages and reads their text.
PDFium and the components inside it are open-source software; their license notices are in
[THIRD-PARTY-NOTICES.txt](THIRD-PARTY-NOTICES.txt). Those licenses cover PDFium only, not the rest of PDF Scout.

---
© 2026 Dialsoft LLC — Marc Frega, Wharton NJ. All rights reserved.
