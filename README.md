# MDMStatus:false / Management-Adjacent Daemon-Layer Anchor: Public Technical Package

## Status

Public preliminary technical review package.

This repository is intended for qualified digital forensics, incident response, mobile forensic, legal-technical, or security research review.

It is not a public accusation.

It is not an attribution claim.

It is not a malware conclusion.

It is not a spyware-family claim.

It is not a claim against any vendor, country, group, product, service, telecom provider, backup tool vendor, mobile app vendor, or individual.

This repository is a focused management-adjacent daemon-layer anchor supporting the broader Shadow Cloud working hypothesis.

The current broader framing is:

Shadow Cloud is a non-attribution forensic model for mobile-native LOTL-like Apple platform-state anomalies.

This means the review target is not a named actor.

The review target is whether normal Apple / iOS / iCloud / iMazing / Microsoft-app behavior can explain the observed clustering of:

- trust state
- restriction state
- management-adjacent daemon state
- backup state
- telecom context
- account-calendar-document state
- evidence-preservation behavior

For this repository, the narrow question is not whether classic visible MDM enrollment exists.

The narrow question is:

Can repeated management-adjacent daemon failures or clustering normally coexist with MDMStatus:false across multiple devices and dates?

In short:

Traditional LOTL:
Living off tools.

Shadow Cloud:
Living off Apple platform state.

This repository is one support anchor.

It is not the final reduced DFRWS core set.

The broader DFRWS-normalized model retains two March-April 2026 core review lines in the main repository after Normal-Hypothesis Reduction.

This repository remains supporting material for the MDMStatus:false / management-adjacent daemon-layer portion of that broader model.

---

## Core Observation

This repository documents a repeated cross-device artifact pattern observed across the devices internally labeled 15G and mini1.

The key observation is not that MDM enrollment is confirmed.

The key observation is that MDMStatus:false repeatedly appears on days where management-adjacent daemons and restriction-related services fail, crash, or cluster together.

Observed component families include:

- managedappdistributiond
- dmd
- ScreenTimeAgent
- ScreenTime
- ManagedSettings
- FamilyControls
- CommCenter
- Baseband
- TelephonyBaseband
- SFA / CKKS / CloudServices
- forceReset
- stacks
- JetsamEvent

Under the updated Shadow Cloud framing, this repository should be read as a management-adjacent daemon-layer seam review package within the broader mobile-native LOTL-like Apple platform-state anomaly model.

The narrow technical question is:

Can repeated management-adjacent daemon failures or clustering normally coexist with MDMStatus:false across multiple devices and dates?

The broader Shadow Cloud question is:

Can Apple platform state itself become the anomaly surface?

---

## Public Repository Boundary

Raw iOS logs are not included in this public repository.

Raw sysdiagnose archives are not included in this public repository.

Large debug archives are not included in this public repository.

Private account data, Apple ID material, BSSID details, OTP / financial data, screenshots, videos, and sensitive backup artifacts are not included in this public repository.

This public repository contains only:

- written technical summaries
- timeline summaries
- device matrix
- artifact indexes
- SHA256 references where available
- referenced log titles
- forensic review questions
- non-attribution statement
- raw artifact handling policy
- reviewer quick-start notes
- reproducibility / analysis scripts

The original raw logs, debug archives, sysdiagnose archives, and sensitive artifacts are preserved separately.

They may be provided later through a secure upload method, NDA, or evidence-handling procedure if required by a qualified reviewer.

---

## Non-Attribution Boundary

This repository does not assert:

- confirmed malware
- confirmed payload
- confirmed C2
- confirmed exploit chain
- confirmed spyware-family deployment
- confirmed MDM enrollment
- confirmed supervision
- confirmed configuration profile proving management
- confirmed actor attribution
- confirmed state attribution
- confirmed government attribution
- confirmed vendor attribution
- confirmed Apple attribution
- confirmed iMazing attribution
- confirmed Microsoft attribution
- confirmed Outlook causation
- confirmed telecom-provider attribution
- confirmed telecom compromise
- confirmed baseband compromise
- confirmed SIM compromise
- confirmed OTP interception
- confirmed attacker identity

