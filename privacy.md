---
title: Sightlore Privacy Policy
permalink: /privacy/
render_with_liquid: false
---

# Sightlore Privacy Policy

**Effective date: October 25, 2026**

Sightlore is an iOS travel app made by **ValCam LLC**. It gives you AI-narrated
commentary about landmarks you photograph during a tour. This policy explains,
in plain language, what information the app collects, how it is used, who
receives it, and the choices you have. ValCam LLC is the **controller** of your
personal information (the business responsible for it).

Questions or requests: **valcamllc@gmail.com** — ValCam LLC,
**502 W 7th St, Ste 100, Erie, PA 16502, USA**.

## The short version

- Sightlore is for adults: you must be 18 or older to use it.
- We collect what the app needs to work: the account details your sign-in
  provider (Apple or Google) shares with us, the name, home city and tour
  preferences you enter, the photos you tour with and where you took them, your
  tour history, your purchases, and crash reports.
- **Before your first tour, the app asks your permission** to send your tour
  photos, location and preferences to the AI providers that write and narrate
  your commentary (OpenAI and ElevenLabs). You can withdraw that permission at
  any time in Settings → Privacy & Data → AI Processing.
- Nearby-landmark discovery runs on your device using Apple Maps — that
  browsing never sends your location to our servers. (Opening a place's card
  asks our servers for a short Wikipedia summary of that place, using the
  place's name and map position — not yours.)
- **Location is optional.** You can start a tour anywhere, with or without
  choosing a place. With location on, each tour photo is sent with where it was
  taken so the AI can work out what it shows. Your iPhone keeps those
  coordinates with the Stop; our servers keep the place it was identified as
  and its neighborhood or city, not its coordinates. With location off, tours
  still work from the photo.
- **No ads. No third-party analytics. No tracking. We never sell or "share"
  your data for advertising, and neither we nor our AI providers train AI
  models on your photos or tours.**
- You can download your data, delete individual tours, or delete your whole
  account directly in the app.

## Information we collect

### Account information

You sign in with your **Apple or Google account** — there is no Sightlore
password, and we never receive your Apple or Google credentials. When you sign
in, your provider shares a stable account identifier, your **email address**
(with Sign in with Apple you can choose Apple's private relay address instead of
your real one), and — on first sign-in only — your **name**, which we use to
prefill your profile. These are managed for us by AWS Cognito (Amazon's
identity service), which also keeps an internal user ID for your account. Each
sign-in method is a separate Sightlore account: signing in with Apple and with
Google creates two different accounts, and we cannot merge them.

### Agreements, age confirmation and AI permission

When you sign in, you confirm that you are **18 or older** and agree to these
Terms and this Privacy Policy. We record **which version you agreed to and
when**, **when you confirmed your age**, and — from the "How Sightlore uses AI"
screen — **whether and when you allowed AI processing** (or withdrew it). These
records are stored with your profile so we can show you honored your choices and
can ask again when the documents change.

### Profile and Tour DNA

During onboarding you provide your **first name** (and, optionally, your **last
name**) and **home city**, and answer a few questions about how you like to
tour — interests, learning style, depth, tone and similar. Together with
preferences you can edit later on the Profile tab (such as pace and tour
length), this is your **Tour DNA**, plus your narration voice choice. Your
profile is stored on your device and synced to our servers so it follows you
across devices and so commentary can be personalized to it.

We no longer ask for an **age range**. Profiles created before October 2026
held one (often the pre-selected answer rather than one you chose); it was never
used for anything, and this version of the app deletes it from your profile, on
your device and on our servers, the next time your profile syncs. The one
exception is an "Under 18" answer: it tells us the account belongs to someone
under 18, so the app blocks the account and we delete it with all its data (see
"Children").

### Location

With your permission, the app uses your **precise location** while you are
using it, for these purposes:

1. **On-device discovery.** Finding Nearby Destinations, For You recommendations, Explore search, and suggesting your home city all use Apple's MapKit directly on your device. **This never sends your location to Sightlore's servers.** When you open a place's card, the app asks our servers for a short Wikipedia summary of that place, sending the place's name and map coordinates (not your own position).
2. **Tours.** You can start a tour anywhere without choosing a place, or start one at a place you pick in Explore or Nearby. When you photograph something on a tour and your iPhone has a usable location reading, the app sends **where the photo was taken** with it, so the AI can work out what you photographed and tell you about it: your iPhone's position when you took the photo (precise if Precise Location is on; with it off, only approximate, and named by city rather than neighborhood), how accurate and how recent that reading is, and the neighborhood, city, region and country your iPhone works out from it using Apple Maps. If you started the tour at a place you picked, that place's name and map position are sent too, and while you are close to it, its position may be sent in place of yours. Our servers use this location to look up Wikipedia articles about what is nearby, and send it to OpenAI with your photo (see "How Sightlore uses AI").
3. **Imported photos.** If you pick a photo from your library, the app reads the location and date saved in that photo (if any). For that photo, its own location — never your current position — is used the same way as a camera photo's location, and the month and year it was taken are sent too. A photo with no saved location is sent without one. A tour that starts with an imported photo is dated by it in your tour history.

On your iPhone, each Stop keeps where its photo was taken. Our servers keep the
place each Stop was identified as and its neighborhood or city, but **not the
coordinates of where you took the photo** — see "Tours and tour history" and
"Data stored only on your device".

Precise geolocation is **sensitive personal information**. We use it only to
provide the features above — never for advertising or to build a profile of
your movements. Location access is optional: without it, tours still work. The
app then doesn't send where you are, and commentary is based on the photo
itself (and on the place you picked, if you started the tour at one); an
imported photo's own saved location is still used, as described above. You can
switch location access off at any time in iOS Settings, and the app never
accesses your location in the background.

### Photos

Photos you take with the in-app camera during a tour, and photos you choose to
import with the iOS photo picker, are sent to our backend for AI analysis and
saved as part of your **tour history** so you can revisit past tours. The app
only receives the photos you pick — it has no general access to your photo
library — and it never saves anything to your library. Before upload, the app
re-encodes each photo, which removes the metadata embedded in the file (such as
GPS coordinates and camera details); only what is described under "Location" is
sent alongside it.

**Other people in your photos.** If people happen to appear in a photo, that
content is processed the same way as the rest of the image, only to describe
the landmark or object you photographed. **Sightlore does not perform facial
recognition, does not identify individuals, and does not extract face geometry,
voiceprints or any other biometric identifier.** You are responsible for having
any permission needed to photograph other people.

### Tours and tour history

For each tour we store its name. A tour you started at a place you picked is
named after that place, and we also store the place's map coordinates and Apple
Maps place identifier (when known); a tour started without choosing a place is
named after the neighborhood or city of its first Stop, or its date. For each
**Stop** we store: the photo (and a thumbnail), the AI-written commentary,
highlights, title and subject, the place it was identified as (its Apple Maps
name and identifier, when the app matches one or you pick one), the
neighborhood or city and country where it was taken (when known), the
"background reading" sources the commentary drew on, the follow-up questions
offered, and the answers to questions you chose to ask. **We don't store the
coordinates of where you took each photo** on our servers; they stay on your
iPhone (see "Data stored only on your device"). You can delete any tour, or
your whole account, in the app.

### Purchases and subscription

Purchases are made through Apple — **we never receive your payment card or
billing address.** When you subscribe or buy a Trip Pass, the app sends us the
**signed transaction record from Apple**, and Apple sends us **notifications**
when it renews, lapses, is refunded or changes. From these we keep the
**product** you bought, the **transaction identifiers**, **purchase and expiry
dates**, renewal and billing-retry status, and which Sightlore account the
purchase is linked to (and how often it has moved between accounts), so we can
tell whether your account is entitled to commentary and narration.

### Crash and performance diagnostics

If the app crashes or hangs, iOS (MetricKit) produces a diagnostic report —
technical details such as stack traces, the app and iOS version, and the device
model, with no photos, location or content. The app uploads these reports to
our servers, linked to your account, so we can find and fix bugs. They are
deleted automatically after **90 days**.

### Reports about AI content

If you use **Report this commentary**, we receive the reason you chose, the
comment you typed (if any), and a snapshot of the reported Stop's content
(commentary, highlights, title, subject, the answer you reported, and — where
known — which AI model and prompt version produced it) so we can review it. Please don't put
personal information in the comment.

### Support and communications

If you email us, we receive your email address and whatever you include, and
use it to respond and to keep a record of the request.

### Technical and security logs

Like most online services, our servers log requests: IP address, device and app
version (user agent), the time, and the address requested (which can include
tour or Stop IDs). We use these logs to operate and secure the Service and to
investigate abuse. We also keep short-lived usage counters per account to
enforce fair-use and daily limits.

### What we don't collect

No advertising identifiers, no third-party analytics or tracking SDKs, no
cross-app tracking, no contacts, no microphone or audio recordings, no general
photo-library access, no background location, no payment card details, no
biometric identifiers, and no selling or renting of personal information.

## Data stored only on your device

- **A local copy** of your profile and tour history, for offline use and speed, and of the tour in progress, so it can pick up again if iOS closes the app.
- **Where each photo was taken** — each Stop keeps the map coordinates of where its photo was taken (rounded to about 11 meters), how accurate the reading was, when it was taken, and whether it came from your iPhone or from the photo itself. These coordinates are not saved with your tours on our servers, so they stay on the iPhone you toured with and don't sync to your other devices; they are deleted along with the tour or your account.
- **Recently Deleted** — a tour you delete is removed from our servers and your other devices at once, but the device you deleted it on keeps a restorable copy for **30 days**, then removes it. Cleared when you sign out or delete your account.
- **Narration audio cache** — narration clips generated for you are kept in a size-limited cache on your device so replays (on the tour or from Tour History) don't generate them again; clips in it play even without a subscription. We never store narration audio on our servers. Cleared when you sign out or delete your account.
- **Saved places** — places you save for later stay on your device, kept separately for each account signed in on it; they are never sent to us, and they are erased when you delete your account.
- **Device preferences** — settings such as narration auto-play.

## How Sightlore uses AI

To create your commentary and narration, Sightlore sends data to two AI
providers — **only after you allow it** on the "How Sightlore uses AI" screen
(shown before your first tour). If you choose "Not now" or later withdraw your
permission in **Settings → Privacy & Data → AI Processing**, the app keeps
working for browsing, your history and your settings, but you can't start new
tours — or generate narration that isn't already on your device — until you
allow it again.

| Provider | What it does | What it receives |
|---|---|---|
| OpenAI | Identifies what you photographed and writes the commentary, highlights and follow-up answers | Your tour photo; where it was taken, when location is on (its map coordinates, how accurate and recent they are, and its neighborhood, city, region and country) — for an imported photo, the location saved in it (if any) and the month and year it was taken; the name and map position of any place you picked (to start the tour at, or to correct a Stop); your first name; your home city; your Tour DNA preferences; the names, short summaries and neighborhoods or cities of your earlier Stops on the tour; and, for a follow-up, that Stop's location details, the commentary you heard, earlier answers at that Stop and the question you chose |
| ElevenLabs | Turns the commentary and answers into spoken narration with the voice you chose | The text to be spoken (which may include your first name) and the voice ID |

- **No training.** Under their API terms, OpenAI and ElevenLabs do not use data sent through their APIs to train their models, and we don't permit them to. **We don't use your photos or tours to train any AI model.**
- **Provider retention.** OpenAI may keep API inputs and outputs for up to **30 days** to monitor for abuse, then deletes them. ElevenLabs processes the text to generate audio and doesn't keep it for training.
- **Synthetic voice.** Narration is an **AI-generated, synthetic voice** — not a recording of a real person — and the app labels AI-generated content.
- **Background reading.** To ground commentary in facts, and for the short place summaries on place cards, our servers search **Wikipedia (Wikimedia Foundation)** for articles about a place or about what you photographed. A search sends a place name or subject and map coordinates — for a tour photo, where it was taken (or the place you picked), to find articles about what is nearby. These lookups come from our servers and carry nothing else about you: no account details, name or photo.
- **Accuracy.** AI-generated content can be wrong. Don't rely on it for safety, navigation or access decisions, and report mistakes with Report this commentary.

## How we use your information

- **Provide the Service** — sign you in, generate personalized commentary and narration about what you photograph, keep your tour history, and sync your profile and tours across your devices.
- **Subscriptions** — verify purchases with Apple and decide whether your account is entitled to paid features.
- **Safety and security** — authenticate requests, prevent fraud and abuse, enforce fair-use limits and our Terms, and review reports about AI content.
- **Fix and improve** — diagnose crashes and errors, and improve Sightlore using **de-identified or aggregated** data that can no longer reasonably identify you. We do not use your information to build advertising profiles, and we do not sell it.
- **Legal** — keep records we're required to keep (for example tax records of purchases), respond to lawful requests, and establish or defend legal claims.

## Legal bases (EEA, UK and Switzerland)

Where the GDPR, UK GDPR or Swiss data-protection law applies, we rely on these
legal bases:

- **Contract** — to create and run your account, sync your profile and tours, process your purchases, and provide the features you ask for.
- **Consent** — to send your photos, location and profile details to our AI providers (the "How Sightlore uses AI" screen), and for iOS camera, photo and location access. You can withdraw consent at any time in Settings or iOS Settings, without affecting processing already carried out.
- **Legitimate interests** — to secure the Service, prevent abuse, keep request logs, and diagnose crashes, in ways that don't override your rights.
- **Legal obligation** — to keep purchase records for tax and accounting and to respond to lawful requests.

## Who receives your information

We share personal information only with the service providers that run
Sightlore for us (who may use it only to provide their service to us), with
the AI providers described above once you allow it, and where the law requires.

| Recipient | Why | What it receives |
|---|---|---|
| Amazon Web Services (Cognito, Lambda, CloudFront, S3, DynamoDB, CloudWatch) | Sign-in, our backend, storage, and logs | Account details from your sign-in provider, profile, consent records, tours and photos, purchase records, diagnostics, reports, request logs |
| Apple | Sign in with Apple, App Store purchases and notifications, on-device Apple Maps search and place lookups (including naming the neighborhood or city where you took a photo), crash reporting, and the App Store rating prompt | Handled under Apple's privacy policy; Apple Maps searches and lookups run from your device, not through our servers, and any rating or review you leave goes to Apple |
| Google | Google sign-in, if you choose it | Authentication happens with Google; we receive the account identifier, email and name it shares |
| OpenAI | Commentary (see "How Sightlore uses AI") | Photo and where it was taken (coordinates, accuracy, neighborhood and city), places you pick, first name, home city, Tour DNA, earlier Stop names, summaries and neighborhoods |
| ElevenLabs | Narration audio (see "How Sightlore uses AI") | The text to be spoken and the voice ID |
| Wikimedia Foundation (Wikipedia) | Background facts and place previews | A place name or subject and map coordinates (for a tour photo, where it was taken or the place you picked), from our servers, with no account details |
| Authorities or others when required | Legal compliance and protecting rights and safety | Only what the law requires, or what is needed to protect people's safety |
| A buyer or successor | If ValCam LLC is involved in a merger, acquisition or sale of assets | Your information, under this policy's protections |

**We do not sell your personal information and we do not "share" it for
cross-context behavioral advertising**, and we have not done so in the past 12
months. **Sightlore does not track you** across other companies' apps or
websites, so it never asks for App Tracking Transparency permission.

## How long we keep it

| Data | How long |
|---|---|
| Profile, Tour DNA and consent records | Until you delete your account |
| Tours, Stops and photos | Until you delete the tour or your account. A deleted tour is removed from our servers immediately; the deleting device keeps a restorable copy in Recently Deleted for 30 days. A photo uploaded for a Stop that never finished saving is deleted automatically within about a day |
| Crash and performance diagnostics | 90 days, then deleted automatically |
| Reports about AI content | 1 year, or until you delete your account if sooner |
| Request logs (IP address, user agent, paths) | 30 days (logs of Apple purchase notifications: 90 days) |
| Fair-use and daily-limit counters | 2 days |
| Purchase and subscription records | As long as needed for tax and accounting; unlinked from you when you delete your account |
| Narration audio | Never stored on our servers; the on-device cache is cleared on sign-out and account deletion |
| Data sent to OpenAI | Up to 30 days at OpenAI for abuse monitoring |

**Deleting your account** (Settings → Delete Account) immediately and
permanently erases your profile, consent records, tours, Stops, photos, reports,
diagnostics, the link between your purchases and your account, and your sign-in
account itself, and erases the copies on the device you deleted from. We keep
only a minimal deletion marker (an internal account ID and nothing else) for 24
hours so your other signed-in devices stop syncing and remove their copies.
Deleted records can remain in our encrypted database backups for up to 35 days
before they are overwritten; we use those backups only to recover from a
disaster. Deleting your account does not cancel a subscription — cancel it in
your Apple ID settings.

## International data transfers

We are based in the United States, and our providers (AWS, OpenAI, ElevenLabs)
process data in the United States and potentially other countries. If you use
Sightlore from the EEA, the UK, Switzerland or elsewhere, your information will
be transferred to and processed in the United States, which may have different
data-protection laws. Where required, we rely on appropriate safeguards such as
the European Commission's **Standard Contractual Clauses** (with the UK
Addendum) or our providers' certifications under the **EU-U.S. Data Privacy
Framework**, and you can ask us for a copy of the relevant safeguards.

