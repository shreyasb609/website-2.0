# Elevate Tutoring Website

Hugo website using the Techly theme and a site-level CSS overlay in `assets/css/custom.css`.

Run `hugo server` for local development. Run `hugo --printPathWarnings` to build.
The deployment base URL is configured in `hugo.yaml`; content links use the `site-url` shortcode so they also work at another base path.

## Site functionality

- Home, About/programs, tutoring inquiries, tutor applications, FAQ, contact, study topic previews, and portal availability page.
- FAQ uses native HTML disclosures. Topic previews support Escape, focus return, and keyboard focus containment.
- Student intake (`content/get-tutored.md`) and tutor applications (`content/join.md`) each embed their own Google Form, with direct-link fallbacks. Manage questions, response access, and submissions in Google Forms.
- The portal is a coming-soon page. Authentication, session tracking, and reminders require a real backend; the previous browser-only simulation did not provide those services.
- Resources currently contain topic overviews, not downloadable PDFs.

## Review limitations

Business claims, testimonials, tutor affiliations, response times, and the contact mailbox require owner verification before publication. They were not independently verified during the formatting review.
