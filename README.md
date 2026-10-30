# glensha.org — Personal linguist website

A lightweight, single-page professional site built with Astro and Tailwind CSS. No headshot, database, CMS, or AI agents required.

## Start locally

Install a Node.js version supported by Astro 7 (Node.js 22.12+ or newer supported release) and run:

```bash
npm install
npm run dev
```

Open http://localhost:4321 .

## Production build

```bash
npm run build
npm run preview
```

Upload the contents of `dist/` to a static host, or connect the GitHub repository to Cloudflare Workers/Pages or Netlify. Set the build command to `npm run build` and output directory to `dist`.

## Customize

- **Edit your text:** `src/content/profile.ts` (biography, teaching, services, assignments, SEO, email)
- **Edit page layout/headings:** `src/pages/index.astro`
- Design styles: `src/styles/global.css`
- Licensed trainer badge and CCC logo: `public/images/`
- Contact address: edit `contact.email` in `src/content/profile.ts`.
- After editing, run `npm run build` before uploading `dist/`.
- Folder names such as `glensha-site 3` do not affect Astro; use one clearly named folder, e.g. `glensha-site`, and run commands inside it.

## Agency marketing context

This personal professional website can be shared with **Hanna Interpretations** for credential and marketing-material review. Hanna Interpretations is not represented as an employer, endorser, or client on the public site.

The site uses the permitted text designation CHI™-Mandarin, not the CCHI organizational logo. The CCHI trademark attribution is included in the footer.

## Prepublication checklist

- Confirm that Apple and Google event references are acceptable under any applicable confidentiality agreements.
- Confirm CCC logo and trainer badge display rights and current trainer standing; these assets were supplied by the credential holder.
- Confirm the scope and public description of litigation-related translation work with counsel.
- Confirm CCHI credential remains active and the certification date shown is current.
- Decide whether to remove the beautera.com link until that site is live.
- Test email link, mobile navigation, accessibility, and domain DNS/HTTPS after deployment.

No case names, confidential details, personal phone number, or unverified endorsements are included.

## Version 4
Added Beyond Language section highlighting international experience, lifelong language learning, AI-assisted pedagogy, and cross-industry cultural fluency.
