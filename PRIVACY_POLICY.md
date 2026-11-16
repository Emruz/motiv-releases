# Motiv privacy policy

_Last updated 15 November 2026. Also published at https://emruz.com/motiv/privacy._

Motiv is a desktop app published by Shahin Pirooz, doing business as Emruz. It runs on your computer and has no analytics. The publisher doesn't receive, store or have access to your recordings, transcripts or meeting data. Buying and managing Pro on emruz.com is covered by the [emruz.com privacy policy](https://emruz.com/privacy).

## What stays on your computer

- **Audio recordings** of your meetings, in the folder you choose (Settings > Storage).
- **Transcripts, summaries, chat conversations, action items** and meeting details, in a local database.
- **Speaker information:** speaker labels and names for each meeting.
- **Voiceprints:** created only when you tick "Recognise this voice" for a speaker. A voiceprint is a numeric representation of a voice used to recognise that person in later meetings. Voiceprints are biometric data; they are stored only in Motiv's local database, never uploaded, and can be deleted at any time in Settings > Meetings. Ask people for consent before saving their voiceprint, as the law where you or they live may require it.
- **Your subscription**, if you have Pro: the subscription ID and a signed lease, in the macOS Keychain, Windows Credential Manager or, on Linux, the Secret Service (GNOME Keyring or KWallet; a file only your user can read if neither is available).
- **Settings**, including Names & terms, and **calendar sign-ins** (stored in the macOS Keychain, Windows Credential Manager or Linux Secret Service).

Transcription and speaker identification run entirely on your computer. Motiv downloads model files (for transcription, speaker identification and, if you choose it, the built-in summary engine) from public model repositories; those downloads send no personal data.

## What leaves your computer, and only when you choose

- **Summary and chat providers.** If you choose a cloud provider (for example Anthropic Claude, OpenAI, Groq, OpenRouter or a custom endpoint), the meeting's transcript text, your question and participant names are sent to that provider to produce the answer, under that provider's terms and privacy policy. Audio is never sent. Local providers (Ollama, the built-in engine) keep everything on your computer.
- **Apple Calendar (macOS).** If you allow it, Motiv reads events from the calendars on your Mac through macOS, on your computer only.
- **Microsoft 365 and Google calendars.** If you connect them, Motiv reads your calendar events (titles, times, organizer, attendees and their responses, meeting links) and, if you turn it on, Microsoft Teams attendance reports and the Teams transcripts of meetings you organized, directly from Microsoft or Google to your computer. Motiv only reads; it never creates, changes or deletes calendar or meeting data. This data is used only to name recordings, show who was in a meeting, name speakers, and help the summary use correct names.
- **Transcript files you import.** A .vtt or .srt file you choose is read on your computer to name speakers, and is not sent anywhere.
- **Browser tabs (macOS).** To notice a Google Meet call, while a browser is using the microphone Motiv reads that browser's open tab addresses on your computer, with your permission. It looks only for Meet addresses and does not store or send them.
- **Email.** "Send by email" opens your own email app with the summary; nothing is sent until you send it.

## Motiv Pro check-in

With Pro, Motiv contacts emruz.com when you register a computer and about once a day afterwards, to keep Pro on. It sends only your subscription ID, a random ID created for the computer (not derived from its hardware), the Motiv version and the operating system family (macOS, Windows or Linux), plus the computer's name only if you choose to share it. It never sends recordings, transcripts, summaries, meeting details or how you use Motiv. Without Pro, Motiv doesn't contact emruz.com.

## Google user data

Motiv's use of information received from Google APIs adheres to the [Google API Services User Data Policy](https://developers.google.com/terms/api-services-user-data-policy), including the Limited Use requirements. Motiv requests read-only access to Google Calendar (`calendar.readonly`) and your email address, uses it only for the features described above, doesn't transfer it to anyone, doesn't use it for advertising, and doesn't allow humans to read it.

## Deleting your data

- Delete a meeting in Motiv to remove its transcript, summary, chat, speakers and calendar link.
- Settings > Storage removes old recording audio automatically if you set a limit; you can also delete the recordings folder.
- Settings > Meetings deletes voiceprints, one or all.
- Settings > Calendars > Disconnect removes calendar sign-ins. To revoke access completely, also remove Motiv at [myaccount.microsoft.com](https://myaccount.microsoft.com) or [myaccount.google.com/permissions](https://myaccount.google.com/permissions).
- Uninstalling Motiv and deleting its data folder (`~/Library/Application Support/com.pirooz.motiv` on macOS, `%APPDATA%\com.pirooz.motiv` on Windows, `~/.local/share/com.pirooz.motiv` on Linux) removes everything else.
- To remove your subscription and computers from emruz.com, see the [emruz.com privacy policy](https://emruz.com/privacy).

## Contact

Questions about this policy: [info@emruz.com](mailto:info@emruz.com).

Motiv © 2026 Shahin Pirooz, doing business as Emruz. All rights reserved.
