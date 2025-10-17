# Markdown to HTML Converter

This is a simple, client-side web application that dynamically converts and displays Markdown content from an `input.md` file into styled HTML. It leverages `Marked.js` for Markdown parsing and `Tailwind CSS` for styling.

## Features

*   **Dynamic Conversion:** Fetches `input.md` and renders it on page load.
*   **Styled Output:** Markdown elements are styled using a custom **Emerald** theme with Tailwind CSS.
*   **Responsive Design:** Optimized for various screen sizes.

## How to Use

1.  Place your Markdown content in a file named `input.md` in the same directory as `index.html`.
2.  Open `index.html` in your web browser.

The application will automatically fetch `input.md` and display its rendered HTML content.

## Technologies Used

*   [Tailwind CSS](https://tailwindcss.com/) - A utility-first CSS framework for rapidly building custom designs.
*   [Marked.js](https://marked.js.org/) - A Markdown parser and compiler written in JavaScript.

## Customization

To change the theme or styling, modify the `style` block within `index.html` or the Tailwind CSS classes applied to the elements. The current theme uses various shades of emerald for headings and links.

## License

This project is open-sourced under the MIT License. See the [LICENSE](LICENSE) file for more details.