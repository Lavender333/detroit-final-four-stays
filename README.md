# Detroit Final Four stays

A buildless hospitality landing page for the April 3 and 5, 2027 men's Final Four in Detroit. Includes corporate stays, full-house inquiries, private events, and Luxe*Work.

## Files

- `index.html`: responsive website, light/dark themes, countdown, mobile navigation and inquiry draft form.
- `assets/architectural-concept.webp`: AI-generated architectural concept, clearly labeled on the site.

## Preview locally

Run `python3 -m http.server 8000` from this repository and open http://localhost:8000.

## Hosting

Upload the repository root to any static host. For GitHub Pages, choose Settings > Pages > Deploy from a branch > main > / (root), if available for your account and repository visibility. This repository does not automatically publish or change access.

## Before public launch

Replace the concept brand and imagery with the approved property name and real photos. Add the confirmed address, contact email, telephone and booking destination. Approve the 1872 history, State Registry citation and Mona's story. Confirm suite amenities, capacities, rates, membership details and terms. Connect inquiry delivery and production analytics.

The form currently validates entries and downloads a text inquiry draft. It does not send requests, process payments, check availability or reserve suites. Conversion hooks emit `hospitality:conversion` browser events for CTA clicks and inquiry draft creation; no analytics destination is connected.

Game tickets and official NCAA hospitality are not included. The website does not claim an NCAA or On Location partnership.

## Validation

JavaScript syntax, internal anchors, asset paths and core text/button contrast checked. Live browser layout and interaction verification remains pending.
