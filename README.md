# KB Group website

A plain HTML site. No build step needed.

## Files

- `index.html` is the home page.
- `mizan-spaces.html` opens from "Explore Mizan Spaces" (services, projects, process, contact).
- `amanah.html` opens from Amanah's "Learn More" (principles, what is being built, roadmap, contact).
- `css/site.css` holds the shared styles and the colour list (under `:root`).
- `css/venture.css` holds the extra styles for the two business pages.
- `img/mizan-*.jpg` are the photos on the Mizan Spaces page (`mizan-hero`, `mizan-about` and the `mizan-project-*` gallery pictures).
- `img/` holds the photos and logos (`logo-amanah-light.png` is the white logo used on the dark Amanah banner):
  - `hero.jpg` top banner photo
  - `leaf.jpg` photo in the "A growing ecosystem" section
  - `mizan.jpg` Mizan Spaces card photo
  - `amanah.jpg` Amanah card photo
  - `door.jpg` photo beside "Who We Are"
  - `logo-kb.png`, `logo-mizan.png`, `logo-amanah.png` logos (transparent background)

## Plans (Basic, Standard, Premium)

- `mizan-spaces.html` has an "Our plans" section with three cards.
- `plan-basic.html`, `plan-standard.html` and `plan-premium.html` are the three plan pages.
- Put your PDFs in the `plans/` folder as `mizan-basic-plan.pdf`, `mizan-standard-plan.pdf` and `mizan-premium-plan.pdf`.
- Each plan page shows its PDF on the page (on phones it shows an "Open the plan PDF" button instead). Nothing else needs typing.
- To change the short line on a plan card, edit the `<p>` under the plan name in the "Our plans" section of `mizan-spaces.html`.

## Preview in VS Code

1. Open this folder in VS Code (File > Open Folder).
2. Install the "Live Server" extension.
3. Right-click `index.html` and choose "Open with Live Server".

## Replace an image

Put your new image in `img/` with the same file name as the one it replaces.
To use a different file name or type (for example a .png), change the matching
`src="img/..."` or `url("img/...")` in `index.html`.

## Add website links

In `index.html`, search for `href="#"`. The "Explore Mizan Spaces" and
"Learn More" (Amanah) links use it. Replace `#` with the full website address.

## Publish for free

Upload this whole folder to Netlify, Vercel or Cloudflare Pages.
