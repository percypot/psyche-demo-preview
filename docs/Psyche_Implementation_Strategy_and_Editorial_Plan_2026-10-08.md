# Psyche Clinical Psychology: Editorial Plan and Implementation Strategy

**For:** Percy only. Not for the client. No bid placed, nothing sent.

**Date:** 8 October 2026 (bidding on Freelancer project 40745684 closes about 9 October).

**Reference point:** the live demo at https://apps-cheap-initially-standard.trycloudflare.com/, which is the same file as the saved `Psyche_Clinical_Psychology_Static_Demo_2026-10-03.html`. This document does not change that file.

**Rules for both parts.** Do not invent anything about the client. Where her material is needed, use a marked slot such as [Client copy: clinician bio] or [Not supplied: session fee]. Any headings, button labels and form labels written by us are marked *proposed*. No public booking calendar. No practice software is built. Her booking system is not named in the brief, so we do not name one.

---

## Part 1. Editorial plan: what needs to change

### 1.1 The three gaps

| Gap | Live demo now | Change to |
|---|---|---|
| **Colours** | Black page, black top bar, white text, cream #e7dcc8 accents, dark #141210 content box | Deep navy, gold and light neutrals. Light or white content box on a light background, dark navy text. Exact hex values come from her brand files. Provisional demo values: navy #1F2A44, gold #B08D57, light neutral #F7F4EE (labelled provisional) |
| **Platform** | One static HTML file (about 1.6 MB, photos embedded, no script) | An editable mainstream CMS such as WordPress or Webflow. The static demo stays as the design preview only |
| **Forms** | One disabled form on Contact, with a dropdown for Individual therapy or REGULATE | Three enquiry forms: Individual Therapy, REGULATE and general. Spam protection noted. Disabled in the demo |

### 1.2 What stays

- Sticky top bar. Only the bar sticks on scroll, nothing else.
- Faded Adelaide landmark photo behind each page, with a content box on top and credits on the page. The box turns light.
- Six pages: Home, About, Individual Therapy, REGULATE, Fees & FAQs, Contact.
- Enquiry instead of a public calendar.
- Crisis line in ordinary readable type: "This is not a crisis service. If you are in danger, call 000. Lifeline is 13 11 14." (proposed wording)
- Demo marking ("Static demo. Not a live practice site.") and the "not supplied" marking.
- No invented details, no people in photos, no testimonials.

### 1.3 Other changes, measured against the demo

| Area | Live demo now | Change to | Why |
|---|---|---|---|
| Navigation | Home, About, Work, Fees, Contact. Individual and REGULATE are reached from "Work" | Home, About, Therapy (small dropdown: Individual Therapy, REGULATE), Fees & FAQs, Contact, plus one Enquire button. Alternative: six flat items. **Percy decides** | Brief names the pages; "Work" is not a term she uses |
| Page structure | Every page is a closed open-and-close section, and Home has five more inside it | Pages show open. Keep open-and-close only for FAQs | Too many expandables hide the content |
| First screen | Three questions: how to book, mission, how to contact. Practice name and "Adelaide" in the faded centre | Practice name (her logo slot), one short line [Client copy: home intro], one Enquire button, crisis line | Matches how local practice sites open; tasteful call to action |
| Extra blocks | Unnamed intro block, "Implementation" and "Editorial" notes visible on the page | Remove from the visitor view. Keep the notes in this plan | They are working notes, not site content |
| Body copy | Percy's own limits-first sentences (not her copy) | Replace with marked slots for her copy. Option: keep a few lines as visible placeholders, marked "Placeholder, not client copy". **Percy decides** | She already has most of her copy |
| Fees | Table inside an expandable, all amounts "Not supplied" | Own page, table visible, slots: [Not supplied: session fee], [Not supplied: REGULATE fee], [Not supplied: cancellation policy], [Not supplied: rebate details]. FAQs below as expandables | Brief asks for Fees & FAQs as one page |
| Photos | Seven Creative Commons Adelaide landmarks | Keep for the demo, labelled demo-only. Live site uses [Client photo: …] slots. **Percy decides** whether to keep them in the bid demo | She has her own photography |
| Type | 18px body, h1 32px, Newsreader and Source Sans 3 | Keep about 16–18px body; larger headings (h1 about 40px, h2 about 28px). Her brand fonts replace these if supplied | Larger heading contrast reads as more premium |
| SEO | One generic page title, no meta description, no alt text | Per-page title and meta description templates; alt text on every image (see 1.4) | Brief lists basic SEO as essential |

### 1.4 Page-by-page content

All headings and labels below are *proposed*. Everything in square brackets is her material or not supplied.

| Page | Sections in order | Call to action | SEO template (title / meta) |
|---|---|---|---|
| Home | Logo slot; [Client copy: home intro]; two short cards for Individual Therapy and REGULATE [Client copy: one-line summaries]; [Client copy: approach]; crisis line | "Make an enquiry" | "Psyche Clinical Psychology, Adelaide" / [Client copy: one-sentence practice description] |
| About | [Client copy: clinician bio]; [Client photo: clinician portrait, if she wants one]; [Client copy: approach to therapy]; [Client copy: registration details she wants shown] | "Make an enquiry" | "About · Psyche Clinical Psychology" / [Client copy] |
| Individual Therapy | [Client copy: what it is, who it suits, what to expect]; [Not supplied: session length]; Individual Therapy enquiry form | "Send an enquiry" | "Individual Therapy · Psyche Clinical Psychology, Adelaide" / [Client copy] |
| REGULATE | [Client copy: program overview, DBT as she describes it]; [Not supplied: format, length, group size, facilitator, dates, fee]; REGULATE enquiry form | "Ask about REGULATE" | "REGULATE DBT Group Program · Psyche Clinical Psychology" / [Client copy] |
| Fees & FAQs | Fee table with slots (1.3); [Client copy: FAQs] as expandables; "Is this a crisis service?" answered with 000 and Lifeline 13 11 14 | "Make an enquiry" | "Fees & FAQs · Psyche Clinical Psychology" / [Client copy] |
| Contact | [Not supplied: phone], [Not supplied: email], [Not supplied: address], [Not supplied: hours]; general enquiry form; crisis line set apart from normal contact | "Send" | "Contact · Psyche Clinical Psychology, Adelaide" / [Client copy] |

