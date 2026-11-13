# Ibra Dreams — Management Workspace

A responsive, static landing page based on the supplied Ibra Dreams consolidated group management system prototype.

## Run locally

Open `index.html` in a browser. No build step, framework, external font, or third-party JavaScript dependency is required.

## Deploy

The page can be hosted as a static site, including with GitHub Pages. In repository settings, enable Pages and select the `main` branch and `/ (root)` as the source.

## Production notes

This repository contains the public-facing landing page only. The dashboard artwork is illustrative and does not display live business data. The original prototype included client-side demo access, a browser Supabase configuration, and sample/model data; those have deliberately not been copied into this public page. Do not treat a frontend-only prototype as a production application or put service-role credentials, passwords, private records, or other secrets in browser code. Before deploying the actual management application, implement and independently review server-side authorization, database row-level security, data retention, backups, auditability, and privacy controls.
