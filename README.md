# Kordelis Android notes


Practical guides for Android developers working with Google Play subscriptions, backend entitlements, and app UI states. Each note stands on its own and includes sources, examples, and clear limits.


## Guides


### Google Play subscription access after cancellation


[Read the guide](google-play-subscription-access.md) for an access checklist and a reproducible cancellation-to-expiry test.


### When a screen gets an error, give it something to show


[Read the guide](when-a-screen-gets-an-error-give-it-something-to-show.md) for a Kotlin UI-state example and a focused error-state test checklist. This topic is useful across Android apps and is not specific to our SDK.


### An RTDN arrived. Is the subscription entitlement correct?


[Read the guide](rtdn-is-a-signal-not-an-entitlement.md) for a five-check reconciliation trace and a reproducible expiry test.


## About the project


Kordelis (formerly Elevate Labs) is developing Android monetization and entitlement tools. Our [Free Android preview](https://github.com/kordelis-dev/android-monetization-open-core) includes a Compose paywall and mock purchase examples. It does not include real Google Play billing or server verification. This repository contains technical notes; the billing and entitlement SDK remains in development.


We share what we have tested, distinguish staging results from general platform guidance, and update examples as the work changes. If you find a technical issue, open an issue with a minimal reproduction. Please leave out purchase tokens, customer identifiers, and private service details.

