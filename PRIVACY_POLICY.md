# Motiv privacy policy

_Last updated: 6 November 2026_

Motiv is a desktop app that runs on your computer. It has no user accounts, no servers and no analytics. The publisher of Motiv does not receive, store or have access to any of your data.

## What stays on your computer

- **Audio recordings** of your meetings, in the folder you choose (Settings > Storage).
- **Transcripts, summaries, chat conversations, action items** and meeting details, in a local database.
- **Speaker information**: speaker labels and names for each meeting.
- **Voiceprints**: created only when you tick "Recognise this voice" for a speaker. A voiceprint is a numeric representation of a voice used to recognise that person in later meetings. Voiceprints are biometric data; they are stored only in Motiv's local database, never uploaded, and can be deleted at any time in Settings > Meetings. Ask people for their consent before saving their voiceprint, as the law where you or they live may require it.
- **Your subscription**, if you have Motiv Premium: the subscription ID and a signed lease, in the macOS Keychain or Windows Credential Manager.
- **Settings**, including Names & terms, and **calendar sign-ins** (stored in the macOS Keychain or Windows Credential Manager).

Transcription and speaker identification run entirely on your computer. Motiv downloads model files (for transcription, speaker identification and, if you choose it, the built-in summary engine) from public model repositories; those downloads send no personal data.

## What leaves your computer, and only when you choose

- **Summary and chat providers.** If you choose a cloud provider (for example Anthropic Claude, OpenAI, Groq, OpenRouter or a custom endpoint), the transcript text of the meeting, your question, and participant names are sent to that provider to produce the answer, under that provider's terms and privacy policy. Audio is never sent. Local providers (Ollama, the built-in engine) keep everything on your computer.
- **Apple Calendar (macOS).** If you allow it, Motiv reads events from the calendars on your Mac through macOS, on your computer only.
- **Calendars.** If you connect Microsoft 365 or Google, Motiv reads your calendar events (titles, times, organizer, attendees and their responses, meeting links) and, if you turn it on, Microsoft Teams attendance reports, directly from Microsoft or Google to your computer. Motiv only reads; it never creates, changes or deletes calendar data. This data is used only to name recordings, show who was in a meeting, and help the summary use correct names.
- **Email.** If you use "Send by email", Motiv opens your own email app with the summary; nothing is sent until you send it.

## Motiv Premium check-in

With Motiv Premium, Motiv contacts emruz.com when you register this computer and about once a day afterwards, to keep Premium on. It sends only your subscription ID, a random ID created for this computer (not derived from its hardware), the Motiv version and the operating system family (macOS or Windows), plus the computer's name only if you choose to share it. It never sends recordings, transcripts, summaries, meeting details or how you use Motiv. Registering a computer happens on emruz.com, under its own privacy policy. Without Premium, Motiv does not contact emruz.com.

## Google user data

Motiv's use of information received from Google APIs adheres to the [Google API Services User Data Policy](https://developers.google.com/terms/api-services-user-data-policy), including the Limited Use requirements. Motiv requests read-only access to Google Calendar (`calendar.readonly`) and your email address, uses it only for the features described above, does not transfer it to anyone, does not use it for advertising, and does not allow humans to read it.

## Deleting your data

- Delete a meeting in Motiv to remove its transcript, summary, chat, speakers and calendar link.
- Settings > Storage removes old recording audio automatically if you set a limit; you can also delete the recordings folder.
- Settings > Meetings deletes voiceprints, one or all.
- Settings > Accounts > Disconnect removes calendar sign-ins. To revoke access completely, also remove Motiv at https://myaccount.microsoft.com or https://myaccount.google.com/permissions.
- Uninstalling Motiv and deleting its data folder (`~/Library/Application Support/com.pirooz.motiv` on macOS, `%APPDATA%\com.pirooz.motiv` on Windows) removes everything else.

## Contact

Questions about this policy: open an issue at https://github.com/Emruz/motiv-releases/issues.
