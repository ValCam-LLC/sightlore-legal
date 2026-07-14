---
title: Sightlore Privacy Policy
permalink: /privacy/
render_with_liquid: false
---

# Sightlore Privacy Policy

**Effective date: July 14, 2026**

Sightlore is an iOS travel app made by **ValCam LLC**. It gives you AI-narrated
commentary about landmarks you photograph during a tour. This policy explains,
in plain language, what information the app collects, how it is used, and the
choices you have. ValCam LLC is the **controller** of your personal
information.

Questions or requests: **valcamllc@gmail.com** — ValCam LLC, **[MAILING
ADDRESS]**.

## The short version

- We collect only what the app needs to work: the email address your sign-in
  provider (Apple or Google) shares with us, the name and tour preferences you
  enter, your tour photos, and tour locations.
- Nearby-landmark discovery runs on your device using Apple Maps — that
  browsing never sends your location to our servers.
- Photos you take during a tour are sent to our backend so an AI model can
  identify and narrate what you photographed, and they are saved as your tour
  history.
- **No ads. No third-party analytics. No tracking SDKs. We never sell or share
  your data for advertising, and we never train AI models on your photos.**
- You can delete your account (and individual tours) directly in the app.

## Information we collect

### Account information

You sign in with your **Apple or Google account** — there is no Sightlore
password, and we never receive your Apple or Google credentials. When you
first sign in, your provider shares a stable account identifier, your **email
address** (with Sign in with Apple you can choose Apple's private relay
address instead of your real one), and — on first sign-in only — your **name**,
which we use to prefill your profile. These are managed for us by AWS Cognito
(Amazon's identity service). Each sign-in method is a separate Sightlore
account: signing in with Apple and with Google creates two different accounts,
and we cannot merge them.

### Profile and Tour DNA

During onboarding you can provide your **first and last name**, **age range**,
and **home city**, and answer eight questions about how you like to tour
(interests, pace, depth, tone, and so on) — together, your **Tour DNA** — plus
a narration voice preference. This profile is stored on your device and synced
to our servers so it follows you across devices and so commentary can be
personalized to it.

### Location

With your permission, the app uses your **precise location** for two things:

1. **On-device discovery.** Finding Nearby Destinations, For You recommendations, and suggesting your home city all use Apple's MapKit search directly on your device. **This never sends your location to Sightlore's servers.**
2. **Tours.** When you start a tour and photograph something, the tour's coordinate (your GPS fix, or the place you selected) is sent with the request so the AI can identify what you photographed, and it is stored with that tour in your tour history.

Precise geolocation is treated as **sensitive information**. Location access is
optional — you can type a location manually instead — and the app never
accesses your location in the background.

### Photos

Photos you take with the in-app camera during a tour are sent to our backend
for AI analysis and saved as part of your **tour history** so you can revisit
past tours. The app does not access your photo library.

**Other people in your photos.** If people or private property happen to appear
in a photo you take, that content is processed the same way as the rest of the
image. **Sightlore does not perform facial recognition and does not attempt to
identify individuals in your photos.** You are responsible for having any
permission needed to photograph and process images of other people.

### Audio

The commentary text is sent to a speech service to generate the narration audio
you hear. We do not record audio and never access your microphone.

### What we don't collect

No advertising identifiers, no third-party analytics or tracking SDKs, no
cross-app tracking, no contacts, no photo library access, no background
location, no selling or renting of personal information. Ever.

## How we use your information

- **Generate commentary** — your Tour DNA, the tour location, and your photo are used to produce personalized narration about what you photographed.
- **Keep your stuff in sync** — your profile and tour history are stored so they survive reinstalls and follow you across devices.
- **Operate and secure the service** — authenticate requests, prevent abuse, and apply fair-use rate limits.
- **Improve the service** — we use **de-identified or aggregated** data (which can no longer reasonably identify you) to understand usage, power recommendations, and improve Sightlore. We do not use this to build advertising profiles, and we do not sell it.

## Legal bases (EEA/UK users)

Where the GDPR or UK GDPR applies, we process your information on these legal
bases: to **perform our contract** with you (creating your account, generating
commentary, syncing your tours); with your **consent** (accessing your precise
location and camera, which you can withdraw at any time in iOS Settings); and
for our **legitimate interests** in operating, securing, and improving the
Service in ways that don't override your rights. Where we rely on consent, you
can withdraw it without affecting processing already carried out.

## AI processing and model training

To generate commentary, your tour photo, the tour coordinate, and your Tour DNA
preferences are sent to our AI provider (OpenAI) via its API. Under OpenAI's
API terms, data sent through the API is **not used to train OpenAI's models by
default**, and OpenAI retains API content only briefly for abuse monitoring
before deletion. **We do not use your photos or tour content to train any AI
model**, and we do not permit our providers to do so. Commentary text is sent
to a text-to-speech provider solely to produce the narration audio.

## Service providers

We use a small number of providers to run Sightlore. They process data only to
provide the service to you:

| Provider | What it does | What it receives |
|---|---|---|
| Amazon Web Services (Cognito, Lambda, S3, DynamoDB) | Sign-in, our backend, and storage of your profile, tours, and tour photos | Account email and name from your sign-in provider, profile, tour records, photos |
| Apple / Google (your choice at sign-in) | Sign in with Apple / Google sign-in | Authentication happens with your provider; we receive the account identifier, email, and name it shares |
| OpenAI | Vision and language models that identify what you photographed and write the commentary | Your tour photo, the tour coordinate, and your Tour DNA preferences |
| Text-to-speech providers (Microsoft neural voices; ElevenLabs for premium voices where enabled) | Turn commentary text into narration audio | The commentary text only |
| Apple (MapKit) | On-device landmark search | Handled by iOS under Apple's privacy terms; not routed through our servers |

## Data stored only on your device

- A local copy of your profile and tour history is cached on the device for offline viewing.

## Data security

We use reasonable technical and organizational safeguards to protect your
information, including encryption in transit, access controls, and reputable
cloud infrastructure (AWS). No method of transmission or storage is 100% secure,
however, and we cannot guarantee absolute security. Your sign-in is protected
by your Apple or Google account — please keep that account secure, and contact
us if you suspect unauthorized access to Sightlore.

## International data transfers

We are based in the United States, and our providers (AWS, OpenAI) process data
in the United States and potentially other countries. If you use Sightlore from
the EEA, the UK, or elsewhere, your information will be transferred to and
processed in the United States, which may have different data-protection laws.
Where required, we rely on appropriate safeguards such as the European
Commission's **Standard Contractual Clauses** for these transfers.

## Retention and deletion

- **Delete a tour**: deleting a tour in the app removes its records and photos from our servers, typically within 30 days.
- **Delete your account**: Settings → Delete Account permanently deletes your sign-in account and erases the profile and tour data stored on your device. Server-stored tour history tied to the deleted account is removed, typically within 30 days, and purged from routine backups within 90 days. To request immediate removal, email **valcamllc@gmail.com**.
- We keep data only as long as your account is active or as needed to provide the service and meet legal obligations. De-identified or aggregated data that can no longer identify you may be retained.

## Your rights

You can access and edit your profile in the app at any time, and delete
individual tours or your whole account in Settings. Depending on where you live,
you may have additional rights described below. To exercise a right, email
**valcamllc@gmail.com**; we may need to verify your identity (for example, by
confirming control of your account email) before acting, and we respond within
the timeframes required by law. We honor these requests for all users
regardless of location, and we won't discriminate against you for exercising
them.

### California privacy rights (CCPA/CPRA)

If you are a California resident, you have the right to know what personal
information we collect, to access and delete it, to correct it, and to limit the
use of **sensitive personal information** (for us, your precise geolocation).
**We do not sell your personal information, and we do not "share" it for
cross-context behavioral advertising** — so there is nothing to opt out of on
that front, and we honor Global Privacy Control signals where applicable. The
categories of personal information we collect are:

| Category | Examples | Do we collect it? |
|---|---|---|
| Identifiers | Account email, account/user ID | Yes |
| Personal records | First and last name | Yes, if you provide them |
| Protected classifications | Age range | Yes, if you provide it |
| Internet/usage activity | App interactions needed to run the service | Yes |
| Geolocation | Tour coordinate (precise) | Yes, with permission |
| Sensory information | Tour photos you capture | Yes |
| Inferences | Your Tour DNA preferences | Yes |

We do not collect Social Security numbers, financial-account numbers, contacts,
biometric identifiers, or advertising identifiers.

### European and UK privacy rights (GDPR)

If you are in the EEA or the UK, you have the right to access, correct, delete,
restrict, or object to our processing of your personal information, to data
portability, and to withdraw consent at any time. You also have the right to
lodge a complaint with your local **data-protection supervisory authority**.

## Personalization

Sightlore personalizes your commentary using your Tour DNA preferences. This is
a simple content-personalization feature; it does not produce legal or similarly
significant effects about you, and we do not use it for automated
decision-making of that kind.

## Children

Sightlore is not directed at children under 13, and we do not knowingly collect
personal information from them. If you believe a child under 13 has created an
account, contact us and we will delete it.

## Changes to this policy

If we change this policy, we will update the effective date above and, for
significant changes, note it in the app or on our published page. Continued use
of Sightlore after a change means you accept the updated policy.

## Contact

ValCam LLC — **valcamllc@gmail.com** — **[MAILING ADDRESS]**
