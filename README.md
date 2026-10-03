# Marginalia

**Read it. Mark it. Keep it in one book.**

Marginalia is a PDF reader for studying. You highlight text, attach notes to the highlights, and write on a notebook page that sits beside every PDF page. Everything you add is saved together with the PDF in a single **`.mar` book**, so you can share one file and the other person gets the PDF *and* all your notes.

It is one self-contained HTML file. There is nothing to install and no account. Your files never leave your device.

---

## Contents

1. [Quick start](#quick-start)
2. [Opening books](#opening-books)
3. [Saving, AutoSave and the `.mar` book](#saving-autosave-and-the-mar-book)
4. [Reading](#reading)
5. [Highlights and notes](#highlights-and-notes)
6. [Notebook pages](#notebook-pages)
7. [Formatting, pasting from Word, and pictures](#formatting-pasting-from-word-and-pictures)
8. [Working with several books](#working-with-several-books)
9. [Appearance settings](#appearance-settings)
10. [Keyboard shortcuts](#keyboard-shortcuts)
11. [Browser and device support](#browser-and-device-support)
12. [The `.mar` file format](#the-mar-file-format)
13. [Large files](#large-files)
14. [Hosting it on GitHub Pages](#hosting-it-on-github-pages)
15. [Limitations](#limitations)

---

## Quick start

1. Open the app and click **Open a book**.
2. Choose a PDF (or a `.mar` book).
3. Select some text and pick a highlight colour. Write a note in the window that opens.
4. Press **Save**. The first time, choose where to create your `.mar` book.
5. From then on, **Save** and **AutoSave** keep that `.mar` file up to date. Share just that one file.

Your original PDF is never modified.

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
* A dot on a book's tab means it has unsaved changes. When you close a book or the tab with unsaved changes, you are asked whether to save or discard.

**Sharing**

Send the `.mar` file. The other person opens it in Marginalia and sees the PDF, your highlights, notes, notebook pages, pictures and colour headings.

---

## Reading

| Action | How |
|---|---|
| Next or previous page | **‹ ›** buttons, **Left/Right arrow keys**, or scroll. |
| Go to a page | Type a number in the page box and press Enter. |
| Zoom | **− / +** buttons, **Ctrl + mouse wheel**, trackpad pinch, or two-finger pinch on touch screens. The percentage is shown between the buttons. |
| Contents (table of contents) | Open the side panel with the **menu** button, then the **Contents** tab. Click an entry to jump. **Hover** an entry for a small scrollable preview of that page. |
| Hide or show the side panel | **Menu** button, top left. |

If a PDF has no built-in table of contents, the panel says so. Use the page box instead.

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

---

## Notebook pages

A **notebook page** is a ruled sheet of paper shown **beside every PDF page**. Use it for your own summary of that page.

| Action | How |
|---|---|
| Turn notebook pages on or off | The **notebook** button in the top bar. |
| Write | Click the notebook page and type. The writing uses a handwriting font and follows the ruled lines. |
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

## Working with several books

* Every open book gets a **tab** under the top bar. Click a tab to switch.
* Close a book with the **×** on its tab, or the **×** in the top bar.
* **Keyboard switching:** hold **N** and press **Tab** to move to the most recently used book. Keep pressing Tab to go further back. Add **Shift** to go the other way. (This works like Alt+Tab.)
* Each book keeps its own page, zoom level, notes, notebook pages and colours.

---

## Appearance settings

| Button | What it does |
|---|---|
| **Moon / sun** | Light or dark theme. |
| **◐** | In dark mode, show PDF pages dark or keep them white. Your choice is remembered. |
| **Aa** | Text darkness: *Normal*, *Bold*, *Extra bold*. Click to cycle. Useful for thin or faint scans. |
| **Notebook** | Show or hide notebook pages. |

### Student name

Click the **person** button, type your name and press **Save name**. It is added to every note you create, so people you share the book with can see who wrote what.

---

## Keyboard shortcuts

| Keys | Action |
|---|---|
| Left / Right arrow | Previous / next page (when not typing) |
| Ctrl + mouse wheel | Zoom |
| Esc | Close the note window or colour bar |
| N + Tab, N + Shift + Tab | Switch between open books |
| Ctrl/Cmd + B / I / U | Bold / italic / underline while writing |
| Tab / Shift + Tab | Indent / outdent in lists |
| `- ` or `1. ` + space | Start a bullet / numbered list |
| Delete / Backspace | Remove a selected picture |

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

---

## The `.mar` file format

A `.mar` file is a single file with three parts:

```
[ header : 2048 bytes ][ your original PDF, unchanged ][ notes data ]
```

* **Header:** a signature that identifies a Marginalia book, plus the sizes and a checksum of the notes data. It is padded so other PDF programs do not mistake the file for a PDF.
* **PDF:** the exact bytes of the PDF you opened.
* **Notes data:** a compressed (gzip) JSON document holding your highlights, notes, notebook pages (with pictures), and colour headings.

Good to know:

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

Very large books depend on your device's memory. Test with a copy of your file first.

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

---

## Credits

Built with [PDF.js](https://mozilla.github.io/pdf.js/) and [pdf-lib](https://pdf-lib.js.org/).

## License

Add your licence here (for example MIT).
