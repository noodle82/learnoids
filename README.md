# Learnoids

A small, self-contained website for learnoids.co.uk. The apps and their saved data are separate from this site.

## Edit and build

Node.js 22 or later. No package installation is required.

Run `npm run build` to generate the 12 pages. Run `npm run check` to check local links and content. Edit `site-config.json` for the operator, email, dates, public launch status and public App Store links. The page templates are in `build.js`; policies are in `content/legal.js`; styling is in `styles.css`. Rebuild after editing templates or configuration. Editing generated HTML directly will be overwritten by the next build.

The site works as ordinary static HTML and CSS without JavaScript. It uses local fonts and rendered images of the existing app characters. It does not install a service worker, save browser data, use analytics, embed third-party widgets or submit forms. Support links open the visitor’s email app.

## Launch status

Public App Store URLs are not yet supplied. Both app pages therefore say “App Store launch coming soon” and do not contain pretend download buttons. Set the correct links once the apps have public product pages. TestFlight invite links are not used as public-release links.

`publicLaunch` is false for the review copy, which keeps search engines out. After approving the content and preparing the site for publication, set it to true and rebuild to allow indexing. This does not change either app or activate payments.

Use a separate GitHub repository called `learnoids`. Upload the website files at its top level, then publish from main / root with GitHub Pages. Do not upload these files into practimals, multiploids or jollybox. See the separate GoDaddy setup guide.

## Policy review

The operator is Mark Atkin and the supplied support/privacy contact is support@bluffle.co.uk. The texts are drafts based on the local Spelloids 0.19.0 and Multiploids 0.4.2 code available on 16 November 2026, with UK-oriented privacy/consumer wording and Apple’s current requirements. They are not a certification of legal compliance. Confirm they match the exact builds submitted to Apple, the actual hosting/email arrangements and your support retention practices before publishing. If the operator becomes a company, add its correct registered details and address. Confirm any business/service-address disclosures that apply to your operation; no home address has been invented or published.

GitHub Pages is the proposed static information host, so its IP/security logging is disclosed. If another host is chosen, update those sections before publishing. A privacy link is also needed inside each app’s grown-up section, in addition to the App Store Connect URL. This website project does not modify either app. Parent-only links/purchases must respect the app’s parental gate.

If future releases add accounts, cloud sync, analytics, online speech or purchases, review the policies, privacy labels and actual child-data processing before deploying those changes. The current site takes no payments and makes no “free forever” promise.

## Checks performed

All 12 pages loaded in a real desktop browser. Home/app/support/privacy/terms pages were checked at 1440, 1024, 768, 390 and 320-pixel widths, with no horizontal overflow. Keyboard skip navigation, reduced motion, image loading, local links, no third-party requests and no site cookies/local storage were checked. These checks do not constitute a full accessibility or legal audit; no physical iPad test was performed.

The website has not been published or connected to GoDaddy by this local preparation. No registrar credentials or private app data are included.
