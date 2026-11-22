## 1.8.1 (2026-11-22)
- New: a Quick Read group at the right end of the Home tab. It has the Quick Read button (F11) and, next to it, the folder Quick Read will flip through, with where you are in it, such as "PDF 3 of 12". Click the folder to open it in File Explorer with the PDF selected.
- Inside Quick Read, a small label at the bottom of the page shows the same thing: the folder being flipped through and your place in it. Click it to open the folder in File Explorer.
- A long folder path is shortened in the middle to fit; the tooltip shows all of it. In a narrow window the Home tab's Quick Read group makes room for the other buttons (the Quick Read button is always on the Organize tab too).

## 1.8.0 (2026-11-22)
- New in Quick Read (F11): sort a folder as you flip through it. Buttons at the top left of the page act on the PDF file you are looking at: Move to Folder (M), Rename (F2) and Delete (Del). After a move or a delete the next PDF in the folder appears, so you can work through a whole pile without leaving the keyboard.
- Move to Folder remembers the folder. After the first move a second button appears, Move to "that folder" (Shift+M), which files the next PDF there with one key and no questions.
- Delete sends the PDF to the Recycle Bin, so it can be brought back. It asks first; Ctrl+Del deletes right away. Nothing is ever overwritten by a move or a rename: if the name is taken, you are offered "name (2).pdf".
- Faster flipping in Quick Read: while you look at one PDF, the first page of the next and the previous PDF is drawn ahead of time, so it is on screen the moment you press the arrow. The PDF you just left is kept ready too, so going back is instant. This helps most with heavy files such as scans.
- The same file commands are on the right-click menu in Quick Read, and every button has a tooltip.

## 1.7.0 (2026-11-22)
- New: Quick Read. Press F11 (or Organize tab > Quick Read, or right-click the page) and flip through the PDFs in a folder the way the Photos app flips through pictures. The Right arrow key opens the next PDF in the same folder and the Left arrow key the previous one; or click the round arrows at the edges of the page.
- In Quick Read the ribbon and the page panel step aside so the page gets the whole window, and each PDF is shown fitted to the window. Up / Down, Page Up / Page Down and the mouse wheel still move through the pages. Esc, F11 or the Exit button brings everything back the way it was.
- Outside Quick Read, Ctrl+Right and Ctrl+Left jump to the next and previous PDF in the folder too.
- The PDFs come in name order, the way File Explorer sorts names. The status bar shows where you are, such as "PDF 3 of 12 in this folder".
- Pages that are narrower than the window (Fit Page, or zoomed out) now sit in the middle of the window instead of at its left edge.

## 1.6.3 (2026-11-17)
- New: select several pages at once in the page panel, the way File Explorer does. Ctrl+click adds a page to the selection (Ctrl+click it again to take it out), Shift+click selects every page from the last one you clicked, and Ctrl+A (after clicking a page in the panel) selects them all. Esc goes back to one page.
- Drag any selected page and they all move together, in order. A small number on the page you're dragging shows how many are coming along.
- Several pages can be taken into a second PDF Scout window in one drag: copied, or moved with Shift. They arrive together, in order, and stay selected.
- Delete Page, Move Up, Move Down, Move to Front, Move to Back and the right-click menu now work on all the selected pages. A PDF still always keeps at least one page.
- Undo (Ctrl+Z) takes back a change to several pages in one step.

## 1.6.2 (2026-11-16)
- Dragging a page to a second PDF Scout window: the page's picture now travels with the mouse all the way across, so you can see what you are carrying.
- Help tab > User Guide now opens the guide on dialsoft.com, where the video tour plays right on the page.

## 1.6.1 (2026-11-16)
- New: User Guide. Help tab > User Guide opens the full PDF Scout manual in your web browser, with a picture for every step, and a link to a short video tour.
- The built-in How to Use help (F1) is brought up to date: deleting pages, taking pages from one PDF into another, and the installer are now covered there too.

## 1.6.0 (2026-11-16)
- New: take pages from one PDF into another. Open each PDF in its own PDF Scout window (Organize tab > Second PDF opens another PDF beside the one you have and puts the two windows side by side). Then drag a page from one window's page panel and let go over the other window's page panel. A blue bar shows where it will land. It works in both directions.
- Dragging a page across copies it: it stays in the PDF it came from. Hold Shift while you let go to move it instead (it is added there and deleted here).
- New: Delete Page. Select a page and click Delete Page on the Organize tab, press Del, or right-click the page in the page panel. A PDF always keeps at least one page.
- New: right-click a page in the page panel for a menu with Delete, the Move commands and Undo.
- Undo (Ctrl+Z) now takes back deleted and brought-in pages as well as moves, one change at a time.
- Nothing changes in a PDF file until you click Save in that window. When pages were deleted or brought in, the file is written out fresh, so a deleted page is really gone from the saved file, not just hidden. Use Save As if you want to keep the original too.
- The PDF's own bookmarks and form fields are kept when you save. Pages that come from another PDF bring their pictures, text and links, but not that PDF's bookmarks or fillable-form behavior. Password-protected PDFs can't be changed or used as a source, as before.

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
