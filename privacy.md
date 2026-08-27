---
layout: default
title: Privacy Policy
---

# Privacy Policy

**PickCharge** ("the App") is developed by **PickCharge**
("we", "us", "our"). This policy explains what information the App
collects, how it's used, and the choices you have. It reflects the App as
it currently works — Sections marked *(planned)* describe functionality
not yet built; this policy will be updated before that functionality
ships.

**Last updated:** 2026-08-27

## 1. Information we collect

**Location.** With your permission, the App uses your device's location
to find charging stations near you and estimate whether you can reach
them. Location is:
- Sent to our backend server as part of each search request, so it can
  return nearby stations — it is used to answer that request and is not
  stored on our servers.
- Cached on your device only (not on our servers), so the App can show
  your area immediately the next time you open it without waiting for a
  fresh GPS fix. This cache stays on your device and is deleted if you
  clear the App's data or uninstall it.

You can deny or revoke location access at any time in your device
settings. Without it, the App falls back to a default location (Porto,
Portugal) and you can still search manually.

**Vehicle profile.** The vehicle you select and your current/target
battery percentage are stored only on your device (not in an account, not
on our servers — the App has no accounts). This information is sent to
our backend with each request so it can calculate reachability, cost, and
charging time estimates for that specific trip; it is not stored there.

**Subscription status.** PickCharge requires an active Google Play
subscription to use. The App sends the Google Play purchase token for
your subscription with each request to our backend, which verifies it
directly against Google's own subscription record (the Google Play
Developer API) to confirm access. This token is not a payment method or
card number — it's an opaque reference Google generates, and Google
handles all payment processing and holds your actual payment details; we
never see or store them.

**We do not collect:** your name, email address, phone number, or any
other account/contact information — the App has no sign-up or login.

## 2. How we use information

Location and vehicle-profile data are used exclusively to answer your
in-app requests: finding nearby stations, and estimating reachability,
cost, and charging time for your selected vehicle. Your subscription
purchase token is used solely to verify you have active access before
answering a request — it's checked against Google's records and briefly
cached in our server's memory (up to 10 minutes) to avoid checking with
Google on every single request; it is not written to a database. We do
not use any of this data for advertising, and we do not sell it to third
parties.

## 3. Third-party services

- **Google Play Billing** handles your subscription purchase and all
  payment processing. We never see or store your payment details; see
  [Google Play's Privacy Policy](https://policies.google.com/privacy) for
  how Google handles that information.
- **Map tiles** are loaded directly from OpenStreetMap's tile servers to
  display the map. This causes your device to make a direct network
  request to OpenStreetMap for each map tile, which may log your IP
  address per [OpenStreetMap's own privacy policy](https://wiki.osmfoundation.org/wiki/Privacy_Policy).
- **Charging station data** (locations, connectors, live availability,
  and prices) is sourced from Portugal's national EV charging network
  (MOBI.E), via the National Access Point operated on behalf of IMT
  (Instituto da Mobilidade e dos Transportes). This is public
  infrastructure data, not personal data.
- **Crash reporting (Sentry).** If the App crashes or hits an unexpected
  error, a report is sent to Sentry containing the error/stack trace and
  basic device/app information (device type, OS version, app version). We
  don't intentionally include your location or vehicle profile in these
  reports.
- **Analytics (PostHog, EU-hosted).** We track two anonymous events - a
  vehicle profile being saved, and a recommendation being shown - plus
  standard device/app metadata (device type, OS version, app version),
  to understand whether the App's core feature is actually useful.
  Neither event includes your precise location or which vehicle you
  selected.

## 4. Data storage and retention

We do not operate user accounts and do not persist your location or
vehicle profile on our servers — both live only on your device, for as
long as the App is installed, until you clear its data or uninstall it.
Our backend server processes your location and vehicle profile in memory
to answer each request and does not write them to a database. Your
subscription purchase token is cached in server memory only, briefly (up
to 10 minutes), and is never written to a database either.

## 5. Your rights

Because your location and vehicle profile are stored only on your device
and never in an account we control, you can access, change, or delete
this information at any time directly in the App (e.g. the vehicle setup
screen) or by clearing the App's data / uninstalling it. If you are in
the European Economic Area, you have rights under the GDPR (access,
correction, deletion, portability, objection) — contact us using the
details below with any request, though in practice there is no
server-side personal data for us to act on beyond what's described above.

## 6. Children's privacy

The App is not directed at children and we do not knowingly collect
information from children under 16.

## 7. Changes to this policy

We may update this policy as the App changes. We'll update the "Last
updated" date above when we do; material changes affecting how your data
is used will be called out in the App's release notes.

## 8. Contact us

Questions about this policy or your data: **support@pickcharge.eu**
