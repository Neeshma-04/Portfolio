# Portfolio

This is my personal portfolio: the marketing portfolio of **Neeshma Mehta**, a product marketer based in Raleigh, North Carolina.

**Live site:** https://neeshmamehta.com (once Cloudflare Pages is connected, see below)

## About me

I turn complex products into stories people choose. Most recently I was a Product Marketing Specialist at Progress Software, where I ran go-to-market content for Progress DataDirect (data connectivity) and Progress Corticon (business rules and decisioning).

- 12 articles on the Progress blog: product explainers, thought leadership, a 3-part series and customer stories
- 4 whitepapers for DataDirect and Corticon
- A product onboarding guide built from zero, used by new marketing and sales hires and by prospects
- Sales and partner enablement: battlecards, datasheets, solution briefs and pitch decks

## What's on the site

| Section | What it shows |
| --- | --- |
| Enablement | The onboarding guide, the two product overview whitepapers and the sales kit |
| Content | Positioning-led articles and the low-code workflow automation series |
| Customer stories | Global Refuge, VirtualZ and the WinSQL partner webinar |
| Analytics | Views for every article, with links to all 12 articles and 4 whitepapers |
| Experience | Progress Software, Humanetics and Bluebird Foods |
| Contact | Email, LinkedIn and a resume download |

## Built with

Plain HTML, CSS and a little JavaScript in a single `index.html`, with no build step. Fonts are Playfair Display and Poppins from Google Fonts. The page works on phones and desktops, follows the visitor's light or dark mode, and scrolls smoothly between sections (it jumps instead for anyone who has reduced motion turned on).

## Files

| File | Purpose |
| --- | --- |
| `index.html` | The whole site |
| `neeshma-mehta.jpg` | Portrait photo |
| `Neeshma_Mehta_Resume.pdf` | Resume linked from the download buttons |
| `.nojekyll` | Tells GitHub Pages to serve the files as they are |

## Run it locally

Open `index.html` in a browser. To test the resume download the way a web server serves it, run `python3 -m http.server` in this folder and visit http://localhost:8000.

## How it's published

The site is hosted on Cloudflare Pages at https://neeshmamehta.com, and Cloudflare redeploys it automatically whenever `main` changes.

First-time setup:
1. In Cloudflare, go to **Workers & Pages → Create → Pages → Connect to Git** and pick this repository.
2. Set the production branch to `main` and the framework preset to None, leave the build command empty, and set the build output directory to `/`.
3. In the project's **Custom domains** tab, add `neeshmamehta.com` (and `www.neeshmamehta.com` if you want that address too). The domain is already on Cloudflare, so it adds the DNS records for you.

## Updating the site

- **Text:** edit `index.html` on GitHub (the pencil icon) and commit. Changes on `main` go live within a minute or two.
- **Photo or resume:** upload a new file with exactly the same name to replace the old one.

## Contact

- Email: neeshmamehta@gmail.com
- LinkedIn: https://www.linkedin.com/in/neeshma-mehta/

## License

The code is under the MIT License (see `LICENSE`). The writing, photo and resume are © 2026 Neeshma Mehta, all rights reserved.
