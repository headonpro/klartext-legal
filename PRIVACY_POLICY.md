# Privacy Policy for KLARTEXT

**Last Updated:** October 25, 2025
**Effective Date:** October 25, 2025

## Introduction

KLARTEXT ("we," "our," or "the app") is committed to protecting your privacy and ensuring transparency about how we collect, use, and protect your personal data. This Privacy Policy explains our data practices in clear, user-friendly language.

KLARTEXT is an AI-powered text correction and text-to-speech application that helps you write better and communicate more effectively. We only collect data that is essential to provide these services.

**Your Rights:** You have full control over your data, including the right to export or delete it at any time through the app's Settings menu.

## Contact Information

**Data Controller:**
Headon Kreativagentur
Deutschland
Email: hallo@headon.pro
For privacy-related inquiries, data export requests, or deletion requests, please contact us at the email above.

## 1. What Data We Collect

### 1.1 Account Information
When you sign in with Google OAuth:
- **Email address:** Used for account identification and authentication
- **User ID:** A unique identifier assigned by our authentication provider

### 1.2 Text Input Data
- **Text you enter for correction:** The text you type into the app to receive AI-powered corrections
- **Corrected text:** The AI-generated corrections and suggestions
- **Note:** We do NOT store your text permanently. Text is processed in real-time and not saved to our servers after processing.

### 1.3 Voice and Language Preferences
- **Selected language:** Your preferred language for text correction (German, English, French, Spanish, Italian, Turkish)
- **Voice selection:** Your chosen text-to-speech voice (voice ID)
- **Voice settings:** Speech speed and auto-play preferences
- **Auto-detect language setting:** Whether automatic language detection is enabled

### 1.4 Usage Statistics
- **AI correction usage:** Daily count of how many times you use AI text correction
- **Text-to-speech usage:** Daily count of how many times you use TTS playback
- **Purpose:** To enforce subscription tier limits (free vs. premium)
- **Note:** Usage counters reset daily and do not include content details

### 1.5 Subscription Information
- **Subscription tier:** Your current plan (free or premium)
- **Payment information:** Processed and stored by Stripe (see Section 3.4)
- **Note:** We do NOT store your credit card information directly

### 1.6 Technical Data
- **Device information:** Platform (iOS/Android), app version
- **Error logs:** Crash reports and error information for debugging (no personal content)
- **Note:** Collected automatically to improve app stability

## 2. How We Use Your Data

### 2.1 Core Service Delivery
- **AI Text Correction:** Your text is sent to Azure OpenAI to generate corrections and translations
- **Text-to-Speech:** Your corrected text is sent to ElevenLabs to generate audio playback
- **Authentication:** Your email is used to create and maintain your account via Supabase
- **Subscription Management:** Your subscription status determines feature access and usage limits

### 2.2 Service Improvement
- **Usage analytics:** Aggregate usage statistics help us understand feature adoption (e.g., which voices are popular)
- **Error tracking:** Crash reports help us identify and fix bugs
- **Note:** We only analyze anonymized aggregate data, never individual user behavior

### 2.3 Communication
- **Service notifications:** Important updates about your account or subscription (via email)
- **Support responses:** Replies to your privacy or support inquiries
- **Note:** We do NOT send marketing emails without your explicit consent

### 2.4 Legal Compliance
- **Compliance:** To comply with legal obligations (e.g., GDPR, tax laws)
- **Protection:** To protect our rights and prevent fraud or abuse

## 3. Third-Party Services

KLARTEXT uses the following third-party services to provide its functionality. Each service processes data according to its own privacy policy:

### 3.1 Azure OpenAI (Microsoft)
- **Purpose:** AI-powered text correction and language translation
- **Data Shared:** Text you input for correction, selected languages
- **Privacy Policy:** https://privacy.microsoft.com/en-us/privacystatement
- **Data Location:** European Union data centers (GDPR-compliant)
- **Retention:** Microsoft does NOT retain your text for AI model training (per our enterprise agreement)

### 3.2 ElevenLabs
- **Purpose:** High-quality text-to-speech audio generation
- **Data Shared:** Corrected text for audio synthesis, selected voice ID
- **Privacy Policy:** https://elevenlabs.io/privacy
- **Data Retention:** ElevenLabs does NOT store your text after audio generation
- **Fallback:** If ElevenLabs is unavailable, we use your device's built-in TTS (no data sharing)

### 3.3 Supabase (PostgreSQL)
- **Purpose:** User authentication, subscription management, and settings storage
- **Data Shared:** Email, user ID, language preferences, voice settings, subscription tier, usage statistics
- **Privacy Policy:** https://supabase.com/privacy
- **Data Location:** European Union (Frankfurt, Germany)
- **Security:** Row Level Security (RLS) ensures you can only access your own data

### 3.4 Stripe
- **Purpose:** Payment processing for premium subscriptions
- **Data Shared:** Email, subscription tier (Stripe also collects payment information directly)
- **Privacy Policy:** https://stripe.com/privacy
- **Compliance:** Stripe is PCI-DSS Level 1 certified for secure payment processing
- **Note:** KLARTEXT never receives or stores your credit card information

### 3.5 Google OAuth
- **Purpose:** Secure authentication (sign-in with Google)
- **Data Shared:** Email address, Google user ID (used only for authentication)
- **Privacy Policy:** https://policies.google.com/privacy
- **Permissions:** We only request email and basic profile access

## 4. Data Storage and Retention

### 4.1 Where Your Data is Stored
- **Account data:** Stored in Supabase (EU data centers, Frankfurt, Germany)
- **Local settings:** Language and voice preferences stored locally on your device
- **Temporary processing:** Text sent to Azure OpenAI and ElevenLabs is processed in EU data centers and NOT retained

