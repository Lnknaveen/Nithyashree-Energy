# Next Actions

## Before promoting the site

- [ ] Sign in to the admin desk with both authorised Google accounts and confirm leads load correctly.
- [ ] Add a privacy policy and terms page; replace the footer placeholder links.
- [ ] Add Firebase App Check (reCAPTCHA v3) and spam protection for the public lead forms.
- [ ] Restrict the Firebase web API key to `nithyashree-energy.web.app`, `nithyashree-energy.firebaseapp.com`, and localhost.
- [ ] Submit the business and dealer forms once to confirm they write to Firestore (survey and quote already tested).
- [ ] Confirm the office address (`First Main` vs PDF's `First Mane`) and the subsidy calculator assumptions with Nithyashree.

## Later

- [ ] Connect a custom domain in Firebase Hosting and verify DNS.
- [ ] Add new-lead email or WhatsApp notifications; Cloud Functions requires Blaze billing.
- [ ] Enable Firestore backups/export and define a lead retention policy.
- [ ] Add privacy-friendly analytics and cookie consent if required.
- [ ] Add a billing budget alert if Cloud Functions or other paid Firebase services are enabled.
