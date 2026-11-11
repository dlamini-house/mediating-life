# Mediating Life

Responsive, buildless HTML, CSS and JavaScript website for client review.

## Preview

Open `index.html` in a browser, or run `python -m http.server 8000` in this directory and visit http://localhost:8000.

## GitHub Pages

1. Create a GitHub repository and upload the contents of this folder, including `.github/workflows/pages.yml`.
2. Use `main` as the default branch.
3. In repository Settings → Pages → Build and deployment, select **GitHub Actions**.
4. Run the Deploy to GitHub Pages workflow (or push to `main`). The workflow returns the review URL.

All internal paths are relative, including assets, so project repository URLs work. This folder is the repository root. No installation or build is needed. GitHub Pages URLs are public unless the account supports private Pages access.

## Contact behaviour

The form validates required fields and opens an email draft. Visitors must send that draft from their email app. No message is stored or submitted by the website. A backend or form provider can replace this after client approval. There is no self-service calendar: consultation requests require office confirmation. Fees are private. WhatsApp opens only from the final Home and Services buttons.

## Content notes before production

- ADR Network SA Panel status is supported by the supplied certificate, effective to 30 September 2027. Review status before that date. Verification details, ADR logos and certificate files are deliberately excluded from the public site.
- Mediation Academy training is supported by the supplied certificate. Commercial mediation training is stated in the client email; no separate commercial training certificate was supplied.
- The book title is included without a fabricated cover or description. Replace/add the actual cover when supplied.
- No testimonials are shown. The founder’s former judicial status is explicit.
- The client’s specific WhatsApp removals, accreditation wording, privacy of fees and approval-only booking requirement are incorporated.
- Google Fonts is optional and falls back to local sans-serif fonts. No analytics are included.
- Review the privacy copy and choose the final enquiry handling service before production launch.

Client-supplied images are included for this project; do not reuse them for other clients.