Microsoft / Outlook / account-calendar-document surfaces, where mentioned, are possible future review surfaces or auxiliary correlative surfaces only.

They are not asserted as causes.

Subjective observations are not treated as standalone proof.

They may be used only as timestamp context for why the observer was interacting with, preserving, or reviewing the device.

The narrow purpose of this repository is to preserve and explain a repeated MDMStatus:false plus management-adjacent daemon failure-chain pattern for technical review.

---

## Devices

## 15G

Internal label: 15G

Physical class: iPhone 12 mini class device

Observed model identifier: iPhone13,1

Observed OS generation: iPhone OS 18.5 / 22F76

Important note:

15G is an internal Ghost / Apple ID lineage label.

It does not mean the physical device is an iPhone 15 Pro.

---

## mini1

Internal label: mini1

Physical class: iPhone 12 mini class device

Observed model identifier: iPhone13,1

Observed OS generation: iPhone OS 18.5 / 22F76

mini1 is included as a cross-device replication anchor.

---

## Reviewed Anchor Dates

Reviewed anchor dates include:

- 2026-03-16 / 15G
- 2026-03-17 / 15G
- 2026-03-18 / 15G
- 2026-03-23 / 15G
- 2026-03-24 / 15G
- 2026-04-03 / mini1
- 2026-05-05 / 15G
- 2026-05-21 / 15G

These dates are review anchors.

They are not conclusions.

They do not prove MDM enrollment.

They do not prove hidden management.

They do not prove telecom compromise.

They do not prove actor attribution.

---

## Core Technical Question

A simple interpretation would be:

MDMStatus:false means the device was not MDM-enrolled.

That may be correct.

However, the reviewed artifacts show a repeated structure that requires normal-first testing:

- MDMStatus:false appears repeatedly
- management-adjacent daemons fail or cluster on the same dates
- restriction-related components appear in the same artifact windows
- account-cloud components appear in the same broader context
- telecom / baseband components appear in the same broader context
- the pattern appears on more than one device

The technical question is:

Can this repeated structure be explained by normal iOS behavior, or does it represent a support-invisible, policy-adjacent, account / cloud, management-layer, or platform-state anomaly requiring formal forensic review?

Under the mobile-native LOTL-like Apple platform-state framing, the issue is not whether a malicious tool is visible.

The issue is whether normal-looking platform states and daemon behaviors cluster in a way that may become the anomaly surface.

---

## Normal-Hypothesis Reduction

Ordinary explanations must be tested first.

The following are treated as normal-hypothesis candidates unless stronger cross-layer coupling remains:

- ordinary iOS crash clustering
- ordinary managedappdistributiond behavior
- ordinary dmd behavior
- ordinary ScreenTimeAgent behavior
- ordinary ManagedSettings behavior
- ordinary ScreenTime / Family Sharing behavior
- ordinary local restriction settings
- ordinary MDMStatus:false behavior
- visible-management absence under normal conditions
- ordinary SFA / CKKS / CloudServices behavior
- ordinary CommCenter / Baseband behavior
- ordinary JetsamEvent or resource-pressure behavior
- ordinary reboot / forceReset behavior
- ordinary app update or App Store distribution behavior
- ordinary storage pressure
- broad keyword hits
- weak temporal joins
- isolated device failure
- local PC / USB / storage explanations
- Microsoft app residue without cross-layer coupling

The purpose is not to prove a malicious explanation.

The purpose is to test whether normal Apple / iOS behavior can reproduce the full coupled structure.

---

## Management-Adjacent Daemon-Layer Seam Definition

A management-adjacent daemon-layer seam is a review point where visible management state appears absent or false while management-adjacent, restriction-related, account-cloud, telecom, or preservation-related components cluster together.

