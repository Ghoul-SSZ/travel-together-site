---
title: Privacy policy · Travel Together
---

# Privacy policy

**Travel Together** · Last updated 12 October 2026

Travel Together is an app for planning a trip with other people, splitting what it costs, and chatting about it. This page says what the app collects, why, who else handles it, how long it’s kept, and what you can ask for. It applies to the Android and iOS apps.

## Who is responsible

The data controller is Steven Shidi Zhou, an individual developer in Sweden. Write to [privacy@traveltogether.now](mailto:privacy@traveltogether.now) about anything on this page.

If you think your data is being mishandled, you can complain to the Swedish data protection authority, [Integritetsskyddsmyndigheten (IMY)](https://www.imy.se/en/), or to the authority where you live.

You must be at least 16 to use Travel Together.

## What the app collects, and why

The legal basis for each item is in brackets. “Contract” means it’s needed to run the app you signed up for (GDPR Article 6(1)(b)). “Legitimate interest” is Article 6(1)(f). “Consent” is Article 6(1)(a).

**Your account.** Your email address, the sign-in method you used (Google, or a one-time code sent to your email), and the display name you choose. If you sign in with Google, Google also passes your name, email and profile picture link, which are stored with your login; the app only uses the name, to suggest your display name. Your email is never shown to other people. Your display name is shown to people in your trips and to anyone you message. *(Contract)*

**What you put in a trip.** Trips, their members, expenses and how they’re split, line items, settlements and payment confirmations, receipt photos, trip photos (with the date each was taken, read from the photo), notes and their attachments, Bookings (including confirmation numbers and ticket codes), and the group chat. Everyone in the trip can see all of it. *(Contract)*

**Direct messages.** Messages and photos you send in a direct message. Only you and the other person can see them. *(Contract)*

**Notifications.** If you allow notifications, the app stores your phone’s push token and whether it’s Android or iOS, plus your notification settings. Signing out removes the token. *(Contract)*

**Sign-in sessions.** While you’re signed in, the hosting provider stores your IP address and your device’s user agent with your session, for security and to keep you signed in. They’re kept until you sign out or delete your account. The provider’s request logs also hold IP addresses for up to one day. *(Legitimate interest: keeping accounts secure)*

**Feedback you send.** If you use Send feedback, the app stores your message, its category, the trip you sent it from, the app version, build and update id, and your phone’s operating system, version and model. The message, your display name, your user id, the trip id and the same app and device details are also copied into an issue on the developer’s private GitHub repository, so the developer can track it. Your email is not included. *(Legitimate interest: fixing what you report)*

**Crash reports.** When the app crashes, it sends a report to Sentry: the error, the phone model, operating system and the app’s state at the time. Reports carry no user id, no email, no screenshots and no screen recordings. *(Legitimate interest: finding and fixing crashes)*

**AI usage counts.** For each AI request, the app records which feature it was, how many tokens it used and what it cost, against your account. No content is kept in these records. They enforce daily limits. *(Contract)*

**On your phone.** The app keeps some things in the phone’s own storage: a cache of your trips, the trip you last opened, Planner drafts, a pending invite, and your answer about AI (below). Signing out clears them. Preferences such as appearance stay on the phone.

The app has **no analytics, no advertising and no tracking across apps or websites.** It never asks for your location, contacts or microphone. It uses the camera only to photograph a receipt. Trip and message photos come from your photo library, and only the ones you pick.

## AI features (Claude, by Anthropic)

Receipt scanning, Split Chat and the Planner use Claude, an AI model made by Anthropic. They send data to Anthropic **only after you allow it in the app.** The app asks the first time you use one of them, and you can change your answer any time in Settings → AI & privacy → *Send to Claude*. Your answer is kept on that phone and forgotten when you sign out, so you’re asked again next time. If you decline, the features stay visible but off. *(Consent)*

What is sent, through Travel Together’s server:

- **Receipt scanning:** the receipt photo.
- **Split Chat:** your Split Chat messages, the receipt as the app read it, and the display names of the trip’s members, so Claude can tell who had what.
- **Planner:** the text of your Brief and the files you attach to it (images, PDFs).

Split Chat sends other members’ display names on your consent alone. We rely on legitimate interest for that: the names are needed to split a shared bill, and nothing else about them is sent.

Turning *Send to Claude* off stops future sends. It doesn’t recall what was already sent.

Anthropic may not train its models on this data ([Commercial Terms](https://www.anthropic.com/legal/commercial-terms), effective 17 June 2025). It deletes inputs and outputs within 30 days. If its automated safety systems flag a request under its Usage Policy, it may keep it for up to 2 years ([Anthropic’s retention article](https://privacy.claude.com/en/articles/7996866-how-long-do-you-store-my-organization-s-data)). Travel Together has no zero-data-retention agreement with Anthropic.

If an AI answer is wrong or inappropriate, use **Report** on the Split Chat reply or Planner Draft. It opens Send feedback with the AI’s output filled in, and goes through the feedback channel described above.

## Photos and files

Photos and receipts are resized and re-encoded on your phone before upload. This removes their embedded metadata, including GPS location. PDFs and other attachments are uploaded exactly as you picked them, so any metadata inside them is kept.

## Notifications on the lock screen

Notifications are sent through Expo’s push service, then Google (Firebase Cloud Messaging) on Android or Apple (Apple Push Notification service) on iPhone. They can show the sender’s name and the first 140 characters of a chat or direct message, the title of a note you were mentioned in, a trip’s name, and payment notices (never amounts). Anyone who can see your lock screen can read them. You can turn notifications off in the app or in your phone’s settings.

## Who else handles your data

These companies process data for Travel Together. Where they handle it outside the EU, the transfer is covered by the EU’s Standard Contractual Clauses (SCCs), by the EU–US Data Privacy Framework (DPF), or both.

| Processor | What for | Where | Transfer safeguard |
|---|---|---|---|
| Supabase | Database, sign-in, file storage, server functions | Ireland (EU) | SCCs, for any access from outside the EU |
| Anthropic | AI features, only after you allow them | USA | SCCs |
| Google | Google sign-in; Firebase Cloud Messaging for Android notifications | USA | DPF and SCCs |
| Apple | Notifications on iPhone | USA | SCCs |
| Expo (650 Industries) | Relays push notifications; delivers app updates | USA | DPF |
| Resend | Sends sign-in code emails | USA | DPF and SCCs |
| Sentry | Crash reports | Germany (EU) | DPF and SCCs, for any access from outside the EU |
| GitHub | Holds copies of feedback you send | USA | DPF and SCCs |

When the app downloads an update, Expo sees your IP address and phone platform, as any download server does.

Nothing is sold, and nothing is shared for advertising.

## How long data is kept

- **Account details** are kept until you delete your account.
- **Trip content** is kept as long as the trip exists. A trip is deleted when its owner deletes it (if it’s empty or they’re the only one left), or when every remaining member agrees to delete it. A request to delete a trip lapses if not everyone approves within 7 days.
- **Uploaded files that nothing uses**, such as a photo you picked and then abandoned, are deleted after 24 hours. Unused note and Planner files are deleted after 30 days.
- **Sign-in sessions** last until you sign out. Request logs are kept for up to a day.
- **AI data at Anthropic:** see above, 30 days by default.

## Deleting your account

You can delete your account in the app, or by email. See [Delete your account](/delete-account) for how.

**What is deleted:** your email address and sign-in identities, your sessions, your push tokens and notification settings, your AI usage records, your feedback records in the app, and any trip that nobody else has been a member of. Your display name is replaced with “Deleted account” everywhere. One more case: if a trip has an open request to delete it and you’re the last member who hasn’t approved, deleting your account completes the request and the trip is deleted for everyone.

**What stays with the people you shared it with,** shown as from “Deleted account”: expenses, settlements, group chat messages, photos, notes, Bookings, and both sides of your direct messages. Removing them would change records other people rely on, such as what everyone owes. We keep them on the basis of legitimate interest. Direct message threads with a deleted account become read-only.

Feedback already copied to GitHub stays there. If you want specific content removed, such as a photo, a message or a GitHub feedback issue, email [privacy@traveltogether.now](mailto:privacy@traveltogether.now). Each request is handled by hand within 30 days.

## Your rights

Under the GDPR you can ask to:

- see the data held about you, and get a copy (access, portability)
- correct it
- have it deleted (erasure)
- limit how it’s used (restriction)
- object to uses based on legitimate interest
- withdraw your AI consent, which you can do yourself in Settings → AI & privacy

Email [privacy@traveltogether.now](mailto:privacy@traveltogether.now) from the address on your account. You’ll get an answer within 30 days. For a quick partial copy, any trip member can open Settings from that trip and use Export trip data, which saves the trip’s expenses and settlements as a CSV file.

You can also complain to IMY, as above.

## Changes to this policy

Material changes are announced in the app or to beta testers before they take effect. The date at the top shows when this page last changed.
