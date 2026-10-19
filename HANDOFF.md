# T&M Clean Out LLC — handoff at ~60%

**Live:** https://10elizabethbell.github.io/tmCleanOut/ · **Repo:** https://github.com/10elizabethbell/tmCleanOut · **Built:** 2026-10-17 from Muse brief (run 2026-10-17, Facebook group ad post)

## What's built
- **World: a window in winter.** Dusk-navy panes (never black) with fern-crystal frost growing in from the glass edges over a street of rooftops with a few gold-lit windows. Ice-blue reading bands, the flyer's gold as the only warm accent. Heavy uppercase system sans.
- **Signature element:** frost you wipe with a finger (every direction in the hero) or by hovering the mouse. Meltwater drops run down the clear glass in stick-slip and leave trails, and the frost grows back after a few seconds. The hero wipes itself in hand-like strokes until it's touched. The same engine runs on the "Empty house?" band and the closing band; on those two, vertical swipes scroll the page.
- **Seams:** a moving snowdrift edge where a pane ends, and an icicle eave with growing, falling drips where one begins.
- **Sections:** header (wordmark, tap-to-call 609-672-7518 top right) → hero ("Cleared out. Cleaned up.", promise, "Get a free estimate" + outlined "Text William", insured / family owned / free estimates) → "Everything I do" (all 15 flyer services as 17 tickable rows in 3 groups; ticking makes a frost-crystal puff, and the ticked list becomes a pre-written text to William) → "Empty house? I'll look after it." → How it works (3 steps) → "I don't post every job" + Facebook → discounts + where I work → close → footer (both numbers, email, Facebook).
- **Contact wiring:** `tel:+16096727518` in the header; every text button is `sms:+16096727518?&body=…`. Bodies were tested and decode correctly. The second number (609-331-3190) appears only in the footer.
- **Verified:** Chromium and WebKit at 360/390/414/430/1440 have no sideways overflow and no tap targets under 44px. The headline and primary button sit on the first screen, with exactly one phone number there. A simulated touch drag (sideways, down, up) clears frost at every size and survives same-size resize events. There are no JS errors. Reduced motion draws a still frame and hides the hint.

## Assumptions I made
- **Colors:** there's no logo, so the brand comes from the flyer (black panel, gold numbers). I kept the gold as trim and put navy in place of black, per house rules.
- **Voice is first person "I", with "my family" for the crew.** He says "I'm family owned" and the flyer says "by William Jones".
- **Service area:** "Burlington County, NJ and the towns around it". This is inferred from the Facebook group the ad ran in. No towns are stated anywhere.
- **Services were re-read from the flyer image, not Muse's OCR.** Added: "Seal EP Henry pavers" (missing from the brief). Corrected: "Bottom boat painting" (not "Boat painting") and "Re key / winterize homes", which I read as re-keying locks plus winterizing. The power-washing line is cut off after "& BO…" (probably boats); I left that out rather than guess.
- **"Tree service and stump grinding" sits under Outside, and moving under Clean outs.** That grouping is mine.
- **Discount line:** his words and their order are kept exactly ("military first responders teachers seniors new clients"). I added only dot separators, so it doesn't read as "military first responders".
- **Copy I wrote in his voice** (he should approve it): the promise line ("treat your house like it's ours, from the garage to the driveway seal"), the vacant-home paragraph ("…winterize it before the first freeze, and look after it like it's my own"), the step texts, and the closing line.
- **How it works step 2** ("You know the price before any work starts") is inferred from "Free estimates".

## Placeholders and gaps
- **Texting is unknown.** Every text button assumes 609-672-7518 takes texts. Confirm with William before handover; if it doesn't, swap the text buttons to call or the second number.
- **Facebook link** goes to the group ad post (https://www.facebook.com/groups/1772980119690817/permalink/4636261316696002/). His page "T&M clean out LLC handyman services" exists but its URL couldn't be found. Get it from him and swap it in (2 places: the proof block and the footer). Also check the post opens for someone who's logged out or not in the group.
- **No logo:** the favicon and home-screen icon are the site's own "T&M" lettering (gold &).
- **No work photos, before/afters or reviews,** so there's no photo proof section. The Facebook block stands in for it.
- **Hours, years in business and towns** are unknown and left off.

## Questions for the owner
- Can people text 609-672-7518? Which number should the site lead with?
- What's the Facebook business page link?
- Can he send 6–10 job photos, ideally before/after pairs (cleanouts, power washing, deck staining, sealcoating)?
- Which towns does he cover? Any he won't drive to?
- Which services matter most, or bring the most work? Should any go first or be dropped?
- Is "& BO…" on the flyer boats? Does he power wash boats?
- Does he winterize for banks and realtors (a separate pitch line)? Does he key-hold for vacant homes?
- Hours, and how fast he usually gets back to people?

## Ideas not built (yours to pick)
- **Runner-up world: the garage cleanout.** A cluttered garage floor where you push boxes out the door with a finger, and they tumble out onto a swept, empty floor. It's closer to the business name but less seasonal.
- **Drops as lenses:** each drop would show a tiny upside-down street pulled from the scene canvas. Recommended by the overdrive pass; more realism, small cost.
- **"Wipe me" written into the frost** with a fingertip, in place of the HTML hint.
- **A send button that rides the bottom of the screen** only while the picker is in view, after the first tick, then docks under the list (the Sunny Side exception). Left out because there's no sticky anything by default; it helps on phones, where the send button is about one screen below the first rows.
- **A window-frame cue:** dark side rails with shading on the panes (no highlight line).
- **Font to try:** none needed; the house stack is kept.
- **A dedicated "Vacant & foreclosed homes" page** aimed at realtors and banks (cleanout + re-key + winterize as one package).

## Not verified
- Real-device touch on iPhone and Android, inside Facebook's in-app browser.
- Real SMS handoff with the pre-filled body (iOS Messages and Android).
- Frame rate on older phones. Headless WebKit holds 60fps at 390 and 1440. Headless Chromium has no GPU and runs about 38ms/frame at 1440, which a GPU machine shouldn't hit, but low-end laptops without acceleration might.
- `ctx.filter` blur on Safari before 18: it falls back to plain bilinear smoothing; not checked on a real older device.
- Whether the Facebook group post opens for people who aren't logged in.
