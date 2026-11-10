# 🤖 Robocode Tank Battle Game

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=21,12,2&height=210&section=header&text=Robocode%20Tank%20Battle%20Game&fontSize=44&fontColor=ffffff&animation=fadeIn&fontAlignY=36&desc=Code%20Your%20Tank.%20Battle%20for%20Glory.&descAlignY=56&descSize=19" width="100%"/>

<br/>

[![Version](https://img.shields.io/badge/version-3.0.1-6B4E1F?style=for-the-badge&logo=semanticrelease&logoColor=white)](https://github.com)
[![Java](https://img.shields.io/badge/Java-17%2B-A67C52?style=for-the-badge&logo=openjdk&logoColor=white)](https://openjdk.org)
[![License](https://img.shields.io/badge/license-MIT-D4A373?style=for-the-badge&logo=opensourceinitiative&logoColor=black)](LICENSE)
[![Arena](https://img.shields.io/badge/arena-1v1%20%7C%20melee%20%7C%20teams-FAEDCD?style=for-the-badge&logo=gamepad&logoColor=black)](https://robocode.sourceforge.io)

<br/>

### 🎯 An AI tank programming game — write code, watch it fight, learn robotics & AI

*⚔️ Programmable Tanks • 🧠 AI Battles • 🏆 Leaderboards • 🚀 Real-Time*

<br/>

<a href="https://share.google/cAdKnasBUBjZO3cnh">
  <img src="https://img.shields.io/badge/🎮_PLAY_NOW-6B4E1F?style=for-the-badge&logo=googlechrome&logoColor=white&labelColor=4A3615" alt="Play Now" height="45"/>
</a>
&nbsp;&nbsp;
<a href="https://share.google/cAdKnasBUBjZO3cnh">
  <img src="https://img.shields.io/badge/📥_GET_SOURCE-A67C52?style=for-the-badge&logo=github&logoColor=white&labelColor=7A5A3B" alt="Get Source" height="45"/>
</a>
&nbsp;&nbsp;
<a href="https://share.google/cAdKnasBUBjZO3cnh">
  <img src="https://img.shields.io/badge/📚_DOCS-D4A373?style=for-the-badge&logo=readthedocs&logoColor=black&labelColor=A17F58" alt="Docs" height="45"/>
</a>

</div>

<img width="570" height="213" alt="robocode_logo_tanks" src="https://github.com/user-attachments/assets/eb22ab75-7343-4e50-ade9-ded12ffb2ac4" />

<br/>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## 🌟 About

**Robocode Tank Battle Game** is a **programming game** where you write code for a tank and watch it battle against other players' tanks in a real-time arena. It's the classic way to learn **robotics, AI, geometry, and Java** — all disguised as a fun, competitive game.

Write your tank's brain, watch it fight, iterate on your strategy, and climb the leaderboard. The best tanks come from **clever algorithms and smart decisions**, not reflexes.

> 💡 **Perfect for:** Java learners, AI/robotics students, competitive programmers, and educators looking for an engaging coding exercise.

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## 🎯 Key Features

<div align="center">

| ⚔️ **Battle Modes** | 🧠 **Programmable AI** | 🏆 **Leaderboards** |
|:---:|:---:|:---:|
| 1v1, melee<br/>& team battles | Full control over<br/>movement & targeting | Track your win rate<br/>& best tanks |

| 🔧 **Easy API** | 🎨 **Visual Arena** | 📊 **Combat Analytics** |
|:---:|:---:|:---:|
| `onScannedRobot`,<br/>`onHitByBullet` & more | Real-time rendering<br/>of every battle | Bullet accuracy,<br/>damage & dodges |

</div>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## 🏆 Why This Game

<div align="center">

| 💎 **Advantage** | 📝 **Description** |
|:---|:---|
| 🎓 **Learn by Competing** | Teaches geometry, AI patterns, and Java — all through gameplay |
| ⚡ **Instant Feedback** | Watch your tank fight in real time and iterate in seconds |
| 🧠 **Real AI Practice** | Learn pathfinding, prediction, targeting & state machines |
| 🎨 **Beginner-Friendly** | Simple starter tank gets you playing in under 5 minutes |
| 🏅 **Active Community** | Hundreds of shared bots to test against |
| 🔧 **Fully Open** | Modify the engine, arena, or rules — it's all yours |

</div>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## 🎬 Battle Preview

<div align="center">

```ascii
╔══════════════════════════════════════════════════╗
║  🤖  Robocode Tank Battle  v3.0.1                ║
╠══════════════════════════════════════════════════╣
║  Round 1 — 1v1 Arena                             ║
║  ──────────────────────────────────────────      ║
║                                                  ║
║     ██████                        ▓▓▓▓▓▓          ║
║     █🤖███  ── bullets ───▶      ▓▓▓🤖▓          ║
║     ██████                        ▓▓▓▓▓▓          ║
║     Alpha                         Bravo          ║
║     HP: 87/100                    HP: 62/100      ║
║                                                  ║
║  💥 Bravo hit! (-18 HP)                          ║
║  🎯 Alpha accuracy: 74%  Bravo accuracy: 51%    ║
║  ⏱️  Round time: 12.4s                           ║
║                                                  ║
║  Your tank: Alpha (java) — Win rate: 68%         ║
║  [ 🎮 Continue ]  [ ⚙️ Edit Code ]  [ 📊 Stats ] ║
╚══════════════════════════════════════════════════╝
```

</div>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## 🧩 Project Structure

```
🤖 robocode-tank-battle/
├── 🎯 bots/
│   ├── starter/               # Beginner tank template
│   │   └── StarterTank.java
│   ├── advanced/              # Advanced AI examples
│   │   ├── TrackerBot.java
│   │   └── DodgerBot.java
│   └── community/             # Community bots
├── ⚔️  engine/                  # Battle engine
│   ├── physics/
│   ├── radar/
│   └── scoring/
├── 🎨 arena/                  # Arena maps & visuals
├── 🧪 tests/                  # Bot & engine tests
└── 📖 docs/                   # API reference & tutorials
```

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## 🛠️ Tech Stack

<div align="center">

![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![Swing](https://img.shields.io/badge/Swing-3776AB?style=for-the-badge&logo=java&logoColor=white)
![JUnit](https://img.shields.io/badge/JUnit_5-25A162?style=for-the-badge&logo=junit5&logoColor=white)
![Maven](https://img.shields.io/badge/Maven-C71A36?style=for-the-badge&logo=apachemaven&logoColor=white)

</div>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## 🤝 Community

Found a bug in the engine? Want to share your bot code?

<div align="center">

<a href="https://share.google/cAdKnasBUBjZO3cnh">
  <img src="https://img.shields.io/badge/💬_Join_Discord-5865F2?style=for-the-badge&logo=discord&logoColor=white" height="35"/>
</a>
<a href="https://share.google/cAdKnasBUBjZO3cnh">
  <img src="https://img.shields.io/badge/🐞_Report_Issue-6B4E1F?style=for-the-badge&logo=github&logoColor=white" height="35"/>
</a>
<a href="https://share.google/cAdKnasBUBjZO3cnh">
  <img src="https://img.shields.io/badge/⭐_Star_Repo-D4A373?style=for-the-badge&logo=github&logoColor=black" height="35"/>
</a>

</div>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## 📜 License

Distributed under the **MIT License**. See [`LICENSE`](LICENSE) for details.

<br/>

<div align="center">

### 🤖 Made with ⚔️ by the Robocode Tank Team

*If this game made you a better programmer — star the repo!*

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=21,12,2&height=120&section=footer" width="100%"/>

</div>
