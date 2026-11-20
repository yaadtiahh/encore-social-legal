# Encore Social — Privacy Policy

**Effective date:** 20 November 2026  
**Last updated:** 20 November 2026

> **Publication checklist:** This draft reflects the currently described Encore Social setup: a locally operated content-management/publishing workflow, OAuth connections to social platforms, local credential storage in macOS Keychain, and local project records. Verify every statement against the actual code and deployment before publishing. Replace all bracketed placeholders. This document is not legal advice.

## 1. Who is responsible for your data?

The controller responsible for personal data processed through Encore Social is:

- **Controller:** [FULL LEGAL NAME / BUSINESS NAME]
- **Address:** [POSTAL ADDRESS, COUNTRY]
- **Privacy contact:** [CONTACT EMAIL]
- **Website / service URL:** [WEBSITE URL, IF ANY]

If Encore Social is operated only by an individual for their own accounts, identify the actual operator accurately rather than inventing a company.

## 2. What Encore Social does

Encore Social is a tool used to organize short-form video content and manage authorized uploads to connected social-media accounts. Depending on enabled features, it may organize video files, prepare captions and hashtags, suggest cover images and publication times, perform content checks, upload videos or drafts, and retrieve platform-provided performance information.

## 3. Personal data we may process

Depending on which integrations and features you enable, Encore Social may process:

### Account and profile information
- social-platform account ID, username, display name, and profile or page identifiers;
- identifiers for connected YouTube channels, Instagram professional accounts, Facebook Pages, or TikTok accounts;
- account connection status and granted permission information.

### Authentication and authorization data
- OAuth access tokens and refresh tokens issued by the relevant platform;
- token expiry and authorization metadata.

The described local setup stores platform credentials in the macOS Keychain. **Verify this against the deployed version before publication.** Do not include actual tokens, client secrets, passwords, or other credentials in this policy or in support messages.

### Content and publishing information
- video and image files selected for processing or upload;
- filenames, source-channel labels, language labels, and content metadata;
- captions, titles, hashtags, cover images, and publication settings;
- upload status, draft status, timestamps, and error logs.

### Performance information
If analytics permissions and features are enabled, Encore Social may retrieve platform-provided metrics such as views, likes, comments, reach, shares, saves, or other metrics made available by the relevant API. The metrics available vary by platform and permission.

### Technical and diagnostic information
The service may create local operational records, task status, timestamps, and error details needed to run the workflow and troubleshoot failures. **Specify any additional telemetry, analytics, crash reporting, or remote logging here before publication:** [DETAILS OR "NONE"].

## 4. Where data is stored

The current design is intended to run locally on the operator's computer. In that setup:
- OAuth credentials are stored in the macOS Keychain;
- project data, task records, and publishing metadata may be stored in local project files or a local database;
- selected media files remain in the local project folders unless and until they are transmitted to a social platform or another service explicitly used by an enabled feature.

Verify the actual storage locations, backup behavior, file permissions, and any cloud synchronization before publishing this statement. If data is sent to a hosted server, cloud storage, or external AI provider, identify that provider and describe the transfer here: **[ADD PROVIDERS AND DATA FLOWS, OR CONFIRM NONE]**.

## 5. Why we use data

We process data only as needed to:
- connect and authenticate the social-media accounts you authorize;
- identify the correct destination account and prevent cross-posting to the wrong account;
- organize and analyze selected content;
- generate or store captions, hashtags, cover images, and other publishing metadata;
- upload content, including drafts where supported by the platform;
- retrieve analytics where enabled and authorized;
- maintain security, diagnose errors, and prevent misuse;
- comply with applicable legal obligations.

## 6. Legal bases (where GDPR applies)

Where the GDPR applies, the Operator must identify and document the appropriate legal basis for each processing purpose. Depending on the actual relationship and use, this may include:
- performance of a contract or steps requested before entering into a contract;
- legitimate interests in operating, securing, and troubleshooting the tool, where those interests are not overridden by the individual's rights;
- consent, where a feature or applicable law requires it;
- compliance with a legal obligation.

**Before publication, the Operator must confirm which legal bases apply to the actual service and users.** Do not treat this draft list as a completed legal assessment.

## 7. Social-media platforms and other recipients

When you connect an account or request an upload, relevant information is exchanged with the platform you selected:
- Google / YouTube;
- Meta / Facebook / Instagram;
- TikTok.

Those platforms process data under their own privacy policies and terms. An upload may include the video, caption, cover image, destination account identifier, and settings required by the platform API.

If the service uses any additional providers—for example, hosting, cloud storage, AI model providers, error monitoring, or scheduling services—list them here and explain what data they receive: **[ADD ALL ADDITIONAL PROVIDERS, OR CONFIRM NONE]**.

We do not sell personal data. Do not publish this statement unless it accurately reflects the Operator's practices.

## 8. International transfers

Social-media platforms and other providers may process data in countries outside your country of residence, including countries that may have different data-protection laws. Their own privacy notices explain their international processing and safeguards.

If the Operator itself transfers personal data outside the European Economic Area or otherwise makes restricted international transfers, it must identify the relevant recipient, destination, and applicable transfer mechanism: **[ADD DETAILS IF APPLICABLE]**.

## 9. Retention

We keep data only for as long as needed for the purposes described in this Policy, unless a longer period is required by law.

Before publication, set and state actual retention periods for:
- OAuth tokens and account connection records: [RETENTION PERIOD / UNTIL DISCONNECTION];
- local task, upload, and diagnostic logs: [RETENTION PERIOD];
- content files and generated metadata: [RETENTION PERIOD / USER-CONTROLLED];
- support or legal records, if any: [RETENTION PERIOD].

Disconnecting an account should stop future access through that authorization, but it may not automatically delete records already stored locally or content already uploaded to a platform. Those may need to be deleted separately.

## 10. Security

The Operator uses reasonable technical and organizational measures appropriate to the actual deployment. The described local implementation uses macOS Keychain for OAuth credentials. No method of storage or transmission is completely secure.

Do not claim encryption, access controls, backups, or other safeguards unless they are actually implemented and maintained.

## 11. Your rights

Where GDPR or other data-protection laws apply, you may have rights to request access, rectification, erasure, restriction, portability, or to object to certain processing. Where processing is based on consent, you may withdraw consent without affecting the lawfulness of processing before withdrawal.

To exercise applicable rights, contact **[CONTACT EMAIL]**. You may also have the right to complain to your local data-protection supervisory authority. If you are in Poland, the supervisory authority is the President of the Personal Data Protection Office (UODO).

Some information may remain in platform systems or local backups after disconnection; you may need to contact the relevant platform or delete local project records separately.

## 12. Children's privacy

Encore Social is not intended for children and is not knowingly designed to collect personal data from children. If you believe a child has provided personal data to the Operator, contact **[CONTACT EMAIL]**.

## 13. Changes to this Policy

We may update this Policy when the service, integrations, or applicable law changes. The current version will be published at **[PRIVACY POLICY URL]** with a revised "Last updated" date.

## 14. Contact

Privacy requests and questions: **[CONTACT EMAIL]**  
Controller: **[FULL LEGAL NAME / BUSINESS NAME]**  
Address: **[POSTAL ADDRESS, COUNTRY]**
