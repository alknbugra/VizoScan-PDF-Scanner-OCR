# VizoScan — Free PDF Scanner & Document OCR App for Android

> **Scan documents. Create PDFs. Share instantly.**  
> A professional document scanner built with Flutter — free and open source.

[![Platform](https://img.shields.io/badge/Platform-Android-green.svg)](https://www.android.com)
[![Flutter](https://img.shields.io/badge/Flutter-3.x-02569B?logo=flutter)](https://flutter.dev)
[![License](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![Version](https://img.shields.io/badge/Version-1.1.4-orange.svg)](https://github.com/alknbugra/VizoScan-PDF-Scanner-OCR/releases)

---

## What Is VizoScan?

**VizoScan** is a free Android app that turns your phone into a powerful document scanner.  
Capture documents, ID cards, and receipts — then instantly compile them into a PDF and share with one tap.

Built with **Flutter** + **Material Design 3**, VizoScan delivers a clean and modern experience on any Android device.

---

## Features

| Feature | Description |
|---|---|
| **Document Scanning** | Camera-based scanning with automatic edge detection |
| **ID Card Scanning** | Scan front & back of ID cards in a single document |
| **PDF Generation** | Combine multiple pages into one PDF, entirely on-device |
| **One-Tap Sharing** | Export PDFs via WhatsApp, email, Google Drive, and more |
| **Document Viewer** | Page-swipe viewer with page indicator (e.g. "Page 1 of 3") |
| **Delete Confirmation** | Safety dialog prevents accidental document deletion |
| **Dark / Light Mode** | Follows Android system theme via Material You |
| **Material Design 3** | Built with Flutter + MD3 for a polished, accessible UI |
| **AdMob Integration** | Banner + interstitial ads (every 2nd share) |

---

## Screenshots

> *(Add screenshots here — drag and drop images into this section)*

---

## Getting Started

### Prerequisites

- Flutter SDK ≥ 3.0
- Android SDK ≥ 21 (Android 5.0 Lollipop)
- Java 17+

### Run Locally

```bash
git clone https://github.com/alknbugra/VizoScan-PDF-Scanner-OCR.git
cd VizoScan-PDF-Scanner-OCR
flutter pub get
flutter run
```

### Build Release APK

```bash
flutter build apk --release
```

---

## Project Structure

```
lib/
├── main.dart                  # App entry point
├── screens/
│   ├── home_screen.dart       # Document list + banner ad
│   └── viewer_screen.dart     # Page swipe viewer
├── services/
│   └── pdf_service.dart       # PDF generation & sharing
└── widgets/
    └── ad_banner.dart         # AdMob banner widget
```

---

## Tech Stack

- **Framework:** Flutter 3.x (Dart)
- **UI:** Material Design 3
- **Document Scanning:** `cunning_document_scanner`
- **PDF Generation:** `pdf` + `path_provider`
- **Monetization:** Google Mobile Ads (AdMob)
- **Splash Screen:** `flutter_native_splash`

---

## Roadmap

- [ ] OCR text extraction from scanned documents
- [ ] Cloud backup (Google Drive integration)
- [ ] Batch rename & organize documents
- [ ] iOS support

---

## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

---

## License

[MIT](LICENSE)

---

## Download

**Available on Google Play:**  
[https://play.google.com/store/apps/details?id=com.bugraalkin.myapp](https://play.google.com/store/apps/details?id=com.bugraalkin.myapp)

**Landing Page:**  
[https://alknbugra.github.io/VizoScan-PDF-Scanner-OCR/](https://alknbugra.github.io/VizoScan-PDF-Scanner-OCR/)
