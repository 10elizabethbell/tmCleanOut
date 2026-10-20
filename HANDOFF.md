# T&M Clean Out LLC — handoff at ~60%

**Live:** https://10elizabethbell.github.io/tmCleanOut/ · **Repo:** https://github.com/10elizabethbell/tmCleanOut · **Built:** 2026-10-17 from Muse brief (run 2026-10-17, Facebook group ad post) · **Revamped:** 2026-10-19 to the calm band style

## What changed in the revamp (2026-10-19)
The frosted-window build (wipeable frost canvas, icicle seams, tick-a-list picker) is gone; it's in git history at `8051745` if you want any of it back. The page is now the house calm band style, copied from DPG's `index.html`, with the DPG fixes from `calm-photo-style.md` applied (own field fill, error border that survives focus, chip focus outline, no split phone number since it's written with dashes).
- **Look:** paper (#f4f6fb), navy (#1b3a5c) and deep navy (#0f2238, faint line texture) bands in place of the flyer's black panel. The flyer's gold (#e2a83c) is the one accent, used as a fill; gold text on light is #7a5410. Headings in Cal Sans, body in the system stack.
- **Structure:** header (T&M wordmark, 609-672-7518 top right) → navy hero → "When you call, you get me." with insured / family owned / free estimates and the Facebook card → services as tappable rows on deep navy → "Empty house? I'll look after it." → free estimate form with the three steps → closing band (discounts, area, big number) → footer.
- **Motion:** the hero H1 bounces in letter by letter, the rest of the page fades up once, and there's a floating gold text circle. Under reduced motion or with no JS, everything shows at once and the circle stays hidden.
- **Contact:** each service row opens a text to William naming that job. On a computer with a mouse, the rows and the empty-house button jump to the form with the job filled in instead, because `sms:` doesn't open there. The form writes the text, and it falls back to "Copy message" plus the number. The floating circle shows after the hero. It hides over the services, the empty-house button and the form, so two text controls are never in view together.
- **Removed:** the tick-a-list picker (rows now text one job each, and the form covers several), the "wipe the glass" hero, the seams, and the hero facts line (now the trust list).

## What's built
- **Hero:** the plain textured navy band, because there are no work photos. The flyer is the only image, and it's a photo of paper, not of a job. Eyebrow "Clean outs & property care". H1 "Cleared out and cleaned up in Burlington County." Promise "I'm William Jones. My family and I treat your house like it's ours." Two buttons: "Get a free estimate" (gold, goes to the form) and "Text William" (outlined).
- **Services:** all 15 flyer lines as 17 rows in three groups (Clean outs, Inside, Outside), same split as the first build.
- **Favicon, home-screen icon and og image** are new, in the calm palette (T&M lettering with a gold &; there's no logo).
- **Verified:** Chromium and WebKit at 360/390/414/430/1440, plus 768, 844 landscape and 1024. No sideways overflow, no tap target under 44px, and one phone number on the first screen. The H1 is offset mid-animation, then restored to the plain heading with the same height. Reduced motion shows everything with no letter spans. The circle is hidden on the hero, over the rows, the empty-house button and the form, and shown elsewhere. Every `sms:` body decodes correctly. The form shows errors and builds the right message. No JS errors.

## Assumptions I made
- **Not a 40+ audience.** The brief doesn't flag one (seniors are one of five discount groups), so the calm motion stays on. If you see William's customers as mostly older, switch off the bounce-in and fade-up (`older-audience.md`).
- **Colors:** there's no logo, so the brand comes from the flyer (black panel, gold numbers). Navy stands in for the black, per house rules.
- **Voice:** first person "I", with "my family" for the crew ("I'm family owned"; "by William Jones").
- **Service area:** "Burlington County, NJ" is inferred from the Facebook group the ad ran in, and it's in the H1. No towns are stated anywhere.
- **Services were re-read from the flyer image, not Muse's OCR.** Added "Seal EP Henry pavers", which is missing from the brief. Read "Bottom boat painting" and "Re key / winterize homes" as re-keying plus winterizing. The power-washing line is cut off after "& BO…", so I left that out.
- **Copy I wrote in his voice** (he should approve it): the hero promise, "When you call, you get me." and its line, the empty-house paragraph, the step texts, and "Your house, looked after." Step 2 ("You know the price before any work starts") is inferred from "Free estimates".
- **Discount line:** his words, in his order. I added only dot separators, so it doesn't read as "military first responders".

## Placeholders and gaps
- **Texting is unknown.** Every text button assumes 609-672-7518 takes texts. The brief says call is the safe path. The header and closing band carry tap-to-call, and the form's fallback shows the number. Confirm with William. If the number doesn't take texts, switch the hero's "Text William", the rows and the circle to `tel:`.
- **Facebook link** goes to the group ad post. His page "T&M clean out LLC handyman services" exists, but its URL couldn't be found. Swap it in, in two places: the Facebook card and the footer. Also check that the post opens for someone who's logged out or not in the group.
- **No work photos, before/afters or reviews,** so there's no photo proof section. The Facebook card sits under the trust list instead of under photos.
- **Second number (609-331-3190)** is in the footer only. **Email** is in the footer only (house rule).
- Hours, years in business and towns are unknown and left off.

## Questions for the owner
- Can people text 609-672-7518? Which number should the site lead with?
- What's the Facebook business page link?
- Can he send 6–10 job photos, ideally before/after pairs (cleanouts, power washing, deck staining, sealcoating)? One good one would go behind the hero.
- Which towns does he cover?
- Which services matter most? Should any go first or be dropped?
- Is "& BO…" on the flyer boats?
- Does he winterize for banks and realtors? Does he keep keys for vacant homes?

## Ideas not built (yours to pick)
- **Runner-up signature world (opt-in): the frosted window.** It's the first build, in git history at `8051745`: frost you wipe off the glass with a finger, which regrows. Other worlds from the trade: a garage you sweep empty, a driveway that goes glossy as the sealcoat squeegee passes, a deck that darkens as stain is brushed on.
- **Photo hero** as soon as William sends a job photo (calm style item 7).
- **Work photo cards** (4:5, no captions) with the "See more of my work on Facebook" row under them, once photos exist.
- **A "Vacant & foreclosed homes" page** for realtors and banks (cleanout + re-key + winterize as one package).
- **Impeccable findings kept because Ellie chose them:** the eyebrow pills (the craft floor bans eyebrows), Cal Sans, the faint 135° line texture (the detector flags "repeating-gradient stripes"), the H1 bounce-in and the floating text circle.

## Not verified
- Real-device touch on iPhone and Android, inside Facebook's in-app browser.
- Real SMS handoff with the pre-filled body (iOS Messages and Android).
- Whether the Facebook group post opens for people who aren't logged in.
