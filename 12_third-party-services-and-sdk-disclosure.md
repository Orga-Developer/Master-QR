# Third-Party Services and SDK Disclosure

**Product:** Master QR  
**Package:** com.qrcodereader.app  
**Effective Date:** [INSERT DATE]  
**Version:** 1.0

## Purpose
This disclosure identifies third-party software development kits, cloud services, analytics platforms, ad networks, and other external processors that may receive data from the application. Its purpose is to make the supply chain visible so that users and reviewers can assess risk and scope.

## Scope
It applies to embedded SDKs, network calls, remote configuration tools, crash reporting, measurement libraries, and consent-management frameworks. The disclosure should note whether a service is always active, conditionally active, or dormant until the user enables a related feature.

## Operational Commitments
The record should include the service name, the type of data exposed, the direction of transfer, and the control path that users can exercise, such as opting out, resetting identifiers, or changing consent preferences. Blanket descriptions are insufficient when the SDK behavior is materially different across regions.

## Application to Master QR
Master QR’s build references AdMob, Firebase Analytics, UMP, barcode tooling, and other libraries. The disclosure should therefore be written as a real integration inventory rather than as a generic template, with a revision history tied to actual Gradle dependencies.

## Review and Governance
The disclosure should be revalidated on every dependency upgrade and every new country rollout. A stale SDK inventory is one of the most common causes of privacy and store-review inconsistency.
