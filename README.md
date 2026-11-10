# PDF Size Compressor

A simple browser-based PDF size compressor.

## Run
1. Extract the ZIP.
2. Open `index.html` in a modern browser (Chrome, Edge, Firefox).
3. Select or drag in a PDF.
4. Choose compression quality and resolution.
5. Click **Compress PDF**. The compressed file downloads automatically.

## Notes
- PDF processing happens in the browser; files are not uploaded to a server.
- PDF.js and jsPDF are loaded from public CDNs, so an internet connection is needed.
- This implementation renders each PDF page to a JPEG image and rebuilds the PDF. It can reduce image-heavy PDFs, but text will no longer be selectable and links, forms, bookmarks, and accessibility structure may be lost.
- Some PDFs may become larger after recompression. Try a lower DPI or quality setting.
- Keep the original PDF, especially for official or archival documents.
