# HAIPS@CCS 2025 Workshop Website

This is the official website for the 1st Workshop on Human-Centered AI Privacy and Security (HAIPS), co-located with ACM CCS 2025.

Website: [haips.com](https://haips.com) (Assuming this domain will point here)

## Built With

*   [Astro](https://astro.build/)

## Development

To run the website locally:

1.  **Install dependencies:**
    ```bash
    pnpm install
    ```
2.  **Start the development server:**
    ```bash
    pnpm dev
    ```
    This will start a local development server, usually at `http://localhost:4321/`.

## Updating Content

*   **Organizers:** Edit the data in `src/data/organizers.js`.
*   **Page Content:** Modify the corresponding `.astro` files in the `src/pages/` directory.
*   **Styling:** Global styles are mostly within `<style is:global>` in `src/layouts/Layout.astro`. Page-specific styles can be added within the `<style>` tags of individual page files.
*   **Navigation:** Update the `navLinks` array in `src/components/Header.astro`.
*   **Important Dates/News:** Update the placeholders in `src/pages/index.astro` and `src/pages/cfp.astro`.

## Deployment

1.  **Build the static site:**
    ```bash
    pnpm build
    ```
    This will generate the static website files in the `dist/` directory.
2.  **Deploy:** Deploy the contents of the `dist/` directory to your preferred hosting provider (e.g., Netlify, Vercel, GitHub Pages, Cloudflare Pages).
