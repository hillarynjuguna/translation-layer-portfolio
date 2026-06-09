# Translation Layer Portfolio Brief

This repository contains the interactive single-page portfolio application of **Hillary Njuguna (AI Systems & Narrative Architect)**. 

The application is built to demonstrate the **Translation Operating Loop** across AI governance, content ecosystems, and practitioner curricula. It presents the creator's structural methodologies and proof of work in a form optimized for both human visitors and AI/AEO retrieval engines.

## Application Structure

The application is structured as a React client-side application bundled with Vite:

*   **`src/App.jsx`**: The single monolithic component containing all page content, internal styling, and structured translation data.
*   **`src/main.jsx`**: React initialization mount.
*   **`src/index.css`**: Global design systems styles.
*   **`index.html`**: Host document setting viewport, loading Google Fonts, and mounting the React bundle.

## Key Sections & Features (App.jsx)

1.  **Header & Positioning**: Frames the practitioner as an "AI Systems & Narrative Architect" with a subline explaining the core premise: structuring knowledge systems for optimized semantic retrieval.
2.  **The Operating Loop**: A five-step methodology timeline mapping out the lifecycle of a knowledge product:
    *   `01 OBSERVE` (complex domains like governance or institutional failure)
    *   `02 FORMALIZE` (primitives, layers, and protocols)
    *   `03 COMPRESS` (named frameworks stable under representational change)
    *   `04 INSTANTIATE` (essays, repos, curricula)
    *   `05 DISTRIBUTE` (SEO/AEO surfaces and search-indexed delivery)
3.  **Translation Demonstrations**: Expandable cards representing three core projects, contrasting their **Internal Structural Form** against their **AEO-Ready Retrieval Queries/Answers**:
    *   `bainbridge-warning` (AI governance framework for institutional failure)
    *   `oscillatory-fields-lexicon` (Notion database canonical alias mapping)
    *   `martha-course` (12-module practitioner training curriculum)
4.  **Distribution Evidence**: A grid demonstrating existing knowledge assets across multiple channels (Web, Long-Form, GitHub, Notion, LinkedIn, and Product).
5.  **Signal Inventory (Honest Assessment)**: A side-by-side verification table outlining confirmed capabilities (e.g., schema-first content architecture, multi-model comparative intelligence) against unproven metrics (e.g., SEO performance, community scale, paid growth mechanics).
6.  **The Offer to Chemin**: A specific strategic positioning block framing the creator's value proposition for the Chemin organization.

## Tech Stack & Design System

*   **Framework**: React 19 + Vite 8
*   **Typography**: *Cormorant Garamond* (serif for headers), *IBM Plex Sans* (sans-serif for body), *IBM Plex Mono* (monospace for code elements/labels)
*   **Styling**: Vanilla CSS injected via a styled template literal to enforce a high-contrast dark theme (using deep grey/black backgrounds `#080808` with parchment `#D4C4A0` and steel blue `#6B9FBF` accents).

## Getting Started

### Prerequisites

*   Node.js (v18 or higher recommended)
*   npm or pnpm

### Running Locally

```bash
# Install dependencies
npm install

# Run the development server
npm run dev

# Build the static site for production (outputs to dist/)
npm run build
```

## Deployment

The application is configured to run as a single-page application (SPA). A `vercel.json` is included to route all incoming requests to `index.html` to prevent 404s on refresh under client-side routing.
