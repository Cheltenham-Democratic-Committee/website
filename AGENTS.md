# Agent Instructions

This document provides context for LLM agents working on this codebase.

## Project Overview

This is the website for the **Cheltenham Democratic Committee**, a political organization in Cheltenham Township, Pennsylvania. It is a static site that provides information about the committee, endorsed candidates, meeting schedules, volunteer opportunities, and donation options.

## Tech Stack

- **SvelteKit** with static adapter (prerendered static site)
- **Svelte** for components
- **TypeScript** (strict mode)
- **Vite** as the build tool
- Deployed to **GitHub Pages**

## Directory Structure

```
src/
├── routes/              # SvelteKit pages (file-based routing)
│   ├── +layout.svelte   # Root layout (header, nav, footer)
│   ├── +page.svelte     # Home page
│   ├── about/           # About the committee
│   ├── donate/          # Donation options
│   ├── get-involved/    # Volunteer opportunities
│   ├── vote/            # Election info and endorsements
│   └── news/            # News section
├── lib/                 # Reusable components
├── app.html             # Base HTML template
└── app.d.ts             # TypeScript type definitions

static/                  # Static assets (images, fonts, CSS, documents)
```

## Commands

```bash
# Install dependencies
yarn install

# Development server
yarn dev

# Production build
yarn build

# Type checking
yarn check

# Linting and formatting check
yarn lint

# Auto-fix formatting
yarn format
```

## Before Committing

Always run these checks before committing changes:

1. `yarn format` - Fix formatting issues
2. `yarn lint` - Verify linting passes
3. `yarn check` - Catch TypeScript errors
4. `yarn build` - Ensure production build succeeds

CI/CD will run build and lint checks on all PRs.

## Code Conventions

- **Routing**: Uses SvelteKit file-based routing with `+page.svelte` files
- **Layouts**: Common structure in `+layout.svelte` (header, navigation, footer)
- **Styling**: Scoped styles within components; global styles in `static/main.css`
- **Colors**: Primary blue (#103578), accent yellow (#f9d95c)
- **Formatting**: Tabs for indentation, single quotes, no trailing commas

## Content Updates

When updating content (candidates, meetings, officers, etc.):

- **Endorsed candidates**: Update `src/routes/vote/+page.svelte`
- **Meeting schedule**: Update `src/lib/Meetings.svelte`
- **Officers and committee members**: Update `src/routes/about/+page.svelte`
- **Volunteer committees**: Update `src/routes/get-involved/+page.svelte`
- **Images**: Add to `static/images/` with descriptive names

### Keeping Content Current

Political websites require regular updates. When working on this codebase:

- Check if candidate endorsements are for the current election cycle
- Verify meeting dates and locations are current
- Confirm officer listings reflect current leadership
- Remove outdated event announcements
- Update copyright year in footer if needed

## Important Notes

- This is a **static site** with no backend; all content is in the source files
- External services: MailerLite (mailing list), PayPal/ActBlue (donations)
- The site must remain accessible and load quickly on all devices
- Follow existing patterns when adding new pages or components
- Do not hardcode version numbers or environment-specific paths in code
- Keep the codebase simple; avoid over-engineering for a community organization site
