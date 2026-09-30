# Court of Love Records

*Where passion has the final word.*

A woman-led record label bringing passionate stories, songs, and films to life through a multicultural lens. Court of Love Records specializes in AI music, AI filmmaking, and AI stories, created by humans with AI as the instrument.

**Live site:** [courtofloverecords.com](https://courtofloverecords.com)

---

## About

Court of Love Records champions Latin, Caribbean, and Asian voices, East and South, with characters who carry their heritage with them: not as a backdrop, but as the heart of the story.

We believe AI isn't a cheat code. It's a way for anyone with a vision to turn it into reality, without the roadblocks. Every release is guided by human hands from first idea to final cut.

### Founders

- **DC**, Founder. Writes, films, and edits every release.
- **RC**, Co-Founder. Music producer under the moniker **RG4M3**; leads the business side of the label and artist outreach.

### Roster

- **Reina Acevedo**, AI Creative Director, Artist, Author & Filmmaker. The hopeless-romantic side of DC, brought to life with AI. Sings in English, Spanish, and Hindi.
- **Shara Rayne**, AI Recording Artist. Cinematic concept albums spanning nu-metal and gothic rock. Sings in English and Chinese.

### Our stack

Higgsfield AI (film and image), Suno (music), Claude (story and direction), ChatGPT (ideas and copy).

---

## Repository contents

| File | Purpose |
| --- | --- |
| `index.html` | The entire site: HTML, CSS, and JavaScript in one file |
| `CNAME` | Custom domain for GitHub Pages (`courtofloverecords.com`) |
| `preview.png` | Social share image shown when the link is posted (1200×630) |
| `reina-acevedo.jpg` | Roster photo for Reina (800×1000, 4:5) |
| `shara-rayne.jpg` | Roster photo for Shara (800×1000, 4:5) |
| `mark-of-the-flame.jpg` | Project thumbnail (16:9) |
| `never-met-always-known.jpg` | Project thumbnail (16:9) |
| `distance-within-time.jpg` | Project thumbnail (16:9) |

The site has no build step, framework, or dependencies. Fonts load from Google Fonts; everything else is in `index.html`.

---

## Editing the site

Open `index.html` and search for `EDIT:` to find the spots meant to be personalized. Sections appear in this order: Hero, Mission, What We Do, Our Stack, Recent Work, The Roster, The Founders, Inquiries, Follow Along.

**Swap a project.** Find the `<article class="film-card">` blocks in the Recent Work section. Change the link, thumbnail filename, badge, title, and logline, then upload the new thumbnail at 16:9 (1280×720 works well).

**Add an artist to the roster.** Copy an existing `<article class="artist ...">` block in The Roster section and paste it below the last one. Add or remove `flip` in the class to alternate which side the photo sits on. Roster photos should be 4:5 portraits (800×1000).

**Update social links.** Company links are in the Follow Along section; artist and co-founder links are in the small round buttons inside each card.

**Refresh the share image.** Replace `preview.png` with a new 1200×630 image using the same filename. Social platforms cache previews, so run the URL through the [Facebook Sharing Debugger](https://developers.facebook.com/tools/debug/) and click "Scrape Again" to update it.

Keep image files under about 300 KB where possible so the page loads quickly on phones.

---

## Hosting

Hosted on GitHub Pages from the `main` branch, root folder.

**DNS records** (set at the domain registrar):

| Type | Host | Value |
| --- | --- | --- |
| A | `@` | `185.199.108.153` |
| A | `@` | `185.199.109.153` |
| A | `@` | `185.199.110.153` |
| A | `@` | `185.199.111.153` |
| CNAME | `www` | `reinaacevedo.github.io` |

Under **Settings → Pages**, the custom domain is `courtofloverecords.com` with **Enforce HTTPS** enabled.

---

## Contact

For inquiries, collaborations, commissions, licensing, and press: **[info@courtofloverecords.com](mailto:info@courtofloverecords.com)**

Are you an AI artist? We'd love to collaborate.

**Follow:** [Instagram](https://instagram.com/courtofloverecords) · [TikTok](https://tiktok.com/@courtofloverecords) · [YouTube](https://youtube.com/@courtofloverecords) · [Facebook](https://www.facebook.com/courtofloverecords)

---

© Court of Love Records. All rights reserved. Artwork, music, and characters are the property of Court of Love Records and may not be reused without permission.
