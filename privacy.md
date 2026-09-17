# IndieDB Privacy Policy

**Last updated: 17 September 2026**

## 1. Introduction

This Privacy Policy explains how IndieDB ("IndieDB", "the application", or "the bot") accesses, uses and handles information when operating within Discord servers.

IndieDB is a Discord server-building and configuration tool. It is designed to access only the information necessary to perform its server-building functionality.

## 2. Information IndieDB Accesses

When IndieDB is used, it may access limited information provided through Discord, including:

- The Discord user ID of an authorised operator interacting with IndieDB.
- Discord server IDs.
- Discord permission information associated with an interaction.
- Channel and category IDs, names, types and parent-category information.
- Role IDs, names and relevant role permission information.
- Button and selection-menu choices made through IndieDB's setup interface.

This information is used to authenticate authorised operators and create or configure Discord server structures.

## 3. Information IndieDB Does Not Collect

IndieDB is not designed to collect or store:

- Discord account email addresses.
- IP addresses.
- Friend lists.
- Discord member lists.
- User avatars or profile information.
- User message content.
- Private messages.
- A history of customer server builds.

IndieDB does not request Discord's Message Content Gateway Intent and does not fetch, analyse or store user message content.

## 4. Temporary Information

While IndieDB is running, temporary setup information may be stored in the application's memory.

This may include:

- Discord server ID.
- Authorised operator user ID.
- Selected server template.
- Available game/category information.
- Selected game choices.

This information is used to complete the requested server build.

Successful builds remove the relevant setup session. Temporary sessions are not written to a customer database or persistent storage and disappear when the bot process is restarted.

## 5. Persistent Storage

IndieDB does not use a customer database or store message content, build history, usernames, email addresses, or other Discord profile information.

For safety, IndieDB maintains a small local ownership record named `.indiedb-ownership.json`.

This record stores Discord server IDs and the IDs of channels, categories, and roles created by IndieDB. It is used to distinguish resources created by IndieDB from resources that already belong to the customer.

The ownership record is necessary to help prevent IndieDB from accidentally modifying or deleting customer-created channels, categories, or roles during future builds, cleanup operations, or failed-build recovery.

The ownership record does not contain Discord message content, usernames, email addresses, IP addresses, passwords, or Discord authentication credentials.

If the ownership record is unavailable or lost, IndieDB does not assume that existing Discord resources belong to it. Resources that cannot be verified as IndieDB-created are treated as customer-owned and are not modified or deleted solely because their names match an IndieDB template.

Local application configuration may separately contain developer credentials and authorised operator identifiers required to operate IndieDB. This configuration is maintained by the developer and is not customer build data.

Local application configuration may contain developer credentials and authorised operator identifiers required to operate IndieDB. This configuration is maintained by the developer and is not customer build data.

## 6. Operational Logging

IndieDB may output operational information and errors to the environment in which the bot is running.

Depending on the nature of an error returned by Discord, technical information may include identifiers such as:

- Server IDs.
- Channel IDs.
- Interaction IDs.
- Discord API request paths.
- Temporary interaction information.

These logs are used for operation, troubleshooting and security purposes.

IndieDB does not intentionally log user message content.

## 7. Third-Party Services

### Discord

IndieDB communicates with Discord's API and Gateway to provide its Discord functionality.

Information processed by Discord is also subject to Discord's own privacy practices and policies.

### Twitch

IndieDB may communicate with Twitch's API to retrieve a catalogue of games or categories for its game-selection functionality.

IndieDB does not intentionally send Discord user IDs, server IDs, channel IDs, Discord message content or the operator's selected game choices to Twitch.

## 8. Data Sharing

IndieDB does not sell customer personal information.

Information is transmitted to Discord as necessary for the bot to operate. Twitch is contacted for game/category information as described above.

IndieDB does not intentionally provide customer Discord information to Twitch.

## 9. Removing IndieDB and Stored Ownership Information

A server owner may remove IndieDB from their Discord server using Discord's normal application and bot-management controls.

After removal, IndieDB can no longer access that Discord server through Discord.

Channels, categories, roles and permissions previously created by IndieDB remain part of the Discord server unless they are separately removed.

IndieDB's local ownership record may retain the Discord server ID and resource IDs of items previously created by IndieDB. This information is retained for operational and safety purposes, including identifying resources created by IndieDB if the bot is later used with that server again.

IndieDB does not use this ownership information to store message content or Discord user profiles.

An unfinished setup session may also remain temporarily in the running application's memory until the process is restarted or the session is otherwise cleared. Temporary setup sessions are not written to persistent customer storage.

## 10. Security

Reasonable technical measures are used to restrict IndieDB's server-building controls to authorised operators and protect application credentials.

No online service can guarantee absolute security.

## 11. Children's Privacy

IndieDB is not designed to knowingly collect personal information from children.

Use of Discord remains subject to Discord's own age requirements and policies.

## 12. Changes to This Privacy Policy

This Privacy Policy may be updated if IndieDB's functionality or data-handling practices change.

The current version will be published at this location with an updated revision date.

## 13. Contact

Questions or privacy enquiries relating to IndieDB can be submitted through the official IndieDB support/contact method provided by the developer.
