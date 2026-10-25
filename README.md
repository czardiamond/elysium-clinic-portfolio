# Elysium / AI consultancy

A bespoke, dependency-free static portfolio for **Elysium**, an independent AI consultancy by Diamond Anyanwu in Lagos.

## First proposed solution

Elysium’s first proposed solution is an exploratory, human-supervised clinic enquiry workflow for independent dental clinics in Lagos. The workflow is not a deployed product or a live or proven service. The page presents three parts of this concept: the enquiry desk, the human handoff, and the weekly note.

All examples and interactions are illustrative and synthetic. There are no real clients, testimonials, case studies, measured outcomes, active clinic accounts, or clinic integrations.

## Scope and boundaries

The proposal explores clinic-approved FAQ drafts, human-reviewed appointment requests, follow-up flags, and a simple enquiry log and weekly summary. It does not include diagnosis, treatment advice, deciding urgency, clinical triage, autonomous booking, or requesting patient information. The portfolio does not process patient data.

The demo tabs and “Mark for human review” controls are local-only UI behavior: nothing is saved, sent, submitted, or connected to a backend. A request does not mean a confirmed appointment. The clinic would retain responsibility for every response and decision.

The contact link is for general clinic-business discovery conversations only. Do not email patient details or appointment requests.

## Technical notes

- One `index.html` containing all HTML, CSS, and JavaScript.
- No dependencies, build step, remote fonts, stock images, forms, backend, network calls, or analytics.
- Responsive layout with keyboard-accessible tabs, visible focus states, semantic landmarks, and reduced-motion support.
- Static hosting only; publishing this portfolio does not activate a clinic workflow, intake, or data connection.

## Local preview

Open `index.html` directly in a browser, or run `python3 -m http.server 8000` from the directory and visit `http://localhost:8000/`.

## Portfolio and source

Source repository: <https://github.com/czardiamond/elysium-clinic-portfolio>

Portfolio URL: <https://czardiamond.github.io/elysium-clinic-portfolio/>
