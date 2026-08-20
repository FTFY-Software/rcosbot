---
layout: default
title: Privacy Policy
---

# Privacy Policy

**Effective 20 August 2026.**

rcosbot ("the bot") is a moderation and audit-logging bot operated by the staff of the AquaFPS
Discord server. This policy describes what the bot processes, why, and how long it is kept. You can
see a short version at any time inside Discord by running `/privacy`.

## Message content

Every message posted in a channel the bot can see is checked, once, at the moment it is posted, to
enforce the server rules: prohibited slurs, links to known scam and phishing domains, misuse of
`@everyone` / `@here`, and per-channel topic rules (channels that accept only links, only Twitch
clips, only YouTube links, or only image attachments).

This check happens in memory and the message is then discarded. Message content is **not** written
to a database, **not** used to build a profile of you, **not** used for advertising or model
training, and **not** sold or shared with anyone.

## Moderator audit log

When a message is deleted or edited, a copy is posted to a staff-only channel inside the same
Discord server, including the message text, its author, the channel, and where Discord makes it
available, which moderator acted. Bans and unbans, joins and leaves, and role, nickname, username
and avatar changes are recorded the same way.

These records exist so moderators can review each other's actions and so reported content can still
be examined after the author deletes it. They stay inside Discord and are visible only to server
staff.

## Joins

When you join the server the bot records your user ID and tag, the time you joined, your account's
creation date, and which invite link was used together with who created it. Invite attribution is
how raids and ban-evasion are traced back to a source.

## What is not collected

The bot does not receive or read direct messages, does not access voice channels, and does not
track presence or activity status. There is no analytics service, no advertising network, and no
third-party data processor.

## Third parties

A YouTube link posted in a designated YouTube channel is fetched from YouTube so the bot can read
the video's public title, description and keywords and confirm the video is on topic. Only the link
you posted is sent, only to YouTube, and the response is not stored.

## Operational logs

The bot writes operational logs on its host for debugging. These record that an event happened and
its shape — for example that a message of 41 characters was deleted — but **not** the message text.
Where an error occurs while parsing something you posted, the log identifies you by a salted
pseudonym rather than by name or user ID.

## Retention, access and removal

Audit records persist in the staff channel until staff delete them or the channel is cleared. To ask
what is held about you, or to request removal of a specific audit entry, contact the server
moderators in Discord. Leaving the server stops all further processing.

## Changes

Material changes to this policy will be announced in the server. The revision history of this page
is public at <https://github.com/FTFY-Software/rcosbot>.

## Contact

Contact the AquaFPS server moderators in Discord, or [CONTACT EMAIL].