**Alt-text pattern.** Describe what is in the photo in plain words, no claims. Demo: "Faded photo of [landmark], Adelaide". Live site: [Client photo: description she approves].

**Form fields (proposed labels).** No clinical questions. Same base on all three forms:

- Name (required)
- Email (required)
- Phone (optional)
- Preferred contact method (email / phone, optional)
- Message, short and optional, with the hint: "A few lines is enough. Please don't include detailed health information."
- Consent checkbox: "I agree to the practice storing these details to reply to my enquiry. [Client copy: link to privacy policy]"
- Note above the button: "This form is not monitored for emergencies. Sending it does not book a session."

Differences: the REGULATE form adds "Which intake are you asking about?" only if she supplies dates [Not supplied: intake dates]. The general form adds a "Subject" field (General question / Referral / Other). The demo forms stay disabled.

### 1.5 Voice, and what to ask her for once awarded

**Voice:** warm, calm, clinically professional, plain. Short sentences. No clichés, no promises of outcomes, no stock photos of smiling people. It is her voice, so our text stays structural.

**Request list:** logo files (SVG and PNG); brand hex values and fonts; copy for each page; photos with permission to use; fees, cancellation and rebate wording; phone, email, address, hours; name of her booking or practice-management system; registration details she wants shown; privacy policy; who receives each form.

---

## Part 2. Implementation strategy: how and in what order

**Fleet rule for every step:** one writer edits the file, a tester checks it, then it is packed and saved. Nothing is deployed to production. The 3 October file is kept untouched; each rebuild is a new dated file.

### Phase 1. Visual rebuild of the demo (before the bid)

| Step | Work | Depends on |
|---|---|---|
| 1 | Colours: navy, gold and light neutral (provisional values); light content box and light page background; keep faded photo behind the box with a lighter veil | — |
| 2 | Sticky bar: navy bar, practice name left, nav with Therapy dropdown (or six flat), gold-outlined Enquire button. Only the bar sticks | 1 |
| 3 | Structure: pages open by default; only FAQs expandable; remove intro, Implementation and Editorial blocks from view | 2 |
| 4 | Content: swap body text for marked slots (per Percy's decision in 1.3); fee table with slots; crisis line on every page and in the footer | 3 |
| 5 | Forms: three disabled forms with the fields in 1.4 | 3 |
| 6 | Mobile check: bar collapses to a menu button, dropdown works by tap, text readable at 16px, contrast checked (navy on light and white on navy pass WCAG AA; gold used for lines and accents, not small body text) | 1–5 |
| 7 | Test, then pack and save as a new dated file | 6 |
| 8 | Refresh the public demo link to the new file | 7 |

### Phase 2. After it looks right (still demo only)

Only once Phase 1 passes testing:

1. SEO: page title and meta description per page from the templates; alt text on every image.
2. Spam protection: a visible note on each form (honeypot field plus a CAPTCHA service such as Cloudflare Turnstile or reCAPTCHA on the live site). Nothing active in the demo.
3. Booking-integration note: the live site can link to or embed her existing booking system once she names it. No public calendar. No software built.
4. CMS bridge note: one line in the demo footer: "Design preview only. The live site would be built in an editable CMS." Then test, pack, save, refresh link.

### Phase 3. Real build (only if she awards the job)

| Step | Work | Depends on |
|---|---|---|
| 1 | Collect her material (request list in 1.5) | Award |
| 2 | Confirm CMS. Percy's lean: **WordPress** (she can self-edit, mature form and spam plugins, many booking systems offer a WordPress embed, she owns hosting and files outright). Webflow is a fair alternative (clean visual editor, native forms with spam filtering) but adds an ongoing plan cost and is less portable. **Percy's decision** | 1 |
| 3 | Set up the theme or template (a lightweight block theme or a Webflow template), apply her brand values and fonts | 2 |
| 4 | Port the demo layout: sticky bar, faded photo behind content box, six pages | 3 |
| 5 | Build three forms (forms plugin or native forms) with honeypot plus CAPTCHA service; route to her email | 4 |
| 6 | Place her copy and photos; replace every slot; check none remain | 4, 1 |
| 7 | Booking link or embed path for her named system | 6 |
| 8 | SEO plugin or settings: titles, meta descriptions, alt text, sitemap | 6 |
| 9 | Performance: compressed images, minimal plugins, caching; mobile test | 6–8 |
| 10 | Handover: short update guide (edit a page, change a fee, swap a photo, read form entries); transfer domain, hosting and admin ownership to her | 9 |

**Before the bid closes (about one day):** Phase 1 is realistic. Phase 2 notes are a stretch goal. Phase 3 is described in the bid, not started.
