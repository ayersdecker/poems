# Poetry Collection

A simple, elegant website to display and share poems.

## Overview

This repository contains a static website for showcasing poetry. The site features a clean, responsive design with a focus on readability and aesthetics.

## Features

- Clean, minimalist design
- Responsive layout (works on desktop, tablet, and mobile)
- Easy to read typography
- Sample poems included
- Ready for GitHub Pages deployment

## Local Development

To view the website locally:

1. Clone this repository
2. Open `index.html` in your web browser, or
3. Run a local web server:
   ```bash
   python3 -m http.server 8080
   ```
   Then navigate to `http://localhost:8080`

## Deployment

### GitHub Pages

To deploy this site using GitHub Pages:

1. Go to your repository settings on GitHub
2. Navigate to "Pages" in the left sidebar
3. Under "Source", select the branch you want to deploy (e.g., `main`)
4. Click "Save"
5. Your site will be available at `https://[username].github.io/poems/`

## Adding Your Own Poems

To add your own poems, edit the `index.html` file:

1. Find the `<article class="poem">` sections
2. Replace the sample poems with your own content
3. Follow the same HTML structure:
   ```html
   <article class="poem">
       <h3>Your Poem Title</h3>
       <div class="poem-content">
           <p>First line of your poem</p>
           <p>Second line of your poem</p>
           <!-- Add more lines as needed -->
       </div>
       <p class="poem-meta">— Your Name</p>
   </article>
   ```

## Customization

You can customize the appearance by editing `style.css`:

- Colors: Change the `background-color` and `color` properties
- Fonts: Modify the `font-family` values
- Layout: Adjust padding, margins, and max-width values

## License

This project is licensed under the Apache License 2.0 - see the LICENSE file for details.