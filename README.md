# Pixelabs F-Droid Repository

Official F-Droid repository for Pixelabs open-source Android applications, automatically built and deployed to GitHub Pages via `fdroidserver` CI/CD.

## Repository Details

- **Website:** [https://fdroid.pixelabs.in](https://fdroid.pixelabs.in)
- **Repository URL:** `https://fdroid.pixelabs.in/repo`
- **Signing Fingerprint (SHA-256):** `3C3E9EF8F74E8E057FA0EA4965D19DE1E6A223719D0B2D6870FDC59F6B20B55E`
- **One-Click Add:** `fdroidrepos://fdroid.pixelabs.in/repo?fingerprint=3C3E9EF8F74E8E057FA0EA4965D19DE1E6A223719D0B2D6870FDC59F6B20B55E`

## Hosted Packages

| Package | Application ID | Version | License |
| :--- | :--- | :--- | :--- |
| **Pixelabs Calculator** | `com.aistudio.calculator.gtypxz` | v19.9.2 (190902) | MIT |

## Automation & Infrastructure

- **Engine:** `fdroidserver` (`fdroid update --create-metadata`)
- **Hosting:** GitHub Pages via custom domain `fdroid.pixelabs.in`
- **DNS & CDN:** Cloudflare DNS (CNAME pointing to `pixelabsdev.github.io`)
- **Keystore Security:** Encrypted in GitHub Actions Secrets (`FDROID_KEYSTORE_BASE64`)
