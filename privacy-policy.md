# S A P O Privacy Policy

**Effective Date:** 2025-11-30  
**Version:** v1.0

This Privacy Policy explains how **S A P O** (referred to as **“S A P O,” “SAPO,” “we,” “us,”** or **“our”**) collects, uses, and shares information when you use our services.


**Controller.** S A P O is operated by Happ Technologies Inc., a company organized under the laws of Delaware, United States. For the purposes of data protection laws (such as the GDPR), Happ Technologies Inc. is the controller of your personal data when you use S A P O. You can contact us at **juanmarzabala8a@gmail.com**.

---

## 0) Scope

This Policy applies to:

- The **S A P O mobile app**, and  
- The **backend services and APIs** we operate to:
  - Perform **phonetic transliteration** and **semantic translation** of text using third-party state-of-the-art AI models,  
  - Manage user accounts and authentication, and  
  - Handle subscriptions and token budgets.

It **does not** apply to:

- Third-party websites, app stores, or services you access via links or native integrations;  
- The independent practices of third-party service providers we rely on (e.g., AI model providers, identity providers, app stores, payment processors, cloud hosting, and databases).

Those third parties process data under their own terms and privacy notices.

---

## 1) What We Collect (Minimization by Design)

We design S A P O to **minimize** personal data collection and retention. However, some data is necessary to provide accounts, subscriptions, and secure access to phonetic transliteration and semantic translation.

### 1.1 Account & Authentication Data

When you create or use an account, we may process:

- **Authentication credentials** handled by our authentication provider (e.g., auth tokens)
- **Third-party sign-in data** when you log in with Apple or Google, including:
  - Email address,  
  - Display name (if provided),  
  - A unique identifier from the third-party provider.  
- **Account metadata**, such as:
  - Account ID,  
  - Subscription tier and token allocation,  
  - Account creation date and last updated date.

> **Mobile app note:** The current mobile app supports sign-in via Apple and Google.

### 1.2 Subscription & Payment Information

When you purchase or manage a subscription:

- **App stores (e.g., Apple App Store, Google Play)** and **payment processors (e.g., Stripe)** process your payment information on their own systems under their own privacy policies.  
- We **do not** receive or store your full card number or full payment instrument details.

From these providers, we receive **limited billing and subscription information**, which may include, for example:

- A transaction or order identifier or purchase token,  
- Product or plan identifier (e.g., which subscription you bought),  
- Price and currency of the purchase,  
- Subscription status (active, canceled, in grace period, etc.),  
- Relevant dates (e.g., start date, renewal date, expiration date),  
- Other metadata that the store or processor makes available to us where applicable (e.g., country or region, if provided).

**What we store in S A P O’s own systems.**  
In our own databases, we store only the **minimal subscription information necessary** to operate S A P O and fulfill legal/operational needs, such as:

- Your subscription tier and associated token allocation,  
- Entitlement status (e.g., whether your subscription is active),  
- Relevant subscription dates (e.g., start, renewal, or expiration),  

Detailed payment data and full transaction records remain primarily with the app store or payment processor and are accessed by us only as needed (for example, to handle refunds, disputes, or audits).

### 1.3 Service Content: Text You Submit

To perform **phonetic transliteration** and **semantic translation**, we process:

- **Input text** you submit to S A P O, and  
- **Output text** generated and returned to you by the AI models.

This text may contain personal data **if you choose to include it**, but we do not require you to submit personal data. You should avoid including sensitive personal information (for example, health data, financial account numbers, government IDs, or special categories of data) unless strictly necessary.

By default:

- Input and output text are processed **transiently** to provide phonetic transliteration and semantic translation and then discarded, subject to:
  - Very short-lived caching or buffering for performance, reliability, and security; and  
  - Limited logging of error cases, minimized and de-identified where feasible.

We use state-of-the-art third-party AI models (currently provided by **OpenAI**) to perform these transformations. Where available, we configure and contractually restrict such providers so your content is **not used to train their models for other customers**.

### 1.4 Technical & Usage Data

When you use S A P O, we, app stores, and our service providers may collect:

- **Device and app data**: device type, operating system, app version, language, general region (e.g., country), and app configuration.  
- **Network data**: IP address, timestamps, and request identifiers necessary to deliver the service securely and reliably.  
- **Usage data** related to S A P O’s core features:
  - Number of requests you make,  
  - Token usage (how much of your AI token budget is consumed),  
  - Language pairs used (in aggregated or de-identified form),  
  - Basic feature usage patterns.

We do **not** use third-party advertising SDKs or cross-site tracking cookies.

### 1.5 Aggregated & De-Identified Data

We may derive **aggregated** or **de-identified** data (for example, statistics about language pair usage, average token consumption, or error rates) that no longer identifies you. We may use this data to:

