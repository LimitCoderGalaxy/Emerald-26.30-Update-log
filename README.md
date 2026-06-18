# Emerald Bot v26.30

**Codename: PRISM** | Quantum Core V2.0.0

## Overview

Quantum Core V2.0 is the next-generation intelligence engine behind Emerald, architected for maximum performance, stability, and transparency. This massive overhaul introduces advanced predictive diagnostics, enhanced cooldown analytics, distributed system integrity checks, and intelligent caching to keep the bot lightning-fast and the community experience bulletproof.

## Quantum Intelligence 2.0

The evolved decision layer inside Quantum Core transforms real-time runtime data into predictive and reactive insights, enabling the bot to self-monitor intelligently, predict and prevent issues before they occur, and adapt behavior dynamically across any server environment. This results in superior diagnostics, exceptional uptime, and truly adaptive bot behavior.

## Core Features

### Core Identity & Monitoring
- ✓ Core identity and versioning
- ✓ Live health diagnostics (latency, memory, uptime)
- ✓ Real-time system monitoring and analytics

### Intelligence & Analytics
- ✓ Cooldown and runtime analytics
- ✓ Integrity checks for config and environment consistency
- ✓ Predictive issue detection and prevention
- ✓ Intelligent caching and performance optimization
- ✓ Distributed system monitoring across server instances

### Economy & Engagement
- ✓ Full economy system with currency management
- ✓ User levels and experience system
- ✓ Badge and achievement system
- ✓ Role management and permissions
- ✓ Moderation tools (warn, ban, timeout)
- ✓ Auto-moderation support for bot account detection and unsafe image scanning

## Technology Stack

- **Runtime:** Node.js >= 22.12.0
- **Library:** discord.js 14.26.4
- **Environment:** dotenv 17.4.2
- **Codename:** PRISM
- **Status:** Stable

## Auto-Moderation Configuration

Use the `.env` file to tune Emerald Auto-Mod:
- `AUTO_MOD_ENABLED` — enable or disable automod
- `AUTO_MOD_ACCOUNT_ACTION` — action for new account detection (`timeout`, `kick`, `ban`)
- `AUTO_MOD_IMAGE_ENABLED` — enable image scanning on attachments
- `AUTO_MOD_IMAGE_ACTION` — action for unsafe image detection (`timeout`, `kick`, `ban`)
- `AUTO_MOD_DELETE_MESSAGE` — remove flagged messages automatically
- `AUTO_MOD_BOT_ACCOUNT_ACTION` — action for detected bot accounts (`kick`, `ban`, `none`)
- `AUTO_MOD_NEW_ACCOUNT_DAYS` — account age threshold in days
- `AUTO_MOD_SUSPICIOUS_IMAGE_SIZE_KB` — image size threshold for suspicious attachment checks
- `AUTO_MOD_ALERT_ONLY` — report only without taking action
- `AUTO_MOD_TIMEOUT_DURATION_MINUTES` — timeout length for `timeout` actions
- `AUTO_MOD_WHITELIST_ROLE_IDS` — comma-separated role IDs excluded from automod
- `AUTO_MOD_WHITELIST_CHANNEL_IDS` — comma-separated channel IDs excluded from automod
- `AUTO_MOD_MAX_MENTIONS` — maximum allowed mentions per message
- `AUTO_MOD_MAX_LINKS` — maximum allowed links per message
- `AUTO_MOD_MAX_ATTACHMENTS` — maximum allowed attachments per message
- `AUTO_MOD_FORBIDDEN_WORDS` — comma-separated forbidden words/phrases
- `AUTO_MOD_AUTO_WARN` — send a warning DM when a rule is triggered
- `AUTO_MOD_LOG_CHANNEL_ID` — optional channel ID for logging automod actions

## Commands

The bot includes **73 commands** across multiple categories:
- Economy (daily, work, pay, rob, etc.)
- Utility (ping, help, botinfo, updates)
- Moderation (ban, kick, warn, timeout, automod detection)
- Games (roulette, rps, coinflip, slots)
- Levels & Progression
- And much more...

## Update Command

The `/updates` command fetches the latest release log from GitHub and highlights the current v26.30 release. It includes:
- Changelog preview or recent commits when logs are unavailable
- Static release summary for the current 26.30 update
- Current bot version and Quantum Core status
- Stable release indicator

---

**It's The Newly Powered Engine**

Thank You All For Your Support!
