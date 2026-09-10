# Slay Speech Privacy Policy

**Effective date: September 10, 2026.**

Slay Speech helps you practice English using lessons, pronunciation feedback, AI conversations, and, if you enable it, speech from your day. This policy explains how **Koel Labs LLC** ("Koel Labs," "we," or "us") handles personal information in the Slay Speech mobile app, **Koel Companion**, the Daily Speaking Inbox, and related services that link here (the **Service**).

This policy controls for the Service. Our [general privacy policy](PRIVACY.md) covers our other websites and public community spaces.

## The essentials

- **Accounts save your progress.** We store your account, settings, learning history, and other synced information so you can use the Service across devices.
- **Speaking features process what you say.** Depending on the feature, audio is processed on your device, on our servers, or by a speech provider. Transcripts and feedback can be saved even when raw recordings are not.
- **AI features involve service providers.** Deepgram transcribes audio; Cerebras generates conversation responses and lessons; Cartesia produces spoken responses and audio lessons. Text sent to AI providers can include excerpts from your speech and conversation context.
- **Optional speech contributions are separate.** “Help improve Slay Speech” and “Contribute to speech research” are off by default. They control Koel Labs' optional model-improvement and research uses, not processing needed to deliver a feature. Provider processing is explained below.
- **Analytics are not anonymous when linked to your account.** We use PostHog Cloud, hosted by PostHog, for first-party product analytics and error reporting.
- **Get permission before capturing other people.** Voice filtering can make mistakes. Other speakers' words can also become text context, even when their audio is not uploaded.
- **We do not sell personal information or share it for targeted advertising.** You can change speech-data choices, delete your account, or contact us about your data.

## 1. Who is responsible and how to contact us

Koel Labs LLC is the controller of the personal information described here, meaning we decide why and how it is used.

Privacy requests: [privacy@slayspeech.com](mailto:privacy@slayspeech.com)\
Support: [info@koellabs.com](mailto:info@koellabs.com)

Koel Labs LLC\
8228 NE 198th St.\
Kenmore, WA 98028, United States

## 2. Information we process

| Information | What it includes and why we need it |
|---|---|
| Account and sign-in | Email address, account ID, username, display name, sign-in provider identifiers, verification and session information. Apple or Google can supply account information you authorize them to share. Email sign-in uses a one-time code. We do not receive your Apple or Google password. |
| Learning profile and progress | Native language, goals, speaking level, language and time-zone settings, onboarding choices, profile customization, completed activities, scores, streaks, practice history, and synced app state. These are used to personalize and restore your learning experience. |
| Speech and conversation content | Audio you record or import, typed phrases, transcripts, conversation messages, prompts, pronunciation measurements, feedback, and generated lessons. Your words can contain personal information about you or other people. |
| Daily Speaking Inbox | Speaking events, selected activities, source app name/identifier, timestamps, duration totals, filtered or ignored speech totals, transcripts, context, sound patterns, and saved written/audio lessons. |
| Paired computers | Device name, operating system, pairing and last-use times, and account/session linkage. These let you pair multiple computers, recognize them, and disconnect them. One-time pairing codes are short-lived and do not replace account authentication. |
| Access and purchases | Premium status and its expiry; where purchases are offered, RevenueCat helps us process product, transaction, purchase/renewal, and entitlement information. The checkout provider processes payment details; we do not receive your full payment-card number through app-store checkout. |
| Usage and diagnostics | Features and screens used, activity outcomes, app version, device/OS details, timestamps, IP address, approximate network-derived location, crash reports, error messages, and account or app identifiers. These help us understand use, diagnose failures, and prevent abuse. |
| Support and preferences | Messages, screenshots you submit, privacy and marketing choices, reminder settings, and records of requests and consent. Screenshots and diagnostic messages may contain personal information. |

We receive information from you, your devices, sign-in and other service providers, and your interactions with the Service. Information about another person can arrive through a recording, transcript, or support submission you provide.

An account ID or random speaker ID is a label, not a guarantee of anonymity. Speaker IDs can be linked to an account, and voices and conversation details may identify someone without a name attached.

## 3. What happens to speech

### Practice and AI conversations

