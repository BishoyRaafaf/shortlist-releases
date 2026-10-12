# Shortlist privacy policy

*Last updated: 13 October 2026*

Shortlist is a free Windows app made by Bishoy Raafat ("I"). This page explains, in plain language, what data the app handles and where it goes.

**The short version:**
- Your CV, searches, tracker, letters and keys stay on your PC.
- You don't need an account.
- There are no ads, and your data is never sold.

## Data that stays on your PC

Everything you put into Shortlist is stored only on your computer, in `%LocalAppData%\ShortlistData`:
- your CVs and profiles,
- your portfolio links and the text Shortlist read from them and from a portfolio file you added,
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
| **Groq** (AI provider, only if you add your own Groq key) | The CV, portfolio and job text needed for the AI feature you use (reading your CV or portfolio, fit checks, letters, CV tailoring). Links are sent without tracking parts | When you use an AI feature. Groq's own privacy policy applies |
| **Portfolio sites you add** (e.g. Behance, GitHub, your own site) | A normal page request, the same as opening the page in a browser | When Shortlist reads your portfolio |
| **Shortlist community server** (runs on Cloudflare) | An anonymous install id: a random number, with no name, email or device details | Once, when the app first starts |
| | Your country, which Cloudflare works out from your connection. It only goes into daily totals, such as "3 new installs from Egypt" or "40 hours of Shortlist being open in Germany", and is never stored with your install id or anything else about you | When the app first starts, and with its hourly check while it is open |
| | Scam and ghost-job reports you make: company name, website domains, job title, link (without tracking parts) and the reason you typed | When you report a job |
| | Feedback you send: your message and its type, plus your email and name **only if you type them**, the app version, your Windows version, and **only if you tick them** a picture of the Shortlist window and recent app logs (emails, keys and your Windows user name are removed from logs first) | When you press Send |
| | Anonymous feature counts, e.g. "deep search used" or "cover letter written". Never content | **Only if you switch on "Share anonymous usage"** |
| | Nothing about you: the app downloads the community list, this week's community numbers and a small signed settings file (announcements, the minimum supported version) | A few times a day |
| | Only if the app finds that its own code files were modified by someone else: the app version and a short fingerprint of the modified files | Once per version |
| **Sentry** (crash reporting) | Technical error details with personal information removed | **Only if you switch on "Send crash reports"** |
| **GitHub** | A check for app updates (GitHub version only) | Every few hours |
| **Microsoft Store** | Updates for the Store version, handled by Windows | Managed by the Store |

The community server also stores a scrambled code for the network you connect from (your internet provider's address range) and for your internet provider. Both are made with a secret key that only the server has, so they can't be turned back into a network or an address. Your IP address itself is never stored. They are used only to limit spam and to make sure one person can't flag an employer alone. The network code is removed from your install record after 30 days.

The server also keeps daily totals of the requests it receives, for example how many update checks or rejected requests arrived. They help me spot problems and abuse, and they contain no install id, network or address.

## How feedback is used

Feedback is emailed to me through Resend (an email service) and kept on the community server so it isn't lost. If you left your email, I use it **only** to reply to you. It's never added to a mailing list or shared.

## Community reports

- An employer appears in other users' warnings only after **several different users, on different networks and internet providers,** report it. Reports from installs less than a few days old don't count toward this.
- Reports never include who you are. They carry only the random install id, so the server can count different users.
- Employers can ask for a wrong flag to be removed (see "Wrongly flagged?" on the [Shortlist page](README.md#wrongly-flagged)).

## How long data is kept

- Feedback and reports are kept for as long as they're useful for running the community list, at most two years.
- Feedback is linked to your install id for two days only (to apply the daily limits). After that it can't be connected to your install or your reports.
- Usage counts are kept at most one year.
- Your install record (the random id, the date and the app version) is kept so installs can be counted. Its network code is removed after 30 days.
- To have your feedback deleted, send a message from the in-app Feedback form or open a GitHub issue. Mention the email you used, if any.

## Children

Shortlist is meant for job seekers aged 16 and over.

## Changes

If this policy changes, the date at the top changes, and the release notes for that version mention it.

- 12 October 2026: added daily totals per country and daily request totals (see above). Nothing else changed.
- 12 October 2026, later: network codes now use a secret key and are removed from install records after 30 days. Community reports now also carry a scrambled code for your internet provider, the only new item. Feedback is unlinked from your install after two days, and the install record is now described.
- 13 October 2026 (version 1.1.3): portfolio links you add are read by Shortlist, and with AI on their text goes to Groq like your CV does. Links sent to Groq or in reports no longer include tracking parts.

## Contact

Use the **Feedback** page in the app, or [open an issue](https://github.com/BishoyRaafaf/shortlist-releases/issues) on GitHub.
