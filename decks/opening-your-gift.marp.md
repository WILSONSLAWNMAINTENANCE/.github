---
marp: true
theme: default
paginate: true
size: 16:9
title: Opening your gift · Wilson's Lawn Maintenance
description: For Jeff, from his brother. What Wilson's Lawn Maintenance has been given on GitHub, what to expect, and what it could become. It asks for nothing.
style: |
  /* Tone: the organisation's four shades from my-template/proposals-template/TONES.md (bare hex, no #). The ground is
     the walkthrough deck's slate for every family; the family shows in the left rule, the stops, the headings' rule and
     the colour strip. Headings and links mix the primary with white, so purple, blue and amber all read on slate.
     Do not hand-edit colours below; change the four placeholders. Icons are inline Lucide SVG (ISC), drawn in the
     text's own colour. */
  section { background: #0f172a; color: #e2e8f0; font-family: "Helvetica Neue", Helvetica, Arial, sans-serif; font-size: 25px; padding: 52px 64px 56px; border-left: 10px solid #65a30d; }
  section::after { color: #94a3b8; font-size: 0.6em; }
  section h1 { color: color-mix(in srgb, #65a30d 55%, white) !important; border-bottom: 2px solid #4d7c0f; padding-bottom: 8px; font-size: 1.45em; margin-bottom: 0.45em; }
  section h2 { color: #ecfccb !important; font-size: 1.1em; margin: 0.2em 0 0.4em; }
  strong { color: color-mix(in srgb, #ecfccb 70%, white); }
  em { color: #cbd5e1; }
  a { color: color-mix(in srgb, #65a30d 40%, white); text-decoration: underline; text-decoration-color: #4d7c0f; }
  code { background: #334155; color: color-mix(in srgb, #ecfccb 80%, white); padding: 1px 6px; border-radius: 4px; font-size: 0.82em; }
  pre { background: #1e293b; color: color-mix(in srgb, #ecfccb 80%, white); border: 1px solid #334155; border-radius: 8px; padding: 12px 16px; font-size: 0.68em; line-height: 1.35; }
  pre code { background: transparent; color: inherit; padding: 0; font-size: 1em; }
  table { border-collapse: collapse; width: 100%; font-size: 0.72em; }
  section table th { background: #334155; color: color-mix(in srgb, #65a30d 45%, white); padding: 6px 10px; text-align: left; border: 1px solid #475569; }
  section table td { background: #1e293b; color: #e2e8f0; padding: 5px 10px; border: 1px solid #334155; }
  blockquote { border-left: 4px solid #65a30d; background: #1e293b; color: #e2e8f0; padding: 8px 16px; margin: 0.6em 0; font-style: normal; }
  ul, ol { margin-top: 0.2em; }
  li { margin: 0.18em 0; }
  .small { font-size: 0.66em; color: #94a3b8; }
  .stop { display: inline-block; min-width: 1.6em; height: 1.6em; line-height: 1.6em; border-radius: 50%; text-align: center; background: color-mix(in srgb, #65a30d 60%, white); color: #0f172a; font-weight: 700; font-size: 0.8em; margin-right: 0.35em; }
  svg.i { width: 1em; height: 1em; vertical-align: -0.15em; margin-right: 0.3em; color: color-mix(in srgb, #65a30d 55%, white); }
  h1 svg.i, h2 svg.i { margin-right: 0.35em; }
  .rail { display: flex; height: 14px; margin: 18px 0 0; border-radius: 3px; overflow: hidden; }
  .rail span { flex: 1; }
  .s1 { background: #365314 } .s2 { background: #4d7c0f } .s3 { background: #65a30d } .s4 { background: #ecfccb }
  section.lead { border-left: none; background: linear-gradient(135deg, color-mix(in srgb, #365314 55%, #1e293b) 0%, #0f172a 70%); justify-content: center; }
  section.lead h1 { border: none; font-size: 2.3em; color: #f8fafc !important; margin-bottom: 0.1em; }
  section.lead h2 { color: #ecfccb !important; font-size: 1.15em; font-weight: 400; }
  section.lead .kicker { color: color-mix(in srgb, #65a30d 60%, white); letter-spacing: 0.25em; font-size: 0.6em; font-weight: 700; }
---

<!--
  Opening your gift, on slides: the page .github/OPENING-YOUR-GIFT.md in the shape of the fleet's welcome deck
  (my-template/decks-template), in the lawn-lime family. For Jeff, from his brother. Public
  (WILSONSLAWNMAINTENANCE/.github/decks); nothing here asks anything of anyone. Render: decks-template/README.md.
-->

<!-- _class: lead -->
<!-- _paginate: false -->

<span class="kicker">A BROTHER'S GIFT · WILSON'S LAWN MAINTENANCE</span>

# Opening your gift

## For Jeff: what this GitHub thing is, in plain words, and what it could become

<span class="small">Five minutes. It asks you for nothing. The same words, as a page you can read any time: OPENING-YOUR-GIFT.md in the business's home on GitHub.</span>

<div class="rail"><span class="s1"></span><span class="s2"></span><span class="s3"></span><span class="s4"></span></div>

---

# <svg class="i" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true"><path d="m16.24 7.76-1.804 5.411a2 2 0 0 1-1.265 1.265L7.76 16.24l1.804-5.411a2 2 0 0 1 1.265-1.265z" /> <circle cx="12" cy="12" r="10" /></svg> If you read one slide, read this one

- <svg class="i" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true"><rect x="3" y="8" width="18" height="4" rx="1" /> <path d="M12 8v13" /> <path d="M19 12v7a2 2 0 0 1-2 2H7a2 2 0 0 1-2-2v-7" /> <path d="M7.5 8a2.5 2.5 0 0 1 0-5A4.8 8 0 0 1 12 8a4.8 8 0 0 1 4.5-5 2.5 2.5 0 0 1 0 5" /></svg> **The business has been given a home on the internet, in its own name,** with its logo and its photos already in it. That place is called GitHub.
- <svg class="i" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true"><path d="M19 14c1.49-1.46 3-3.21 3-5.5A5.5 5.5 0 0 0 16.5 3c-1.76 0-3 .5-4.5 2-1.5-1.5-2.74-2-4.5-2A5.5 5.5 0 0 0 2 8.5c0 2.3 1.5 4.05 3 5.5l7 7Z" /></svg> **You owe nothing and you don't have to learn anything.** The phone, the Facebook page and the truck go on exactly as today. If this sits untouched for a year, it waits.
- <svg class="i" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true"><path d="M16 21v-2a4 4 0 0 0-4-4H6a4 4 0 0 0-4 4v2" /> <circle cx="9" cy="7" r="4" /> <line x1="19" x2="19" y1="8" y2="14" /> <line x1="22" x2="16" y1="11" y2="11" /></svg> **Your first ten minutes:** make an account, type your own password, send your username to Christopher. Then back to work.
- <svg class="i" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true"><rect width="18" height="11" x="3" y="11" rx="2" ry="2" /> <path d="M7 11V7a5 5 0 0 1 10 0v4" /></svg> **Your password is only yours.** Nobody who is really helping you will ever ask for it, or for a code sent to your phone. Not your brother, not any helper.
- <svg class="i" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true"><path d="M7 20h10" /> <path d="M10 20c5.5-2.5.8-6.4 3-10" /> <path d="M9.5 9.4c1.1.8 1.8 2.2 2.3 3.7-2 .4-3.5.4-4.8-.3-1.2-.6-2.3-1.9-3-4.2 2.8-.5 4.4 0 5.5.8z" /> <path d="M14.1 6a7 7 0 0 0-1.1 4c1.9-.1 3.3-.6 4.3-1.4 1-1 1.6-2.3 1.7-4.6-2.7.1-4 1-4.9 2z" /></svg> **It can grow, if you want it to.** Including the word you've been curious about. Optional, like everything here.

<div class="rail"><span class="s1"></span><span class="s2"></span><span class="s3"></span><span class="s4"></span></div>

---

# <svg class="i" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true"><path d="M12 7v14" /> <path d="M3 18a1 1 0 0 1-1-1V4a1 1 0 0 1 1-1h5a4 4 0 0 1 4 4 4 4 0 0 1 4-4h5a1 1 0 0 1 1 1v13a1 1 0 0 1-1 1h-6a3 3 0 0 0-3 3 3 3 0 0 0-3-3z" /></svg> What GitHub is, in plain words

> Think of the folder for a big landscaping job: the estimate, the sketch of the beds, the mulch order, the day it was done, the photo at the end. Now picture that folder keeping every earlier version, never getting lost, and nobody ever writing over the estimate by accident. **GitHub is that folder, on the internet.**

| | On a job | On GitHub | Means |
|---|---|---|---|
| <svg class="i" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true"><rect width="8" height="5" x="14" y="17" rx="1" /> <path d="M10 20H4a2 2 0 0 1-2-2V5a2 2 0 0 1 2-2h3.9a2 2 0 0 1 1.69.9l.81 1.2a2 2 0 0 0 1.67.9H20a2 2 0 0 1 2 2v2.5" /> <path d="M20 17v-2a2 2 0 1 0-4 0v2" /></svg> | The job folder | **repository** | one project, every version kept |
| <svg class="i" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true"><circle cx="18" cy="18" r="3" /> <circle cx="6" cy="6" r="3" /> <path d="M13 6h3a2 2 0 0 1 2 2v7" /> <line x1="6" x2="6" y1="9" y2="21" /></svg> | An estimate sent for the customer's OK | **pull request** | a change, waiting for someone to say yes |
| <svg class="i" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true"><circle cx="18" cy="18" r="3" /> <circle cx="6" cy="6" r="3" /> <path d="M6 21V9a9 9 0 0 0 9 9" /></svg> | The customer signing it | **merge** | the yes; nothing goes on the ground before this |
| <svg class="i" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true"><line x1="6" x2="6" y1="3" y2="15" /> <circle cx="18" cy="6" r="3" /> <circle cx="6" cy="18" r="3" /> <path d="M18 9a9 9 0 0 1-9 9" /></svg> | A sketch of a new bed, beside the yard as it is | **branch** | try it without touching the real one |
| <svg class="i" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true"><path d="M21 15a2 2 0 0 1-2 2H7l-4 4V5a2 2 0 0 1 2-2h14a2 2 0 0 1 2 2z" /></svg> | A note on the job ticket | **issue** | a question or a thought, kept with the job |

<span class="small">You don't need to know how to program to own one, or to read what's in it.</span>

---

# <svg class="i" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true"><rect x="3" y="8" width="18" height="4" rx="1" /> <path d="M12 8v13" /> <path d="M19 12v7a2 2 0 0 1-2 2H7a2 2 0 0 1-2-2v-7" /> <path d="M7.5 8a2.5 2.5 0 0 1 0-5A4.8 8 0 0 1 12 8a4.8 8 0 0 1 4.5-5 2.5 2.5 0 0 1 0 5" /></svg> What you have been given

| | What | In plain words |
|---|---|---|
| <svg class="i" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true"><path d="M6 22V4a2 2 0 0 1 2-2h8a2 2 0 0 1 2 2v18Z" /> <path d="M6 12H4a2 2 0 0 0-2 2v6a2 2 0 0 0 2 2h2" /> <path d="M18 9h2a2 2 0 0 1 2 2v9a2 2 0 0 1-2 2h-2" /> <path d="M10 6h4" /> <path d="M10 10h4" /> <path d="M10 14h4" /> <path d="M10 18h4" /></svg> | **WILSONSLAWNMAINTENANCE**, the business's home on GitHub | the building, with your name on the door and you as an owner |
| <svg class="i" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true"><path d="M9.937 15.5A2 2 0 0 0 8.5 14.063l-6.135-1.582a.5.5 0 0 1 0-.962L8.5 9.936A2 2 0 0 0 9.937 8.5l1.582-6.135a.5.5 0 0 1 .963 0L14.063 8.5A2 2 0 0 0 15.5 9.937l6.135 1.581a.5.5 0 0 1 0 .964L15.5 14.063a2 2 0 0 0-1.437 1.437l-1.582 6.135a.5.5 0 0 1-.963 0z" /> <path d="M20 3v4" /> <path d="M22 5h-4" /> <path d="M4 17v2" /> <path d="M5 18H3" /></svg> | **brand-assets** | your logo and the photos from your Facebook page, in one place, with a page saying who may use them |
| <svg class="i" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true"><path d="M13 4h3a2 2 0 0 1 2 2v14" /> <path d="M2 20h3" /> <path d="M13 20h9" /> <path d="M10 12v.01" /> <path d="M13 4.562v16.157a1 1 0 0 1-1.242.97L5 20V5.562a2 2 0 0 1 1.515-1.94l4-1A2 2 0 0 1 13 4.561Z" /></svg> | **the reading room** | the back office: everything written for the business, each page with a PDF beside it |
| <svg class="i" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true"><circle cx="12" cy="12" r="10" /> <path d="M12 2a14.5 14.5 0 0 0 0 20 14.5 14.5 0 0 0 0-20" /> <path d="M2 12h20" /></svg> | **the public reading room** | the front window: only what's been listed for visitors |
| <svg class="i" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true"><path d="M15 12h-5" /> <path d="M15 8h-5" /> <path d="M19 17V5a2 2 0 0 0-2-2H4" /> <path d="M8 21h12a2 2 0 0 0 2-2v-1a1 1 0 0 0-1-1H11a1 1 0 0 0-1 1v1a2 2 0 1 1-4 0V5a2 2 0 1 0-4 0v2a1 1 0 0 0 1 1h3" /></svg> | **procedures** | how each thing is done, step by step, like a checklist on the dash |
| <svg class="i" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true"><path d="M7 20h10" /> <path d="M10 20c5.5-2.5.8-6.4 3-10" /> <path d="M9.5 9.4c1.1.8 1.8 2.2 2.3 3.7-2 .4-3.5.4-4.8-.3-1.2-.6-2.3-1.9-3-4.2 2.8-.5 4.4 0 5.5.8z" /> <path d="M14.1 6a7 7 0 0 0-1.1 4c1.9-.1 3.3-.6 4.3-1.4 1-1 1.6-2.3 1.7-4.6-2.7.1-4 1-4.9 2z" /></svg> | **proposals** | ideas offered, never asked. "Not now" is a complete answer, and so is silence |
| <svg class="i" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true"><line x1="3" x2="21" y1="22" y2="22" /> <line x1="6" x2="6" y1="18" y2="11" /> <line x1="10" x2="10" y1="18" y2="11" /> <line x1="14" x2="14" y1="18" y2="11" /> <line x1="18" x2="18" y1="18" y2="11" /> <polygon points="12 2 20 7 4 7" /></svg> | **a legal folder** | a private place for paperwork, if ever wanted: empty today, and nothing in it is advice |
| <svg class="i" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true"><path d="M2.586 17.414A2 2 0 0 0 2 18.828V21a1 1 0 0 0 1 1h3a1 1 0 0 0 1-1v-1a1 1 0 0 1 1-1h1a1 1 0 0 0 1-1v-1a1 1 0 0 1 1-1h.172a2 2 0 0 0 1.414-.586l.814-.814a6.5 6.5 0 1 0-4-4z" /> <circle cx="16.5" cy="7.5" r=".5" fill="currentColor" /></svg> | **a second owner** | a spare key held by Christopher, so the place never depends on one person, you included |

---

# <svg class="i" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true"><path d="m16.24 7.76-1.804 5.411a2 2 0 0 1-1.265 1.265L7.76 16.24l1.804-5.411a2 2 0 0 1 1.265-1.265z" /> <circle cx="12" cy="12" r="10" /></svg> What to expect

**What will happen**
- <svg class="i" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true"><rect width="20" height="16" x="2" y="4" rx="2" /> <path d="m22 7-8.97 5.7a1.94 1.94 0 0 1-2.06 0L2 7" /></svg> Once you send your username, an email from GitHub inviting you to join. It waits for you.
- <svg class="i" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true"><path d="M12 8V4H8" /> <rect width="16" height="12" x="4" y="8" rx="2" /> <path d="M2 14h2" /> <path d="M20 14h2" /> <path d="M15 13v2" /> <path d="M9 13v2" /></svg> AI helpers named in the history, like Alfred and Littlebird. They do the typing; a person says yes to what they prepare.

**What won't happen**
- <svg class="i" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true"><path d="M19 14c1.49-1.46 3-3.21 3-5.5A5.5 5.5 0 0 0 16.5 3c-1.76 0-3 .5-4.5 2-1.5-1.5-2.74-2-4.5-2A5.5 5.5 0 0 0 2 8.5c0 2.3 1.5 4.05 3 5.5l7 7Z" /></svg> No bill. GitHub's free plan is all this needs.
- <svg class="i" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true"><path d="M20 13c0 5-3.5 7.5-7.66 8.95a1 1 0 0 1-.67-.01C7.5 20.5 4 18 4 13V6a1 1 0 0 1 1-1c2 0 4.5-1.2 6.24-2.72a1.17 1.17 0 0 1 1.52 0C14.51 3.81 17 5 19 5a1 1 0 0 1 1 1z" /> <path d="m9 12 2 2 4-4" /></svg> Nothing leaves the back office by being written there. A page reaches the front window only after it's listed and a check has read it.
- <svg class="i" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true"><rect width="18" height="11" x="3" y="11" rx="2" ry="2" /> <path d="M7 11V7a5 5 0 0 1 10 0v4" /></svg> Nobody asks for your password, a sign-in code, or your bank login. Not Christopher, not any helper.
- <svg class="i" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true"><path d="M16 21v-2a4 4 0 0 0-4-4H6a4 4 0 0 0-4 4v2" /> <circle cx="9" cy="7" r="4" /> <path d="M22 21v-2a4 4 0 0 0-3-3.87" /> <path d="M16 3.13a4 4 0 0 1 0 7.75" /></svg> Nothing about customers. No names, no addresses, no prices go in here, by rule.

> Wanting anything changed is still **one message to Christopher.** You never need GitHub for that.

---

# <svg class="i" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true"><path d="M16 21v-2a4 4 0 0 0-4-4H6a4 4 0 0 0-4 4v2" /> <circle cx="9" cy="7" r="4" /> <line x1="19" x2="19" y1="8" y2="14" /> <line x1="22" x2="16" y1="11" y2="11" /></svg> Your first ten minutes

| | Step | You should see |
|---|---|---|
| <svg class="i" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true"><rect width="20" height="16" x="2" y="4" rx="2" /> <path d="m22 7-8.97 5.7a1.94 1.94 0 0 1-2.06 0L2 7" /></svg> | Go to `github.com/signup` and enter **your own** email address | a page asking for a password |
| <svg class="i" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true"><rect width="18" height="11" x="3" y="11" rx="2" ry="2" /> <path d="M7 11V7a5 5 0 0 1 10 0v4" /></svg> | **Type a password of your own.** Nobody else types it, sees it or keeps it | a box asking for a username |
| <svg class="i" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true"><path d="M12 10a2 2 0 0 0-2 2c0 1.02-.1 2.51-.26 4" /> <path d="M14 13.12c0 2.38 0 6.38-1 8.88" /> <path d="M17.29 21.02c.12-.6.43-2.3.5-3.02" /> <path d="M2 12a10 10 0 0 1 18-6" /> <path d="M2 16h.01" /> <path d="M21.8 16c.2-2 .131-5.354 0-6" /> <path d="M5 19.5C5.5 18 6 15 6 12a6 6 0 0 1 .34-2" /> <path d="M8.65 22c.21-.66.45-1.32.57-2" /> <path d="M9 6.8a6 6 0 0 1 9 5.2v2" /></svg> | Choose a username: it's public and it lasts, so one you'd be happy to see on the side of the truck | a puzzle, or a code sent to your email |
| <svg class="i" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true"><path d="M20 13c0 5-3.5 7.5-7.66 8.95a1 1 0 0 1-.67-.01C7.5 20.5 4 18 4 13V6a1 1 0 0 1 1-1c2 0 4.5-1.2 6.24-2.72a1.17 1.17 0 0 1 1.52 0C14.51 3.81 17 5 19 5a1 1 0 0 1 1 1z" /> <path d="m9 12 2 2 4-4" /></svg> | Enter the code and choose the **Free** plan | a nearly empty page with a little patterned picture top right |
| <svg class="i" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true"><path d="M19 14c1.49-1.46 3-3.21 3-5.5A5.5 5.5 0 0 0 16.5 3c-1.76 0-3 .5-4.5 2-1.5-1.5-2.74-2-4.5-2A5.5 5.5 0 0 0 2 8.5c0 2.3 1.5 4.05 3 5.5l7 7Z" /></svg> | Send **only your username** to Christopher, wherever you already talk | nothing more today |

<span class="small">That's all for today. When you have an hour, **SOP-COM-001 "New to GitHub: your first hour"** goes on from here, one step at a time: two-factor sign-in, accepting the invitation, five words, reading your room in a browser. Nothing in it asks you to type a command.</span>

---

# <svg class="i" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true"><path d="M21 15a2 2 0 0 1-2 2H7l-4 4V5a2 2 0 0 1 2-2h14a2 2 0 0 1 2 2z" /></svg> What you might be wondering

| | Question | Answer |
|---|---|---|
| <svg class="i" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true"><path d="M14.7 6.3a1 1 0 0 0 0 1.4l1.6 1.6a1 1 0 0 0 1.4 0l3.77-3.77a6 6 0 0 1-7.94 7.94l-6.91 6.91a2.12 2.12 0 0 1-3-3l6.91-6.91a6 6 0 0 1 7.94-7.94l-3.76 3.76z" /></svg> | Can I break it? | Reading can't break anything. A change waits for a sign-off, like an estimate, and a signed-off change can be taken back, which is more than you can say for mulch. |
| <svg class="i" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true"><path d="M2.586 17.414A2 2 0 0 0 2 18.828V21a1 1 0 0 0 1 1h3a1 1 0 0 0 1-1v-1a1 1 0 0 1 1-1h1a1 1 0 0 0 1-1v-1a1 1 0 0 1 1-1h.172a2 2 0 0 0 1.414-.586l.814-.814a6.5 6.5 0 1 0-4-4z" /> <circle cx="16.5" cy="7.5" r=".5" fill="currentColor" /></svg> | Is it really mine? | You're an owner: you see everything and decide who else can. The second owner is a spare key, not a landlord. |
| <svg class="i" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true"><path d="M12 7v14" /> <path d="M3 18a1 1 0 0 1-1-1V4a1 1 0 0 1 1-1h5a4 4 0 0 1 4 4 4 4 0 0 1 4-4h5a1 1 0 0 1 1 1v13a1 1 0 0 1-1 1h-6a3 3 0 0 0-3 3 3 3 0 0 0-3-3z" /></svg> | Do I need to learn to code? | No. Most of it is pages you read. |
| <svg class="i" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true"><path d="M3 12a9 9 0 1 0 9-9 9.75 9.75 0 0 0-6.74 2.74L3 8" /> <path d="M3 3v5h5" /> <path d="M12 7v5l4 2" /></svg> | What if it's the busy season and I ignore it? | It waits. Nothing expires because you were out mowing. |
| <svg class="i" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true"><path d="M16 21v-2a4 4 0 0 0-4-4H6a4 4 0 0 0-4 4v2" /> <circle cx="9" cy="7" r="4" /> <path d="M22 21v-2a4 4 0 0 0-3-3.87" /> <path d="M16 3.13a4 4 0 0 1 0 7.75" /></svg> | What if the people who set this up move on? | That's why there are two owners. Everything is ordinary files you can download, and anyone you hire can read them. |
| <svg class="i" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true"><path d="M20 13c0 5-3.5 7.5-7.66 8.95a1 1 0 0 1-.67-.01C7.5 20.5 4 18 4 13V6a1 1 0 0 1 1-1c2 0 4.5-1.2 6.24-2.72a1.17 1.17 0 0 1 1.52 0C14.51 3.81 17 5 19 5a1 1 0 0 1 1 1z" /> <path d="m9 12 2 2 4-4" /></svg> | Someone is asking for my password or a code. | The answer is no, whoever they say they are. Tell Christopher. |

---

# <svg class="i" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true"><path d="M7 20h10" /> <path d="M10 20c5.5-2.5.8-6.4 3-10" /> <path d="M9.5 9.4c1.1.8 1.8 2.2 2.3 3.7-2 .4-3.5.4-4.8-.3-1.2-.6-2.3-1.9-3-4.2 2.8-.5 4.4 0 5.5.8z" /> <path d="M14.1 6a7 7 0 0 0-1.1 4c1.9-.1 3.3-.6 4.3-1.4 1-1 1.6-2.3 1.7-4.6-2.7.1-4 1-4.9 2z" /></svg> What it could become

> **A picture of what's possible, not a plan and not advice.** Nothing here is built, nothing is needed, some of it may never arrive. Not financial, tax or legal advice; nothing here says what to buy, hold or sell. Ask a professional before anything involving money or ownership.

You've mentioned being curious about crypto. Set aside the coins and the noise: the idea under **web3** is that some records can live on a shared public ledger instead of inside one company's database, so nobody has to take one company's word for who owns what.

| | What you have today | Practice for | Could grow into, if you ever want it |
|---|---|---|---|
| <svg class="i" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true"><path d="M3 12a9 9 0 1 0 9-9 9.75 9.75 0 0 0-6.74 2.74L3 8" /> <path d="M3 3v5h5" /> <path d="M12 7v5l4 2" /></svg> | Every change on record, and who made it | records you don't take on trust | a finished job with a record a later buyer of the property can check |
| <svg class="i" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true"><path d="M12 10a2 2 0 0 0-2 2c0 1.02-.1 2.51-.26 4" /> <path d="M14 13.12c0 2.38 0 6.38-1 8.88" /> <path d="M17.29 21.02c.12-.6.43-2.3.5-3.02" /> <path d="M2 12a10 10 0 0 1 18-6" /> <path d="M2 16h.01" /> <path d="M21.8 16c.2-2 .131-5.354 0-6" /> <path d="M5 19.5C5.5 18 6 15 6 12a6 6 0 0 1 .34-2" /> <path d="M8.65 22c.21-.66.45-1.32.57-2" /> <path d="M9 6.8a6 6 0 0 1 9 5.2v2" /></svg> | Your own sign-in, that only you hold | holding your own keys | a wallet for the business: a key only you hold |
| <svg class="i" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true"><path d="M16 21v-2a4 4 0 0 0-4-4H6a4 4 0 0 0-4 4v2" /> <circle cx="9" cy="7" r="4" /> <path d="M22 21v-2a4 4 0 0 0-3-3.87" /> <path d="M16 3.13a4 4 0 0 1 0 7.75" /></svg> | Two owners, no single point of failure | shared control | two signatures before anything moves |

<span class="small">Curious about the words? The reading room has a page for that, **The words of web3** (wallet, seed phrase, hot and cold, what never to type into a website), and beside it **Before you connect a wallet**. They explain; they don't advise.</span>

---

# <svg class="i" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true"><path d="m16.24 7.76-1.804 5.411a2 2 0 0 1-1.265 1.265L7.76 16.24l1.804-5.411a2 2 0 0 1 1.265-1.265z" /> <circle cx="12" cy="12" r="10" /></svg> Where to start

| | You are… | Open |
|---|---|
| <svg class="i" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true"><rect x="3" y="8" width="18" height="4" rx="1" /> <path d="M12 8v13" /> <path d="M19 12v7a2 2 0 0 1-2 2H7a2 2 0 0 1-2-2v-7" /> <path d="M7.5 8a2.5 2.5 0 0 1 0-5A4.8 8 0 0 1 12 8a4.8 8 0 0 1 4.5-5 2.5 2.5 0 0 1 0 5" /></svg> | Jeff, today | this deck's page: **OPENING-YOUR-GIFT.md** at [https://github.com/WILSONSLAWNMAINTENANCE/.github](https://github.com/WILSONSLAWNMAINTENANCE/.github) |
| <svg class="i" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true"><path d="M16 21v-2a4 4 0 0 0-4-4H6a4 4 0 0 0-4 4v2" /> <circle cx="9" cy="7" r="4" /> <line x1="19" x2="19" y1="8" y2="14" /> <line x1="22" x2="16" y1="11" y2="11" /></svg> | ready for the first hour | **SOP-COM-001** in [https://github.com/WILSONSLAWNMAINTENANCE/ops-standard-operating-procedures-public](https://github.com/WILSONSLAWNMAINTENANCE/ops-standard-operating-procedures-public) |
| <svg class="i" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true"><path d="M13 4h3a2 2 0 0 1 2 2v14" /> <path d="M2 20h3" /> <path d="M13 20h9" /> <path d="M10 12v.01" /> <path d="M13 4.562v16.157a1 1 0 0 1-1.242.97L5 20V5.562a2 2 0 0 1 1.515-1.94l4-1A2 2 0 0 1 13 4.561Z" /></svg> | signed in, with a seat | the reading room: [https://github.com/WILSONSLAWNMAINTENANCE/reading-room](https://github.com/WILSONSLAWNMAINTENANCE/reading-room) |
| <svg class="i" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true"><path d="M12 8V4H8" /> <rect width="16" height="12" x="4" y="8" rx="2" /> <path d="M2 14h2" /> <path d="M20 14h2" /> <path d="M15 13v2" /> <path d="M9 13v2" /></svg> | an AI helper | the repository's `README.md`, then **SOP-OPS-002** (helpers open pull requests; people merge) |
| <svg class="i" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true"><path d="M19 14c1.49-1.46 3-3.21 3-5.5A5.5 5.5 0 0 0 16.5 3c-1.76 0-3 .5-4.5 2-1.5-1.5-2.74-2-4.5-2A5.5 5.5 0 0 0 2 8.5c0 2.3 1.5 4.05 3 5.5l7 7Z" /></svg> | stuck anywhere | Christopher |

> **What stays true however far this goes:** you decide, you keep your own keys, and "not now" is always a complete answer.

<div class="rail"><span class="s1"></span><span class="s2"></span><span class="s3"></span><span class="s4"></span></div>