We process recordings to transcribe speech and assess pronunciation. Some processing happens locally; features that need server analysis send audio to our servers. Certain transcription requests also send audio to Deepgram. Every Deepgram request opts out of its model-improvement program. We select its EU, Australian, or global endpoint using the device time zone, with the saved account time zone as a fallback. European time zones route to the EU, Australian time zones to Australia, and other recognized geographic time zones to the global endpoint; when no usable region hint is available, we use the EU endpoint. Conversation and lesson features send relevant text, learning context, and feedback to Cerebras. Cartesia receives the text to be spoken, which can quote your conversations.

We do not intentionally keep a server copy of raw practice audio after processing unless one of your optional speech-contribution choices permits it. **This does not mean that everything is deleted when feedback appears:** transcripts, conversation messages, scores, usage records, and saved lessons can remain to provide history, progress, support, and the Service. Device caches and retry queues also have their own lifetimes. Third-party processing is described in section 5.

### Daily Speaking Inbox and Koel Companion

The inbox is an optional feature. Setup lets you select activities, link a computer, and create a voice profile where needed. The companion can start listening when a selected app uses the microphone, or when you manually start a session. App-based triggers can cover more activity than a particular meeting or browser tab; check the capture status and stop capture when it is inappropriate.

The device processes microphone and, where supported, system/speaker audio separately. Local models try to remove noise and keep speech that matches your enrolled voice. System audio and other speakers' audio are processed locally for context rather than intentionally uploaded as recordings. **Text derived from those speakers may be included in the context sent to our servers and AI providers.** Filtering is imperfect: unwanted speech may pass through, and wanted speech may be missed.

For file or share-sheet imports, the device processes the selected recording; for videos it extracts the audio. Temporary working copies are separate from the original in your files, photos, or source app. Removing an inbox item or account does not delete those originals.

We store accepted speaking events and compact analysis results so you can review sound patterns and prior lessons. We also store duration and source information for filtered or over-limit events. Passing a daily limit does not mean all metadata stops being collected. We try to remove some obvious identifiers from lesson evidence, but this is **not complete anonymization**. Names, workplaces, confidential details, and identifying context may remain. Avoid capturing sensitive or confidential conversations unless you have all necessary permissions.

### Voice setup and biometric information

Voice setup creates a mathematical voice profile and microphone calibration information used to distinguish your speech from other audio. Calibration runs locally; the temporary calibration recordings are discarded after setup processing. The profile is kept in device secure storage and is not intentionally uploaded to our servers or used as an account login method. The companion may temporarily retain a failed recording for playback while you retry setup.

A profile used to recognize your voice can be biometric data under some laws. Local processing does not automatically remove those protections. Where required, your separate informed consent is understood to come from activating the optional feature. You can reset the mobile voice profile or unlink the companion to remove its profile. Disconnecting a remote computer revokes access, but cannot guarantee immediate erasure of files on a computer that is offline.

We do not sell, lease, trade, or otherwise profit from biometric identifiers or biometric information. Where biometric laws apply, we limit disclosure as those laws require and destroy covered information when its collection purpose is satisfied or within three years of your last interaction with us, whichever comes first, unless a different rule is legally required. This includes covered copies and derived data, not just raw recordings.

## 4. Your optional speech contributions

Both choices below are off by default, separate from each other, and can be changed in settings. Saying no does not prevent ordinary pronunciation feedback. Enabling one may permit retention of recordings without enabling the other purpose.

**Help improve Slay Speech.** If enabled, Koel Labs may retain and use your submitted speech recordings and related transcripts, pronunciation measurements, learning-profile information, source/context metadata, and speaker identifier to train, test, and evaluate our speech models. Relevant staff or contractors may review examples for these purposes.

**Contribute to speech research.** If enabled, Koel Labs may retain and share relevant speech data with approved research partners under data-use agreements. Those agreements must restrict use to approved research, prohibit attempts to identify or contact you and unauthorized onward sharing, and require appropriate security and deletion obligations. They must prohibit advertising and employment, credit, insurance, housing, immigration, or similar eligibility uses.

We do not treat either choice as permission to publicly release your identifiable raw recordings. Public release of such recordings requires separate, specific consent. We do not consider a recording anonymous just because names or account IDs were removed.

Turning a choice off stops new collection and future Koel Labs use for that optional purpose; it is not itself a request to delete existing copies. You can request deletion separately. We will handle requests affecting previously shared data with the relevant recipients as required by law and our agreements. Published aggregate research and changes already incorporated into trained models may not be reversible; that does not remove our duties to delete identifiable source data or stop future uses when required.

