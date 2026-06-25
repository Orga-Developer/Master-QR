# Permissions Usage and Sensitive Permissions Disclosure

**Product:** Master QR  
**Package:** com.qrcodereader.app  
**Effective Date:** [INSERT DATE]  
**Version:** 1.0

## Purpose
This policy explains why the application requests each Android permission, how the permission is used, and whether the permission is essential to the product’s core function. The goal is to reduce user confusion and to prevent unnecessary collection of sensitive data.

## Scope
It applies to runtime prompts, manifest declarations, onboarding screens, support articles, and store disclosures. The policy should clearly state which permissions are optional, which are required, and what functionality breaks or degrades when the permission is denied.

## Operational Commitments
Any sensitive permission should be justified narrowly and in context. The explanation should not rely on vague claims such as convenience or optimization. Instead, it should specify the user action that triggers the permission and the exact operation that is performed once access is granted.

## Application to Master QR
Master QR’s manifest includes camera access, which is directly tied to QR scanning. The app should avoid presenting this permission as a general device entitlement; it should be framed as a narrowly tailored input channel for decoding codes locally on the device.

## Review and Governance
The policy should be kept consistent with onboarding UX and store listings. If future builds introduce location, contacts, microphone, or biometric features, this notice must be revised before rollout.
