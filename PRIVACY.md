# OtterBot Privacy Policy

Last updated: May 6, 2026

## Overview

OtterBot is a Discord bot that provides moderation, ticketing, onboarding, automation, analytics, and community features for Discord servers.

This policy explains what data OtterBot may access, collect, store, use, export, and delete when server administrators enable its features.

## Data We Process

OtterBot may process the following categories of Discord API data when needed to provide its features:

### Basic Discord Metadata

- Guild IDs, channel IDs, role IDs, message IDs, user IDs, usernames, display names, and avatar URLs.
- Server configuration data such as log channel IDs, ticket category IDs, onboarding settings, automation settings, and scheduled message settings.

### Feature-Specific Data

- Moderation:
  moderation cases, warning records, appeals, reports, reasons, evidence links, and staff notes.
- Tickets:
  ticket configuration, ticket records, ticket history, and transcript files generated when a server uses ticket exports.
- Suggestions:
  suggestion content, suggestion status, staff responses, and vote state.
- Onboarding and verification:
  configured verification channel/role settings and verified user references.
- Birthdays:
  user ID, guild ID, date of birth, and birthday delivery state.
- Automation:
  autoresponders, custom commands, scheduled messages, and application templates.
- Analytics:
  aggregated command usage statistics and guild-level usage summaries.
- Voice and temporary runtime state:
  in-memory voice/session state, timers, and caches used to operate the bot.

### Message Content

OtterBot may access message content and attachments only where required for enabled functionality, such as:

- automoderation and anti-spam checks,
- suggestion/report/confession style features,
- moderation logging,
- ticket transcripts,
- legacy text-triggered features still enabled by a server.

OtterBot does not use Discord message content to train machine learning or AI models.

## How We Use Data

OtterBot uses data only to provide, secure, maintain, and improve the bot’s stated functionality, including:

- processing commands and interactions,
- applying server moderation and automation rules,
- generating ticket logs and moderation logs,
- delivering configured reminders, onboarding prompts, and announcements,
- supporting exports, debugging, and incident response,
- maintaining aggregated usage analytics and operational health.

OtterBot does not sell Discord API data and does not disclose Discord API data to data brokers or advertising networks.

## Data Retention

Retention depends on the feature and server configuration:

- Temporary runtime data:
  in-memory caches, timers, and voice/session state are usually cleared on restart or shutdown.
- Config and operational data:
  guild configuration and feature state may remain stored while the bot is installed and the feature remains in use.
- Moderation, ticket, and support records:
  may remain stored until deleted by a server administrator, removed through a user deletion request where supported, or no longer required for the feature.
- Ticket transcripts and log messages:
  if a transcript or log copy has already been posted into a Discord channel, that copy may remain on Discord until deleted from the relevant channel.
- Retention settings:
  some guild-level retention/export defaults can be configured with `/data retention`.

When data is no longer needed for supported functionality, OtterBot should remove it as part of normal feature cleanup, server removal, or a supported deletion workflow.

## Data Exports and Deletion

OtterBot provides in-bot privacy tools for supported data scopes:

- `/data info`
- `/data export-me`
- `/data delete-me`
- `/data export-guild`
- `/data retention`

`/data delete-me` is designed to remove supported guild-scoped database records linked to the requesting user, such as birthdays, ticket records/history, warnings, LOA records, suggestions they created, stored suggestion vote references, and verification list references where applicable.

Important limits:

- Deletion commands do not automatically remove every message copy that already exists in Discord channels, including moderation logs, suggestion posts, or transcript files already posted in a server channel.
- Server-level configuration records may be retained if they are not personal user data.
- Some records may be retained where required for security, abuse prevention, legal compliance, or core operational integrity.

## Data Sharing

OtterBot does not intentionally share Discord API data with third parties except:

- when required to operate the bot’s hosting/infrastructure stack,
- when required by law,
- when necessary to fulfill a user- or server-admin-requested bot function,
- when Discord requires disclosure under applicable platform terms.

## Security

OtterBot is intended to store data using commercially reasonable safeguards. However, no system can guarantee absolute security.

If a security incident affects Discord API data processed by OtterBot, remediation and notification should be handled in accordance with applicable law and Discord’s Developer Terms.

## Server Administrator Responsibilities

Server administrators are responsible for:

- enabling only the features they want to use,
- configuring logging, ticketing, automation, and exports appropriately for their server,
- making this policy available to their members where required,
- deleting or pruning server-side Discord content they no longer wish to retain.

## Contact

For support, privacy questions, or deletion requests that cannot be completed through in-bot commands, use the OtterBot support server:

- Support Server: https://discord.gg/C94CCcge

## Changes

This policy may be updated from time to time. Continued use of OtterBot after an update means the updated policy applies going forward.