- Monitor stability and performance of phonetic transliteration and semantic translation,  
- Improve prompts, system design, and user experience,  
- Support our mission to build a global open phonetic database in a privacy-preserving way.

---

## 2) How We Use Data (and What We Don’t Do)

### 2.1 Provide Core Services

We process data as necessary to:

- Operate the **S A P O** app and servers,  
- Receive your text and perform **phonetic transliteration and semantic translation** using AI models,  
- Manage and secure your **account** and **authentication**,  
- Manage your **subscription**, token budget, and access to paid features.

### 2.2 Authentication & Account Management

We use your account and authentication data to:

- Register you as a user of S A P O,  
- Log you in securely via our identity provider and/or OAuth providers (Apple, Google),  
- Maintain sessions and prevent unauthorized access,  
- Synchronize basic settings or entitlements across devices,  
- Communicate with you about account security, important updates, or subscription status where allowed by law (non-marketing).

### 2.3 Payments, Subscriptions, and Token Budgets

We use subscription and payment-related data to:

- Confirm your subscription via app stores and/or payment processors,  
- Maintain up-to-date **entitlements** (e.g., which plan you are on and what features/token budget you have access to),  
- Enforce plan limits fairly, including tracking token usage to respect your subscribed budget,  
- Handle refunds or billing-related issues in coordination with the relevant app store or payment processor,  
- Satisfy accounting, tax, and compliance requirements to the extent they apply.

**Token budgets and unused tokens.**  
Each subscription plan includes a **monthly AI token budget** used to perform phonetic transliteration and semantic translation. If you do not use your full token budget within a billing period:

- The **unused portion** may be redirected to run additional AI processes that expand and improve S A P O’s **open phonetic database**.

Your own private transliteration and translation sessions are **not automatically repurposed as training data** for the open phonetic database. If we ever wish to use your user content in a way that could reasonably identify you or your text, we will obtain **specific, informed consent** where required, or we will properly anonymize the content.

### 2.4 Security, Abuse Prevention, and Legal Compliance

We process technical and usage data to:

- Protect S A P O against spam, abuse, fraud, and security threats,  
- Detect, investigate, and fix bugs and outages,  
- Enforce our Terms of Use,  
- Comply with applicable legal obligations, and  
- Respond to lawful requests from authorities where required.

### 2.5 Service Improvement and Open Phonetic Database

We process aggregated or de-identified data to:

- Improve and tune the performance of **phonetic transliteration and semantic translation**,  
- Guide where to allocate additional background AI processing (for example, which language pairs to prioritize),  
- Build and publish a global open phonetic database that contains phonetic mappings and transliterations *between languages* without revealing your identity.

We **do not** publish or share your identifiable personal data as part of this open database.

### 2.6 What We Don’t Do

- We do **not** sell your personal data.  
- We do **not** “share” your personal data for cross-context behavioral advertising under U.S. state privacy laws.  
- We do **not** run targeted advertising inside S A P O.  
- We do **not** use S A P O to make automated decisions with legal or similarly significant effects about you; we only perform transformations on text that you choose to submit.

---

## 3) Legal Bases (GDPR and Similar Laws)

If you are in the **EU/EEA, UK, Switzerland**, or a similar jurisdiction that requires a legal basis for processing, we rely on:

1. **Contract performance**  
   - To deliver S A P O’s core functionality (phonetic transliteration and semantic translation),  
   - To manage your account and authentication,  
   - To provide and manage subscriptions and token budgets you choose to purchase.

2. **Legitimate interests**  
   - To maintain security, prevent abuse, and prevent fraud,  
   - To perform internal analytics and service improvement (in a minimized and aggregated way),  
   - To pursue our mission of building a global open phonetic database in a manner that respects privacy.  

   We balance these interests against your rights and freedoms by minimizing data, avoiding sensitive categories, limiting retention, and providing rights such as objection where applicable.

3. **Consent**  
   - For specific processing where required by law (for example, certain optional features or marketing communications). You can withdraw consent at any time, which does not affect the lawfulness of processing that occurred before withdrawal.

4. **Legal obligations**  
   - To comply with tax, accounting, consumer protection, or data protection laws and to respond to lawful requests.

You have the right to **object** to processing based on legitimate interests and to request restriction in some cases.

---

## 4) Storage & Retention

### 4.1 Text Content (Transliteration and Translation)

- Input and output text for phonetic transliteration and semantic translation are processed **ephemerally** to serve your request and to protect system integrity.
- We avoid storing full text content in persistent logs. Where logs or error reports might incidentally include snippets, we minimize and restrict access and retention.

### 4.2 Account and Subscription Data

