# DO2E Wastewater — do2e wastewater treatment llc

Static marketing site (HTML / CSS / JS, no build step) hosted on GitHub Pages
at `do2ewastewatertreatmentllc.shop`.

> Generated from `C:\Users\souha\coaching-sites-factory` (content file `sites/do2ewastewatertreatmentllc.mjs`).
> To change the content, edit that file and run `node build.mjs do2ewastewatertreatmentllc` — editing the
> HTML here directly would be overwritten on the next build.

## Before you promote this site

| Priority | What | Where |
|---|---|---|
| 🔴 Blocking | Legal page: fill every `[BRACKET]` (legal name, address, state, payment provider). Have a lawyer review it if you can. | `legal.html` |
| 🟠 Important | `contact@do2ewastewatertreatmentllc.shop` doesn't exist yet: set up free email forwarding in Namecheap (*Domain List → Manage → Redirect Email*). | Namecheap |
| 🟠 Important | Contact form: replace `VOTRE_ID_FORMSPREE` with your Formspree id (until then it falls back to `mailto:`). | `contact.html` |
| 🟠 Important | Add a real introduction of the coach (name, background, photo). Never invent credentials. | `about.html` |
| 🟡 Later | Prices ($Quote / $Quote / $Quote) and plan contents should match what you actually sell. | `index.html` `#pricing` |
| 🟡 Later | Testimonials: only add real ones, with permission. Fake reviews are illegal (FTC). | — |

## Business description (Stripe, directories…)

```
DO2E Wastewater Treatment LLC, a Florida limited liability company (document number L07000087596), supplies and services wastewater treatment equipment for municipal, industrial and agricultural operators: aeration systems for lagoons, ponds and treatment basins, sludge reduction and biological treatment programmes, odour and surface crust control, and inspection, servicing and parts for installed systems. Every supply is quoted in writing after a site assessment of flows, loadings and existing equipment. The company supplies and services equipment and does not perform licensed contracting, engineering design or permitting work. Site: do2ewastewatertreatmentllc.shop
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
