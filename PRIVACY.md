# Privacy Policy

Last updated 21 November 2026.

This page explains what Sakerhet stores about you, why, and how to get it deleted. We try to keep it short and simple. We try to store as little as we can.

**The short version:** Sakerhet keeps your user ID and a hash of your bulkdelete password. It also keeps a short log when you post a blocked link. Anonymous messages are saved without your user ID. You can delete your data at any time with `/forgetme`.

## Who we are

Sakerhet is a free and open source Discord bot. It is made by kynorie. The code is on [GitHub](https://github.com/kynorie/sakerhet). You can reach us in the Sakerhet Discord server or by [opening an issue on GitHub](https://github.com/kynorie/sakerhet/issues).

## What Sakerhet stores

| Data | Why | Linked to you? | Kept for |
| --- | --- | --- | --- |
| Your user ID and a hash of your bulkdelete password (argon2id) | So `/bulkdelete` and other sensitive commands can check your password. | Yes | Until you run `/forgetme` |
| Blocked link log: your user ID, the blocked link and the time | To keep a record when someone posts an NSFW website or Discord server link. | Yes | 30 days |
| Anonymous messages: the nickname and the message | To post and keep a record of anonymous messages. | No. Your user ID is never saved. | 30 days |
| Lockdown logs: the server ID, the time, and whether the bot or an admin started it | To show when a server was locked or unlocked. | No | 30 days |
| Server data: the server ID, the Sakerhet channel and category IDs, lockdown state and your `/config` settings | To run lockdown, raid protection and your settings. | No, it is about the server | While the bot is in the server |

## What Sakerhet does not store

Sakerhet does not store your messages, your profile picture, your username or anything else about your Discord profile. The only exceptions are the items in the table above.

## How the bot reads messages

To find bad links, message floods and mention spam, the bot has to see messages in the servers it is in. It checks each message as it arrives and does not save it. The only thing it saves is the blocked link log in the table above.

## Who can see your data

- Other users and server admins cannot see your data, and they cannot see your password.
- Your password is only stored as a hash, so nobody can read it.
- The data is stored in files on the server that runs the bot. Only the bot owner can open those files.
- We do not sell your data. We do not share it with anyone.

Discord handles everything you send through Discord. Discord has its own privacy policy, and it still applies.

## Your choices

- Run `/forgetme` to delete your user ID, your password hash and any blocked link logs about you.
- Anonymous messages are not linked to you, so `/forgetme` cannot find them. If you want one removed, contact us and tell us what it says.
- Do not want the bot to read messages? Remove it from your server.

## Security

Passwords are hashed with argon2id. Too many wrong password tries will lock you out for a while. No system is perfect, so please use a password you do not use anywhere else.

## Children

Sakerhet is only for people who are allowed to use Discord. Discord's minimum age rules apply.

## Changes to this policy

If we change this policy, we will change the date at the top of this page.

## Contact

Questions or deletion requests? Join the Sakerhet Discord server or [open an issue on GitHub](https://github.com/kynorie/sakerhet/issues).