We retain:

- Core account data (e.g., name, email, account ID),  
- Minimal subscription data (e.g., subscription tier, entitlement status, relevant dates),  
- Records of your communications with us regarding account or privacy requests,

for as long as your account is active and for a reasonable period afterward, or as required by applicable law for legal, tax, accounting, security, or dispute-resolution purposes.

### 4.3 Technical Logs

Technical logs (e.g., IP addresses, request identifiers, timestamps) are stored only as long as needed for:

- Security and abuse monitoring,  
- Troubleshooting and reliability,  
- Legal or compliance reasons where applicable.

We de-identify or aggregate logs where feasible.

### 4.4 Deletion and De-Identification

When data is no longer needed for the purposes described above, we:

- Delete it; or  
- Irreversibly de-identify or aggregate it so it no longer relates to an identifiable user.

---

## 5) Children and Digital Age of Consent

S A P O is **not directed to children** and is intended for use only by individuals who can lawfully consent to the processing of their personal data.

- We **do not knowingly collect** personal data from anyone below the **digital age of consent** in their country (typically between **13 and 16**).  
- Account and subscription flows are intended for adults or individuals above the applicable digital age of consent.

If we become aware that we have collected personal data from someone under the digital age of consent without appropriate authorization:

- We will take reasonable steps to delete that data; and  
- We may close or restrict the associated account.

If you believe a child has provided personal data to S A P O, please contact us at **juanmarzabala8a@gmail.com**.

---

## 6) How We Share Data

We do **not** sell your personal data. We share data only in limited situations:

### 6.1 Service Providers (Processors/Sub-Processors)

We use service providers acting as our processors to help operate S A P O, including:

- **Identity provider** (e.g., Clerk)  
  - Processes: account data, session tokens.  
  - Purpose: account creation, sign-in, session management.  

- **AI model provider** (currently a third-party such as OpenAI)  
  - Processes: input text and generated outputs, transiently and subject to configuration, as well as technical metadata.  
  - Purpose: perform phonetic transliteration and semantic translation.  
  - Safeguards: contractual restrictions, no-training/no-reuse settings where available, security controls.

- **App stores and payment processors** (e.g., Apple App Store, and in the future Google Play and/or Stripe on certain platforms)  
  - Processes: payment information, limited billing and subscription metadata.  
  - Purpose: process payments, manage subscriptions, handle refunds and disputes.  
  - Safeguards: data-processing terms, PCI-DSS or equivalent standards, encryption and access controls.

- **Cloud hosting, infrastructure, and database providers**  
  - Processes: technical metadata, limited account and subscription data, and transient copies of requests.  
  - Purpose: host and run the S A P O backend, store account and subscription records, maintain reliability and security.  
  - Safeguards: access control, security certifications, contractual protections, and transfer mechanisms for international transfers.

We require our processors to:

- Process personal data only on our documented instructions,  
- Implement appropriate technical and organizational measures,  
- Not use data for their own independent advertising or unrelated purposes.

### 6.2 App Stores and OAuth Providers as Independent Controllers

**Apple**, **Google**, and similar providers may also act as **independent controllers** of your personal data. For example:

- When you create or use an Apple ID or Google account, or make in-app purchases,  
- When you use Sign in with Apple or Google Sign-In.

They collect and process data under their own terms and privacy notices. We receive only a subset of that data (for example, name, email, an identifier, and limited subscription status) and use it as described in this Policy. We do **not** control their independent data practices and recommend reviewing their privacy policies.

### 6.3 Legal, Safety, and Business Transfers

We may disclose information:

- To comply with applicable law, legal process, or enforceable governmental requests;  
- To enforce our terms or protect our rights;  
- To protect the safety, rights, or property of our users, the public, or S A P O.

If S A P O (or Happ Technologies Inc.) is involved in a merger, acquisition, reorganization, or sale of assets, your information may be transferred as part of that transaction, subject to this Policy or an equivalent level of protection. We will notify you of any material changes affecting your personal data.

---

## 7) International Data Transfers

We are based in the **United States** and may use service providers that process data in the U.S. and other countries.

When your personal data is transferred from your country to another country that may have different data protection laws:

- We implement appropriate safeguards required by law, such as:
  - European Commission or UK-approved **Standard Contractual Clauses (SCCs)**,  
  - Reliance on applicable **adequacy decisions**,  
  - Other recognized transfer mechanisms.

We also reduce risk through **data minimization**, **limited retention**, and **de-identification** where appropriate.

You can contact us for more information about the safeguards used for international transfers.

---

## 8) Security

We use reasonable and appropriate technical and organizational measures to protect your personal data, including:

