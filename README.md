# Markdown to HTML Renderer

This project provides a simple, single-page web application (`index.html`) that converts a Markdown file (`input.md`) into a fully styled HTML document. It uses the `marked.js` library for Markdown parsing and `Tailwind CSS` for responsive styling.

## Features

*   **Markdown to HTML Conversion:** Automatically fetches `input.md` and renders its content as HTML.
*   **Responsive Design:** Styled with Tailwind CSS for optimal viewing across various device sizes.
*   **Single-File Application:** All necessary code is contained within `index.html` for easy deployment.
*   **Client-Side Rendering:** No backend server is required, making it ideal for static hosting.

## How to Use

1.  **Place Files:** Ensure `index.html` and `input.md` (and any image attachments referenced within `input.md`) are in the same directory.
2.  **Open `index.html`:** Simply open `index.html` in your web browser.

The page will automatically load `input.md`, convert its content, and display it as formatted HTML.

## Project Structure

*   `index.html`: The main application file, containing all HTML, CSS (via Tailwind CDN), and JavaScript (for `marked.js` and custom logic).
*   `input.md`: The Markdown file whose content will be converted and displayed.

## Technologies Used

*   **HTML5:** Structure of the web page.
*   **Tailwind CSS (CDN):** For utility-first styling and responsive design.
*   **Marked.js (CDN):** A full-featured markdown parser and compiler written in JavaScript.

## License

This project is open-sourced under the MIT License. See the `LICENSE` file for more details.