# Cookie and Local Storage Policy

**Product:** Master QR  
**Package:** com.qrcodereader.app  
**Effective Date:** [INSERT DATE]  
**Version:** 1.0

## Purpose
This policy explains how the application and its companion web surfaces use cookies, local storage, shared preferences, database records, and similar persistence technologies. Its purpose is to clarify that not all persistent storage is “tracking,” while still acknowledging the privacy implications of saved state.

## Scope
It applies to websites, embedded web views, consent pages, help centers, and any offline storage mechanisms used by the mobile application. The policy should identify what is stored, how long it remains, whether it is user-controlled, and whether it can be reset through settings or by clearing app data.

## Operational Commitments
Local storage should be described in functional terms rather than in abstract technical jargon. For example, the policy can explain that scan history, language preferences, or consent choices are stored so the app can remember user decisions and operate consistently across sessions.

## Application to Master QR
Master QR’s Room database and shared-preference features make local persistence part of the product experience. The policy should distinguish those records from cookies used by web pages or ad/analytics sessions that may be managed by third-party SDKs.

## Review and Governance
The document should be reviewed when storage classes change, when offline capabilities are added, or when the app begins to synchronize preferences across devices. Any browser-based feature should trigger a separate review of cookie disclosures.
