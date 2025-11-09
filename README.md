# Digikala — Static Site / Template

This repository contains a static HTML/CSS template for an e-commerce / product listing site. The project is organized as plain HTML files with separate folders for CSS, images, fonts, and icon assets. It's suitable as a static site or as a starting point for front-end development.

## What’s in this repository

- Main HTML files such as `Index.html`, `mode.html`, `form.html`, `supermarket.html`, `svg.html`, etc.
- `css/` directory with individual stylesheet files for sections and components
- `images/` directory with categorized image folders
- `fonts/` and `font-awesome/` for icons and typefaces

## Example structure (excerpt)

```
/ (project root)
	├─ Index.html
	├─ form.html
	├─ css/
	│    ├─ header.css
	│    ├─ main.css
	│    └─ ...
	├─ images/
	│    ├─ header/
	│    ├─ product1/
	│    └─ ...
	└─ font-awesome/
```

## View locally

No build step is required — you can open the HTML files directly in your browser. For a better local experience (and to avoid certain path issues), run a simple HTTP server in the project folder.

PowerShell (Windows) — using Python 3:

```powershell
# Run in the project folder
python -m http.server 8000; # then open http://localhost:8000 in your browser
```

Or with Node.js (if `http-server` is installed):

```powershell
# If not installed: npm install -g http-server
http-server -p 8000
# then open http://localhost:8000
```

Alternatively, simply open `Index.html` with your browser (right-click → Open with → choose browser).

## Development notes

- Styles are split into many CSS files, each usually tied to a page section (header, footer, gallery, products, etc.). Consider consolidating them with Sass or PostCSS if you plan to maintain or extend the project.
- Images are organized under `images/`. To improve performance, compress images using tools like `imagemin` or online compressors.
- If you want to convert this into a dynamic site or a component-based frontend (React/Vue), convert the HTML files into templates or components.

## Responsive / Mobile

- There is a `mobile.css` and other styles targeting mobile. Test on multiple screen sizes and tweak breakpoints as needed.

## Contributing

If you want to contribute changes or improvements:

1. Create a new branch.
2. Make your changes and commit them.
3. Open a Pull Request against `main` describing the changes.

## License

There is no license file included at the moment. If you plan to publish this repository, consider adding a license such as MIT or Apache 2.0 by adding a `LICENSE` file.

## Contact

If you have questions or would like to collaborate, please open an issue or contact the repository maintainer via GitHub.

---

If you’d like, I can also:

- Add an English + Persian bilingual README (both languages in the same file or separate files).
- Add GitHub badges (license, website link) and example screenshots.
- Create a small `LICENSE` file (e.g., MIT) for you.

Tell me which of the above you'd like next and I’ll apply it.
"# digikala" 
