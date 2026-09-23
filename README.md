# HTML, CSS & JavaScript - Practical Assignment

| | |
|---|---|
| **Student Name** | B.Teja naik |
| **Register Number** | 250200211 |
| **Class / Section** | 7 |
| **Subject** | Web Technology (HTML, CSS & JavaScript) |
| **Assignment** | Practical Programs Website |

**Total number of programs completed: 322**
(HTML: 15, CSS: 75, JavaScript: 232; plus 2 helper pages for the multi-page form program).

## How to run

1. Unzip the folder.
2. Open `index.html` in any modern browser (Chrome, Edge, Firefox, Safari). No server or installation is needed.
3. Use the three cards on the home page to open the HTML, CSS or JavaScript program lists, then click any program.
4. Every program page has **Home** and **Back to Programs** links (and Previous / Next links), plus a
   **View source code** panel at the bottom that shows the HTML, CSS and JavaScript of that page.

## Project structure

```
practical-programs/
├── index.html              Home page with 3 cards (HTML / CSS / JavaScript)
├── html/                   index.html + 15 HTML programs
├── css/                    index.html + 75 CSS programs
├── javascript/             index.html + 232 JavaScript programs
│   ├── basic/              Basic JavaScript programs
│   ├── arrays-objects/     Arrays & Objects
│   ├── dom/                DOM Manipulation
│   ├── events/             JavaScript Events
│   ├── forms-validation/   Forms & Validation
│   ├── browser-objects/    Browser Objects
│   ├── web-storage/        Web Storage
│   ├── advanced/           Advanced JavaScript
│   └── mini-projects/      Mini Projects
├── assets/
│   ├── css/style.css       Shared styles (page frame, buttons, helpers)
│   ├── css/external-demo.css   Used by the "external CSS" programs
│   ├── images/             SVG pictures used by galleries, cards and demos
│   ├── media/              Sample audio (.wav) and video (.mp4) for the audio/video program
│   └── icons/
└── README.md
```

## Programs that need an internet connection

These work offline except for the part that talks to the internet (they show a friendly message if the connection fails):

* HTML: *Bootstrap components* (Bootstrap is loaded from a CDN)
* JavaScript: *Fetch API*, *Display API data*, *Weather application* (Open-Meteo API), *Currency converter* (open.er-api.com; sample rates are used when offline)
* Geolocation programs ask the browser for permission. Some browsers only allow this on `https://` or `localhost`.

## Notes

* Every program is a separate HTML file inside its topic folder; nothing is combined into one page.
* Local storage programs keep their data in the browser (`localStorage` / `sessionStorage`).
* Code uses meaningful names, comments and responsive layouts. Pages were tested in Chromium with no console errors.