Relevant management-adjacent components include:

- managedappdistributiond
- dmd
- ScreenTimeAgent
- ScreenTime
- ManagedSettings
- FamilyControls
- MDMStatus:false
- IsSupervised:false
- visible profile absence
- configuration profile absence

Relevant adjacent layers include:

- Apple ID trust state
- iCloud trust state
- SFA / CKKS / CloudServices
- CommCenter
- Baseband
- TelephonyBaseband
- SIM context
- JetsamEvent
- forceReset
- stacks
- storage pressure
- evidence-preservation behavior

The review target is not:

Does MDMStatus:false prove hidden MDM?

The review target is:

Can MDMStatus:false normally coexist with the observed daemon-layer and restriction-layer clustering across multiple dates and devices?

---

## High-Level Timeline

## 2026-03-16 to 2026-03-18 / 15G

Cluster 1.

Observed structure:

- managedappdistributiond crash
- MDMStatus:false
- dmd crash
- forceReset context
- ScreenTime / ManagedSettings context
- SFA family context

Interpretation:

This cluster is treated as an early repeated 15G management-adjacent daemon / restriction-state review window.

It does not prove MDM enrollment.

It raises the question of whether normal iOS behavior can explain MDMStatus:false appearing together with management-adjacent daemon failures and restriction-state context.

Review question:

Can ordinary iOS crash clustering, App Store distribution behavior, ScreenTime / ManagedSettings behavior, SFA / CKKS / CloudServices behavior, and forceReset context explain this cluster?

---

## 2026-03-23 to 2026-03-24 / 15G

Cluster 2.

Observed structure:

- MDMStatus:false
- managedappdistributiond repeated crashes
- forceReset artifacts
- ScreenTime / ManagedSettings context
- SFA / CKKS / CloudServices context
- CommCenter / Baseband context

Interpretation:

This cluster is treated as a stronger 15G cross-layer seam window because management-adjacent daemon activity, restriction-state context, account-cloud context, and telecom / baseband context appear in the same broader period.

It does not prove telecom compromise.

It does not prove Apple attribution.

It is a review target.

Review question:

Can ordinary iOS, account-cloud, restriction-state, resource-pressure, and telecom/baseband behavior explain this convergence?

---

## 2026-04-03 / mini1

Cross-device anchor.

Observed structure:

- MDMStatus:false
- managedappdistributiond crashes
- ScreenTimeAgent crash
- Analytics with CommCenter / Baseband / SFA context
- stacks containing dmd / ScreenTime / ManagedSettings / CommCenter / Baseband
- SFA / CKKS / CloudServices later the same day

Interpretation:

This date is important because the pattern appears on mini1, not only 15G.

The value is cross-device replication of a management-adjacent daemon-layer seam.

It does not prove a shared attacker.

It supports a review question about whether the same platform-state pattern can appear across multiple devices under normal conditions.

Review question:

Can ordinary iOS behavior reproduce MDMStatus:false plus management-adjacent daemon clustering across more than one device under the reviewed conditions?

---

## 2026-05-05 / 15G

Follow-up anchor.

Observed structure:

- MDMStatus:false
- managedappdistributiond crash cluster
- ScreenTimeAgent crash cluster
- CommCenter / Baseband / TelephonyBaseband context in Analytics
- BasebandPowerCycle context
- Preferences crash

Interpretation:

This date is treated as a follow-up 15G anchor linking management-adjacent daemon activity, ScreenTimeAgent, telecom / baseband context, and Preferences crash behavior.

It does not prove baseband compromise.

It does not prove a proximity attack.

It raises a condition-review question.

Review question:

Can ordinary iOS crash behavior, telecom/baseband behavior, Preferences behavior, and ScreenTimeAgent behavior explain this cluster?

---

## 2026-05-21 / 15G

Telecom / restriction crash anchor.

Observed structure:

