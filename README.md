# Gopal Bhunia — Portfolio

A dark, responsive personal portfolio built with Astro. It introduces Gopal Bhunia, highlights development skills and technologies, showcases projects, and provides a contact form.

## Tech stack

- [Astro](https://astro.build/) for the site and page components
- [React](https://react.dev/) for interactive components
- [Tailwind CSS](https://tailwindcss.com/) for styling
- TypeScript

## Requirements

- Node.js `>=22.23.4` (see `package.json`)
- npm

## Getting started

Install dependencies and start the local development server:

```sh
npm install
npm run dev
```

Astro prints the local URL in the terminal. To create and preview a production build:

```sh
npm run build
npm run preview
```

## Project structure

```text
src/
  components/   Astro sections for navigation, home, projects, and contact
  layouts/      Shared page layout and metadata
  pages/        Site routes
  react/        Interactive React components
  styles/       Global styles and theme
public/         Static icons, technology logos, and fonts
```

## Personalizing the portfolio

The site content is currently a starter portfolio. Before publishing, update the sample content and links:

- Edit the introduction, social links, and email in `src/components/home.astro`.
- Replace the sample project titles, images, GitHub links, and previews in `src/components/projects.astro`.
- Set your location in `src/components/contact.astro` and update the Formspree endpoint in the `mailApiUrl` constant to your own form URL.
- The contact form is configured to submit directly to Formspree. If you want to change the destination, update the endpoint in `src/components/contact.astro`.
- Update the social links in `src/components/footer.astro`.
- Change the site title, description, canonical URL, and Open Graph metadata in `src/layouts/Layout.astro`.

The skills accordion is in `src/react/SkillsList.tsx`; the technology marquee is in `src/components/logoWall.astro`.

## Available scripts

| Command | Description |
| --- | --- |
| `npm run dev` | Start the Astro development server |
| `npm run build` | Build the site for production |
| `npm run preview` | Preview the production build locally |
| `npm run astro` | Run the Astro CLI |