## Data security

We use reasonable technical and organizational safeguards to protect your
information, including encryption in transit and at rest, access controls,
private storage reachable only through short-lived signed links, and reputable
cloud infrastructure (AWS). No method of transmission or storage is 100% secure,
however, and we cannot guarantee absolute security. Your sign-in is protected by
your Apple or Google account — please keep that account secure, and contact us
if you suspect unauthorized access to Sightlore. If a breach affects your
personal information, we will notify you and the authorities as the law
requires.

## Your rights and choices

**In the app, at any time:**

- **See and edit** your name, home city and Tour DNA on the Profile tab.
- **Download your data** — Settings → Privacy & Data → Download My Data gives you a file with your profile, consent records, tours, commentary, photos, purchase status, reports and diagnostics.
- **Delete** individual tours from Tour History, or your whole account in Settings → Delete Account.
- **Withdraw AI permission** in Settings → Privacy & Data → AI Processing.
- **Turn off** camera, photo or location access in iOS Settings.

**By email:** for any other request, email **valcamllc@gmail.com** from the
email on your account (or tell us the email and sign-in method you use). We
verify requests by asking you to confirm details only the account holder would
know, or by asking you to make the request from inside the signed-in app. We
respond within the time the law requires (generally 30 days in the EEA and UK,
45 days in the US). We honor these rights for all users, wherever they live,
and **we won't discriminate against you** — no different prices or service — for
exercising them.

