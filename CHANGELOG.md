## 1.5.1 (2026-11-16)
- New: PDF Scout now comes two ways. PDFScout.exe is the portable copy, as before. PDFScout-Setup.exe is an installer: it adds PDF Scout to the Start menu (and the Desktop if you like), lists it under Windows "Installed apps" with an uninstaller, and adds it to "Open with" for PDFs.
- The installer asks who PDF Scout is for. "Just me" needs no administrator password. "Everyone who uses this PC" installs into Program Files and asks Windows for an administrator's permission.
- Installed copies keep themselves up to date too: Update now downloads the new installer, checks it, and runs it quietly. A copy installed for everyone asks for an administrator's permission each time it updates.
- For IT: PDFScout-Setup.exe /S installs without showing anything (/ALLUSERS for everyone, /DESKTOP for a Desktop shortcut, /NOUPDATES to switch off automatic update checks on PCs you update yourself). Uninstall.exe /S removes it the same way.
- An installed copy uses the PDF engine the installer put next to it, so nothing has to be unpacked the first time it runs.
- Help > Diagnostic Report now says whether the copy is portable or installed.
- If you use the portable copy, nothing changes for you.

## 1.5.0 (2026-11-16)
- PDF Scout now has its own PDF engine built in: PDFium, the open-source engine Google Chrome uses. Pages, page-panel pictures and printouts are drawn by it, so PDF Scout no longer depends on the PDF engine inside Windows and looks the same on every PC. It is still one portable EXE (now about 4.7 MB); the first time it runs it unpacks the engine into your user profile.
- New: Find (Home tab, or Ctrl+F). Type a word or phrase and every match in the document is highlighted; Next and Previous (F3 / Shift+F3, or Enter / Shift+Enter) step through them.
- New: select and copy text. Drag across text to select it, double-click to select a word, Ctrl+A to select everything, Ctrl+C to copy. Right-click a page for a menu with Copy, Select All and Find.
- New: links work. Click a link inside a PDF to jump to the page it points to. A link to a web address shows you the real address and asks before opening your browser.
- New: bookmarks. If a PDF has its own table of contents, click Bookmarks at the top of the side panel and click an entry to jump there. The part you're reading is highlighted.
- The Page Panel button moved from the Home tab to the Organize tab to make room for Find (F4 still shows and hides the panel).
- PDFium needs 64-bit Windows 10 or 11. On Windows 8.1, or if the engine can't be unpacked, PDF Scout uses the Windows engine as before: pages show and print, but Find, copy, links and bookmarks are off. Help > Diagnostic Report says which engine is in use.
- Scanned documents are pictures of text, so there is nothing to find or copy in them unless they were saved as "searchable".

## 1.4.2 (2026-11-15)
- New: Help tab > Diagnostic Report. If something doesn't work on your PC, do the thing that fails and then click it. PDF Scout saves a text file on your Desktop (and copies it to the clipboard) describing what it has been doing, so the problem can be tracked down. It contains nothing from inside your documents.
- The page panel can no longer be left waiting behind the big pages: after each big page is drawn, a page-panel picture gets its turn.
- While a page-panel picture is still being drawn, the panel shows a shrunken copy of the big page if that has already been drawn, instead of a blank box.
- PDF Scout now decides whether a page picture is up to date from the size it asked Windows for, so a picture that comes back a pixel off is never redrawn over and over.

## 1.4.1 (2026-11-15)
- Fixed: the large help tooltip no longer pops up on top of the page panel. In 1.4.0 it appeared whenever the mouse rested on the panel and covered the pages, which made dragging look like it wasn't working. The help text now appears only when you point at the "Pages" heading at the top of the panel.
- While you drag a page in the page panel, a see-through copy of the page now follows the mouse, along with the blue bar that shows where it will land.
- The page panel has a "Pages — drag to reorder" heading.

