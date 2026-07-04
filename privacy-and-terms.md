# Privacy Policy & Terms of Service

Welcome to the **"lolbot"** (hereinafter referred to as "the Bot"). To protect your rights and explain how the Bot processes data and provides its services, please read the following *Privacy Policy* and *Terms of Service* carefully before using the Bot.

By inviting the Bot to your Discord server or using its commands, you agree to the contents described in this document.

---

## Part 1: Privacy Policy

We highly value the privacy of our users and servers. The Bot collects only the absolute minimum amount of data required to maintain its core functionalities.

### 1. Data We Collect
When you use configuration commands in your server (such as `!setchannel`, `!setteam`, `!setplay`, `!setlive`), the Bot records the following data in its local database:
*   **Discord Server Information:** Guild ID, Channel ID, and the Role ID selected to be pinged/mentioned.
*   **Tracking Target Information:** LCK team codes, Riot IDs (including name and tag), streaming platforms (SOOP / CHZZK), and streamer IDs configured by the administrator for tracking.
*   **The Bot absolutely does not collect, record, or store any user text conversations, voice records, personal account information, or other private data.**

### 2. How We Use the Data
The data we collect is used solely for the following single purpose:
*   To determine and execute automated push notifications (sending match schedules, in-game statuses, and live stream alerts to your designated Discord channel).
*   To ping the corresponding roles based on your configuration when sending notifications.

### 3. Data Sharing and Protection
*   **No Sharing or Selling:** We will absolutely not sell, exchange, or share your server configurations or tracking lists with any third parties.
*   **Local Storage:** All data is securely stored in a local SQLite database where the Bot operates.

### 4. Third-Party Services and APIs
To retrieve game and live stream information, the Bot sends the tracked Riot IDs and Streamer IDs to the following third-party services (we do not send any Discord user data to them):
*   Riot Games API & LoLEsports API
*   OP.GG (including its internal API) / Fow.kr
*   SOOP Live API / CHZZK (Naver) API

### 5. Data Deletion and Modification
*   Server administrators can remove specific tracking targets from the database at any time via Bot commands (e.g., reconfiguring to "no players selected" or unchecking them).
*   If you kick the Bot from your Discord server, we also provide a service to manually clear the corresponding Guild ID data. You can contact the developer using the contact information below.

*(Last Updated: June 2026)*

---

## Part 2: Terms of Service

### 1. Service Content and Availability
The Bot aims to provide *League of Legends* esports information, pro player Solo Queue statuses, and live stream notifications. We will make our best effort to keep the Bot running 24/7, but we do not guarantee 100% uptime. Services may be temporarily interrupted due to maintenance, updates, or force majeure events.

### 2. Disclaimer Regarding Reliance on Third-Party Services
The core functions of this Bot heavily rely on public data and APIs from third-party platforms (e.g., Riot Games, OP.GG, SOOP, CHZZK).
*   If these third-party platforms change their website structures, restrict API access (e.g., Riot officially hiding ranked match history), or experience server outages, it may cause the Bot to fail to send notifications or retrieve data properly.
*   The developer assumes no responsibility for Bot function failures, delays, or errors caused by changes in third-party services.

### 3. Usage Restrictions and Guidelines
You agree to abide by the following guidelines when using the Bot:
*   **No Abuse:** Do not use malicious scripts, send massive amounts of commands, or otherwise conduct denial-of-service attacks or consume the Bot's server resources.
*   **Permission Responsibility:** Configuration commands (e.g., `!setplay`) are restricted to server "Administrators" by default. Server owners should properly manage their server permissions; the developer is not responsible for unexpected configuration changes made by unauthorized users.

### 4. Service Termination
The developer reserves the right to modify, suspend, or permanently terminate part or all of the Bot's services at any time without prior notice. If a server is found to be maliciously abusing the Bot, the developer reserves the right to blacklist the server and refuse to provide services.

### 5. Modification of Terms
We reserve the right to modify this *Privacy Policy & Terms of Service* at any time. When major modifications occur, we may announce them via the Bot's status or other appropriate means. Continued use of the Bot is deemed acceptance of the modified terms.

---

## 📬 Contact the Developer
If you have any questions about this *Privacy Policy & Terms of Service*, or need to report bugs or suggest new features, please contact the developer via:

*   **Discord:** `feithjjju`
*   **[our Support Discord](https://discord.com/invite/UrKYbDysp3)**

*(Last Updated: June 2026)*
