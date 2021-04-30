# Infragram
A cross platform Telegram client designed to feel native-like.
## Structure
Infragram is a C# app. Due to the goal described above the app is split into 2 types of projects:
- Infragram.Core - the main core of the app. Handles the connection to Telegram and other shared stuff.
- Infragram.UI:
  - Infragram.UI.Windows - the Windows UI. Built as a WPF app.
  - Infragram.UI.Linux - the Linux UI. Built as a GtkSharp app.
## Infragram vs TDesktop
You might say that if a cross platform desktop app for Telegram already exists, then what's the point of Infragram?

Infragram is designed to look as much as the OS it's running on as possible, while TDesktop uses it's own design.
