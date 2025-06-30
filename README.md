# PDF Title Cleaner

🧹 A simple browser-based tool to **remove the Title metadata** from one or more PDF files.  
This helps ensure that **Google Chrome and other browsers display the filename** in the tab title, instead of the embedded document title.

## 🌟 Features

- ✔️ Batch process multiple PDF files in your browser (no upload to server)
- ✔️ Automatically removes the `/Title` field from PDF metadata
- ✔️ Allows individual download or one-click ZIP download of all processed files
- ✔️ Works entirely offline (just open the HTML file in a browser)

## 🤔 Why This Tool?

Chrome tends to display the PDF’s internal **Title metadata** in the tab, rather than the filename.  
This becomes confusing when working with multiple PDFs that have generic or identical titles.  
This tool solves that by stripping the title field from the metadata.

## 🚀 How to Use

1. Open `index.html` in your browser
2. Upload one or more PDF files
3. Click:
   - Download links for individual files
   - Or click **Download ZIP** to get all processed files at once

## 🛠️ Technologies Used

- [pdf-lib](https://github.com/Hopding/pdf-lib) — PDF editing in browser
- [JSZip](https://github.com/Stuk/jszip) — Client-side ZIP archive generation
- Pure HTML + JS, no frameworks or dependencies required

## 📅 Developed

June 30, 2025

---

Feel free to use, modify, or improve it. No license restrictions.
