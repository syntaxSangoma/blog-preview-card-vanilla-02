# Blog Preview Card (Vanilla)

A clean, responsive Blog Preview Card component built using vanilla HTML and CSS.

![Alt text](./images/my-picture.png)

## Key Features & Benefits

- **Clean and Simple:** Built using only vanilla HTML and CSS, making it lightweight and easy to understand.
- **Responsive Design:** Adapts to different screen sizes, ensuring optimal viewing on various devices.
- **Easy to Integrate:** Can be dropped into any web project without external dependencies.
- **Customizable:** Uses CSS variables and simple class structure so you can quickly adapt styles.

## Prerequisites & Dependencies

- A web browser (e.g., Chrome, Firefox, Safari) to view the component.
- A text editor or IDE to edit the HTML and CSS files (e.g., VS Code, Sublime Text).

## Installation & Setup Instructions

1. **Clone the repository:**

```bash
git clone https://github.com/syntaxSangoma/blog-preview-card-vanilla-02.git
```

2. **Navigate to the project directory:**

```bash
cd blog-preview-card-vanilla-02
```

3. **Open `index.html` in your web browser:**
   - Double-click `index.html` or open it from your editor.
   - Or serve the folder using a simple local server (recommended for consistent image and font loading):

## Usage Examples

The component is static and intended as a visual preview card. To modify content, edit `index.html`:

- Replace the hero image at `images/illustration-article.svg` with another image.
- Change the author avatar at `images/image-avatar.webp`.
- Update the title, date, and description directly in `index.html`.

Example: Replace `images/illustration-article.svg` with a different image file (keep filename or update the `src`).

## Configuration Options

Most visual changes are done in `style.css` using CSS variables defined in the `:root` selector. Common customizations:

- **Colors:** Modify `--YELLOW`, `--GRAY-950`, `--GRAY-500`, and `--WHITE` in `style.css`.
- **Shadow:** Tweak `--CARD-SHADOW` to change the card elevation effect.
- **Font:** The project uses the `Figtree` font via Google Fonts (`--FF`). Change or replace the font import in `style.css` to use another font.
- **Card Dimensions:** Adjust `.blog-card` width, padding and `.blog-card__hero-image` dimensions in `style.css` to change card sizing.
- **Image behavior:** The hero image can be controlled with `object-fit` on `.blog-card__hero-image img`.

## Contributing Guidelines

Contributions are welcome. Suggested flow:

1. Fork the repository.
2. Create a feature branch (e.g., `feature/fix-styles`).
3. Make changes with clear commit messages.
4. Push to your fork and open a pull request.

## License

License not specified.

## Acknowledgments

- Google Fonts for the `Figtree` font used in this project.
