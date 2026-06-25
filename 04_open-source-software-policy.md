# Open Source Software Policy

**Product:** Master QR  
**Package:** com.qrcodereader.app  
**Effective Date:** [INSERT DATE]  
**Version:** 1.0

## Purpose
This policy governs the selection, inclusion, review, and distribution of open-source software used by the project. It explains how the team accepts external libraries, how license compatibility is evaluated, and how dependency provenance is documented for downstream users and store reviewers.

## Scope
It applies to Gradle dependencies, transitive packages, code snippets, documentation templates, build plugins, and any reused sample code. The policy is especially important for a project that uses modern Android tooling, camera components, barcode libraries, analytics SDKs, and security libraries.

## Operational Commitments
Every open-source component must be recorded, licensed, and reviewed before production release. The distribution package must preserve required notices and must not strip mandatory disclaimers. If a dependency introduces network behavior, tracking behavior, or data collection, that behavior must also be reflected in the relevant privacy and disclosure materials.

## Application to Master QR
Master QR’s build indicates a multi-library Android stack, so the open-source register should be tied to the actual dependency catalog rather than to generic assumptions. All inherited obligations must match the exact artifacts shipped in the release build, including optional plugins or disabled components that might later be enabled.

## Review and Governance
The policy should be updated whenever dependencies are added, removed, or version-bumped. A license review step should be embedded into release gating so that compliance is not deferred until after publication.
