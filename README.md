### ScanarX — Privacy‑first Receipt Scanner

**ScanarX** is a lightweight, local‑first receipt scanner and analytics app for iPhone and iPad. Scan receipts with the device camera, run on‑device OCR and parsing, categorize expenses, and export CSV/PDF — all stored locally by default.

---

### Features
- **On‑device scanning & OCR** — document camera, auto‑crop, perspective correction, and local OCR.
- **Deterministic parsing** — extracts totals, dates, merchant names, taxes, and payment methods.
- **Category analytics** — donut charts, category rows, monthly/yearly pickers, and per‑category exports.
- **Flexible exports** — CSV for periods or categories, PDF per receipt, and share image + OCR text.
- **Local‑first privacy** — scans, OCR results, parsed fields, and exports remain on the device unless you explicitly share or export.
- **Optional on‑device AI** — Apple Intelligence classification when available and enabled (device dependent).
- **Widget support** — optional App Group for a small shared cache between app and widget.
- **Robust settings** — default currency, default category, export month selector, and full data clear option.
- **Accessibility** — VoiceOver labels and dynamic type support.
- **Simple monetization** — one‑time paid app (no subscriptions required).

---

### Download & Install
**App Store**  
ScanarX is distributed as a one‑time purchase on the App Store. Set your bundle ID and App Store metadata as usual:

- **Bundle ID:** `com.yourcompany.scanarx`  
- **Pricing:** Paid one‑time (set price tier in App Store Connect)  
- **Required Info.plist keys:** `NSCameraUsageDescription`, `NSPhotoLibraryUsageDescription`, `NSPhotoLibraryAddUsageDescription`, `NSMicrophoneUsageDescription` (if voice notes are supported)

**Testing**  
- Test scanning and document camera features on a real device.  
- Use sandbox testers only if you later enable In‑App Purchase for optional unlocks.

---

### Privacy & Terms
- **Default behavior:** All data is stored locally on the device. No account is required.  
- **Optional network features:** Exchange‑rate lookups or cloud backup are strictly opt‑in and clearly disclosed.  
- **Data deletion:** `Settings → Data → Clear All Receipts` permanently deletes local data after confirmation.  
- **Privacy policy:** Provide a public URL in App Store Connect and link it inside the app (Settings → About → Privacy).  
- **Terms of Use:** Include a Terms of Use (EULA) link inside the app (Settings → About → Terms). Example: Apple Standard EULA `https://www.apple.com/legal/internet-services/itunes/dev/stdeula/`.

---

### Languages (localized)
ScanarX is translated into the following languages. Flags are shown as a quick visual reference.

| Flag | Language |
|---:|:---|
| 🇬🇧 / 🇺🇸 | English |
| 🇦🇪 | Arabic (United Arab Emirates) |
| 🇧🇬 | Bulgarian |
| 🇨🇳 | Chinese (Simplified) |
| 🇹🇼 | Chinese (Traditional) |
| 🇭🇷 | Croatian |
| 🇨🇿 | Czech |
| 🇩🇰 | Danish |
| 🇳🇱 | Dutch |
| 🇫🇮 | Finnish |
| 🇫🇷 | French |
| 🇨🇦 | French (Canada) |
| 🇩🇪 | German |
| 🇬🇷 | Greek |
| 🇮🇳 | Hindi |
| 🇭🇺 | Hungarian |
| 🇮🇩 | Indonesian |
| 🇮🇹 | Italian |
| 🇯🇵 | Japanese |
| 🇰🇷 | Korean |
| 🇱🇹 | Lithuanian |
| 🇵🇱 | Polish |
| 🇧🇷 | Portuguese (Brazil) |
| 🇵🇹 | Portuguese (Portugal) |
| 🇷🇴 | Romanian |
| 🇷🇺 | Russian |
| 🇸🇮 | Slovenian |
| 🇪🇸 | Spanish |
| 🇺🇸 | Spanish (United States) |
| 🇸🇪 | Swedish |
| 🇹🇷 | Turkish |
| 🇺🇦 | Ukrainian |
| 🇻🇳 | Vietnamese |

> If you want flags as small PNG/SVG assets for the homepage, I can provide a recommended set of filenames and sizes to include in your site assets.

---

### Support & Contact
- **Support email:** `support@yourdomain.com`  
- **Privacy requests:** `privacy@yourdomain.com`  
- **Feature requests / ideas:** `ideas@yourdomain.com`  
- **In‑app links:** Settings → About → Help, Privacy, Terms of Use, Support

**Quick troubleshooting tips**
- Camera permission: `Settings → Privacy → Camera`  
- Photo library: `Settings → Privacy → Photos`  
- AI features: require device support and iOS model downloads (iOS 26 for FoundationModels)

---

### Contributing & License
- Fork the repo, create a feature branch, add tests for parsing and export, and open a pull request with screenshots and a clear description.  
- **License:** Add your chosen license (e.g., MIT) and copyright notice.

---
