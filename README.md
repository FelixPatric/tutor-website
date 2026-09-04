# Tutor Website

Tutor is a responsive static landing page for a video course about creating and launching video courses. It includes course topics, chapter summaries, takeaways, author information, testimonials, and a contact page.

## Features

- Responsive navigation with a mobile menu
- Course introduction, learning topics, chapters, summary, and takeaways
- Author, audience, testimonials, and partner sections
- Contact form and location map
- Scroll-aware navigation styling
- Local image, icon, stylesheet, and JavaScript assets

## Project Structure

```text
.
├── index.html          # Main course landing page
├── contact.html        # Contact page
├── css/styles.css      # Site styles
├── js/script.js        # Mobile menu and scroll behavior
└── img/                # Images, icons, logo, and favicon
```

## Running Locally

This project does not require a build step or package installation. Serve the project directory with any static web server. For example, with Python:

```bash
python3 -m http.server 8000
```

Then open [http://localhost:8000](http://localhost:8000) in a browser.

Opening `index.html` directly also works for most page content, but a local server is recommended for a consistent browser experience.

## Customization

- Update page content and navigation in `index.html` and `contact.html`.
- Modify the visual design in `css/styles.css`.
- Update interactive behavior in `js/script.js`.
- Replace or add media files in `img/`.
- Update the Formspree endpoint in `contact.html` before using the contact form in production.

## External Resources

The pages load Open Sans from Google Fonts, Font Awesome icons from cdnjs, Google Maps for the location embed, and Formspree for contact form submissions.
