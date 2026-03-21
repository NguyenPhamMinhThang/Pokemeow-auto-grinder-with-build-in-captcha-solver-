# 🎮 PokéMeow Automation Pro 🚀

[![Language](https://img.shields.io/badge/Language-Python%20%2F%20Golang-blue.svg)]() 
[![Status](https://img.shields.io/badge/Status-Active-brightgreen.svg)]()
[![Safety](https://img.shields.io/badge/Anti--Ban-Enabled-orange.svg)]()
[![License](https://img.shields.io/badge/License-MIT-yellow.svg)]()

A comprehensive, powerful, and intelligent automation solution for the **PokéMeow** Discord bot. This tool is designed to optimize grinding, manage resources, and hunt rare Pokémon 24/7 with human-like precision.

---

## 🛠 Detailed Features List

### ⚡ Core Grinding System
* 🐾 **Auto Catch (`;p`):** Automatically finds and catches Pokémon as soon as the cooldown ends with optimized latency.
* 🎣 **Auto Fishing (`;f`):** Perfectly timed fishing; recognizes bite prompts and executes catches with 100% accuracy.
* 🎯 **Smart Ball Selection:** Intelligently selects the best ball (Pokéball, Great, Ultra, Master) based on rarity (Shiny, Legendary, Event, etc.).
* 🛒 **Auto Buy Balls:** Monitors your inventory and automatically purchases balls when stocks are low, ensuring you never miss a rare encounter.

### 🧠 AI & Captcha Solver
* 👁️ **YOLO-based Detection:** Integrated Object Detection model to solve PokéMeow's image captchas with high accuracy.
* 🔄 **Auto-Resume:** Automatically resumes activities immediately after a successful captcha solve without manual intervention.
* 🔔 **Webhook Alerts:** Instant notifications via Discord/Telegram for captchas or special events (Catching a Shiny/Legendary).

### 📦 Resource & Inventory Management
* 🎁 **Auto Lootbox:** Automatically opens all types of supply crates (Common, Uncommon, Rare, etc.) upon receipt.
* 🌿 **Grass Berry Automation:** Schedules and uses Grass Berries to boost encounter rates for rare Pokémon.
* 🧪 **Research Exchange:** Monitors and automates item exchanges within the Research system to maximize resource efficiency.
* 🥚 **Auto Egg Hatching:** Tracks hatching progress and replaces hatched eggs with new ones instantly.

### 📋 Tracking & Quests
* 📅 **Daily Check:** Automatically claims the daily reward (`;d`) right after the server reset.
* 📜 **Quest Tracker:** Monitors and prioritizes actions to complete active quests as quickly as possible.
* 🔍 **Hunt & Swap Monitoring:** Supervises currently hunted Pokémon and frequently checks swap commands to ensure you never miss a rotation.

### ⚔️ Advanced Interactions
* 🤺 **Auto Battle:** Automatically engages in NPC battles to farm PokéCoins and EXP for your team.
* 🚦 **Smart Priority Queue:** Intelligent command queuing that prioritizes Captcha solving and Rare Pokémon catches over auxiliary commands.

### 🛡️ Security & Anti-Detection
* ⏱️ **Human-like Delays:** Features a randomized delay generator between commands to simulate natural human typing patterns.
* 🛌 **Short Break Cycles:** Automatically triggers short rest periods after extended activity to bypass behavioral bot-detection systems.
* 🕵️ **Status Management:** Dynamically manages Discord status to make the account appear active and natural.

---


## 📂 Project Structure
```text
├── 📂 src
│   ├── 📄 main.py          # Main execution script
│   ├── 📄 captcha.py       # AI YOLO processing module
│   └── 📄 logic.py         # Command queue management
├── 📂 config
│   └── 📄 settings.json    # Ball config, delays, etc.
└── 📄 requirements.txt     # Necessary libraries & dependencies

