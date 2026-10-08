# Horizon Institute Website

A responsive, multi-page website for Horizon Institute — an educational institution offering technology, design, and business programs.

## Project Structure

institute-website/
│
├── index.html
├── about.html
├── courses.html
├── admissions.html
├── contact.html
│
├── css/
│   └── style.css
│
├── js/
│   └── script.js
│
├── images/
│   ├── home-hero.jpg
│   ├── about-hero.jpg
│   ├── courses-hero.jpg
│   ├── admissions-hero.jpg
│   ├── contact-hero.jpg
│   └── history.jpg
│
└── README.md


## Features

- **Multi-page Structure:** 6 separate HTML pages.
- **Responsive Design:** Mobile, tablet, and desktop.
- **Course Filtering:** Filter courses by category.
- **FAQ Accordion:** Expandable Q&A section.
- **Google Sheets Integration:** Contact & Application forms save to Google Sheets.
- **Modern UI:** Poppins & Inter fonts, smooth transitions, professional color palette.

## Setup Instructions

1. Download or clone the project folder.
2. Open `index.html` in any modern web browser.
3. Navigate using the top navigation bar.
4. Make sure all images are placed in the `images/` folder.

## Required Images

Add these images to the `images/` folder:

| Image | Purpose |
|-------|---------|
| `home-hero.jpg` | Home page hero banner |
| `about-hero.jpg` | About page hero banner |
| `courses-hero.jpg` | Courses page hero banner |
| `admissions-hero.jpg` | Admissions page hero banner |
| `contact-hero.jpg` | Contact page hero banner |
| `history.jpg` | About page History section |

**Recommended sizes:** 1200x600 or 1920x800

## Google Sheets Integration

1. Create a Google Sheet with two tabs: `Applications` and `Contacts`.
2. Open **Extensions → Apps Script** and paste the script (see docs).
3. Deploy as a Web App with access set to "Anyone".
4. Copy the Web App URL and paste it into `js/script.js` where you see `GOOGLE_SCRIPT_URL`.

## Customization

- **Colors:** Edit CSS variables in `css/style.css` (e.g., `--primary`, `--secondary`).
- **Courses:** Edit the `courses` array in `js/script.js`.
- **Text:** Directly edit the HTML files.

## Development Standards

- Clean, properly indented code.
- Reusable CSS classes.
- No external frameworks (only Font Awesome & Google Fonts).
- Well-commented for clarity.

## License

For educational purposes only.