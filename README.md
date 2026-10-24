# Elysium / clinic portfolio

A bespoke, dependency-free static portfolio for **Elysium**, an early-stage studio by Diamond Anyanwu in Lagos.

## What this is

This site is an exploratory concept for a proposed managed, human-supervised patient-access / appointment-request administrative assistant for independent dental clinics in Lagos. It presents three concept studies:

- **The enquiry desk** — clinic-approved FAQs and visible next actions.
- **The human handoff** — appointment requests held for clinic review; never autonomous booking.
- **The weekly note** — a simple, illustrative summary of enquiry themes and follow-ups.

This is not a live or proven service. There are no real clients, testimonials, case studies, measured outcomes, integrations, analytics, or active clinic accounts.

## Scope and boundaries

The proposed scope is limited to clinic-approved FAQs, human-reviewed appointment requests, follow-up on missed enquiries, a simple enquiry log, and a weekly summary. It does **not** include diagnosis, treatment advice, deciding urgency, clinical triage, autonomous booking, or requesting patient information.

Every mockup and interaction is labeled or described as illustrative / synthetic. The demo tabs and “Mark for human review” controls are local-only UI behavior: nothing is saved, sent, submitted, or connected to a backend. “Request” does not mean “confirmed appointment.” The clinic retains responsibility for every response and decision.

The contact link is for clinic-business discovery conversations only. Do not email patient details or appointment requests.

## Technical notes

- One `index.html` containing all HTML, CSS, and JavaScript.
- `.nojekyll` included for straightforward GitHub Pages hosting.
- No dependencies, build step, remote fonts, stock images, forms, backend, network calls, or analytics.
- Responsive layout designed to remain usable at 375px and larger.
- Keyboard-accessible tabs with arrow-key navigation, visible focus states, semantic landmarks, and `prefers-reduced-motion` support.

## Local preview

Open `index.html` directly in a browser, or serve the directory with any static server. For example:

```bash
python3 -m http.server 8000
```

Then visit `http://localhost:8000/`.

## Portfolio and source

Source repository: <https://github.com/czardiamond/elysium-clinic-portfolio>

Portfolio URL: <https://czardiamond.github.io/elysium-clinic-portfolio/>

Static hosting only. Publishing this portfolio does not activate a clinic workflow, patient intake, or data connection.
