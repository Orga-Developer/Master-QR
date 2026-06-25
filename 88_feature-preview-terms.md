# Feature Preview Terms

## Purpose
These terms govern preview functionality such as experimental export formats, enhanced QR rendering, and future localization features. They explain that preview functionality is non-final, may be withdrawn, and may not reflect production-grade guarantees. The document is written for the Master QR project, which combines QR scanning, QR generation, scan history persistence, language localization, consent and advertising surfaces, share/export helpers, and store-ready distribution scaffolding and ships through Google Play, Huawei AppGallery, and other multi-store release channels. The policy or register is intentionally scoped to the actual codebase, especially the camera permission flow, local scan history, QR generation screens, language switching layer, and export mechanism that copies the bundled legal archive to user-selected storage.

## Scope and Operational Context
The scope covers the Android application, its release artifacts, the legal documentation bundle, the distribution workflow, and the third-party services that are intentionally enabled in the build, including CameraX, Room, Jetpack Compose, FileProvider-based exports, AdMob, Firebase Analytics, and the permissions flow centered on CAMERA and INTERNET. Where a control is not implemented in code, this document treats it as a governance obligation rather than pretending the app already performs that control. That distinction matters for reviewers, platform auditors, and enterprise procurement teams.

## Standards of Conduct
All actions governed by this document must be executed with transparency, necessity, and traceability. Users should never be surprised by data practices, permission requests, or monetization choices. The app's design already favors runtime-permission minimization, in-context disclosure, data deletion expectations, and transparent consent handling; this document reinforces that design by requiring contextual explanations, minimal collection, and narrowly tailored retention. Any expansion into new SDKs, telemetry channels, AI services, or partner integrations must be reviewed before release.

## Implementation Notes
The document should be paired with the current manifest, build configuration, privacy notices, store disclosures, and release checklist. Because the app includes a modular legal export flow and a multi-language interface, the text also anticipates future regional packaging and translated disclosures. For compliance work, this file can be treated as an executive-control layer that sits above lower-level technical policies, helping the project remain coherent as it grows.

## Review and Revision
Each revision must be synchronized with code changes, store policy updates, and legal counsel feedback. If the app adds accounts, cloud sync, contact access, biometrics, or new analytics identifiers, the scope must be expanded immediately. Until then, the policy remains a disciplined reflection of a camera-first, QR-centric, low-data Android application operating across multiple marketplaces and jurisdictions.
