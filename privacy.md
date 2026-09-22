---
layout: default
title: Privacy Policy
---

# Privacy Policy

This policy explains what information the **PickCharge** app collects,
how it's used, and the choices you have. It describes the App as it
currently works.

**Last updated:** 2026-10-08

## 1. Information we collect

**Location.** With your permission, the App uses your device's location
to find charging stations near you and estimate whether you can reach
them. Location is:
- Sent to our backend server as part of each search request, so it can
  return nearby stations. It is used to answer that request and is not
  saved to our database. Because the coordinates are part of the request
  address, they can appear in the standard short-term request logs kept
  by our hosting provider, Render, for operations and troubleshooting.
  These logs are not linked to any account or identity, because the App
  has no accounts.
- Cached on your device only, never on our servers, so the App can show
  your area immediately the next time you open it without waiting for a
  fresh GPS fix. This cache is deleted if you clear the App's data or
  uninstall it.

You can deny or revoke location access at any time in your device
settings. Without it, or if you're outside the App's coverage area of
mainland Portugal, the Azores, and Madeira, the App falls back to a
default location in Porto, Portugal, and you can still search manually.

**Vehicle profile.** The vehicle you select and your current and target
battery percentage are stored only on your device. They are not stored
in an account or on our servers, as the App has no accounts. This
information is sent to our backend with each request so it can calculate
reachability, cost, and charging time estimates for that specific trip;
it is not stored there.

**Subscription status.** PickCharge requires an active Google Play
subscription to use. The App sends the Google Play purchase token for
your subscription with each request to our backend, which verifies it
directly against Google's own subscription record through the Google
Play Developer API to confirm access. This token is not a payment method
or card number. It's an opaque reference Google generates. Google
handles all payment processing and holds your actual payment details; we
never see or store them.

**Feedback you send.** If you use *Settings > Send feedback*, the App
sends your star rating, any comment you choose to write, your platform,
such as Android, and the App's language. This is stored in our database
so we can read it and improve the App. It isn't linked to your name,
your subscription, or your location. Please don't put personal
information in the comment.

**App preferences.** Your language choice and whether you've already
seen the onboarding screens and tips are stored only on your device.

**We do not collect:** your name, email address, phone number, or any
other account or contact information. The App has no sign-up or login.

## 2. How we use information

Location and vehicle profile data are used exclusively to answer your
in-app requests: finding nearby stations, and estimating reachability,
cost, and charging time for your selected vehicle. Feedback is used only
to understand and improve the App. Your subscription purchase token is
used solely to verify you have active access before answering a request.
It's checked against Google's records and briefly cached in our server's
memory, for up to 10 minutes, to avoid checking with Google on every
single request; it is not written to a database. We do not use any of
this data for advertising, and we do not sell it to third parties.

## 3. Third-party services

- **Google Play Billing** handles your subscription purchase and all
  payment processing. We never see or store your payment details; see
  [Google's Privacy Policy](https://policies.google.com/privacy) for how
  Google handles that information.
- **Map tiles** are loaded directly from OpenStreetMap's tile servers to
  display the map. This causes your device to make a direct network
  request to OpenStreetMap for each map tile, which may log your IP
  address as described in
  [OpenStreetMap's privacy policy](https://wiki.osmfoundation.org/wiki/Privacy_Policy).
- **Charging station data**, including locations, connectors, live
  availability, and prices, is sourced from MOBI.E, Portugal's national
  EV charging network, through the National Access Point operated on
  behalf of IMT, the Instituto da Mobilidade e dos Transportes. This is
  public infrastructure data, not personal data.
- **Crash reporting by Sentry.** If the App crashes or hits an unexpected
  error, a report is sent to Sentry containing the error details and
  basic device and app information: device type, OS version, and App
  version. We don't intentionally include your location or vehicle
  profile in these reports.
- **Analytics by PostHog, hosted in the EU.** We record a small number of
  anonymous usage events: a vehicle profile being saved, a recommendation
  being shown and on which screen, and standard app lifecycle events such
  as the App being installed, updated, opened, or sent to the background.
  Each event includes standard device and app information, namely device
  type, OS version, and App version, and a random identifier PostHog
  generates on your device. We use this to understand whether the App's
  core feature is actually useful. None of these events include your
  location or which vehicle you selected. As with any network request,
  PostHog receives your IP address; see
  [PostHog's privacy policy](https://posthog.com/privacy).
- **Navigation apps.** If you tap to navigate to a station, the App opens
  Google Maps or Waze with that station's coordinates as the destination.
  From then on, that app's own privacy policy applies.
- **Hosting by Render.** Our backend server and database are hosted by
  Render, which processes requests on our behalf as described above.

## 4. Data storage and retention

We do not operate user accounts. Your location, vehicle profile, and
preferences are stored only on your device, for as long as the App is
installed, until you clear its data or uninstall it. Our backend server
processes your location and vehicle profile in memory to answer each
request and does not write them to a database. As noted in Section 1,
request coordinates can appear in our hosting provider's short-term
request logs. Your subscription purchase token is cached in server
memory only, for up to 10 minutes, and is never written to a database.
Feedback you send is kept in our database for as long as it's useful for
improving the App.

## 5. Your rights

Because your location and vehicle profile are stored only on your device
and never in an account we control, you can access, change, or delete
this information at any time directly in the App, for example on the
vehicle setup screen, or by clearing the App's data or uninstalling it.
If you are in the European Economic Area, you have rights under the
GDPR, including access, correction, deletion, portability, and
objection. Contact us using the details below with any request. Because
feedback and request logs aren't linked to any account or identity, we
usually can't tell which entries came from you. If you want a feedback
comment removed, tell us what it said and roughly when you sent it.

## 6. Children's privacy

The App is not directed at children and we do not knowingly collect
information from children under 16.

## 7. Changes to this policy

We may update this policy as the App changes. We'll update the "Last
updated" date above when we do; material changes affecting how your data
is used will be called out in the App's release notes.

## 8. Contact us

Questions about this policy or your data: **support@pickcharge.eu**
