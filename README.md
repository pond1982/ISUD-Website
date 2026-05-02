# I.S.U.D. Zero Website

Static App Store support site for I.S.U.D. Zero.

## Files

- `index.html` - public marketing page / optional Marketing URL.
- `support.html` - App Store Connect Support URL.
- `privacy.html` - App Store Connect Privacy Policy URL.
- `styles.css` - shared responsive styling.
- `assets/` - local website copies of the current icon and App Store screenshots.

## App Store Connect URLs

After hosting this folder on a public HTTPS domain, use URLs like:

- Marketing URL: `https://your-domain.example/isud-zero/`
- Support URL: `https://your-domain.example/isud-zero/support.html`
- Privacy Policy URL: `https://your-domain.example/isud-zero/privacy.html`

Apple's current App Store Connect reference says the Privacy Policy URL is required for iOS apps, and the Support URL is required for the app version and must lead to actual contact information.

## Before Submission

1. Replace every `support@isudzero.com` instance if that mailbox is not real.
2. Host the full `Marketing/Website/` folder on a public HTTPS URL.
3. Open the hosted `support.html` and confirm the email link works.
4. Open the hosted `privacy.html` and confirm it matches the Firebase Analytics, Game Center, and support practices in the submitted build.
5. Add the final URLs to App Store Connect before submitting the app for review.

## Apple References

- App information and Privacy Policy URL: https://developer.apple.com/help/app-store-connect/reference/app-information/
- Platform version information and Support URL: https://developer.apple.com/help/app-store-connect/reference/app-information/platform-version-information/
- App privacy details: https://developer.apple.com/app-store/app-privacy-details/
