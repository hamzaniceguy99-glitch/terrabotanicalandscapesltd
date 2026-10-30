# Terra Botanica — terra botanica landscapes ltd

Static marketing site (HTML / CSS / JS, no build step) hosted on GitHub Pages
at `terrabotanicalandscapesltd.shop`.

> Generated from `C:\Users\souha\coaching-sites-factory` (content file `sites/terrabotanicalandscapesltd.mjs`).
> To change the content, edit that file and run `node build.mjs terrabotanicalandscapesltd` — editing the
> HTML here directly would be overwritten on the next build.

## Before you promote this site

| Priority | What | Where |
|---|---|---|
| 🔴 Blocking | Legal page: fill every `[BRACKET]` (legal name, address, state, payment provider). Have a lawyer review it if you can. | `legal.html` |
| 🟠 Important | `contact@terrabotanicalandscapesltd.shop` doesn't exist yet: set up free email forwarding in Namecheap (*Domain List → Manage → Redirect Email*). | Namecheap |
| 🟠 Important | Contact form: replace `VOTRE_ID_FORMSPREE` with your Formspree id (until then it falls back to `mailto:`). | `contact.html` |
| 🟠 Important | Add a real introduction of the coach (name, background, photo). Never invent credentials. | `about.html` |
| 🟡 Later | Prices ($Quote / $Quote / $Declined) and plan contents should match what you actually sell. | `index.html` `#pricing` |
| 🟡 Later | Testimonials: only add real ones, with permission. Fake reviews are illegal (FTC). | — |

## Business description (Stripe, directories…)

```
Terra Botanica Landscapes Ltd is a landscaping business in Norfolk, trading since 2024. We design and plant gardens, manage hedges and trees, build hard landscaping and maintain grounds. One rule changes how we schedule work, and most clients have never heard of it. It is a criminal offence to damage or destroy a wild bird's nest while it is in use or being built, which means a hedge cut between roughly March and August has to be checked first, and sometimes left. The offence is committed by whoever does the cutting, so this is our exposure as well as yours. We also check for Tree Preservation Orders and conservation areas before touching a tree, since pruning a protected one without consent carries an unlimited fine, and green waste leaves your site through a registered carrier. Site: terrabotanicalandscapesltd.shop
```

## Structure

```
index.html            Home: hero, programs, method, pricing, approach, FAQ
programs.html         The four programs in detail
about.html            How we work, principles
contact.html          Contact form
legal.html            Business info, privacy policy, terms of service
404.html              Error page (absolute paths)
assets/css/style.css  Brand colors at the top, shared styles below
assets/js/main.js     Menu, theme, animations, form
```

## DNS (Namecheap → Advanced DNS)

Delete the parking records, then add:

| Type | Host | Value |
|---|---|---|
| A Record | `@` | `185.199.108.153` |
| A Record | `@` | `185.199.109.153` |
| A Record | `@` | `185.199.110.153` |
| A Record | `@` | `185.199.111.153` |
| CNAME Record | `www` | `hamzaniceguy99-glitch.github.io.` |
