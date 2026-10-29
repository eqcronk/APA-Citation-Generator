# APA 7th Citation Generator & RIS File Manager

A web-based tool designed to create, manage, and format academic citations according to the **APA 7th Edition** guidelines. The application supports full **RIS (Research Information Systems) import and export**, allowing seamless integration with reference managers like Zotero, Mendeley, EndNote, and Paperpile.

---

## 🌟 Key Features

* **APA 7th Edition Formatting:** Automatically formats references for common source types:
  * Journal Articles
  * Books & Edited Books
  * Book Chapters
  * Webpages / Online Resources
  * Conference Papers
* **RIS File Import:** Drag-and-drop or upload `.ris` files to quickly parse and populate your bibliography.
* **RIS File Export:** Export individual references or your entire reference collection into standard `.ris` files.
* **Dynamic Citations:** Generates formatted reference list entries with hanging indents and proper sentence casing.
* **Copy to Clipboard:** Copy formatted HTML citations with preserved italics or plain text with a single click.
* **Local Reference Management:** Add, edit, search, filter, and delete entries within an interactive session workspace stored locally in your browser.

---

## 🚀 Getting Started

### Prerequisites

No installation or backend server is required. The application runs entirely in your web browser using HTML, CSS, and JavaScript.

### Usage

1. **Open the App:** Open `index.html` in any modern web browser (Google Chrome, Mozilla Firefox, Apple Safari, or Microsoft Edge).
2. **Add a Reference:** 
   * Click **"New Reference"** to manually enter source metadata (Authors, Title, Journal/Publisher, Year, Volume, Issue, Pages, DOI/URL).
3. **Import RIS:**
   * Navigate to **"Import / Export"**, drag and drop your `.ris` file, or paste raw RIS text directly into the importer window.
4. **Export RIS / Bibliography:**
   * Click **"Export List (.RIS)"** to download your bibliography as a `.ris` file.
   * Click **"Copy All (Formatted)"** to copy your full bibliography with formatted hanging indents directly into Microsoft Word or Google Docs.

---

## 📑 Supported Source Types & APA Examples

| Source Type | APA Reference Format Example |
| :--- | :--- |
| **Journal Article** | Author, A. A., & Author, B. B. (Year). Title of article. *Title of Journal*, *Volume*(Issue), Page–Page. https://doi.org/xx.xxx |
| **Book** | Author, A. A. (Year). *Title of work: Capital letter also for subtitle*. Publisher. |
| **Book Chapter** | Author, A. A. (Year). Title of chapter. In E. E. Editor (Ed.), *Title of book* (pp. xx–xx). Publisher. |
| **Webpage** | Author, A. A. (Year). *Title of work*. Website Name. URL |

---

## 🛠️ Technology Stack

* **Frontend:** HTML5, Modern JavaScript (ES6+)
* **Styling:** Tailwind CSS (via CDN)
* **Icons:** Font Awesome (via CDN)

---

## 📄 License

This project is open-source and available for personal, academic, and commercial use.