### European, UK and Swiss privacy rights

You have the right to **access** your personal information, **correct** it,
**delete** it, **restrict** or **object to** our processing (including
processing based on legitimate interests), to **data portability**, and to
**withdraw consent** at any time. You also have the right to lodge a complaint
with your local **data-protection supervisory authority**, though we'd
appreciate the chance to address your concern first.

### California and other U.S. state privacy rights

Residents of California and of other states with consumer privacy laws (such as
Colorado, Connecticut, Virginia, Utah, Texas, Oregon and others) have the right
to **know** and **access** the personal information we collect, to **correct**
it, to **delete** it, to **obtain a portable copy**, to **opt out** of sale,
"sharing" for cross-context behavioral advertising, targeted advertising and
profiling with legal or similarly significant effects (we do none of these),
and to **limit** the use of **sensitive personal information**. The only
sensitive personal information we collect is your **precise geolocation**, and
we use it only to provide the Service you request — which the law permits
without an opt-out — so there is nothing further to limit. We honor **Global
Privacy Control** signals where applicable.

**Notice at collection.** In the past 12 months we collected these categories
of personal information, from you, your device and your sign-in provider, for
the purposes described in "How we use your information", and kept them for the
periods in "How long we keep it":

| Category | Examples | Disclosed for a business purpose to |
|---|---|---|
| Identifiers | Email, account and user IDs, IP address | AWS; Apple or Google (sign-in) |
| Personal records | Name, home city | AWS; OpenAI (first name, home city) |
| Commercial information | Subscription and purchase records | AWS; Apple |
| Internet or network activity | Request logs, crash and performance diagnostics | AWS |
| Geolocation (sensitive) | Where each tour photo was taken (its coordinates are stored only on your device), the place and neighborhood or city each Stop was identified as, places you pick | AWS; OpenAI; Wikimedia (place names and coordinates only, no account details); Apple (Apple Maps lookups from your device) |
| Audio, electronic, visual or similar | Tour photos you take or import | AWS; OpenAI |
| Inferences | Your Tour DNA preferences | AWS; OpenAI |
| Protected classification characteristics | Age range — only profiles created before October 2026, deleted as described in "Profile and Tour DNA" | AWS |
| Other | Commentary reports and comments, consent records | AWS |

