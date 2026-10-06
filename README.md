# Marginalia

**Read it. Mark it. Keep it in one book.**

Marginalia is a PDF reader for studying. You highlight text, attach notes to the highlights, write on a notebook page that sits beside every PDF page, draw on the pages, bookmark places, search everything, and review with flashcards. All of it is saved together with the PDF in a single **`.mar` book**, so you can share one file and the other person gets the PDF *and* everything you added.

It is one self-contained HTML file. There is nothing to install and no account. Your files never leave your device.

*This document describes version 47.*

---

## Contents

1. [Quick start](#quick-start)
2. [The top bar at a glance](#the-top-bar-at-a-glance)
3. [The quick tour](#the-quick-tour)
4. [Opening books](#opening-books)
5. [Saving, AutoSave and the `.mar` book](#saving-autosave-and-the-mar-book)
6. [Reading](#reading)
7. [Searching the book](#searching-the-book)
8. [Bookmarks](#bookmarks)
9. [Highlights and notes](#highlights-and-notes)
10. [Notebook pages](#notebook-pages)
11. [Formatting, pasting from Word, and pictures](#formatting-pasting-from-word-and-pictures)
12. [Drawing on pages](#drawing-on-pages)
13. [Split view](#split-view)
14. [Studying: flashcards, progress and the study timer](#studying-flashcards-progress-and-the-study-timer)
15. [Exporting and sharing notes](#exporting-and-sharing-notes)
16. [Backups and earlier versions](#backups-and-earlier-versions)
17. [Working with several books](#working-with-several-books)
18. [Appearance settings](#appearance-settings)
19. [Keyboard shortcuts](#keyboard-shortcuts)
20. [Browser and device support](#browser-and-device-support)
21. [The `.mar` file format](#the-mar-file-format)
22. [Large files](#large-files)
23. [Where your data is stored](#where-your-data-is-stored)
24. [Hosting it on GitHub Pages](#hosting-it-on-github-pages)
25. [Limitations](#limitations)
26. [What's new since version 35](#whats-new-since-version-35)

---

## Quick start

> **First time here?** A short guided tour starts by itself on your first visit. Press **Skip tour** to close it, or **Esc**. You can replay it any time with the **?** button in the top bar.

1. Open the app and click **Open a book**.
2. Choose a PDF (or a `.mar` book).
3. Select some text and pick a highlight colour. Write a note in the window that opens.
4. Press **Save**. The first time, choose where to create your `.mar` book.
5. From then on, **Save** and **AutoSave** keep that `.mar` file up to date. Share just that one file.

Your original PDF is never modified.

---

## The top bar at a glance

From left to right:

| Group | Button | What it does |
|---|---|---|
| Left | **Menu** | Show or hide the side panel (Contents and Notes). |
| Left | **Folder** | Open a book (PDF or `.mar`). |
| Left | **✎** | [Draw on the pages](#drawing-on-pages): pen, colours, eraser. |
| Left | **◫** | [Split view](#split-view): a floating reference pane. |
| Left | **⏱** | [Progress and the study timer](#studying-flashcards-progress-and-the-study-timer). |
| Left | **×** | Close the current book. |
| Left | Book name | The title of the open book. |
| Centre | **‹ ›** and page box | Previous and next page. Type a number to jump. The total pages are shown after the box. |
| Centre | **🔍** | [Search](#searching-the-book) the book, your notes and your notebook pages. |
| Centre | **🔖** | [Bookmarks](#bookmarks). |
| Centre | **− / +** | Zoom out and in. The percentage is shown between them. |
| Right | **Notebook** | Show or hide [notebook pages](#notebook-pages). |
| Right | **AutoSave** | The [AutoSave](#saving-autosave-and-the-mar-book) switch and its state. |
| Right | **Aa** | Text darkness. |
| Right | **◐** | Dark or white PDF pages in dark mode. |
| Right | **Person** | Your [student name](#student-name). |
| Right | **?** | Replay the [quick tour](#the-quick-tour). |
| Right | **Moon / sun** | Light or dark theme. |
| Right | **Save** | Save the book. A dot on it means there are unsaved changes. |
| Right | **▾** | [Backups and earlier versions](#backups-and-earlier-versions). |

The study buttons (✎ ◫ ⏱ 🔍 🔖 ▾) each open one small panel directly under the button you pressed. Press the same button again, click outside the panel, or press **Esc** to close it.

On phones the top bar scrolls sideways, and a few buttons are hidden to save space (title, zoom, previous/next, close, Aa, ◐, AutoSave and Notebook).

---

## The quick tour

Marginalia has a short interactive tour (9 steps) that highlights the main buttons one at a time: opening a book, the tabs, highlighting and notes, notebook pages, Save, AutoSave, and your name and theme.

* **It starts by itself** the first time you open the app in a browser.
* **Skip tour** (bottom left of the tour card) or **Esc** closes it at any step. The app remembers that you have seen it, so it does not start again by itself.
* **Next / Back** move between steps. You can also use the **Right / Left arrow keys**.
* **To restart it:** press the **?** button in the top bar, or the **Take the quick tour** link on the start screen (when no book is open).
* The tour is remembered per browser. If you clear the site's data, it starts again on your next visit.

---

## Opening books

You can open two kinds of file:

* a **PDF** file
* a **Marginalia book** (`.mar`) file

**How to open**

| Method | Steps |
|---|---|
| Open button | Click **Open a book** (centre of the empty screen) or the folder icon in the top bar. You can select several files at once. |
| Another tab | Click the **+** at the end of the book tabs. |
| Drag and drop | Drag a `.pdf` or `.mar` file onto the window. |

The Open dialog lists `.pdf` and `.mar` files only. The app remembers the last folder you opened from.

When a book opens, the app tells you how many notes it loaded.

---

## Saving, AutoSave and the `.mar` book

There is **one Save button**, and it always saves a `.mar` book.

**If you opened a PDF**

1. Press **Save** (top right).
2. A save dialog opens with the type **Marginalia book** and the name suggested from your PDF, for example `Algebra.mar`.
3. Choose a place and confirm.
4. From now on this book *is* the `.mar` file. The original PDF stays untouched.

**If you opened a `.mar` book**

* **Save** writes your changes back into the same file.

**While it saves**

* A thin bar runs under the top bar and turns **green** during a save, and the Save button is switched off for a moment so you cannot start a second save.
* When it finishes, the Save button flashes green and a short message says "Saved to …" (or "Autosaved …").
* If a save fails, the button is switched back on so you can try again.

**AutoSave**

* After the book is saved once as a `.mar`, AutoSave saves it **5 minutes after your latest change**.
* The **AutoSave** switch at the top shows the state:

| Switch | Meaning |
|---|---|
| Green, **On** | Changes are saved automatically. |
| Amber, glowing, **Save** | This book has no `.mar` file yet. Click it (or press Save) to create one. After that, AutoSave starts. |
| Amber, glowing, **Allow** | The browser needs your permission to write to the file. Click it and allow. |
| Grey, **Off** | You turned AutoSave off. Click to turn it back on. You can still press Save. |
| Grey, no file | The book was opened without a link to its file (for example by drag and drop in some browsers). Click it for steps to connect the file. |

* AutoSave never interrupts typing. It waits until you pause.
* A dot on a book's tab, and on the Save button, means the book has unsaved changes. When you close a book or the browser tab with unsaved changes, you are asked whether to save or discard.

**Sharing**

Send the `.mar` file. The other person opens it in Marginalia and sees the PDF, your highlights, notes, replies, notebook pages, pictures, drawings, bookmarks and colour headings. (To share only one colour of notes, see [Exporting and sharing notes](#exporting-and-sharing-notes).)

---

## Reading

| Action | How |
|---|---|
| Next or previous page | **‹ ›** buttons, **Left/Right arrow keys**, or scroll. |
| Go to a page | Type a number in the page box and press Enter. |
| Zoom | **− / +** buttons, **Ctrl + mouse wheel**, trackpad pinch, or two-finger pinch on touch screens. The percentage is shown between the buttons. |
| Contents (table of contents) | Open the side panel with the **menu** button, then the **Contents** tab. Click an entry to jump. **Hover** an entry for a small scrollable preview of that page. |
| Hide or show the side panel | **Menu** button, top left. |

If a PDF has no built-in table of contents, the panel says so. Use the page box or [search](#searching-the-book) instead.

---

## Searching the book

Click **🔍** (next to the page count).

1. Type at least two letters. Searching starts a moment after you stop typing.
2. Results appear as you wait. The first results are your **notes** and **notebook pages**, then the **PDF text**, page by page. A progress line shows "Searching… page 12 of 300".
3. Each result shows a short snippet with your words marked, a label (**Note**, **Notebook** or **Text**) and the page number.
4. **Click a result.** The book jumps to that page. If the result is a note, the note opens. The matching words **blink in the accent colour** for a couple of seconds, in the PDF text, on the notebook page and inside the note. Nothing is added to your notes.

Details:

* Search looks inside the **open book** only.
* It finds up to **3 matches per PDF page** and stops after **300 results**. The result line tells you if the limit was reached ("first 300").
* Notes are searched by their highlighted text and the note you wrote (replies are not searched).
* The last **5 searches** are remembered and listed (with a 🕘) whenever the search box is empty. Click one to run it again. Pressing **Enter** also remembers the search.
* The first search in a large book reads every page's text, so it takes a little longer. Page text is kept in memory afterwards, so later searches are faster.

---

## Bookmarks

Click **🔖** (next to the search button).

* Type an optional label, then press **Bookmark this page**. Without a label the bookmark is called "Page N".
* Bookmarks are listed in page order. **Click** one to jump to it. **✕** removes it.
* Bookmarks are saved in the `.mar` book, are listed at the top of an [exported notes document](#exporting-and-sharing-notes), and are included in [backups and earlier versions](#backups-and-earlier-versions).

---

## Highlights and notes

### Make a highlight

1. **Select text** in the PDF with the mouse or your finger.
2. A small colour bar appears. Click a colour.
3. The note window opens, ready for typing.

### Write the note

* Type in the note window. It has its own formatting bar (see [Formatting](#formatting-pasting-from-word-and-pictures)).
* Click **Save the note** to finish.
* The note records who wrote it and when, using your [student name](#student-name).

### Open, edit or delete later

| Action | How |
|---|---|
| Open a note | Click the highlight. |
| Edit | Open the note, then **Edit the note** (or **Write the note** if empty). |
| Change colour | Click another colour dot at the top of the note window. |
| Delete | Click the **bin** icon in the note window and confirm. This removes the highlight and its note. |
| Close | **×** in the note window, or press **Esc**. |

### Replies and citations (inside every note window)

At the bottom of every note window:

* **Copy citation** copies the highlighted text with its source, for example `“the highlighted words” (Algebra, p. 14)`, ready to paste into an essay.
* **Replies:** type in the reply box and press **Enter** to add a reply to the note. Replies are shown under the note as "↳ Name: text" and are signed with your [student name](#student-name) (or "Reader" if you have not set one). Use them for a teacher or a friend answering your note, or for a conversation in a shared book.
* Replies are saved with the note in the `.mar` book and appear in the exported notes document.

### Colours and what they mean

Each book has its own set of highlight colours, and each colour can carry a **heading** (for example "Definition", "Exam", "Doubt").

1. In the colour bar that appears after you select text, click the **gear** icon.
2. Change a colour with the picker, type a heading, add a colour with **+ Add colour**, or remove one with the bin icon.
3. A book can have up to **12 colours**. They are saved inside the `.mar` book.

### The Notes list

Open the side panel and choose the **Notes** tab.

* Every note in the book is listed with its page, colour heading, author, date, the highlighted text and the start of your note.
* **Click** a note to jump to it and open it.
* Use the **colour chips** at the top to show only one colour, or **All**.
* At the top of the Notes tab are two buttons: **🃏 Study** (flashcards) and **⤓ Export** (see [Studying](#studying-flashcards-progress-and-the-study-timer) and [Exporting](#exporting-and-sharing-notes)).

---

## Notebook pages

A **notebook page** is a ruled sheet of paper shown **beside every PDF page**. Use it for your own summary of that page.

| Action | How |
|---|---|
| Turn notebook pages on or off | The **Notebook** button in the top bar. |
| Write | Click the notebook page and type. The writing uses a handwriting font and follows the ruled lines. |
| Search it | The [search](#searching-the-book) panel also looks inside your notebook pages. |
| Where it is saved | Inside your `.mar` book, with everything else. |

Notes about availability:

* On laptops and larger screens the notebook is on by default.
* On phones the notebook pages are not shown. Highlights and notes still work.
* In the saved file, other PDF programs do not see notebook text. It belongs to the `.mar` book.

---

## Formatting, pasting from Word, and pictures

Both the **note window** and the **notebook pages** have a formatting bar.

| Button | What it does |
|---|---|
| **B**, *I*, <u>U</u>, ~~S~~ | Bold, italic, underline, strikethrough. |
| • List, 1. List | Bullet and numbered lists. |
| ⇤ and ⇥ | Outdent and indent (nested lists). |
| **H** | Heading. |
| **A** (colour) | Text colour. |
| **▮** (colour) | Highlight colour for text. |
| 🖼 Image | Insert a picture. |
| ✕ Image | Remove the picture you clicked. |
| Clear | Remove formatting. |

In the notebook, the bar appears when you click into a page. On very narrow windows it is hidden; the note window keeps its own bar.

**Shortcuts while writing**

* Type `- ` and a space at the start of a line to begin a bullet list.
* Type `1. ` and a space to begin a numbered list.
* **Tab** indents a list item, **Shift + Tab** outdents.
* **Ctrl/Cmd + B, I, U** for bold, italic, underline.

### Pasting from Microsoft Word

You can paste formatted Word content straight into a note or a notebook page.

* **Kept:** bold, italic, underline, strikethrough, subscript and superscript, headings, bullet and numbered lists **including nested levels**, **tables** (with borders and merged cells), links, text colour and highlight colour.
* **Equations:** Word sends equations to the clipboard as small pictures. They are kept as inline images at their original size.
* **Pictures that arrive together with text** from Word or a web page may not come across, because those programs do not pass them on in a usable form. Copy the picture on its own and paste it, or use the **Image** button.

### Pictures

Three ways to add a picture to a note or notebook page:

1. Click **🖼 Image** and choose one or several files.
2. **Paste** a picture (for example a screenshot).
3. **Drag and drop** an image file into the writing area.

Pictures are shrunk to at most 1200 px and compressed, then stored inside the `.mar` book. Many large pictures make the file bigger.

**To remove a picture:** click it (it becomes selected) and press **Delete** or **Backspace**, or press the **✕ Image** button.

---

## Drawing on pages

Click **✎** to draw or write on the PDF pages with a pen, a mouse or your finger.

1. Press **Turn pen on**. The ✎ button lights up while the pen is on.
2. Pick a colour: red, blue, green, black or yellow.
3. Pick a thickness: **Thin**, **Medium** or **Thick**.
4. Draw on any page.

Other controls in the panel:

| Control | What it does |
|---|---|
| **Eraser** | Rub over a stroke to remove it. Turning the eraser on also turns the pen on. |
| **Undo last stroke (page N)** | Removes the most recent stroke on the page you are on. |
| **Clear page N** | Removes all drawing on that page (asks you to confirm). |
| **Pen is ON – turn off** | Switches drawing off. |

Good to know:

* **While the pen is on, you cannot select text or click highlights**, and touching the page draws instead of scrolling. Turn the pen off to go back to normal reading.
* Strokes are stored as proportions of the page, so they stay in the right place at every zoom level.
* Drawings are saved in the `.mar` book and are included in the [exported notes document](#exporting-and-sharing-notes) as pictures of the drawn pages.
* Drawing works on the **PDF page**, not on the notebook page.
* Drawings are **not** part of the automatic backups and the earlier saved versions (see [Backups and earlier versions](#backups-and-earlier-versions)).

---

## Split view

Click **◫**, then **Open split view**. A floating **reference pane** appears at the bottom left, so you can look at one page while working on another. For example, keep a formula sheet or an earlier chapter open beside your work.

* Choose **any open book** from the drop-down at the top of the pane.
* Move through its pages with **‹ ›** or type a page number.
* Zoom with **− / +**, or press **Fit** to fit the pane's width.
* **Drag the pane's bottom-right corner** to resize it.
* Close it with **✕** on the pane, or **◫ → Close split view**.

The pane shows the plain PDF page. It does not show highlights, notes, notebook pages or drawings, and it does not follow the page you are reading.

---

## Studying: flashcards, progress and the study timer

### Flashcards

Open the side panel, choose the **Notes** tab, and press **🃏 Study**.

* Every highlight becomes a card: the **highlighted text** on the front, **your note** on the back (or "(no note written)").
* **Flip** shows the other side. **Prev** and **Next** move through the cards (the counter shows "3 / 25 · page 14"). **Shuffle** mixes the order.
* Shuffling only changes the order of the cards you are looking at. Your notes are not rearranged.
* If the book has no highlights yet, the panel tells you to make some first.

### Progress

Click **⏱**.

* **Pages visited** (for example "42 of 300, 14%"), with a progress bar.
* **Time reading**, in minutes.
* **Study sessions finished**.

How it is counted: every 15 seconds, while the page is visible, the app adds 15 seconds to the reading time and counts the page you are on as visited. A page you only scroll past quickly may not be counted.

### 25-minute study timer

In the same panel, press **Start 25-minute study timer**.

* When 25 minutes are up, a message says "Study session done. Take a 5 minute break." and the session is added to your count.
* Press **Stop study timer** to cancel it.
* The timer runs only while the app is open. Closing the tab cancels it.

Progress and finished sessions are saved in the `.mar` book. Reading time and visited pages on their own do not mark the book as changed, so they are saved the next time the book is saved for any reason.

---

## Exporting and sharing notes

Open the side panel, choose the **Notes** tab, and press **⤓ Export**. Choose **All colours** or one colour from the list first if you want to limit the output.

| Button | What you get |
|---|---|
| **Export notes** | Downloads `<book name>-notes.html`. It lists your highlights and notes **grouped by colour heading and then by page**, each with the page, author, date, the highlighted text, your note (with its formatting and pictures) and any replies. A **Bookmarks** list comes first. If the book has drawings, the drawn pages follow as pictures under **Drawings**. Open the file in a browser and print it, or choose *Save as PDF*, to get a document. |
| **Copy quotes with citations** | Copies all highlighted quotes (or just the chosen colour), each as `“quote” (Book, p. N)`, one after another. Paste them straight into an essay. |
| **Share .mar with this colour only** | Pick one colour first. Downloads a new `.mar` named like `Algebra-Definition.mar`. It contains the PDF and **only the notes of that colour**, and no version history. Your own book is not changed. |

Good to know about the colour-only share:

* It still includes your **notebook pages, bookmarks, drawings and reading progress**. Only the highlights and notes are filtered by colour.
* The exported notes document does not include notebook pages.
* The exported notes document always includes the drawings, whichever colour you chose.

---

## Backups and earlier versions

Click **▾** (next to Save). The panel lists:

* **Currently open ✓**: what is on screen now, and whether it has unsaved changes.
* **Automatic backup of unsaved work**: while a book has unsaved changes, a copy of your highlights, notes, notebook pages, colours and bookmarks is stored in the browser **every minute**. If the browser or computer crashes, reopen the book and restore it from here.
* **Earlier saved version** (up to **3**): each time you save into an existing `.mar` book, the previously saved state is kept inside the book.

To go back to one of them, press **Restore this** and confirm. Your current notes are backed up first, so you can undo a restore. After restoring, press **Save** to keep it.

Good to know:

* Backups and earlier versions cover **highlights, notes, notebook pages, colours and bookmarks**. They do **not** cover drawings or reading progress.
* Earlier versions are not kept if your notes data (pictures included) is larger than about 2 MB, so the file does not grow too much.
* There is one automatic backup slot per **file name**. Two different books with the same file name share a slot.
* The panel only lists versions that differ from what is currently open.

---

## Working with several books

* Every open book gets a **tab** under the top bar. Click a tab to switch.
* Close a book with the **×** on its tab, or the **×** in the top bar.
* **Keyboard switching:** hold **N** and press **Tab** to move to the most recently used book. Keep pressing Tab to go further back. Add **Shift** to go the other way. (This works like Alt+Tab.)
* Each book keeps its own page, zoom level, notes, notebook pages, colours, bookmarks, drawings and progress.
* The [split view](#split-view) can show a page from any of the open books.

---

## Appearance settings

| Button | What it does |
|---|---|
| **Moon / sun** | Light or dark theme. |
| **◐** | In dark mode, show PDF pages dark or keep them white. Your choice is remembered. |
| **Aa** | Text darkness: *Normal*, *Bold*, *Extra bold*. Click to cycle. Useful for thin or faint scans. |
| **Notebook** | Show or hide notebook pages. |

### Student name

Click the **person** button, type your name and press **Save name**. It is added to every note and reply you create, so people you share the book with can see who wrote what.

---

## Keyboard shortcuts

| Keys | Action |
|---|---|
| Left / Right arrow | Previous / next page (when not typing) |
| Ctrl + mouse wheel | Zoom |
| Esc | Close the note window, the colour bar or a study panel |
| N + Tab, N + Shift + Tab | Switch between open books |
| Ctrl/Cmd + B / I / U | Bold / italic / underline while writing |
| Tab / Shift + Tab | Indent / outdent in lists |
| `- ` or `1. ` + space | Start a bullet / numbered list |
| Delete / Backspace | Remove a selected picture |
| Enter (in the search box) | Remember the search |
| Enter (in a reply box) | Add the reply |

---

## Browser and device support

Marginalia runs in a modern browser. How *saving* works depends on the browser:

| Browser | Open | Save and AutoSave |
|---|---|---|
| Chrome, Edge (Windows, macOS, Linux, ChromeOS) | Yes | **Direct save into the `.mar` file, with AutoSave.** The save dialog shows the type "Marginalia book". |
| Firefox, Safari (desktop) | Yes | **Save downloads** a new `.mar` file each time. No AutoSave. Replace your old copy with the download. |
| iPhone, iPad, Android | Yes | **Save downloads** a new `.mar` file. No AutoSave. The system decides how the downloaded type is labelled. |

Mobile file pickers sometimes do not list `.mar` files by name. If you cannot see it, choose "All files" in the system picker.

> Only Chrome and Edge have been designed for direct saving. Other browsers use the download method.

Other features and what they need:

| Feature | Needs |
|---|---|
| Drawing | Pen, mouse or touch input (any modern browser). |
| Search blink (the flashing matches) | A browser with the *CSS Custom Highlight API* (recent Chrome, Edge, Safari and Firefox). In older browsers the result still opens on the right page, but the words do not blink. |
| Automatic backups | Browser storage (IndexedDB). It may be unavailable in private browsing windows, in which case backups are skipped silently. |

---

## The `.mar` file format

A `.mar` file is a single file with three parts:

```
[ header : 2048 bytes ][ your original PDF, unchanged ][ notes data ]
```

* **Header:** a signature that identifies a Marginalia book, plus the sizes and a checksum of the notes data. It is padded so other PDF programs do not mistake the file for a PDF.
* **PDF:** the exact bytes of the PDF you opened.
* **Notes data:** a compressed (gzip) JSON document holding:
  * your highlights and notes, with their replies,
  * notebook pages (with pictures),
  * colour headings,
  * bookmarks,
  * drawings (strokes stored per page),
  * reading progress (pages visited, reading time, finished study sessions),
  * the last 3 earlier saved versions of the notes.

Good to know:

* Books saved by older versions still open. Anything they do not have (bookmarks, drawings, progress, history) simply starts empty.
* The file is meant to be opened by Marginalia only. Other programs will not read it.
* It is **not encrypted**. Anyone with the file and this app can read it.
* A damaged or cut-off `.mar` file gives a clear error instead of opening wrongly.
* If something else changes the `.mar` file on disk while it is open, Save refuses instead of overwriting it, and your unsaved notes stay on screen.

---

## Large files

* A PDF is read into memory once when you open it, and no extra copy is kept.
* When saving a `.mar` book, the PDF part is **copied by the browser straight from the file on disk**, so it is not loaded into memory again. Only the small notes part is rebuilt.
* The browser still writes the whole file each time you save, so saving a very large book takes a few seconds of disk work.
* PDFs over about 120 MB skip a slow check for notes embedded by older versions of this app, unless they are plainly visible.
* Earlier saved versions add up to three more copies of the notes data (not the PDF) to the file. They are skipped when the notes data is larger than about 2 MB.
* The first [search](#searching-the-book) in a big book reads the text of every page, which takes a moment.
* The [split view](#split-view) draws one page at a time, so it adds little memory.

Very large books depend on your device's memory. Test with a copy of your file first.

---

## Where your data is stored

| What | Where |
|---|---|
| Your PDF, highlights, notes, replies, notebook pages, pictures, drawings, bookmarks, progress, colours, earlier versions | In the `.mar` file you saved, on your device. |
| Automatic backup of unsaved work | In your browser's storage (IndexedDB) on this device. |
| Your last 5 searches, your student name, theme, text darkness, notebook on/off, AutoSave on/off | In your browser's local storage on this device. |

Nothing is uploaded. There is no server and no account. The app only contacts public CDNs to load its libraries and fonts (see below).

---

## Hosting it on GitHub Pages

Marginalia is a single HTML file, so it works well on GitHub Pages.

1. Put the app file in your repository and rename it **`index.html`**.
2. In the repository, go to **Settings → Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**, pick your branch and the `/ (root)` folder, then **Save**.
4. Open the link GitHub gives you (it uses `https://`, which direct saving needs).

**Internet needed for the libraries:** the app loads PDF.js, pdf-lib and the fonts from public CDNs (cdnjs and Google Fonts). If you want a fully offline copy, download those files into your repository and change the `<script>` and font links at the top of the file to point to them.

Direct saving into files needs a secure address (`https://` or `localhost`). If you only double-click the HTML file, some browsers may behave differently.

---

## Limitations

* Notes and highlights are stored in the `.mar` book, not inside the PDF. Other PDF readers will not show them.
* Notebook pages are hidden on phones.
* AutoSave and direct saving are available in Chrome and Edge on computers only.
* Pictures pasted together with text from Word or the web are not carried over. Paste or insert them separately.
* The Open dialog on phones is controlled by the system and may not filter by `.mar`.
* **Search** reads the PDF's text layer. Scanned pages without text cannot be searched. Replies are not searched.
* **Drawings and reading progress** are not included in automatic backups or earlier versions.
* **Reading progress** changes alone do not trigger AutoSave. They are saved the next time the book is saved for another reason.
* **Drawing** works on PDF pages only, not on notebook pages, and it turns off text selection while the pen is on.
* **Split view** shows plain pages only (no highlights, notes, notebook or drawings).
* The **exported notes document** does not include notebook pages.
* **Sharing one colour** still includes your notebook pages, bookmarks, drawings and progress.
* The **study timer** is not saved if you close the app before it finishes.
* There is **one automatic backup slot per file name**.

---

## What's new since version 35

**New features**

* **Quick tour** for first-time visitors, with Skip tour and a **?** button to replay it.
* **Search** across the PDF text, your notes and your notebook pages, with recent searches and blinking matches.
* **Bookmarks** with optional labels.
* **Drawing** on pages: pen, five colours, three thicknesses, eraser, undo and clear page.
* **Split view**: a resizable floating reference pane that can show any page of any open book.
* **Flashcards** made from your highlights, with flip, previous, next and shuffle.
* **Progress and study timer**: pages visited, reading time, finished sessions, and a 25-minute timer.
* **Replies** under every note, and **Copy citation** inside each note window.
* **Export notes** as a printable document grouped by colour heading, **copy quotes with citations**, and **share a `.mar` with one colour only**.
* **Automatic backup** of unsaved work every minute, and **earlier saved versions** (the last 3) with a **Restore** panel.

**Changes**

* The `.mar` notes data now also stores bookmarks, drawings, progress, replies and earlier versions. Books from version 35 still open.
* Each study feature has its own button in the top bar, and the Notes tab has Study and Export buttons.
* The Save button no longer changes its label to "Saving…". Progress is shown by the bar under the top bar, which turns green during a save.
* The Save button is always switched back on after a save attempt, even if the save fails.

**Fixes**

* The unsaved-changes dot on the Save button is no longer cut off on the right. The right side of the top bar no longer shrinks.

---

## Credits

Built with [PDF.js](https://mozilla.github.io/pdf.js/) and [pdf-lib](https://pdf-lib.js.org/).

## License

Add your licence here (for example MIT).
