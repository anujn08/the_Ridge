# the Ridge

A static website for the Ridge, a Japanese-inspired mountain retreat in Tungnath Valley, Uttarakhand. The design brings together Japanese calm and Garhwali character.

## Preview locally

Run this command from the repository directory:

```sh
python -m http.server 8080
```

Open http://localhost:8080. No dependency installation or build step is required.

## Publish with GitHub Pages

The site files are at the repository root and use relative asset paths, so they work at a GitHub Pages project URL.

Option 1: In **Settings > Pages**, select **Deploy from a branch**, choose **main**, and select **/ (root)**. Save. The expected address is https://anujn08.github.io/the_Ridge/ once GitHub finishes deployment.

Option 2: Select **GitHub Actions** as the Pages source, then manually run **Deploy website to GitHub Pages** from the Actions tab. The included workflow is manual; pushing this repository does not automatically run it.

The site can also be hosted by any static hosting provider. Publish the repository root with no build command.

## Files and editing

- `index.html`: Page copy, room cards, sample prices, contact links, map, and business metadata.
- `style.css`: Responsive layouts, branding, colours, and visual details.
- `script.js`: Room filters, photo viewer, experience tabs, mobile menu, and stay wish-list download.
- `rooms.json`: Reference data for room concepts and sample specifications. The page is static: edits here must also be reflected in `index.html`; this file does not automatically render the room cards.
- `assets/`: The photographs, concept illustrations, video, and SVG logos referenced by the site.
- `BRAND.md`: Logo and brand notes.

## Content to finalise before opening bookings

Room prices, assigned views, balconies, bed layouts, and capacities are sample layout details. Confirm them and update their visible labels when final. Interior pictures include AI-generated concepts and design references; they are not completed-room photographs. Review image rights before using supplied references in a public commercial launch.

The stay planner creates a downloadable text wish list. It does not send a message, reserve a room, take payment, or store a booking. Visitors can contact the resort through the phone, email, and Instagram links.

The site uses externally hosted Google Fonts and an embedded Google Map. Local photos, video, and logos are included in this repository.

## Contact

- Phone: +91 7895515156
- Email: amitnautiyal50@gmail.com
- Instagram: https://www.instagram.com/theridge_270
- Location: 30.508829422817914, 79.13545488483066

Contact details appear in multiple places, including `index.html`, its structured metadata, and `script.js`; keep them consistent when updating.
