# Refer 2 Earn: Method Sheet for Adding New Offers

Follow these steps to add a new offer to the site, ensuring consistency and brand alignment.

---

## 1. Create the Offer Page
- **Duplicate** an existing offer HTML file (e.g., `offers/baremetrics.html`).
- **Rename** the file to match the new offer (e.g., `offers/newbrand.html`).
- **Update** the following:
  - **Title** in the `<title>` tag.
  - **Brand-specific class** in the `<body>` tag (e.g., `brand-newbrand`).
  - **Headline, subheadline, and offer details** in the body.
  - **Button text and link**.
  - **Card colors and accent styles** to match the new brand (update CSS if needed).

## 2. Add Brand-Specific Styles
- In `styles.css`, add a new section for the brand if it needs unique colors or gradients.
- Follow the format of existing brand styles (e.g., `.brand-baremetrics`).

## 3. Update the Navbar
- Add the new offer to the appropriate category in `navbar.html` with the correct link and incentive.

## 4. Update the Homepage Carousel
- Add a new `.offer-card` for the brand in the relevant section in `index.html`.

## 5. Add to Referral Links List
- Add the new offer's main referral link to `all-referral.links.txt` in the root folder.
  - Format: `Brand Name: https://referral-link-here.com`

## 6. Test
- Check the new offer page on desktop and mobile.
- Test navigation and carousel functionality.

---

**Keep this file up to date for future reference!** 