## 1.4.0 (2026-11-14)
- New page panel: a strip down the right side of the window shows a small picture of every page. Click a page to jump to it. Hide or show the panel with Page Panel on the Home or Organize tab, or press F4.
- Rearrange pages: drag a page up or down in the page panel and drop it where you want it. A blue bar shows where it will land, the list scrolls by itself near the top and bottom, and Esc cancels.
- New Organize tab: Move Up, Move Down, Move to Front and Move to Back for the selected page (Alt+Up, Alt+Down, Alt+Home, Alt+End), and Undo Move (Ctrl+Z) to take moves back one at a time.
- Save (Ctrl+S) writes the new page order into the PDF; Save As (Ctrl+Shift+S) writes a new file and leaves the original alone. A * in the title bar means the new order hasn't been saved, and PDF Scout asks before closing, opening another PDF, sending or updating with unsaved changes.
- Saving is careful: PDF Scout writes the new file next to the old one, has Windows read it back to check every page, and only then replaces the old file. Pictures, text, bookmarks and form fields stay exactly as they were. Only the order of the pages changes.
- Printing follows the order on screen, including moves you haven't saved yet.
- Password-protected PDFs can still be read and printed, but their pages can't be rearranged.

## 1.3.0 (2026-11-13)
- Set as default PDF app: a new button on the Settings tab makes PDF Scout the program that opens when you double-click a PDF. Windows 10 and 11 make you confirm the choice yourself, so PDF Scout adds itself to Windows' list of PDF programs, opens the right Windows screen and tells you exactly what to click. "Default: yes / no" next to the button shows the current state and updates by itself.
- If you move PDFScout.exe to another folder, it repairs its link with Windows the next time you start it.
- Compatibility fix: PDF Scout now starts on Windows 8.1 again (it was asking Windows for a function in a place where only Windows 10 and 11 keep it).
- Spelling in the program now follows American English throughout.

## 1.2.0 (2026-11-06)
- New Send window (Share tab): pick a saved person or type a new one, choose whether to send the PDF you're reading or a note about PDF Scout, and send it.
- Email is sent by PDF Scout itself, straight through your own mail server, with the PDF attached. Set up the server once with Share > Email Server; your password is encrypted by Windows, and "Send test email" checks the settings.
- Text messages: PDF Scout opens Windows Phone Link, types the person's number and the message, and presses Send for you (you can switch off the automatic Send). If TextDesk is running, the text goes through TextDesk instead. If anything goes wrong, the message is copied so you can finish in Phone Link.
- WhatsApp, Facebook Messenger and Microsoft Teams open straight to a chat with the person, with the message typed. When you're sending the PDF it's copied, so you just press Ctrl+V in the chat. Gmail and Outlook.com open a new email already addressed to them.
- People you send to are remembered (name, email, mobile number, Messenger name) and can be picked from the To box; "Forget person" removes one.
- New Share tab layout with Send, Email, Text Message, WhatsApp, Messenger, Teams, Copy Link, Show in Folder and Email Server buttons.

## 1.1.0 (2026-11-05)
- New ribbon interface with Home, Settings, Share and Help tabs and color icons for every function, matching the other Dialsoft tools.
- Automatic updates: PDF Scout checks for a new version when it starts and every 6 hours. A yellow bar offers "Update now", the download is verified (SHA-256 checksum and version check), and PDF Scout swaps itself in and restarts with the same PDF open at the same page. You can turn automatic checks off on the Settings tab.
- Settings tab (every change takes effect immediately): how new documents open (fit width, fit page or 100%), reopen the last PDF at the page you left, background color, page shadows, print size, print quality and automatic page turning when printing.
- Share tab: tell someone about PDF Scout by email, Gmail, Outlook.com, Facebook Messenger, WhatsApp, text message or Microsoft Teams, email the PDF you're reading as an attachment, or show it in File Explorer.
- Release notes: Help > Release Notes lists what changed in every version, and after an update PDF Scout shows what's new automatically.
- PDF Scout remembers its window size and position.

## 1.0.0 (2026-11-04)
- First release: a tiny, portable, single-EXE PDF viewer that uses the PDF engine built into Windows 10 and 11.
- Open by File > Open, drag and drop, or "Open with"; continuous scrolling; zoom, fit width, fit page; rotate left and right; print all pages, the current page or a page range; password-protected PDFs.
