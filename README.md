# AwakenedCore

AwakenedCore is a static website template designed for an online supplement store. The project includes a single HTML page styled with custom CSS and local fonts.

## Project structure

```
/awakenedcore
├── index.html              # Main webpage
├── assets/
│   ├── font/               # Roboto font files used by the site
│   ├── img/                # Icons and product images
│   └── style/              # CSS files
└── README.md               # Project documentation
```

## Getting started

Because this is a purely static project, no build step is required. You can simply open `index.html` in your browser. For local development it is often convenient to run a small web server so that assets are served correctly.

### Using Python

If you have Python 3 installed, run the following command in the project directory:

```bash
python3 -m http.server
```

Then open `http://localhost:8000` in your web browser to view the site.

## Customization

- **Styles**: Modify the CSS under `assets/style/` to change fonts, colors or layout.
- **Images**: Replace files under `assets/img/` with your own product images or logos.
- **Fonts**: The Roboto font family is included in `assets/font/`. Update `assets/style/fonts.css` if you want to use different fonts.

## License

No license file is provided. If you intend to use this project publicly, consider adding an appropriate open-source license.

