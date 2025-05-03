# 🛡️ ShieldX Discord Bot

## 📌 Overview

**ShieldX** is a robust, high-performance Discord moderation and protection bot designed to secure your community with advanced features like Anti-Nuke, AutoMod, Ticketing, Role Protection, and a dynamic Premium System.

---

## 🚀 Features

| Module            | Description                                                                            |
| ----------------- | -------------------------------------------------------------------------------------- |
| 🛡️ AntiNuke      | Real-time protection against mass bans, kicks, channel/role deletions and more.        |
| 🤖 AutoMod        | Filters profanity, invites, spam, links, caps, emojis, and custom rules.               |
| 🎟️ Ticket System | Hybrid ticketing with auto-setup, management tools, and panel control.                 |
| 🧑‍⚖️ Moderation  | Commands like warn, kick, ban, timeout, purge, and warn tracking.                      |
| 🪪 Whitelist      | User/role-based whitelist system for protection modules.                               |
| 🪙 Premium        | Tier-based premium with feature-gated plans (Trial, Basic, Pro, Enterprise, Lifetime). |
| 🧠 AI Detection   | (Optional) Suspicious behavior detection and automated reaction.                       |
| 🛠️ Auto Setup    | Easy one-command setup for any module.                                                 |
| 🔄 Recovery       | Restoration of deleted roles/channels instantly.                                       |
| 🔒 Protect Mode   | Temporarily disables dangerous permissions on all roles instantly.                     |

---

## 📖 Commands

### ⚙️ Setup

* `/antinuke enable`
* `/automod enable`
* `/Shield enable`
* `/protectmode`

### 👮 Moderation

* `/warn <user> [reason]`
* `/clearwarns <user>`
* `/ban <user> [reason]`
* `/kick <user> [reason]`
* `/timeout <user> [duration] [reason]`
* `/purge <amount>`

### 🔥 AntiNuke

* Listens for:

  * Channel Create/Delete
  * Role Create/Delete
  * Member Ban/Kick
* Custom punishments: Ban, Kick, Timeout, Derank, Quarantine
* Recovery system for deleted roles/channels
* Whitelist system for members and roles

### 🧠 AutoMod

* Filters:

  * Profanity
  * Invites
  * Mass Mentions
  * Caps Lock
  * Emoji Spam
  * Zalgo Text
* Custom triggers and actions

### 🎫 Ticket System

* Hybrid support: slash + prefix
* Auto-setup: Categories, Roles, Logs
* Panel-based UI
* Manage tickets: rename, close, claim, add/remove

### 🧾 Premium

* `/premium redeem <key>`
* `/premium info`
* Plan Tiers:

  * Trial: 7 days
  * Basic: 30 days
  * Pro: 90 days
  * Enterprise: 365 days
  * Lifetime: Forever

---

## 🗂️ Database

* `warn.db`: Tracks warnings
* `antinuke.db`: Whitelist + logs
* `premium.db`: Key management
* `automod.db`: Filter rules
* `tickets.db`: Ticket logs

---

## 🔐 Required Bot Permissions

* Administrator (recommended)
* Manage Roles
* Manage Channels
* Moderate Members
* Ban Members
* Kick Members
* View Audit Log

---

## 💬 Support & Resources

* **Support Server:** [Join Here](https://dsc.gg/cpre-dev)
* **Email:** [support@shieldx.app](mailto:coredevlops@gmail.com)

---

## 🧠 Developer Info

* **Language:** Python 3.11+
* **Library:** Pycord / discord.py 
* **Database:** SQLite (modular per feature)
* **Architecture:** Cogs-based modular design

---

## 🧪 Example Usage

```bash
/warn @user Spamming
/clearwarns @user
/premium redeem LIFETIME-XXXX-XXXX
/antinuke
/protectmode enable
```

---

**© 2025 ShieldX - All rights reserved.**
