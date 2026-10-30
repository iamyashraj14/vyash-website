# Vyash Cybersecurity Private Limited — Website

Single-page company website for Vyash Cybersecurity: Aadhaar compliance support, ISO/IEC 27001 implementation, DPDP readiness, RBI/SEBI/CERT-In regulatory readiness, VAPT, IS audits, vCISO and incident readiness.

## Structure

- `index.html` — the whole site (HTML, CSS and JS in one file). Fonts load from Google Fonts; no build step.
- `assets/` — Vyash logo, monogram and wordmark (transparent PNGs cut from the brand logo).

## Run locally

Open `index.html` in a browser, or serve the folder:

```bash
python3 -m http.server 8080
```

## Deploy with GitHub Pages

1. Repository **Settings → Pages**
2. Source: **Deploy from a branch**, branch `main`, folder `/ (root)`
3. Save. The site goes live at `https://<username>.github.io/<repo>/`

## Before going live

- Replace the placeholder email (`contact@vyashcyber.in`) and phone (`+91 00000 00000`) in the Contact section.
- The enquiry form currently prepares an email for the visitor to copy. Connect it to a form handler (e.g. Formspree, Netlify Forms or your own mail endpoint) to receive enquiries directly.
- Add client references or testimonials only with the client's permission.

## Scope statement

The site states that Vyash is not a CERT-In empanelled auditing organisation, a certification body or a UIDAI-appointed auditor. Keep this wording accurate if the company's empanelment status changes.
