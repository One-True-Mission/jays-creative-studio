# Jay's Creative Studio - Asset & Swap Checklist

Demo build, OTM background-build standard. Dark atmospheric locked background, ivory
floating frames, deep rose-red primary accent (#A8294A), metallic gold trim (#C2A04C),
deep wine emphasis bands (#4A2335). Fonts: Fraunces + Nunito Sans.

Pages: Home, Services, About, Book (+ thank-you, privacy, terms, accessibility, sitemap, robots).

---

## IMAGES TO DROP IN  (all go in `assets/`, flat, no subfolders)

There is no events stock library yet, so every photo slot below needs sourcing
(Unsplash+ / per-project Envato) or a real client photo. Each `<img>` and gallery
slide is coded to hide / fall back cleanly until the file exists, so the layout
already holds without them.

### Unique hero per nav page (never reuse one across these four)
- [ ] `hero-home.jpg` - Home hero. Wide, elegant quince / event scene.
- [ ] `hero-services.jpg` - Services hero. Distinct from the others.
- [ ] `hero-about.jpg` - About hero. Distinct from the others.
- [ ] `hero-book.jpg` - Book hero. Distinct from the others.

### Backgrounds
- [ ] `body-bg.jpg` - Locked atmospheric background (dark, elegant: soft bokeh, draped
      venue, dark florals). Darkened in CSS by `filter: brightness(0.62)`. 2560x1440 ideal, < 400kb.
- [ ] `cta-bg.jpg` - CTA strip background (on-brand event photo). Sits behind a wine 0.82 overlay.

### Content photos
- [ ] `home-intro.jpg` - Home intro media (a styled setup / celebration shot).
- [ ] `about-main.jpg` - **REAL PHOTO you already have:** the "Mis Quince Jaylena" floral
      photo wall + neon sign you texted. Save it here. (Feel free to reuse it as `gallery-1.jpg` too.)
- [ ] `gallery-1.jpg` ... `gallery-6.jpg` - 6 event photos for the homepage carousel
      (photo booth setup, custom backdrop, merch table, a banner, choreography, party favors).

### Brand
- [ ] `logo.png` - Transparent logo. **None yet**, so the nav/footer currently show the
      typographic wordmark "Jay's Creative Studio". Drop a PNG in later and it appears automatically.
- [x] `og-image.jpg` - GENERATED (1200x630, brand colors + wordmark). Regenerate from a real logo once one exists.

---

## TEXT / CONFIG TO SWAP BEFORE LAUNCH

- [ ] **Formspree endpoint** in `book.html`: replace `YOUR_FORMSPREE_ENDPOINT_HERE`
      with the real per-client endpoint.
- [ ] **Phone** `(512) 555-0143` is a placeholder - swap to Jay's real number, or remove
      the phone rows from `book.html` + the footer if she doesn't want one public.
- [ ] **Email** `hello@jayscreativestudio.com` is a placeholder - swap to the real address.
- [ ] **Instagram** links point to `https://www.instagram.com/` - swap to the real handle.
- [ ] **Domain** `jayscreativestudio.com` is used in every canonical, og:url, sitemap,
      robots, and the schema block. Swap to the real domain (or the `*.github.io` URL)
      before launch. Then submit `sitemap.xml` in Google Search Console and run the home
      page through Facebook's Sharing Debugger once.

---

## NOTES

- **No reviews / ratings** are shown anywhere (brand-new business). The testimonials
  section and `aggregateRating` schema were intentionally left out so nothing is fabricated.
  Add the reviews carousel + rating once real Google reviews exist.
- **No Shop page yet.** Merch + the surprise box live as a service and are showcased in the
  gallery. When Jay is ready to take orders/payment online, add a dedicated Shop page (and a
  Returns/Refund + Shipping policy, which the Terms already partly cover).
- Contact/phone/name were placeholdered per your call. If Jay wants her name listed publicly,
  say so and I'll add it.
