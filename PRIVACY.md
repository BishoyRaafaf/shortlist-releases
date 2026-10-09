# Shortlist privacy policy

*Last updated: 9 October 2026*

Shortlist is a free Windows app made by Bishoy Raafat ("I"). This page explains, in plain language, what data the app handles and where it goes.

**The short version:**
- Your CV, searches, tracker, letters and keys stay on your PC.
- You don't need an account.
- There are no ads, and your data is never sold.

## Data that stays on your PC

Everything you put into Shortlist is stored only on your computer, in `%LocalAppData%\ShortlistData`:
- your CVs and profiles,
- your searches and saved searches,
- the jobs you find,
- your tracker, cover letters and tailored CVs,
- your settings,
- your API keys, which are encrypted with your Windows account.

You can delete all of it at any time from **Settings → Privacy & community → Delete all my data**, or by uninstalling the app and deleting that folder.

## Data Shortlist sends, and to whom

| Where it goes | What is sent | When |
|---|---|---|
| **Job sites** (e.g. Adzuna, Arbeitnow, Remotive, company career pages; LinkedIn/Indeed via JSearch if you add that key) | Your search words, locations and filters | When you search |
| **Groq** (AI provider, only if you add your own Groq key) | The CV and job text needed for the AI feature you use (reading your CV, fit checks, letters, CV tailoring) | When you use an AI feature. Groq's own privacy policy applies |
| **Shortlist community server** (runs on Cloudflare) | An anonymous install id: a random number, with no name, email or device details | Once, when the app first starts |
| | Scam and ghost-job reports you make: company name, website domains, job title, link and the reason you typed | When you report a job |
| | Feedback you send: your message and its type, plus your email and name **only if you type them**, the app version, your Windows version, and **only if you tick them** a picture of the Shortlist window and recent app logs (emails, keys and your Windows user name are removed from logs first) | When you press Send |
| | Anonymous feature counts, e.g. "deep search used" or "cover letter written". Never content | **Only if you switch on "Share anonymous usage"** |
| **Sentry** (crash reporting) | Technical error details with personal information removed | **Only if you switch on "Send crash reports"** |
| **GitHub** | A check for app updates | Every few hours |

The community server also stores a one-way hash of the network you connect from (for example, a scrambled version of your internet provider's address range). It never stores your IP address itself. The hash is used only to limit spam and to make sure one person can't flag an employer alone.

## How feedback is used

Feedback is emailed to me through Resend (an email service) and kept on the community server so it isn't lost. If you left your email, I use it **only** to reply to you. It's never added to a mailing list or shared.

## Community reports

- An employer appears in other users' warnings only after **several different users on different networks** report it.
- Reports never include who you are.
- Employers can ask for a wrong flag to be removed (see "Wrongly flagged?" on the [Shortlist page](README.md#wrongly-flagged)).

## How long data is kept

- Feedback and reports are kept for as long as they're useful for running the community list, at most two years.
- Usage counts are kept at most one year.
- To have your feedback deleted, send a message from the in-app Feedback form or open a GitHub issue. Mention the email you used, if any.

## Children

Shortlist is meant for job seekers aged 16 and over.

## Changes

If this policy changes, the date at the top changes, and the release notes for that version mention it.

## Contact

Use the **Feedback** page in the app, or [open an issue](https://github.com/BishoyRaafaf/shortlist-releases/issues) on GitHub.