## 5. Providers and other disclosures

We use providers to deliver the Service. The main feature-related recipients are:

| Provider | Role and information involved |
|---|---|
| Amazon Web Services (AWS) | Hosting-related infrastructure, object storage and delivery, and email delivery, including recordings retained with permission, generated audio, support attachments, and email addresses/messages. [AWS privacy](https://aws.amazon.com/privacy/) |
| Deepgram | Transcription for features that use its speech-to-text API; receives the submitted audio and request settings. [Deepgram privacy](https://deepgram.com/privacy) |
| Cerebras | Generates text responses, feedback, and lesson material from relevant transcripts, conversation history/context, learning information, and prompts. [Cerebras privacy](https://www.cerebras.ai/privacy-policy) |
| Cartesia | Converts response and lesson text to synthetic audio. We send text, not your microphone recordings or local voice profile. That text can contain excerpts from your speech and other conversation context. [Cartesia privacy](https://www.cartesia.ai/legal/privacy) |
| PostHog Cloud (hosted by PostHog) | First-party product analytics and error reporting, including account ID and username, screen/activity events, learning-profile attributes, app/device details, and diagnostics. [PostHog privacy](https://posthog.com/privacy) |
| RevenueCat | Subscription management where purchases are available, including account/app user ID, product and transaction details, purchase history, entitlement status, and relevant app/device information. [RevenueCat privacy](https://www.revenuecat.com/privacy/) |
| Apple and Google | Sign-in, app distribution, device/app integrity checks, and purchases where offered. They receive information needed for those functions and process their own account/store activity under their policies. [Apple privacy](https://www.apple.com/legal/privacy/) · [Google privacy](https://policies.google.com/privacy) |

Not every provider receives every category of information or is involved in every feature. Provider privacy pages give background; our agreements and the settings applicable to our use determine their processing of Service data. Providers may also use their own infrastructure providers.

**Provider training and retention:** all Deepgram requests use its model-improvement opt-out (`mip_opt_out=true`). Deepgram describes opted-out request content as retained only for the time needed to process the request; technical usage records are separate. Cerebras describes its handling of inference inputs and outputs in its linked policy and applicable service agreements.

**Cartesia does not provide zero data retention or a regional endpoint choice.** Text and generated audio may be retained and processed under Cartesia's applicable terms, including any permitted service/model-improvement uses, and may be processed outside your country. Our optional Koel Labs speech-contribution switches do not change Cartesia's provider settings. Although we do not send it your recorded voice, quoted text can still reveal names, personal matters, or confidential information.

We use **hosted PostHog Cloud for first-party product analytics**: understanding use of our own Service and diagnosing errors. We do not use it for cross-company advertising tracking, sell analytics data, or combine it with activity from other companies' apps for advertising. Analytics records events and errors and associates them with your account when signed in. This collection is separate from the two speech-contribution choices. Applicable objection or consent rights are not waived by this policy; where local law requires a separate choice for nonessential analytics, we will honor that requirement. Contact us to exercise your privacy rights.

We may also disclose necessary information to authorized personnel and professional advisers, approved research partners when you opt in, and recipients involved in legal compliance, security incidents, or protecting rights. We assess legal requests rather than promising disclosure in response to every inquiry. In a business sale or reorganization, information may transfer subject to applicable law and protections consistent with this policy.

**We do not sell personal information, share it for cross-context behavioral advertising, or use your recordings for advertising.**

## 6. Why we process information

We process information to provide requested features, keep accounts and devices secure, restore learning progress, troubleshoot problems, understand product use, answer support requests, and meet legal obligations. Optional contributions serve only their separately described purposes.

Where European or similar data-protection laws apply, we rely on contract necessity for core requested services; legitimate interests in security, reliability, and proportionate product improvement where those interests are not overridden by your rights; legal obligations; and consent for optional contributions and other processing that requires it. We obtain explicit consent where required for biometric or other sensitive data. You may withdraw consent without affecting earlier lawful processing. We do not use learning scores to make decisions with legal or similarly significant effects about you.

## 7. Retention and deletion

We keep information for its stated purpose. The following describes the retention rules for our copies; provider terms, legal requirements, and device storage also matter.

| Category | Retention rule |
|---|---|
| Raw audio processed for feedback without optional contribution consent | Used for request processing, not intentionally saved as a retained server recording. Temporary device processing/playback/retry copies can remain until completed, cleared, or removed. |
| Account, synced progress, conversation history, inbox evidence and lessons | Kept to maintain your account and learning history until deletion or until no longer needed for that purpose, subject to necessary legal/security records. A daily quota reset does not delete prior lessons. |
| Optional model-improvement/research speech data | Until no longer needed, or deletion is required, whichever is sooner. Turning off a switch stops the optional future uses described above. The earlier biometric destruction rule applies to covered data. |
| Device voice profiles | Until reset or removed, or their purpose ends; the biometric destruction rule applies where required. Removing an app may not remove every OS keychain or backup copy. |
| Support notes and screenshots | Up to 24 months, unless a specific unresolved support, security, or legal matter requires longer. |
| Security logs and abuse records | Normally up to 90 days; longer only for a specific security, fraud, or legal need. |
| Product analytics | Only as long as needed to understand usage and diagnose problems under the configured analytics retention settings. |
| Purchase, consent and privacy-request records | As needed to administer entitlements, document choices, resolve disputes, and meet applicable recordkeeping duties. |
| Backups | Rolling expiry, normally within 90 days; necessary legal holds may apply. Restored backups must remain subject to recorded deletion requests. |

**Deleting your account is different from signing out or uninstalling.** Account deletion in the app removes the account and initiates deletion of associated server data and linked stored speech assets. External cleanup may finish after the account disappears. It does not automatically cancel an app-store subscription or erase originals in your files, photos, other apps, or offline devices. Contact us if you need help deleting those copies or provider-held data.

Limited exceptions may apply for legal duties, security, disputes, and information that is genuinely de-identified. Restrictions on further use continue while deletion is being completed.

## 8. Your controls and rights

You can edit profile information, change the two speech-contribution choices, manage microphone and file/photo permissions, change or stop capture, reset voice setup, disconnect paired computers, and delete your account. Reminders use device notification scheduling; settings may be synced to your account. Device settings can disable notifications. Marketing messages, if you request them, include an unsubscribe option; necessary sign-in and service messages are separate.

For access, export, correction, deletion, objection, restriction, consent withdrawal, or an applicable appeal, use available app controls or email [privacy@slayspeech.com](mailto:privacy@slayspeech.com). We may need to verify account ownership or request authority. You can ask through an authorized agent where permitted. We respond within applicable legal deadlines and do not penalize you for exercising rights; a feature may stop working if it needs data you ask us not to process.

For older accountless installations, a speaker ID or in-app request record may help us locate data. Do not send account passwords or verification codes in a privacy request.

Rights depend on your location. Where applicable, you can complain to your local data-protection authority, including an EEA supervisory authority or the UK Information Commissioner's Office. Contact us to appeal a denied request; we will explain applicable further complaint options.

### California residents

If the CCPA applies to us, the information categories above include identifiers, customer/account records, commercial information, internet/electronic activity, audio and other sensory information, learning-related inferences, and sensitive information such as covered voice profiles. Sections 2–7 describe their sources, purposes, recipients, and retention criteria. We do not sell or share personal information for cross-context behavioral advertising, including information about minors. We use sensitive information for requested services, permitted security/legal purposes, or separately consented uses. Applicable rights include access/knowledge, correction, deletion, and nondiscrimination, subject to lawful exceptions.

## 9. International processing and security

Koel Labs is based in the United States. Data may be processed there and in other countries where our infrastructure and providers operate. Protections can differ. When a transfer requires safeguards, we must use a valid mechanism, such as applicable standard contractual clauses or a legally recognized adequacy arrangement. Contact us for information about the safeguards relevant to your data.

We use safeguards appropriate to the information, including access controls, secure transmission, and protected storage. Access is limited by role and purpose. No service or device can guarantee absolute security. Secure your devices and sign-in accounts, especially computers that hold voice profiles or queued recordings.

## 10. Children and updates

The Service is not intended for children under 13. Users who are minors must have a parent or guardian's permission; a higher local age or a required parental-consent rule may apply. Do not submit a child's recordings unless the feature permits it and all required permissions have been obtained. Contact us if you believe we have collected a child's information unlawfully so we can investigate and delete it as required.