- MDMStatus:false
- CommCenter crash
- ScreenTimeAgent crashes
- FaceTime service crash
- contactsd crash
- JetsamEvent containing managedappdistributiond / dmd / ScreenTime / ManagedSettings / SFA / CommCenter
- SFA / CKKS / CloudServices in morning and evening windows

Interpretation:

This date is treated as a stronger telecom / restriction / daemon-layer convergence anchor.

It connects:

- MDMStatus:false
- CommCenter
- ScreenTimeAgent
- FaceTime service
- contactsd
- managedappdistributiond
- dmd
- ManagedSettings
- SFA / CKKS / CloudServices

The review question is whether this is ordinary iOS crash clustering, resource pressure, account-cloud behavior, telecom behavior, or a platform-state seam requiring deeper review.

---

## Cross-Device Interpretation

The value of this repository is not any single crash.

The value is the repeated structure:

MDMStatus:false
+
management-adjacent daemon failures
+
restriction-state services
+
account-cloud services
+
telecom / baseband context
+
resource or crash windows
+
more than one device

The technical question is:

Can normal Apple / iOS behavior reproduce this repeated cross-device pattern?

If yes, the hypothesis should be weakened.

If no, the pattern may represent a management-adjacent daemon-layer seam within the broader mobile-native LOTL-like Apple platform-state anomaly model.

---

## Relationship to Main Shadow Cloud Repository

This repository is a focused support anchor package.

It should be read as supporting material for the broader Shadow Cloud model, not as a standalone conclusion.

The broader model asks whether normal Apple / iOS / iCloud / iMazing / Microsoft-app behavior can explain a long-term, cross-device structure involving:

- trust state
- restriction state
- management-adjacent daemon state
- backup state
- account-calendar-document state
- telecom context
- proximity context
- evidence-preservation behavior

This repository focuses only on the MDMStatus:false and management-adjacent daemon failure-chain portion of that broader model.

---

## Relationship to DFRWS-Normalized Core Lines

The broader DFRWS-normalized Shadow Cloud model retains two March-April 2026 core review lines after Normal-Hypothesis Reduction:

1. 2026-03-15 to 2026-03-21
   Centered on 2026-03-17 to 2026-03-19

2. 2026-03-29 to 2026-04-04
   Centered on 2026-03-31 to 2026-04-02

This support repository is not the final reduced core set.

It is a narrower management-adjacent daemon-layer anchor that supports the MDMStatus:false / restriction-state / daemon-clustering branch of the broader model.

The value of this repository is not that it proves Shadow Cloud.

The value is that it preserves a focused review sequence for testing whether management-adjacent daemon clustering can coexist with MDMStatus:false under ordinary iOS behavior.

---

## Relationship to Visible MDM

This repository does not claim classic visible MDM enrollment.

This repository does not claim confirmed supervision.

This repository does not claim that a configuration profile proving management was found.

The point is the mismatch:

- visible management state appears absent or false
- MDMStatus:false appears
- management-adjacent daemons and restriction-related components fail or cluster repeatedly

The review target is not:

Is there a visible MDM profile?

The review target is:

Can visible MDM absence normally coexist with the observed daemon-layer and restriction-layer clustering?

---

## Relationship to Telecom / Baseband Context

CommCenter, Baseband, TelephonyBaseband, SIM, OTP, and related telecom artifacts are treated only as context and review targets.

This repository does not claim:

- confirmed telecom compromise
- confirmed baseband compromise
- confirmed SIM compromise
- confirmed OTP interception
- telecom-provider attribution

The review question is whether telecom / baseband events are independent normal events, or whether they align with management-adjacent daemon state, restriction state, account-cloud state, or evidence-preservation windows.

---

## Relationship to Microsoft / Outlook Surfaces

Microsoft / Outlook / account-calendar-document surfaces are not central to this anchor repository.

They are mentioned only because the broader Shadow Cloud model treats them as possible future review surfaces.

This repository does not claim:

