# COLORA Client Care Academy

**COLORA - COLOR YOUR AURA**

Static training website for foundational client-care knowledge, gemstone literacy, after-sales conversations and scenario-based assessment. Built for the COLORA team and adapted from the COLORA Client Care System V1.0 (31.10.2026).

## Features

- Responsive COLORA design using ivory, navy and gold; Cormorant Garamond display and Open Sans body.
- Three tracks: Nền tảng, Client Advisor, Marketing.
- Nine learning modules, 18 situational scripts and 42 MCQ questions with explanations.
- Instant-feedback practice: 10 random questions per attempt.
- Final assessment: 15 questions for foundation; 18 for the other tracks. Pass rule is at least 80% AND no incorrectly answered selected critical question.
- Local-only lesson completion, exam history and JSON progress export.
- Search for lessons and scripts, with quick links to official COLORA policies.
- No framework, npm, backend or external tracking.

## Security and privacy

**This repository is PUBLIC.** Anyone can read the source, content and question bank. The portal has no actual authentication, access control, exam integrity or secure personnel LMS.

- Do NOT input or upload real customer names, phone numbers, emails, orders, case attachments, IDs or any personal information.
- localStorage saves selected role, lesson completion and results on the visitor's device only. Results may be modified by the visitor and must not be treated as official HR certification.
- The source intentionally contains no API keys, spreadsheets, private SOPs, customer records, tokens or contracts.
- A future private internal academy needs genuine server-side identity and role permissions before handling employee records or customer data.
- The noindex,nofollow tag is only a search discovery hint, NOT security.

## Start locally

Open index.html directly in a browser. Alternatively start a simple server:

    python3 -m http.server 8000

Visit http://localhost:8000.

Hash routes (such as #/home, #/learn and #/exam) remain compatible with GitHub Pages project paths and refreshes.

## Deploy with GitHub Pages

1. Open repository Settings > Pages.
2. Under Build and deployment, set Source to **GitHub Actions**.
3. The workflow in .github/workflows/deploy-pages.yml publishes the static website on updates to main, or manual dispatch.
4. Check Actions > Deploy COLORA Academy for a successful run; Settings > Pages provides the verified published URL.

Pages must be enabled in settings. The workflow alone does not guarantee the website has already gone live. GitHub Pages is PUBLIC when deployed.

## File organization

- content.js: training modules, scripts, questions and reference URLs. The correct answer index is zero-based (0 denotes the first option); critical questions require correct responses to pass the exam.
- app.js: navigation, quiz engine, assessment, UI rendering and locally stored progress.
- styles.css: brand palette, typography, components and responsive layouts.
- index.html: shell, accessible navigation and metadata.
- favicon.svg: minimal faceted gemstone mark.
- .github/workflows/deploy-pages.yml: deployment workflow.

## Policies: source of truth

- Warranty: https://colora.vn/pages/chinh-sach-bao-hanh
- Returns: https://colora.vn/pages/chinh-sach-doi-tra
- Shipping: https://colora.vn/pages/chinh-sach-giao-hang
- Sizing and resizing: https://colora.vn/pages/size-resizing
- Complaints: https://colora.vn/pages/phan-anh-khieu-nai
- Privacy: https://colora.vn/pages/chinh-sach-bao-mat

Verify these references and the latest policy version before using them with customers. This training website never overrides public policies or applicable consumer law. Do not copy unapproved draft metal fineness, gemstone treatment, coating specifications or services into customer communication.

## Pre-release review

- [ ] Check the latest official policy pages.
- [ ] Verify gemstone, treatment, metal and finish details per active SKU.
- [ ] Test Chrome/Safari on phone and desktop.
- [ ] Review quiz answers with Client Care Lead and QC.
- [ ] Enable Pages and verify a successful deployment.
- [ ] Decide whether a public educational website is appropriate or a private authenticated LMS is needed.

© COLORA.