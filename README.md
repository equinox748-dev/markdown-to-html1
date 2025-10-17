# Markdown to HTML Converter

This project provides a simple, client-side Markdown to HTML converter. It dynamically fetches a Markdown file (`input.md`) and renders its content as HTML directly in the browser using `Marked.js` and styled with `Tailwind CSS`.

## Features

*   **Dynamic Rendering**: Fetches `input.md` and renders it on page load.
*   **Responsive Design**: Built with Tailwind CSS for a mobile-first, responsive layout.
*   **Dark Theme**: The application now features a sleek dark theme, providing a comfortable viewing experience.
*   **Custom Markdown Styling**: Tailwind CSS is used to style standard Markdown elements (headings, paragraphs, lists, code blocks, tables, images, etc.) to ensure a clean and consistent presentation within the dark theme.

## How to Use

1.  **Place your Markdown**: Ensure your Markdown content is in a file named `input.md` in the same directory as `index.html`.
2.  **Open `index.html`**: Open the `index.html` file directly in your web browser. The Markdown content from `input.md` will be automatically rendered.

## Technologies Used

*   **HTML5**: Structure of the web page.
*   **Tailwind CSS**: For utility-first styling and responsive design.
*   **Marked.js**: A JavaScript library for parsing Markdown to HTML.

## Customization

You can customize the appearance by modifying the Tailwind CSS classes in the `<style>` block of `index.html`. To change the Markdown content, simply edit `input.md`.
