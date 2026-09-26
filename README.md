# Elevate Tutoring Website

Hugo website using the Techly theme and a site-level CSS overlay in `assets/css/custom.css`.

Run `hugo server` for local development. Run `hugo --printPathWarnings` to build.
The deployment base URL is configured in `hugo.yaml`; content links use the `site-url` shortcode so they also work at another base path.

## Site functionality

- Home, About/programs, tutoring inquiries, tutor applications, FAQ, contact, study topic previews, and portal availability page.
- FAQ uses native HTML disclosures. Topic previews support Escape, focus return, and keyboard focus containment.
- Set `params.formspree_action` in `hugo.yaml` to a real Formspree endpoint to enable the intake and application forms. Until configured, both pages show an email contact option and hide/disable submission fields.
- The portal is a coming-soon page. Authentication, session tracking, and reminders require a real backend; the previous browser-only simulation did not provide those services.
- Resources currently contain topic overviews, not downloadable PDFs.

## Review limitations

Business claims, testimonials, tutor affiliations, response times, and the contact mailbox require owner verification before publication. They were not independently verified during the formatting review.
