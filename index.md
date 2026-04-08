# Applydex Privacy Policy

**Last Updated: April 5, 2026**

## What Applydex Does

Applydex is a Chrome extension that analyzes LinkedIn job postings to detect potentially fraudulent or "ghost" job listings using AI.

## Data We Collect

### 1. Account Information
- **Google Account**: Email address, name, and profile picture (via Google Sign-In)
- **Purpose**: To create and manage your Applydex account

### 2. LinkedIn Job Data
- Job titles, company names, locations, descriptions, and posting metadata from LinkedIn job pages you visit
- **Purpose**: To analyze jobs for ghost job indicators and provide match scores
- **Note**: We only access job pages within LinkedIn's `/jobs/` paths

### 3. Resume & Profile Data
- Uploaded resume files (PDF, DOCX, TXT)
- Extracted skills, experience, and job preferences
- **Purpose**: To match your profile against job listings and generate tailored documents

### 4. Application Tracking Data
- Jobs you save, apply to, or track through Applydex
- Application stages and notes
- **Purpose**: To help you manage your job search pipeline

### 5. Payment Information
- Processed securely by Razorpay (our payment processor)
- **We do not store** credit card numbers, bank details, or payment credentials
- We store only: subscription ID and plan status

## How We Use Your Data

- Analyze job postings for ghost job indicators using AI (Anthropic Claude)
- Match jobs against your resume profile
- Generate tailored resumes, cover letters, and interview prep materials
- Track your job application pipeline
- Send daily email digests (if enabled by you)

## Where Your Data Is Stored

- **Backend Server**: Hosted on Railway.app (US-based cloud infrastructure)
- **Database**: Supabase (PostgreSQL, hosted on AWS)
- **Local Storage**: Auth tokens and daily scan stats are cached locally in your browser

## Data Sharing

We do **NOT** sell, rent, or share your personal data with third parties. Your data is only shared with:

- **Anthropic (Claude AI)**: Job descriptions are sent for AI analysis (no personal data included)
- **Razorpay**: Payment processing only (if you upgrade to Pro)
- **Supabase**: Database hosting provider
- **Google**: Authentication only (via OAuth)

## Data Retention & Deletion

- Your data is retained as long as your account is active
- You can request complete deletion of your account and all associated data by emailing **privacy@applydex.app**
- Upon deletion, all personal data is permanently removed within 30 days

## Your Rights

You have the right to:
- **Access**: Request a copy of your personal data
- **Correction**: Update or correct your information
- **Deletion**: Request permanent deletion of your account and data
- **Portability**: Export your application tracking data (CSV export available in-app)

## Security

- All data is transmitted over HTTPS (TLS encryption)
- Authentication tokens are stored securely in Chrome's local storage
- Backend API endpoints require authentication
- Payment processing is handled by PCI-compliant Razorpay

## Children's Privacy

Applydex is not intended for users under 13 years of age. We do not knowingly collect data from children.

## Changes to This Policy

We may update this policy from time to time. Changes will be posted on this page with an updated date.

## Contact

For privacy questions or data requests:
- Email: **privacy@applydex.app**
