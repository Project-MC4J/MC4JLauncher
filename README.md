# MC4J Launcher

A launcher designed for Minecraft Legacy Console Edition.

MC4J Launcher is an independent Windows application focused on managing and running Minecraft Legacy Console Edition installations.

It provides an organized environment for handling multiple game installations, managing extensions, preparing runtime sessions, and launching the game through a unified interface.

## ✨ Features

- **Installation Management** — Automatically discovers and lists available Minecraft installations.
- **Multiple Installations** — Manage multiple game installations independently.
- **GameHDD Access** — Quickly access each installation's GameHDD directory.
- **Extension System** — Load, manage, and execute supported extensions.
- **Runtime Management** — Prepares the required environment before launching the game.
- **Session Management** — Manages temporary game sessions.
- **Process Monitoring** — Tracks the Minecraft process and detects when the game starts or exits.
- **Automatic Cleanup** — Handles temporary files and session cleanup.
- **Error Logging** — Records diagnostic information.
- **Windows Integration** — Opens installation directories directly through Windows Explorer.

## 🖥️ Platform

| Component | Support |
|---|---|
| Operating System | Windows |
| Application | MC4J Launcher |
| Game | Minecraft Legacy Console Edition |
| Extensions | MC4J Extension System |

## 🚀 Getting Started

### Requirements

- Windows
- A valid Minecraft Legacy Console Edition installation

**No Python installation is required.** MC4J Launcher is distributed as a standalone executable.

### Installation

1. Download the MC4J Launcher executable.
2. Place it in a convenient location.
3. Run `MC4JLauncher.exe`.

No additional Python setup or dependency installation is necessary.

## 🎮 Using MC4J Launcher

### Selecting an Installation

Available installations are displayed in the main window.

Select an installation to view its description, version, and package information.

### Launching the Game

1. Select the desired installation.
2. Click **PLAY**.
3. Wait for the runtime preparation process.
4. Minecraft will launch automatically.

The launcher monitors the game process and updates its status when Minecraft exits.

### Managing Extensions

Right-click an installation and select **Extensions** to access its extension management window.

From there, you can:

- View detected extensions.
- Inspect extension information.
- Execute selected extensions.
- Refresh the extension list.

### Accessing Installation Directories

The installation context menu provides shortcuts to:

- **Open GameHDD**
- **Open Extensions Folder**

These directories allow users to access installation-specific files.

## 🧩 Extension System

MC4J Launcher includes an extension management system designed to allow additional functionality to be integrated into the launcher.

Extensions can interact with launcher events, including:

- `game_started`
- `game_stopped`

Extension loading and execution are managed internally by the launcher.

Extension development documentation and API specifications are not currently publicly available.

## 📦 Game Files and Source Code

MC4J Launcher does not include or distribute Minecraft Legacy Console Edition source code or game files.

Users must obtain their own legally accessible game files and provide their own source code when creating custom `.mc4j` packages with MC4JEditor.

The Minecraft source code is not included with MC4J Launcher or MC4JEditor. Downloading either application does not provide a copy of the game's source code.

Users are responsible for obtaining and using game files they are legally entitled to use.

## 📋 Logging and Recovery

MC4J Launcher records diagnostic information to help identify application and runtime issues.

Temporary execution sessions are managed by the application.

## ⚠️ Disclaimer

MC4J Launcher is an independent community project.

It is not affiliated with, endorsed by, or officially associated with Mojang Studios, Microsoft, or 4J Studios.

Minecraft is a trademark of Microsoft Corporation.

Users are responsible for providing their own legally obtained game files.

## 📜 License

See the repository's `LICENSE` file for licensing information.

---

**MC4J Launcher — Bringing a new way to manage Minecraft Legacy Console Edition.**
