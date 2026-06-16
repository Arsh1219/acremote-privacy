# AC Universal Remote Control — Privacy Policy &amp; Terms

This repository hosts the public **Privacy Policy** and **Terms of Use** for the
**AC Universal Remote Control** Android app (`com.ac.air.conditioner.acremote`).

- **Privacy Policy:** https://arsh1219.github.io/acremote-privacy/ (`index.html`)
- **Terms of Use:** https://arsh1219.github.io/acremote-privacy/terms.html (`terms.html`)

Use those URLs in:
- Google Play Console → Store listing → Privacy policy
- Google Play Console → App content → Data safety
- The app's `lib/core/constants/app_info.dart` (`privacyPolicyUrl` / `termsUrl`)

The pages are self-contained HTML (no build step). Edit and commit to update the live site.

## What the policy discloses

The app collects/shares data only through Google service providers:

- **Google AdMob** — ads in the free version (advertising/device IDs, IP-derived coarse location, device info, ad-interaction data).
- **Google Firebase Analytics** — pseudonymous feature-usage events + an app-instance ID, to understand usage.
- **Firebase Crashlytics** — crash stack traces &amp; device state (released builds only), to fix crashes.
- **Google Play Billing** — subscription/purchase status + token (no card details).
- **On-device only** — saved remotes &amp; settings (`shared_preferences`), never uploaded.

> **Play Data Safety reminder:** because Firebase Analytics + Crashlytics are now in the
> app, the Play Console **Data safety** form must declare *App activity / app info &amp;
> performance* (analytics) and *Crash logs / Diagnostics* (Crashlytics) in addition to the
> ads identifiers — keep it in sync with this policy.

Contact: billionwebpteltd@gmail.com
