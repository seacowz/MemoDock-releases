# MemoDock

A note-taking app for Windows, macOS and Linux, built with C++17 and Qt 6 QML.

Your notes are Markdown files in a folder on your own disk (a vault), edited in a rich text editor. No account and no cloud: cloud sync is planned for a later version.

## Features

- **Rich editor, plain Markdown files** - formatting shows as you type (headings, bold and italic, lists and task lists, tables, code blocks, quotes, links and images), and every note is saved as a standard Markdown file.
- **Local and private** - one folder on your disk holds the vault; nothing leaves your computer.
- **Fast search** - matches the start of words (`net` finds "network"), ignoring case and accents, with "exact phrases" and filters by notebook, tag, date and Trash; title matches come first.
- **Notebooks** - organize notes into notebooks, renamed or deleted from the sidebar.
- **Nothing gets lost** - deleted notes go to the Trash for 30 days, every note keeps a revision history you can restore from, the vault is backed up before anything is deleted for good, and a save that fails keeps your changes for recovery.
- **Attachments and images** - attach any file or insert images; Ctrl+click opens a link in its own app or the browser.
- **Import, export and print** - import Markdown and text files (also with "Open with"), export a note as Markdown, PDF or a self-contained HTML page, or print it.
- **Concurrency** - several windows, and computers on a local network, can work in the same vault at once; a note being edited elsewhere opens read-only and says where, and changes to notebooks and the Trash show everywhere within seconds.
- **Your look** - light, dark or system theme, and your choice of editor font, size and highlight colours.

## Download

The [latest release](https://github.com/seacowz/MemoDock-releases/releases/latest) has:

- **Windows 10 or 11 (x64):** `MemoDock-<version>-windows-x64-setup.exe`. The installer is not signed: at the SmartScreen warning, choose More info, then Run anyway.
- **macOS 12 or later (Apple silicon):** `MemoDock-<version>-macos-arm64.dmg`. The app is not notarized: the first time, right-click it and choose Open.
- **Ubuntu 22.04 or later (x64):** `memodock_<version>_amd64.deb`. Open it with App Center, or run `sudo apt install ./memodock_<version>_amd64.deb`.
