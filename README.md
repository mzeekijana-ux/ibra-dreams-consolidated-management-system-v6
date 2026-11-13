# Ibra Dreams — Management Workspace

A responsive, accessible, single-page product website for the Ibra Dreams management-system concept. It is built with plain HTML, CSS and JavaScript: no build step, framework, font download or third-party runtime dependency is required.

## Features

- Responsive page navigation with a mobile menu.
- Light/dark theme toggle, initialized from the browser preference and saved locally.
- Product overview, workflow, operating principles and contact sections.
- Accessible contact form with required-field validation, consent and a honeypot field.
- Illustrative dashboard preview clearly marked as sample content; it contains no live business data.

## Run locally

Open `index.html` in a browser. The theme toggle and navigation work locally. The contact form needs a form-handling host to receive submissions.

## Deploy

### Netlify (contact form enabled)

Deploy this repository as a static site on Netlify. The form uses Netlify Forms markup (`data-netlify="true"`) and redirects to `thank-you.html` after a successful submission. Enable form detection for the site and submit a test enquiry after deployment. Review Netlify's current form handling, spam protection and retention settings before collecting real enquiries.

### GitHub Pages (static page)

Enable GitHub Pages for the `main` branch and repository root. The landing page and theme work there, but GitHub Pages does not process form submissions. To collect enquiries on GitHub Pages, connect a form provider or backend and configure its endpoint; do not assume submissions are stored by this static site.

## Security and production scope

This repository is the public-facing landing page, not the management application or its backend. The dashboard visual is illustrative. The original prototype included browser-side demo access, sample data and a Supabase anon key; those were intentionally not copied into this public website. Do not put service-role credentials, passwords, private records or sensitive operational data in client-side code. Before deploying the actual management app, implement and independently review server-side authorization, database row-level security, privacy, audit logging, retention and backup controls.
