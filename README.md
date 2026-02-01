# isaiah-reader
An HTML text‑to‑speech reader for the Book of Isaiah, featuring collapsible chapters and selectable system voices.

## Live Reader
https://michaeldbowles.github.io/isaiah-reader/

## Technical Notes

- The reader uses the browser’s built‑in **Web Speech API** for text‑to‑speech.
- Available voices depend on the **user’s device and operating system**. Some voices shown in the interface may not be available on all systems.
- Voice playback quality varies by browser; the best support is typically found in Chromium‑based browsers and Safari.
- All functionality is **client‑side only**. No data is sent to any server, and no external scripts or libraries are used.
- The reader is a **single‑page HTML application** (`index.html`) with no build system or dependencies.
- Designed for modern browsers with speech synthesis support. Older browsers may not provide any voices.
- Mobile devices (iOS/Android) support the reader, but voice availability and behavior may differ from desktop environments.
- The reader is optimized for **dark‑theme readability** and long‑form scripture study.
- The tool is limited to the **Book of Isaiah (KJV)** as included in the HTML file. It does not fetch or load external scripture content.

## Download Instructions

You can download the Isaiah Reader for offline use in several ways:

### Option 1: Download individual file 'index.html'
- Click on the file in this repository.
- Select **Download raw file**.

### Option 2: Download ZIP
1. Click the **Code** button at the top of this repository.
2. Select **Download ZIP**.
3. Extract the ZIP file.
4. Open `index.html` in any modern web browser.

### Option 3: Clone the repository (for developers)

## Stewardship Note

This project is MIT-licensed for open use. If someone wishes to adapt or steward this reader and requires additional rights, I am open to discussing options that support their work.
For stewardship or licensing inquiries, please open an Issue on this repository.
