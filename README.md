# Mind Mirror — launch community website

Static HTML/CSS update based on Empowered's feedback. No build command or installation is needed. The original README identifies Netlify as the host, connected to this GitHub repository. Confirm that connection in Netlify before relying on an automatic deployment.

## Files
- index.html — Adults across Canada, one primary launch-community CTA; dedicated 18–34 programs planned.
- employers.html — separate workplace pilot page for SMEs in tech, healthcare, and finance.
- styles.css — responsive shared design.
- thank-you.html — signup confirmation and next steps.
- mind-mirror-logo.jpeg — original logo, unchanged.

## Upload through GitHub
1. Extract the supplied ZIP on your computer.
2. Open https://github.com/kartikga82/mindmirror-website and select the branch currently used for your Netlify production deployment (the original download was main).
3. Click Add file → Upload files.
4. Drag the files INSIDE the extracted folder into GitHub. Do not upload the ZIP or the enclosing folder. index.html must remain at the repository root.
5. Use the commit message: Refocus Mind Mirror on launch community and employer pilots.
6. Commit changes. If using a new branch, merge the resulting pull request into the production branch when ready.
7. Open your existing Netlify site's Deploys page. Check that a deployment for this commit completes successfully, then open its published URL.

## Before advertising
- Confirm hello@mindmirror.ca is monitored. It is retained from the original source, not independently verified.
- Confirm the proposed community offer: no payment to join, optional interviews/prototype feedback, email updates, no promised launch date. Set a practical communication schedule internally.
- Confirm the employer-funded pilot direction with the team. No pilot price or results are claimed.
- In the existing Netlify site, confirm form detection is enabled, redeploy if changed, and confirm the early-access form is detected. The form name, hidden form-name field, POST method, and honeypot are retained from the original site.
- Submit a real test from the deployed site. Verify the submission appears in Netlify Forms AND the browser reaches thank-you.html. Check notification delivery separately. Local preview or GitHub Pages alone does not process this Netlify form.
- Check the actual consent, contact details, privacy notice and email handling against your operational setup before collecting signups. No unverified privacy guarantees have been added. This source package does not establish retention settings, unsubscribe automation, or a full privacy policy.
- Test the site on a phone and desktop. Check email links with an email app configured.
- Confirm your actual production domain in Netlify. The source does not change DNS or domain settings.

## Research and launch plan
1. Interview 50–60 Canadian adults across clearly defined age segments, including the planned 18–34 program audience. Ask about a recent real example, what they tried, where it fell short, and what they paid for. Record exact phrases with permission.
2. Interview SME decision-makers separately: problem owner, current spending, purchase approval, privacy requirements, and criteria for a paid pilot.
3. Replace the provisional problem statements on the homepage with recurring interview language. Current copy is a hypothesis, not research findings or quotations from customers.
4. Offer optional interviews and prototype feedback with clear schedules and expectations. Track consent and honour withdrawal requests.
5. Only show a remaining-spots count if a real capacity exists and the count is maintained. No artificial scarcity is included.
6. After validating the form and offer, run a limited consumer ad test to the homepage. Keep employer outreach focused on employers.html.
7. Compare qualified registrations, participation, repeat engagement and paid commitments. Do not treat signups alone as evidence of willingness to pay.

## Implementation notes
The product illustration is a clearly labelled static concept. It does not collect reflections or imply that a live app exists. No fabricated testimonials, partner logos, clinical claims or user counts are used. Broad caregiver, chronic-illness and multilingual feature promises were removed from this initial landing page.

The original script stored emails in localStorage before the server confirmed success and blocked retries. That script was removed. The form now uses Netlify's native POST flow, without locally claiming successful submission. The thank-you page is reached through the form action when hosting processes the submission.

The design uses optional Google Fonts with system fallbacks. All other assets are local. No analytics, Meta pixel, ad campaign, automatic email sequence, payment flow or backend was added. This package does not publish changes to GitHub or Netlify by itself.

## Refreshed prototype preview
The homepage now includes five screen concepts based on MirrorMind_PoC_Prototype_UpdatedVersion.pptx: daily home, guided reflection, journal, patterns, and preferences. The designs use the current green/cream palette and editable HTML/CSS. No image uploads or additional dependencies are needed. Screen switching uses a small inline script; all phone contents remain illustrative.

The previous prototype's clinical score, therapist availability, chronic-illness alerts and clinical screening claims were not carried into the public preview. All names, journal entries and check-ins in the new screens are fictional. The actual account, AI, storage, privacy and clinical capabilities have not been implemented by this website update.

Upload index.html, styles.css and README.md to the repository root to apply this revision. The full ZIP also contains the unchanged employer page, confirmation page and original logo. Test all five screen selectors at desktop and phone widths, then test the existing Netlify signup flow on the deployed site.

## Inclusive adult audience update
The homepage, metadata, employer copy and signup now welcome adults of all ages across Canada. The mandatory 18-34 eligibility checkbox has been removed; required email consent remains. No age field is collected. Dedicated programs for ages 18-34 are described as planned, since the product is in development.

The research FAQ links to Statistics Canada's 2023 summary of its 2022 survey and accurately distinguishes its highlighted 15-24 group from Mind Mirror's chosen 18-34 program focus. Research is not presented as evidence of product effectiveness.

For this update, upload index.html, employers.html and README.md at the repository root. Your current larger-layout styles.css stays in place. Once Netlify publishes, confirm an adult over 34 can complete the signup without an age checkbox, check the new FAQs, and verify the submission in Netlify Forms.
