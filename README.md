# Learnoids

Static source for learnoids.co.uk, hosted on GitHub Pages from main / root. The apps and their saved data are separate from this website.

## Edit and build

Node.js 22 or later; no package installation is required. Run npm run build to generate 13 pages plus the 404 page. Run npm run check to check local links and basic content.

Edit site-config.json for contact details and availability. Page templates are in build.js, Multiploids templates in content/multiploids.js, and policies in content/legal.js. Shared styling is in styles.css; scoped Multiploids styling is in multiploids.css. Rebuild after editing source. Generated HTML is overwritten on rebuild.

The site uses static HTML, CSS, local fonts and local artwork. It installs no service worker, browser storage, analytics, third-party widgets or forms. Support opens the visitor's email app.

## Availability

Multiploids: Times Tables v1.0.0 is described as coming soon. Only set multiploidsApproved to true after Apple approval, and only set multiploidsAppStoreUrl to the live public apps.apple.com product URL. Both conditions are required before its download button appears. Do not use TestFlight invitation links for public availability. Spelloids availability is maintained separately.

publicLaunch controls search indexing only; it does not approve an app, activate payments or enable a download link.

## Product and privacy information

Updated on 23 November 2026 for Multiploids v1.0.0: ages 5–11, numbered rockets, five preparation activities, twelve correct facts for launch, Cosmo Hop, two starter Starbase games and one for each different numbered rocket launched, practice customisation rewards and a weekly suit earned through 20 different practice questions.

Mark Atkin operates Learnoids; support and privacy enquiries go to support@bluffle.co.uk. Multiploids is free, with no advertising, in-app purchases or third-party analytics. Core learning and built-in speech work offline; progress is local, with no accounts or device syncing. Website hosting and optional support email are explained separately in the notices. If app data practices or hosting change, update the policies and App Store disclosures before publishing those changes.

Spelloids' existing artwork and visual theme are retained. Multiploids uses the supplied mint three-eyed logo and app icon. Social cards use local artwork. Private review access details must never be published in this repository.

## Validation

The 13 pages were checked in Chrome at 1440, 1024, 768, 390 and 320 pixels: no horizontal overflow or broken images. Keyboard skip navigation, reduced motion, FAQ controls, local links, support email, offline/privacy wording and absence of third-party requests, cookies and browser storage were checked. These checks are not a full accessibility audit or a physical-device test.

## Divoids homepage feature

The homepage introduces Divoids as a free browser playtest on Planet Moz, with its existing coral character and a direct /divoids/test/ link. Navigation, parent information and support include the playtest. Its application file is preserved byte for byte. divoids-home.css scopes the new card and announcement styling. The local-link checker treats the self-contained playtest separately from the static marketing documents.
