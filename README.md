# Luna and Sol website

A no-build static website hosted on GitHub Pages at [www.lunaandsol.org](https://www.lunaandsol.org/). The published entry point is `index.html`; there are no dependencies or build commands.

## Keeping the site current

- Keep the published contact email current and check that it receives messages.
- Keep the app listings and links current. Add Flame Aid release links when they are public.
- Add a privacy policy for each app and ensure the page reflects its actual data practices before entering a privacy URL in App Store Connect.
- Make the site's public contact details and business identity consistent with your developer account and business records.

## App Store organization credibility

Apple expects an organization's website to be publicly available and functional. A useful company site should have original, accurate company information, working contact details, real app listings when available, and privacy/support information that matches the apps.

If you mean **public App Store distribution**, the Apple Developer Program is generally the relevant program. Apple says organization enrollment requires a legal entity, D‑U‑N‑S Number (with stated exceptions), authority to bind the organization, a work email on its domain, and a functional organization website.

The **Apple Developer Enterprise Program is not a route for publishing public App Store apps**. Apple currently limits it to qualifying organizations with at least 100 employees, distributing proprietary in-house apps securely to their employees for use cases not adequately served by public apps, Apple Business/custom apps, Ad Hoc, or TestFlight. Apple also requires a legal entity, D‑U‑N‑S Number, verification, and a domain-associated public website. Check Apple's current eligibility before applying; the website alone cannot establish eligibility.

Official guidance:

- [Apple Developer Enterprise Program](https://developer.apple.com/programs/enterprise/)
- [Organization enrollment requirements](https://developer.apple.com/help/account/membership/program-enrollment/)
- [D‑U‑N‑S information](https://developer.apple.com/support/D-U-N-S/)
- [App Store Connect privacy requirements](https://developer.apple.com/help/app-store-connect/manage-app-information/manage-app-privacy/)

## GitHub Pages

GitHub Pages publishes this site from the `main` branch and repository root. The live address is [https://www.lunaandsol.org/](https://www.lunaandsol.org/).

## Updating the website yourself

There is no separate admin login on the website. To make changes, sign in to the GitHub account that owns the site repository or has write access to it:

1. Open the `lunaandsol.org` repository on GitHub.
2. Select `index.html` from the file list.
3. Click the pencil **Edit this file** button.
4. Make your changes. For text, use the editor's search (`⌘F` on Mac, `Ctrl+F` on Windows) to find the current wording.
5. Click **Commit changes**, enter a short summary, and confirm the commit.
6. GitHub Pages will publish the updated page after its deployment finishes. Refresh your website to see it.

You need write access to the repository. If GitHub asks you to create a branch or pull request, the repository may require an owner to review and merge your changes. [GitHub's file editing guide](https://docs.github.com/en/repositories/working-with-files/managing-files/editing-files) has screenshots and more detail.
