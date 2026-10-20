# A Y M Affordable Tree Service — handoff at ~60%

**Live:** https://10elizabethbell.github.io/aymAffordableTreeService/ · **Repo:** https://github.com/10elizabethbell/aymAffordableTreeService · **Built:** 2026-10-20 from Muse brief of 2026-10-20 (flyer post in "Morris County Business Network") · **Call Sheet:** site URL set

## What's built
- One page, `index.html`, single file, phone first. Sections: header (AYM wordmark + tap-to-call number top right), hero, "We treat your yard like our own" (five flyer claims), services (six rows on green, each pre-ticks its job in the form), storm damage ("Trees don't care about your schedule.", three points, the truck photo, then the Facebook link "Click to see more of our work."), How it works (3 steps), "Tell us about the tree" estimate form, closing band ("Don't wait, call today." + big number), footer.
- Calm band style in AYM colours: paper `#f5f6f2`, truck-door green `#1f5a3c`, deep forest green `#0e3021` (diagonal-line texture on How it works and footer), marker-light amber `#f5a524` as the one accent (fills only, deep green text on it; `#874a00` when it must be text on light). Cal Sans display, system body 16/1.7.
- Hero: their own crane truck photo (Facebook profile picture) under a deep-green overlay. Phones: full-bleed behind the text. Desktop (1024+): photo on the right ~60%, masked into solid green behind the text, so it shows at about its native size and stays sharp. White text measured at 6.6:1 or better by pixel sampling.
- Motion: H1 letter bounce-in (restores the plain H1 after), 12px fade-up for content below the first screen, floating amber text circle (shows after the hero, hides over the form). All off under reduced motion; everything visible with JS off.
- Contact: `tel:+12017072057` top right and in the closing band; hero "Text us" and the float open SMS with "Hi AYM, I found your website. I need help with a tree: ". The form composes "Hi AYM, this is <name>. I'd like a free estimate for: <jobs>. Where: <town>. <notes>" and reminds them to add photos of the tree. No email anywhere (none exists).
- Favicon / home-screen icon: "AYM" in the site's lettering on green with an amber bar (no logo file exists). `og.png` is a 1200×630 capture of the hero.

## Assumptions I made
- **Place = Little Falls, NJ.** The brief said "area unknown" and warned not to confuse them with "A&M Affordable Tree Service (Little Falls NJ)". But the Facebook page at the brief's own ID (61588044986207) titles itself **"A Y M Affordable Tree Service | Little Falls NJ"** (og:title, fetched 2026-10-20). So Little Falls is their own claim and it's in the H1. **Confirm first**; if wrong, change the H1, `<title>`, meta, close band and footer (search "Little Falls").
- **"Emergency calls, 24/7" and "crane"** come from the page's own description ("Experts in tree removal, pruning, emergency 24/7, stump removal and crane...", truncated) and the crane truck in their profile photo. Not on the flyer. Confirm.
- **Colours:** inferred from the green lettering on the truck door (photo) and the amber marker lights. No logo file or brand colours were available.
- **Name:** "A Y M Affordable Tree Service" as on the Facebook page; wordmark "AYM" as lettered on the truck door. The flyer OCR "A&N M ... LLC" is unconfirmed; "LLC" is left off.
- **Voice:** "we" (flyer says "EXPERIENCED CREW").
- **Copy I wrote (approve with the owner):** "Safe, fast tree work in Little Falls." (from "SAFE. FAST. RELIABLE."), "We treat your yard like our own." and its paragraph (from "ON TIME, EVERY TIME", "CLEAN & CAREFUL"), "Big tree or small, we handle it.", the storm lede, the three How-it-works lines, "Tell us about the tree".
- **Audience:** general homeowners and businesses, so the calm-style motion is on.

## Placeholders and gaps
- **Only one photo** (the truck). No job photos, no before/afters, no logo. The Facebook timeline is login-only and the group "flyer" link returned the group's stock cover image, not the flyer.
- Licence plate on the truck cropped out (bottom of the photo removed). Raw originals stay in `src-assets/` (git-ignored).
- No email, hours, town list, reviews or prices. Nothing about them is on the page.

## Questions for the owner
- Is Little Falls right, and which towns do you cover?
- Is it "A Y M" or "A&N M", and is it an LLC?
- Do you really answer emergencies 24/7, and do you do crane work?
- Can we have 6–10 job photos (before/after of removals and stump grinding especially) and the flyer itself?
- A logo file, if one exists (the truck-door lettering would do)?
- An email for the footer? Hours?
- Your licence number, if you want it shown?

## Ideas not built (yours to pick)
- **Work photo cards + before/after sliders** once real job photos arrive (calm kit components 5 and the slider module).
- **Runner-up signature motion (opt-in):** falling leaves / sawdust that drift across the hero and scatter from the finger, settling into a pile along the hero's bottom edge. Other worlds considered: chainsaw-cut wood grain rings, a swaying canopy, a stump being ground away under the finger, bark texture.
- A "storm season" seasonal banner line in the storm section (Muse flagged storm cleanup as the winter hook).
- Self-host Cal Sans (woff2 + preload) so first paint in Facebook's in-app browser doesn't wait on Google Fonts.

## Not verified
- Real-device touch, and the SMS handoff on iOS/Android and inside Facebook's in-app browser (tested in Chromium and WebKit via Playwright only).
- Frame rate on old phones.