- **Encryption in transit** (e.g., TLS) between your device and our services,  
- **Access controls** and least-privilege principles,  
- **Secure key management** and hardened infrastructure,  
- **Vendor security reviews** when engaging processors,  
- **Incident detection and response** procedures.

No method of transmission or storage is perfectly secure, but we intentionally **minimize** what we collect and retain, which helps limit risk.

If we become aware of a personal-data breach likely to result in a high risk to your rights and freedoms, we will notify you and relevant supervisory authorities in accordance with legal requirements.

---

## 9) Your Privacy Rights

Depending on your location, you may have some or all of the following rights:

- **Access / Know** – to confirm whether we process your personal data and obtain a copy.  
- **Correction (Rectification)** – to request that inaccurate or incomplete data be corrected.  
- **Deletion (Erasure)** – to request deletion of certain personal data.  
- **Portability** – to receive certain data in a structured, machine-readable format and/or to have it transmitted to another controller.  
- **Restriction** – to request that we limit processing of certain data.  
- **Objection** – to object to processing based on our legitimate interests.  
- **Opt-out of “sale” or “sharing”** – under U.S. state laws where applicable (we do not “sell” or “share” personal data for targeted advertising).  
- **Withdraw consent** – where we rely on consent for specific processing activities.  
- **Lodge a complaint** – with your local data protection authority or regulator.

### How to Exercise Your Rights

You can submit a request by:

- Emailing us at **juanmarzabala8a@gmail.com**.

To protect your privacy, we may need to verify your identity, which can involve:

- Asking you to sign in to your S A P O account, and/or  
- Requesting limited additional information to match against our records.

We will respond within the time frames required by applicable law. Where we have little or no personal data about you (for example, if you used S A P O without an account and we store no persistent identifiers), we will confirm that.

We will not discriminate against you for exercising your privacy rights.

---

## 10) Do Not Track, Global Privacy Control (GPC), and Similar Signals

S A P O does **not** use your data for cross-site or cross-app targeted advertising and does **not** sell or “share” your personal data for such purposes.

Because of this:

- Browser “Do Not Track” signals do not change how S A P O operates today.  
- Where applicable laws require us to treat **Global Privacy Control (GPC)** or similar signals as opt-out requests from “sale” or “sharing,” we honor that, though we already do not engage in those activities.

If this changes in the future, we will update this Policy and our practices accordingly.

---

## 11) Third-Party Links & Content

S A P O may offer links to third-party websites, content, or documentation. When you follow those links:

- You interact directly with that third party, and  
- Their terms and privacy policies apply to your use of their services.

We are not responsible for the content, privacy practices, or security of third-party websites or services.

---

## 12) Changes to This Policy

We may update this Privacy Policy as S A P O evolves (for example, when we:

- Launch Android or web versions,  
- Add new payment options such as additional app stores or Stripe,  
- Introduce new features or analytics).

When we make **material changes**, we will:

- Update the **Effective Date**, and  
- Provide additional notice where reasonable (e.g., in-app notice, release notes, or email).

Your continued use of S A P O after the updated Policy becomes effective signifies that you have read and understood the changes, to the extent permitted by law.

---

## 13) Contact & Complaints

If you have questions, concerns, or requests about this Policy or how we process your personal data, you can contact us at:

> **Email:** juanmarzabala8a@gmail.com  

You also have the right to lodge a complaint with your local data protection authority or regulator, especially if you are in the EU/EEA, UK, or another jurisdiction with a dedicated data protection authority.

---

## 14) Plain-Language Snapshot

This summary is for convenience only. If there is any conflict, the full Policy above controls.

- **What S A P O does.** We use state-of-the-art AI (currently provided by a third party) to perform **phonetic transliteration and semantic translation** of text you submit.  
- **Accounts & auth.** We use an identity provider and OAuth (Apple, Google).  
- **Subscriptions & payments.** App stores and payment processors handle your payment details. We only store minimal subscription data (tier, status, dates, and token allocation) plus basic, mostly aggregated analytics.  
- **Unused tokens.** Unused parts of your monthly AI token budget may fund background AI processing to expand the **open phonetic database**. Your private sessions are not used as training data in any identifying way without clear consent.  
- **Data minimization.** Text you submit is processed mainly in memory or short-lived buffers to generate results, then discarded or minimized. We avoid unnecessary logs and do not profile you for advertising.  
- **No ads / no sale.** We do not sell your personal data or “share” it for targeted advertising.  
- **Children.** We do not knowingly collect data from anyone below the digital age of consent in their country.  
- **Your rights.** You can ask to access, correct, delete, or port your data and object to certain processing, depending on where you live.  
- **Mission.** Our long-term goal is to build a global open phonetic database while respecting your privacy, keeping data collection minimal, and applying strong security practices.