We do not collect Social Security numbers, financial-account numbers, contacts,
biometric identifiers or advertising identifiers.

**Authorized agents.** You may use an authorized agent to make a request on your
behalf. We may ask the agent for proof of your signed permission and ask you to
verify your identity with us directly.

**Appeals.** If we decline your request, you can appeal by replying to our
decision; if you disagree with the outcome of the appeal, you may contact your
state attorney general.

## Personalization and automated decisions

Sightlore personalizes commentary using your Tour DNA. This is a simple
content-personalization feature; it does not produce legal or similarly
significant effects about you, and we don't use automated decision-making or
profiling of that kind.

## Children

Sightlore is **only for adults 18 and older**. It is not directed at children,
and we do not knowingly collect personal information from anyone under 18. If
we learn that an account belongs to someone under 18 — including from an "Under
18" answer stored in its profile before Sightlore became adults-only — we close
it and delete its data within 30 days of learning it. Until then, the app blocks
an account whose profile says "Under 18": it can only be deleted (which erases
its data at once) or signed out of. If you believe someone under 18 has an
account, contact us.

## Changes to this policy

If we change this policy, we will update the effective date above. For material
changes, the app shows you the updated documents and asks you to agree before
you continue, and we'll ask for any new consent the law requires. Previous
versions are available on request.

## Contact

ValCam LLC — **valcamllc@gmail.com** —
**502 W 7th St, Ste 100, Erie, PA 16502, USA**
