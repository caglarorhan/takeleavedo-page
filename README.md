# TakeLeaveDo: Stop Checklist — Official Web & User Guide

Official web landing page, documentation, and privacy compliance portal for **TakeLeaveDo: Stop Checklist** — the smart location-aware stop & routine assistant for Android.

Hosted live on GitHub Pages:
[https://caglarorhan.github.io/takeleavedo-page/](https://caglarorhan.github.io/takeleavedo-page/)

---

## Site Pages & Architecture

- **`index.html`**: Flagship marketing & feature landing page (features, interactive mockups, how it works, FAQs).
- **`docs.html`**: Comprehensive user manual, voice command syntax, time-window conflict rules, slide-to-delete with 2-second Undo, Wi-Fi fingerprint corroboration, and complete Web/API JSON schema.
- **`privacy.html`**: Google Play Store compliant Privacy Policy detailing background location (`ACCESS_BACKGROUND_LOCATION`), microphone access (`RECORD_AUDIO`, `FOREGROUND_SERVICE_MICROPHONE`), camera QR scanning, and 100% on-device data sovereignty.
- **`terms.html`**: Terms of Service and safety notices.
- **`support.html`**: Help center, signal diagnostics checklist, and issue tracker.
- **`assets/`**:
  - `css/style.css`: Clean, responsive stylesheet with dark/light mode toggle.
  - `js/main.js`: Local theme preference persistence and interactive components.
  - `img/`: High-resolution app icon and real application screenshots.

---

## Enabling GitHub Pages

To activate this site on GitHub:
1. Navigate to the repository settings: `https://github.com/caglarorhan/takeleavedo-page/settings/pages`
2. Under **Build and deployment > Source**, select **Deploy from a branch**.
3. Under **Branch**, select `main` and folder `/ (root)`.
4. Click **Save**. GitHub Pages will deploy within 1–2 minutes at:
   `https://caglarorhan.github.io/takeleavedo-page/`