- Microsoft attribution
- Outlook causation
- Microsoft app causation
- Microsoft service causation
- Microsoft mobile apps directly modified Manifest.db
- Microsoft mobile apps directly modified Apple backup state
- Microsoft mobile apps directly modified iOS backup services
- Microsoft surfaces caused management-adjacent daemon behavior

The safe interpretation is:

Microsoft / Outlook surfaces, if later reviewed in preserved artifacts, should be evaluated as possible account-calendar-document-policy surfaces, not assumed causes.

---

## Strengthening Conditions

This MDMStatus:false / management-adjacent daemon-layer anchor is strengthened if qualified review shows that:

- repeated MDMStatus:false plus management-adjacent daemon failures is not expected under normal iOS behavior
- managedappdistributiond / dmd / ScreenTimeAgent / ManagedSettings clustering is abnormal without visible management indicators
- restriction-state behavior cannot be explained by user settings, Family Sharing, or local ScreenTime configuration
- telecom / baseband context aligns with restriction-state or account-cloud changes
- SFA / CKKS / CloudServices context aligns with management-adjacent daemon clustering
- the pattern appears across 15G and mini1 but not clean comparison devices
- crash / resource-pressure explanations do not reproduce the full structure
- the pattern aligns with broader Shadow Cloud backup, trust-state, and evidence-preservation observations

---

## Weakening or Falsification Conditions

This MDMStatus:false / management-adjacent daemon-layer anchor is weakened if qualified review shows that:

- MDMStatus:false plus managedappdistributiond crashes is ordinary and documented behavior
- dmd / ScreenTimeAgent / ManagedSettings clustering is normal under reviewed conditions
- all restriction-state context is explained by user settings, Family Sharing, or local ScreenTime behavior
- CommCenter / Baseband context is independent and ordinary
- SFA / CKKS / CloudServices context is ordinary and unrelated
- crash clustering is caused by storage pressure, OS version behavior, or local device state
- the same pattern is reproduced on clean controls
- cross-device recurrence disappears after normal controls are applied
- subjective observations are the only remaining support

If these conditions are met, this anchor should be weakened or rejected.

---

## Reviewer Questions

A qualified reviewer should ask:

1. Can repeated MDMStatus:false plus management-adjacent daemon failures be reproduced under normal iOS behavior?
2. Can managedappdistributiond / dmd / ScreenTimeAgent / ManagedSettings clustering occur normally without visible MDM or supervision?
3. Can the repeated structure be explained by ordinary ScreenTime, Family Sharing, user configuration, or local restriction settings?
4. Can SFA / CKKS / CloudServices context explain the account-cloud side of the cluster?
5. Can CommCenter / Baseband / TelephonyBaseband context be explained as independent normal telecom behavior?
6. Can resource pressure, JetsamEvent, stacks, or crash clustering explain the pattern without invoking a broader platform-state anomaly?
7. Can the same pattern be reproduced on clean comparison devices under similar OS conditions?
8. Does the cross-device recurrence between 15G and mini1 remain after normal explanations are applied?
9. Does the pattern align with broader Shadow Cloud trust-state, restriction-state, backup-state, telecom-state, and evidence-preservation observations?
10. If normal Apple / iOS behavior explains the pattern, what reproducible test demonstrates it?

---

## Practical Takeaway

This repository does not ask reviewers to accept the Shadow Cloud hypothesis.

It asks reviewers to test whether a repeated MDMStatus:false plus management-adjacent daemon failure-chain pattern can be reproduced through normal Apple / iOS behavior.

The final position is:

MDMStatus:false is context, not proof of hidden management.

Management-adjacent daemon failures are review targets, not conclusions.

Telecom/baseband context is review context, not compromise proof.

This repository is a supporting daemon-layer anchor, not the final reduced core set.

If normal behavior explains the sequence, this anchor should be weakened.

If normal behavior does not explain the sequence, this repository may represent a focused management-adjacent daemon-layer seam requiring deeper mobile forensic review.