### 4.2 How Long We Keep Your Data
- **Account information:** Retained until you delete your account
- **Usage statistics:** Reset daily, no historical data stored beyond current day
- **Text input:** NOT stored permanently – processed in real-time only
- **Settings:** Retained until you delete your account or clear app data
- **Error logs:** Retained for up to 90 days for debugging purposes

### 4.3 Data Security
We implement industry-standard security measures:
- **Encryption in transit:** All data transmitted via HTTPS/TLS
- **Encryption at rest:** Database stored on encrypted servers
- **Access controls:** Strict authentication and row-level security
- **Regular backups:** Automated backups with encryption
- **Incident response:** Monitoring for security breaches with notification procedures

## 5. Your Rights Under GDPR

As a user in the European Union, you have the following rights:

### 5.1 Right to Access
You can view all your stored data through the app's Settings screen.

### 5.2 Right to Data Portability (Export)
**How to export:** Go to **Settings → Privacy → Export My Data**
- You will receive an email with a JSON file containing all your data:
  - Account information (email, user ID)
  - Settings (language, voice preferences, subscription tier)
  - Usage statistics (current day's AI and TTS usage counts)
  - Export timestamp

### 5.3 Right to Erasure (Delete Account)
**How to delete:** Go to **Settings → Privacy → Delete My Account**
- This action is **permanent and irreversible**
- All your data will be deleted within 30 days:
  - Account information removed from Supabase
  - Google OAuth association revoked
  - Stripe subscription cancelled (if active)
  - Usage statistics deleted
- **Note:** Some data may be retained for legal/tax compliance (e.g., payment records for 7 years per EU law)

### 5.4 Right to Rectification
You can update your settings (language, voice preferences) at any time through the Settings screen.

### 5.5 Right to Restrict Processing
Contact us at hallo@headon.pro to request restricted processing of your data.

### 5.6 Right to Object
You can object to data processing for specific purposes by contacting hallo@headon.pro.

### 5.7 Right to Withdraw Consent
You can withdraw consent for data processing by deleting your account through the app.

### 5.8 Right to Lodge a Complaint
You have the right to file a complaint with your local data protection authority if you believe your rights have been violated.

## 6. Children's Privacy

KLARTEXT is intended for users aged 16 and older. We do not knowingly collect data from children under 16. If you believe we have inadvertently collected data from a child under 16, please contact us immediately at hallo@headon.pro, and we will delete it promptly.

## 7. International Data Transfers

For users outside the European Union:
- Your data may be transferred to and processed in EU data centers (Germany)
- We rely on Standard Contractual Clauses (SCCs) for international transfers as approved by the European Commission
- Third-party services (Azure, ElevenLabs, Stripe) are GDPR-compliant and use SCCs

## 8. Cookies and Tracking

KLARTEXT does NOT use cookies or third-party tracking technologies. We do not track your behavior across websites or apps.

**Analytics:** We use minimal error tracking (Expo built-in) to capture app crashes. This does NOT include advertising identifiers or cross-app tracking.

## 9. Changes to This Privacy Policy

We may update this Privacy Policy from time to time to reflect changes in our practices or legal requirements. When we make significant changes:
- We will update the "Last Updated" date at the top
- For material changes, we will notify you via email or in-app notification
- Your continued use of the app after changes constitutes acceptance of the updated policy

**Version history:** Previous versions of this policy are available upon request at hallo@headon.pro.

## 10. Legal Basis for Processing (GDPR)

We process your personal data based on the following legal bases:

- **Contract performance:** Processing necessary to provide the AI correction and TTS services you requested
- **Consent:** For optional features like auto-play or auto-detect language
- **Legitimate interests:** For service improvement, error tracking, and fraud prevention (where not overridden by your rights)
- **Legal obligation:** For compliance with tax laws, GDPR requirements, and other regulations

## 11. Data Sharing and Disclosure

We do NOT sell, rent, or share your personal data with third parties except:
- **Service providers:** Azure OpenAI, ElevenLabs, Supabase, Stripe (as described in Section 3)
- **Legal requirements:** If required by law, court order, or government regulation
- **Protection of rights:** To enforce our Terms of Service, prevent fraud, or protect user safety
- **Business transfers:** In the event of a merger or acquisition (you will be notified in advance)

## 12. Your Choices and Controls

### 12.1 Account Settings
- Change language, voice, and TTS settings anytime in **Settings**
- Enable/disable auto-detect language
- Enable/disable TTS auto-play

### 12.2 Subscription Management
- Upgrade or downgrade your plan through **Settings → Subscription**
- Cancel subscription via Stripe Customer Portal (accessible in Settings)

### 12.3 Communication Preferences
- Opt out of non-essential emails by contacting hallo@headon.pro
- Service-critical emails (e.g., subscription expiration) cannot be disabled

### 12.4 Data Deletion
- Delete your account and all data through **Settings → Privacy → Delete My Account**

## 13. Questions and Support

If you have questions about this Privacy Policy or your data:

- **Email:** hallo@headon.pro
- **Response time:** We aim to respond within 5 business days
- **Data requests:** For data export or deletion, allow up to 30 days for processing

For technical support (non-privacy related), contact hallo@headon.pro.

---

**Summary:** KLARTEXT collects only essential data to provide AI text correction and text-to-speech services. We use trusted third-party providers (Azure OpenAI, ElevenLabs, Supabase, Stripe) and give you full control over your data. You can export or delete your data at any time through the app's Settings. We are GDPR-compliant and committed to protecting your privacy.

Thank you for trusting KLARTEXT with your data.
