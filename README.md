# ClearReply MY

**Better replies. Less back-and-forth.**

A minimal, responsive website for an independent copywriting service helping Malaysian residential cleaning businesses explain their services and respond to customer enquiries.

[Visit the website](https://spiffy-cupcake-a00065.netlify.app)

## The service

The RM199 Customer Enquiry Kit includes one service description, eight customer FAQs, ten reusable enquiry replies and one revision round. Visitors can request a consultation through the website.

## Website

- Responsive layout with clear typography and restrained colours.
- Accessible form labels, keyboard focus states and reduced-motion support.
- Consultation form with contact preferences, consent and a hidden spam-trap field.
- Netlify Forms integration and a dedicated thank-you page.
- Plain HTML, CSS and JavaScript. No build step or external dependencies.
- No owner email address embedded in the website files.

## Project structure

```text
public/
  index.html        Landing page and consultation form
  thank-you.html    Form submission destination
netlify.toml        Publishes only the public directory
```

## Local preview

Open `public/index.html` in a browser. The page works without installing dependencies. Submissions are intentionally blocked in a local preview; receiving applications requires deployment with Netlify Forms enabled.

## Deploy on Netlify

Use the existing Netlify project to preserve its URL. Link this repository, use `main` as the production branch, leave the build command empty and publish the `public` directory. The included `netlify.toml` declares that directory.

Enable form detection under **Forms** before deploying. After deployment, confirm the `consultation` form appears, send a test using your own details, and verify it arrives in the private Forms dashboard. A thank-you page alone is not proof of receipt. Optional submission notifications can be configured privately in Netlify.

For manual deployment, upload the contents of the `public` folder.

[Netlify Forms setup](https://docs.netlify.com/manage/forms/setup/)

GitHub stores this website's code. Keep Netlify as the live host: GitHub Pages does not provide this site's Netlify form handling.

## Privacy and editing

Keep personal contact addresses, submission exports, customer information and credentials out of commits. Store application data in the private form dashboard. Edit only the current website files; older email-based versions are not included here.

The conversation shown on the landing page is illustrative. Service details must remain accurate; do not add unverified testimonials or outcome guarantees.

## Ownership

© 2026 Omar Ahmed. ClearReply MY is a working service name. No open-source license is granted by this repository.
