<a id="readme-top"></a>

<!-- PROJECT SHIELDS -->
<div align="center">

[![Contributors](https://img.shields.io/github/contributors/danilow-dev/tako-bot.svg?style=for-the-badge)](https://github.com/danilow-dev/tako-bot/graphs/contributors)
[![Forks](https://img.shields.io/github/forks/danilow-dev/tako-bot.svg?style=for-the-badge)](https://github.com/danilow-dev/tako-bot/network/members)
[![Stargazers](https://img.shields.io/github/stars/danilow-dev/tako-bot.svg?style=for-the-badge)](https://github.com/danilow-dev/tako-bot/stargazers)
[![Issues](https://img.shields.io/github/issues/danilow-dev/tako-bot.svg?style=for-the-badge)](https://github.com/danilow-dev/tako-bot/issues)
[![MIT License](https://img.shields.io/github/license/danilow-dev/tako-bot.svg?style=for-the-badge)](https://github.com/danilow-dev/tako-bot/blob/main/LICENSE)

</div>

<!-- PROJECT LOGO -->
<br />
<div align="center">

  <h1 align="center">🐙 Takito Bot</h1>

  <p align="center">
    A multipurpose Discord bot to send custom messages, embed Discohook JSON payloads, and manage welcome/goodbye workflows.
    <br />
    <br />
    <a href="https://github.com/danilow-dev/tako-bot/issues/new?labels=bug&template=bug-report---.md">Report Bug</a>
    &middot;
    <a href="https://github.com/danilow-dev/tako-bot/issues/new?labels=enhancement&template=feature-request---.md">Request Feature</a>
  </p>
</div>

<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#roadmap">Roadmap</a></li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#acknowledgments">Acknowledgments</a></li>
  </ol>
</details>

---

<!-- ABOUT THE PROJECT -->
## About The Project

Takito Bot is built to simplify server administration and message customization in Discord. It allows admins to broadcast messages to specific channels, render complex JSON embeds exported from Discohook, and configure welcome or goodbye greetings with instant test triggers.

**Key Features:**
* 📩 **Message Dispatcher:** Send formatted text or raw Discohook JSON embeds to any target channel.
* 👋 **Welcome & Goodbye System:** Easily set custom welcome and departure messages for new or leaving members.
* 🧪 **Testing Suite:** Instantly preview welcome/goodbye settings using test commands without altering server membership.
* ⚙️ **Server Overview:** Use `!showconfig` to inspect current channel settings and active configurations.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

### Built With

* [![NodeJS](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)](https://nodejs.org/)
* [![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
* [![Discord.js](https://img.shields.io/badge/Discord.js-5865F2?style=for-the-badge&logo=discord&logoColor=white)](https://discord.js.org/)

<p align="right">(<a href="#readme-top">back to top</a>)</p>

---

<!-- GETTING STARTED -->
## Getting Started

Follow these steps to get a local instance of Takito Bot running.

### Prerequisites

* **Node.js** (v18 or higher) and **npm**
  ```sh
  npm install npm@latest -g
