# UNMUTE — public launch landing page

This is a safe, static public-facing launch page for UNMUTE. It does not pretend to provide working user accounts, anonymous posting, public discussions, or admin moderation. Those features must be implemented with a secure backend before the community opens.

## Quick deploy with Vercel (recommended)

1. Create a GitHub account if you don't already have one.
2. Create a new GitHub repository named `unmute`.
3. Upload `index.html` and the `public/` folder to the repository root.
4. Sign in to Vercel using GitHub and choose **Add New → Project**.
5. Import the `unmute` repository.
6. For this plain static site, leave the framework preset as **Other** and the build command/output directory blank (or use the root as the static output).
7. Deploy. Vercel will provide a temporary `*.vercel.app` URL.
8. Test the site on mobile and desktop before sharing it.
9. Add a custom domain later in Vercel's project settings after purchasing/confirming a domain.

Alternative: Netlify can deploy this folder by drag-and-drop, or connect the same GitHub repository.

## Before opening community features

Build and test a real backend:
- Supabase Auth with email verification and password reset
- Database tables for profiles, posts, moderation events and reports
- Row-level security and server-side moderator roles
- Anonymous posting that never exposes author identity in public API responses
- Admin approval queue, report/block flows, spam limits and audit logs
- Privacy policy, terms, deletion/export workflow and safety escalation process

Do not deploy the old browser-storage demo as a public community service. Its demo credentials and admin switch are not secure.

## Brand note

Name: UNMUTE
Tagline: Speak freely. Grow together.
Palette: forest green, warm ivory, muted gold.

Domain and trademark availability have not been checked.
