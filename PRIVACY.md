# VoidBot - Privacy Policy

**Last updated: 8 September 2026**

VoidBot ("the bot", "we", "us") is a community-management bot operated by
the **Void Lounge** staff for the **Void Lounge** Discord server.
This policy explains what data the bot collects, how it is used, how long it is kept,
and the choices you have. It applies only to the bot - your use of Discord itself is
governed by [Discord's Privacy Policy](https://discord.com/privacy).

We handle this data under our **legitimate interests** in running the Void Lounge
community: organising and summarising group events, maintaining role and staff
displays, recording community donations, and enforcing the server's rules about run
signups. Staff members listed as donation recipients provide an in-game account
name for that purpose, and can ask to be taken off the list at any time.

## What we collect and store

VoidBot stores a limited amount of data on its own server (not within Discord) to
provide its features:

- **Discord identifiers** - your Discord user ID and username; for staff, your
  server nickname.
- **Group-event ("progathon") activity** - when you post, lead, or are listed in
  a "looking for group" (LFG) post in designated channels: your user ID (as
  organiser and/or participant) and, if you led the run, your username, together
  with the run's boss, required rank, scheduled time, and the post's
  message/channel IDs.
- **Aggregate role statistics** - counts of how many members hold each rank/role,
  and periodic snapshots of those counts over time. These are **totals**, not tied
  to you individually.
- **Signup role-check records** - if you sign up to a run without the required rank
  role, we record your user ID, which run, and a short note, so the bot can notify
  the run organiser and track repeated occurrences.
- **Staff roster** - for staff members: display name, nickname, and roles, used to
  render a staff listing.
- **Donation records** - if you use the community donation system: your user ID and
  Discord name, and the donation amount, type, date, and the ID of the message the
  bot posts to record it. Donations are of in-game currency and items only; the bot
  never handles real-world money or payment details.
- **Donation recipient list** - if you are a staff member added to the list of people
  who can receive community donations: your user ID, Discord name, and the in-game
  account name and region recorded for you. That account name is shown to members
  choosing where to donate, and appears in the donation posts the bot makes.
- **Personal templates** - if you use the `/template` commands, the text you save
  and the tag you save it under, stored against your user ID until you delete it.
- **Operational mappings** - message and channel IDs the bot uses to link posts to
  the summaries it generates, and a timestamped record of which commands were run
  (the command name and the time, with no user attached).
- **Operational logs** - the bot writes log files on its own server recording what it
  did. These lines can include your Discord username, user ID and nickname, and a
  note of an action involving you, such as a signup role-check or a link you posted
  being validated. Many of the same lines are also posted into a staff-only logging
  channel in the server.

The bot also posts messages in the server that name members: a summary of your LFG
post in the overview channel, a record of a donation in the donation channel, staff
notices about repeated signup issues, and its own operational log lines in a
staff-only logging channel. These are ordinary Discord messages and stay visible in
the server.

## What we do **not** collect

- **The content of your messages, with two narrow exceptions.** LFG posts are read
  only momentarily to extract the details above (boss, rank, time, the members
  tagged); the text itself is not kept. The exceptions: staff can mark a particular
  message for tracking, which stores that message's text so a display can be kept
  in sync, and a link you post in a log channel can appear in the bot's operational
  log when a staff member runs a log check with debug output turned on.
- **Direct message content.** The bot only *sends* DMs (for example, notifying a run
  leader about a signup issue); it does not read or store your DMs.
- We do **not** use any data to train artificial-intelligence or machine-learning
  models.
- We do **not** collect Discord presence, online/offline status, or Discord activity
  status such as the game you are playing. The bot can see how many members are
  connected to voice channels so it can report a count, and does not record who.

## How we use your data

We use the data above only to operate Void Lounge community features:

- Posting clean summaries of LFG posts into a read-only overview channel.
- Tracking community progression events and generating aggregate statistics/reports
  for organisers.
- Maintaining role-count and staff-roster displays.
- Verifying that members who sign up to runs hold the required rank, and notifying
  organisers of issues.
- Validating posted combat-log links.
- Recording community donations.

## How we share your data

We do **not** sell your data, and we do **not** share it with third parties, except:
(i) with infrastructure/service providers strictly necessary to run the bot;
(ii) where required by law; or (iii) where you expressly ask us to.

One staff command sends data to a separate service in order to do its work: when a
staff member runs an account check, the combat-log link and the in-game account name
being checked are passed to a log-analysis service under (i) above, which returns the
result. That service keeps an access record of each check for seven days, holding the
account name, the combat-log link and the calling server's IP address. No other bot
data is sent to external services beyond what this policy describes.

## Storage and security

Data is stored in files on an access-restricted server controlled by the Void
Lounge staff and is not publicly accessible. We use commercially reasonable
administrative and technical measures to protect it, including restricting access
to that server. No method of storage is perfectly secure, but we take reasonable
steps to safeguard your information.

If we become aware of unauthorised access to personal data the bot holds, we will
investigate, take reasonable steps to contain and remedy it, and give whatever
notifications are required by applicable law or by Discord's developer requirements.

## How long we keep it

We keep data only as long as it is needed to provide these features:

- Event/progathon and donation records are retained as historical community
  statistics, and are deleted on request.
- Aggregate role counts and snapshots are retained as historical statistics. They
  are totals only and hold nothing about you individually.
- Signup role-check records are kept for as long as they remain relevant to
  moderating the server, and are deleted on request.
- Saved templates are kept until you delete them with `/template delete`.
- Staff roster entries are kept while a person is staff. If a nickname was set for
  them, that entry is kept afterwards so the nickname is not lost.
- Operational logs are kept on the server for troubleshooting. They are not
  organised by member and are not used to build any profile of you.
- We delete data that is no longer necessary, we delete your data on request (with
  the exceptions set out below), and if the bot ceases operating we delete the
  data it holds.

## Your rights and choices

You may, at any time, ask to **access**, **correct**, or **delete** the data the bot
holds about you:

- Open a ticket in the Void Lounge server, **or**
- Contact us at **voidloungegw2@gmail.com**, or ask a member of the Void Lounge staff.

We normally respond within one month. Where a request is complex, or where there are
several, we may need longer, and we will tell you if so. To protect your data we may
ask you to confirm that you control the Discord account a request relates to; we will
never ask for your password or a token.

On a deletion request we remove your progathon and donation records, your signup
role-check records, your entry on the donation-recipient list, your saved templates,
and the LFG summaries and donation posts the bot made that name you. The staff
roster is rebuilt from current Discord roles, so it clears itself once you are no
longer staff; any nickname stored for you is removed on request.

Separately, a deletion request is not applied to the operational logs described above.
The log files on our server are not kept as a member database and are not indexed or
routinely searched by member. The copies posted into the staff-only logging channel
can be searched within Discord, but each message there batches together unrelated
lines about many people, so one member's line cannot be removed without deleting
other members' entries with it. These logs exist for troubleshooting rather than to
answer questions about you.

Messages the bot has already sent are treated separately from the records it keeps.
Deleting your records does not automatically remove notices the bot posted in staff
channels at the time, and we do not routinely go back through those channels. A
direct message the bot sent, such as a note to a run organiser about a signup issue,
is beyond our reach entirely: it sits in a private conversation between the bot and
the person who received it. The same applies to anything another member has quoted
or screenshotted elsewhere.

Depending on where you live, applicable privacy laws may give you further rights,
including access, correction, deletion, restriction of processing, objection,
portability, and the right to lodge a complaint with the data protection authority
for your country. We apply these rights regardless of where you live, subject to the
exceptions above.

## Children

The service is intended for users who meet Discord's minimum age requirement for your
country. We do not knowingly collect data from anyone below that age; if you believe a
child has provided data, contact us and we will remove it.

## Changes to this policy

We may update this policy from time to time. The "Last updated" date above reflects the
current version; significant changes will be announced in the Void Lounge server.

## Contact

Questions or requests: **voidloungegw2@gmail.com**, or reach the Void Lounge staff directly
in the server.
