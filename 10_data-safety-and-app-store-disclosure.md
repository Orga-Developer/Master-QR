# Data Safety and App Store Disclosure

**Product:** Master QR  
**Package:** com.qrcodereader.app  
**Effective Date:** [INSERT DATE]  
**Version:** 1.0

## Purpose
This document describes the data categories that the app accesses, the purposes for which those categories are used, and the protection measures that accompany collection or transmission. It is intended to mirror store-review disclosures and to reduce the risk of mismatch between code behavior and catalog statements.

## Scope
It applies to store questionnaires, privacy labels, in-app notices, and public-facing compliance pages. The disclosure should classify whether data is collected, shared, processed temporarily, or retained, and it should explain whether the information is user-provided, device-generated, or observed through SDK instrumentation.

## Operational Commitments
All entries should be grounded in the actual build. If a permission is declared but not functionally used, the disclosure should still avoid overstating behavior. If an SDK collects advertising identifiers, consent signals, or analytics events, that collection must be reflected accurately and in plain language.

## Application to Master QR
Master QR requests camera access and internet access, uses AdMob and Firebase-related components, and retains local scan history. The data safety summary should therefore separate the camera scanning path from analytics and advertising paths so reviewers can see what is essential to the product and what is ancillary.

## Review and Governance
The disclosure should be refreshed each time a permission, SDK, or major feature is added or removed. A documented review checkpoint should sit between code freeze and release signing.
