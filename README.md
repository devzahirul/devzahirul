# Md. Zahirul Islam — Senior Mobile Engineer (iOS · Android)

I've spent 10 years shipping native mobile apps. I take products from an empty repo to the App Store and Google Play, and I own the architecture, testing, CI/CD and release work along the way.
Currently at **[@UgoRound](https://github.com/UgoRound)** · Dhaka, BD · Open to senior / lead mobile roles · [LinkedIn](https://www.linkedin.com/in/islam-md-zahirul-82183889/)

**iOS:** Swift 6 · SwiftUI · UIKit · Swift Concurrency · Combine · Core Data / SwiftData · SPM modularization · WidgetKit · Extensions · StoreKit
**Android:** Kotlin · Jetpack Compose · Coroutines / Flow · Hilt · Room · WorkManager · multi-module Gradle
**Cross-platform:** Flutter
**Quality & delivery:** XCTest / swift-testing · JUnit · snapshot & UI tests · TDD · GitHub Actions · Fastlane · SwiftLint / ktlint

---

## What I engineer

Each of these repos has a README, tests and CI. They show how I design systems, not only screens.

| Project | Platforms | What it demonstrates |
|---|---|---|
| **[NovaShop: Offline-first E-commerce](https://github.com/devzahirul/NovaShop-iOS)** | iOS · Supabase | 18-module SwiftUI app in Swift 6 strict concurrency. Local-first cart with state-based sync and reconciliation, a transactional server checkout (Row Level Security, idempotency keys), and launch, CPU and leak profiling on device with Instruments. 115 tests |
| **[RTLS: Offline-first Location Sync SDK](https://github.com/devzahirul/Offline_first_location_sync_Mobile)** | iOS · Android · Flutter · RN | Modular telemetry SDK: GPS collection, an offline queue that loses no data, WebSocket real-time sync, pick-only-what-you-need modules |
| **[SwiftHilt](https://github.com/devzahirul/swift_hilt)** | Swift | Dependency injection library that is DAG-aware and inspired by Hilt: scopes, graph validation, test overrides |
| **[AsyncSwiftyNetworking](https://github.com/devzahirul/AsyncSwiftyNetworking)** | Swift | async/await networking layer: typed endpoints, retries, interceptors, fully tested |
| **[PlaceAlertMe](https://github.com/devzahirul/PlaceAlertMe)** | iOS | Background geofencing that still delivers alerts after the app is killed |
| **[TDD High-Performance E-commerce](https://github.com/devzahirul/TDDHighPerformance-ecommerceSwiftui)** | iOS | Test-driven SwiftUI with a focus on rendering performance |
| **[Attendance HR (Android)](https://github.com/devzahirul/AttendenceHRAndroid)** | Android | Compose + clean architecture, multi-module, CI |

---

## Open-source contributions

These PRs were merged upstream after review by the maintainers.

**[Firefox for iOS](https://github.com/mozilla-mobile/firefox-ios)** (Mozilla)
- [#34675](https://github.com/mozilla-mobile/firefox-ios/pull/34675) **Memory leak:** fixed a `BoolSetting` retain cycle that leaked `AppSettingsTableViewController`
- [#34569](https://github.com/mozilla-mobile/firefox-ios/pull/34569) **Widgets:** the widget now waits for tab restoration before it closes private tabs, which fixes a state race
- [#34809](https://github.com/mozilla-mobile/firefox-ios/pull/34809) **Dead code:** removed unused `TabManager` code that Periphery flagged
- [#34568](https://github.com/mozilla-mobile/firefox-ios/pull/34568) **Logging:** separated how fatal and non-fatal logs are reported
- [#34553](https://github.com/mozilla-mobile/firefox-ios/pull/34553) **Tests:** telemetry tests now compare objects by identity (`===`) instead of equality

**[Kingfisher](https://github.com/onevcat/Kingfisher)** (Swift's most popular image downloading and caching library)
- [#2539](https://github.com/onevcat/Kingfisher/pull/2539) **Concurrency:** fixed a data race in `SessionDataTask.forceCancel()`
- [#2541](https://github.com/onevcat/Kingfisher/pull/2541) **Concurrency:** fixed a data race on `RetrievingContext.propagationErrors`
- [#2561](https://github.com/onevcat/Kingfisher/pull/2561) **Memory:** the image view is now released while its download is still in progress
- [#2556](https://github.com/onevcat/Kingfisher/pull/2556) **Performance:** disk cache lookups now take a single metadata syscall
- [#2540](https://github.com/onevcat/Kingfisher/pull/2540) **Bug fix:** disk caching now works when the image URL path contains `@`

---

## Shipped to production

Apps I built and shipped for clients and employers:

| App | Highlights | Link |
|---|---|---|
| **AISocial – AI Assistant** | LLM chat, PDF summarization, subscriptions, Share Extension, Widgets, Firebase, modular SPM, unit/UI/snapshot tests, CI | [App Store](https://apps.apple.com/us/app/aisocial-ai-assistant-ai-chat/id6446788161) |
| **Alloy Sports – Betting Companion** | Subscriptions, modular architecture, snapshot tests, GitHub Actions CI | [App Store](https://apps.apple.com/au/app/alloy-sports-betting-companion/id1624936582) |
| **Davi & Dani – Wholesale Shop** | E-commerce, payments, offline catalog (Core Data) | [App Store](https://apps.apple.com/qa/app/davi-and-dani-wholesale-shop/id6444211395) |
| **Adora Los Angeles** | E-commerce, payments | [App Store](https://apps.apple.com/us/app/adora-los-angeles/id6470774390) |
| **Mello USA** | E-commerce, Stripe | [App Store](https://apps.apple.com/us/app/mello-usa/id6451467071) |
| **StylePick** | E-commerce, Stripe | — |
| **Wholesale Scan** | Barcode/QR scanning, business-card OCR with Gemini, PDF printing, server sync | Internal |

<details>
<summary>📸 Screenshots</summary>

<p>
<img src="https://is1-ssl.mzstatic.com/image/thumb/PurpleVideo112/v4/58/84/1e/58841ef6-bd7d-9c1c-46ce-1cce25efe927/Jobd16859f6-6466-4a14-a103-55527db39fac-163970506-PreviewImage_preview_image_nonvideo_sdr-Time1709367678631.png/230x0w.webp" width="180">
<img src="https://is1-ssl.mzstatic.com/image/thumb/PurpleSource126/v4/0a/1d/90/0a1d9073-90b7-900f-5aa9-065bffea3a23/7ddbdebb-20b4-4edb-8767-816a40499498_Fanalysts_Inc_Alloy_Sports_iOS_US_Screenshot_Mocks_230821_01.png/230x0w.webp" width="180">
<img src="https://is1-ssl.mzstatic.com/image/thumb/PurpleSource126/v4/fb/ad/2b/fbad2b71-3427-9635-2b58-00cdf928a241/a33039bd-dd5c-4c9d-9577-3d7d67bb9284_Simulator_Screenshot_-_iPhone_11_Pro_Max_-_2023-07-04_at_15.27.36.png/230x0w.webp" width="180">
<img src="https://is1-ssl.mzstatic.com/image/thumb/PurpleSource116/v4/8d/12/80/8d128066-736d-5ddf-6dca-8f0cc41d4236/2db89795-622d-4562-9669-c45630716553_Simulator_Screenshot_-_iPhone_14_Pro_Max_-_2023-12-26_at_16.00.03.png/230x0w.webp" width="180">
<img src="https://is1-ssl.mzstatic.com/image/thumb/PurpleSource116/v4/3f/b8/05/3fb8052b-fa97-a0eb-7436-a2a751c22d8d/44123773-82b4-4751-b9f2-b84b81613b70_1.png/230x0w.webp" width="180">
<img src="https://github.com/devzahirul/devzahirul/assets/10805452/dee4fb3b-9694-4eb3-8b66-c7dc5ca5f573" width="180">
<img src="https://github.com/devzahirul/devzahirul/assets/10805452/819a3fed-5e39-44fc-a29f-69eadd548200" width="180">
</p>
</details>

---

## How I work

- **Architecture first:** modular (SPM / Gradle multi-module), unidirectional data flow, clear domain boundaries, and DI that stays testable.
- **Tests I trust:** TDD where it pays off, plus snapshot tests for UI and CI that gates every PR.
- **Background and offline:** geofencing, background location, sync queues that survive process death and a bad network.
- **Shipping:** I own releases (signing, TestFlight / Play tracks, phased rollouts, crash monitoring).
- **Sharing:** knowledge and reusable libraries (SwiftHilt, AsyncSwiftyNetworking, [Swift design patterns](https://github.com/devzahirul/oop_design_patterns_swift)).

📫 Reach me on [LinkedIn](https://www.linkedin.com/in/islam-md-zahirul-82183889/)
