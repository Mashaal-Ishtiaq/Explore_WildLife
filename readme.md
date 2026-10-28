
# Explore Wildlife 🐾

A wildlife exploration website that introduces visitors to fascinating animals through an interactive, visually styled web experience.

## Overview

Explore Wildlife is a front-end web project built to showcase animal information and encourage awareness of wildlife and biodiversity. It includes a landing page, an interactive animal carousel, and a contact page.

## Features

- **Wildlife Homepage** — An introduction to the animal kingdom and wildlife conservation.
- **Interactive Animal Carousel** — Browse featured animals using previous and next navigation.
- **Animal Profiles** — Explore descriptions of animals such as stags, wolves, horses, elephants, and tigers.
- **Contact Form** — Enter a name, email address, and message through a simple form interface.
- **Responsive Styling** — CSS media queries adapt the layout for smaller screens.
- **Custom Visual Design** — Styled navigation, backgrounds, typography, and interactive elements.

## Tech Stack

- **HTML5** — Page structure and content.
- **CSS3** — Layout, styling, and responsive design.
- **JavaScript** — Carousel navigation and contact-form interactions.

## Project Structure

```text
Explore_WildLife/
├── index.html
├── home.css
├── HTML/
│   ├── animal.html
│   └── contact.html
├── CSS/
│   ├── animal.css
│   └── contact.css
└── images/
    └── Wildlife image assets
```

## Getting Started

### Prerequisites

You only need a modern web browser. No package installation or backend server is required for the basic front-end experience.

### Run Locally

1. Clone the repository:

   ```bash
   git clone https://github.com/Mashaal-Ishtiaq/Explore_WildLife.git
   ```

2. Open the project folder:

   ```bash
   cd Explore_WildLife
   ```

3. Open `index.html` in your browser.

For more reliable navigation and asset loading, you can also serve the folder using a local development server.

## How to Use

1. Open the homepage.
2. Select **Explore Animals** to visit the wildlife carousel.
3. Use the previous and next buttons to browse the featured animals.
4. Open the contact page to try the contact form.

## Current Limitations

- The contact form displays a success message locally; it does not send messages to a server or email address.
- Some asset and page links use root-relative paths, which may need adjustment when running the site directly from a local folder or deploying it under a subpath.
- The website uses static content and does not currently include a backend or database.

## Future Improvements

- Connect the contact form to a backend service.
- Improve accessibility and keyboard navigation.
- Add more animal profiles and wildlife conservation resources.
- Refine responsive layouts and verify all asset paths across deployment environments.

## License

No license has been specified in the repository. Please add a license file if you intend to define how others may use, modify, or distribute this project.
