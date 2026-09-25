# Luna and Sol website

A no-build static website hosted on GitHub Pages at [shaunkim.github.io/lunaandsol.org](https://shaunkim.github.io/lunaandsol.org/). The published entry point is `index.html`; there are no dependencies or build commands.

## Before launch

- Confirm that `lunaandsol.org` is registered and configure DNS at GoDaddy to point to the chosen host. Add the host's requested DNS records and enable HTTPS.
- Replace `hello@lunaandsol.org` with an email address you control on the company's domain. Set up that mailbox and test receiving messages first.
- Replace the generic studio copy with accurate details about the legal business, its location/contact details as appropriate, and the actual apps. The 2048³ App Store and GitHub links are now in the app catalog; keep those destinations and the listing information current.
- Add a privacy policy for each app and ensure the page reflects its actual data practices before entering a privacy URL in App Store Connect.
- Make the site's public contact details, domain, and business identity consistent with your developer account and business records.

## App Store organization credibility

Apple expects an organization's website to be publicly available, functional, and on a domain associated with that organization. A thin placeholder page or registrar parking page is not enough. A useful company site should have original, accurate company information, working domain email/contact details, real app listings when available, and privacy/support information that matches the apps.

If you mean **public App Store distribution**, the Apple Developer Program is generally the relevant program. Apple says organization enrollment requires a legal entity, D‑U‑N‑S Number (with stated exceptions), authority to bind the organization, a work email on its domain, and a functional organization website.

The **Apple Developer Enterprise Program is not a route for publishing public App Store apps**. Apple currently limits it to qualifying organizations with at least 100 employees, distributing proprietary in-house apps securely to their employees for use cases not adequately served by public apps, Apple Business/custom apps, Ad Hoc, or TestFlight. Apple also requires a legal entity, D‑U‑N‑S Number, verification, and a domain-associated public website. Check Apple's current eligibility before applying; the website alone cannot establish eligibility.

Official guidance:

- [Apple Developer Enterprise Program](https://developer.apple.com/programs/enterprise/)
- [Organization enrollment requirements](https://developer.apple.com/help/account/membership/program-enrollment/)
- [D‑U‑N‑S information](https://developer.apple.com/support/D-U-N-S/)
- [App Store Connect privacy requirements](https://developer.apple.com/help/app-store-connect/manage-app-information/manage-app-privacy/)

## GitHub Pages

GitHub Pages is enabled from the `main` branch and repository root. The live address is [https://shaunkim.github.io/lunaandsol.org/](https://shaunkim.github.io/lunaandsol.org/).

When `lunaandsol.org` is registered, open the repository's **Settings → Pages** and add it as the custom domain. Follow the DNS records GitHub displays at GoDaddy; typically this means a `www` CNAME and apex A/AAAA records. Wait for DNS verification, enable **Enforce HTTPS**, and test the domain on mobile and desktop.

GitHub's current instructions: [Managing a custom domain for your GitHub Pages site](https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site).

## Updating the website yourself

There is no separate admin login on the website. To make changes, sign in to the GitHub account that owns the site repository or has write access to it:

1. Open the `lunaandsol.org` repository on GitHub.
2. Select `index.html` from the file list.
3. Click the pencil **Edit this file** button.
4. Make your changes. For text, use the editor's search (`⌘F` on Mac, `Ctrl+F` on Windows) to find the current wording.
5. Click **Commit changes**, enter a short summary, and confirm the commit.
6. GitHub Pages will publish the updated page after its deployment finishes. Refresh your website to see it.

You need write access to the repository. If GitHub asks you to create a branch or pull request, the repository may require an owner to review and merge your changes. [GitHub's file editing guide](https://docs.github.com/en/repositories/working-with-files/managing-files/editing-files) has screenshots and more detail.
