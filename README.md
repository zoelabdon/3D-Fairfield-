# Fairfield University Campus Explorer · 2026

An interactive, browser based 3D campus directory for Fairfield University. It includes 66 searchable destinations, campus categories, clickable buildings, orbit/zoom/pan controls, and walking routes that follow the model's campus path network. The scene includes campus roads and names, parking bays and cars, paths, trees, benches, lamps, entrance signage, ponds, courts, and athletic fields. Building silhouettes vary by type: Bellarmine Hall has stone manor wings and steep roofs; the library and Dolan School have layered masonry and glass; residence halls have brick elevations and stair towers; the arena has a faceted bowl; and the Kelley garage has open parking decks. Published building photos are shown on selected destination cards for reference.

## Open it

Open `index.html` in a modern browser with an internet connection. Three.js and the display fonts load from public CDNs. No build step is required.

## Publish on GitHub Pages

The workflow at `.github/workflows/pages.yml` publishes the root `index.html` whenever changes are pushed to `main` or `master`. It can also be run manually from the repository's Actions tab. After the first workflow run, set the repository's **Settings → Pages → Build and deployment → Source** to **GitHub Actions**. For the linked `zoelabdon/3D-Fairfield-` repository, the expected Pages address is `https://zoelabdon.github.io/3D-Fairfield-/`.

## Using the map

- Search or filter the directory, then select a destination.
- Click a building in the model to open its information card.
- Choose a **Route from** location, then **Route here** to draw a campus path route and see an estimated distance and time.
- Drag to orbit, scroll to zoom, right-drag to pan. On a touch screen, use one finger to orbit and pinch to zoom.
- Toggle building models and labels from the map controls.

## Model scope

This is a detailed illustrative campus model, not an official survey, construction drawing, or accessible turn-by-turn routing service. Building footprints, exact placement, paths, heights, and route distances are schematic; the buildings are hand-modeled approximations informed by published photos and facility descriptions. The directory is a curated set of main-campus destinations, not a guarantee that every room, entrance, or facility is represented. Confirm current building access and routes with Fairfield University before relying on them for navigation.

The destination list and campus context use Fairfield University's [2024–25 Fact Book and campus map](https://www.fairfield.edu/_files/documents/pdfs/about_office-and-departments_institutional-research_fact-book-2024-2025.pdf), current [campus locations](https://www.fairfield.edu/about/locations/), and 2026 building announcements. The 2026 layer includes [E. Gerald Corrigan Hall](https://www.fairfield.edu/news/2026/april/e-gerald-corrigan-residence-hall.html), announced for Fall 2026, and the [Barron Center](https://acppubs.com/NEC/article/12212A42-gilbane-celebrates-groundbreaking-of-fairfield-college-preparatory-school-s-new-barron-center-for-arts-recreation), scheduled for Fall 2026. The main campus is publicly described as more than 200 acres with nearly 2,000,000 square feet of building space. Campus facilities and naming may change over time.
