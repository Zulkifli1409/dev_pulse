# DevPulse — Project Manager Desktop

> **Multi-project management made simple.** DevPulse is a lightweight desktop application that helps developers manage multiple local projects from a single unified interface.

## 🎯 Overview

DevPulse solves common development workflow challenges:

- 📦 Start/stop projects with a single click instead of opening multiple terminals
- 📋 Monitor real-time logs from all your projects in one place
- 🔌 Track which ports are being used and quickly open them in your browser
- 📱 Receive notifications when processes start, stop, or crash
- 🎯 Minimize to system tray to keep your workspace clean
- ⚙️ Auto-start on Windows login for always-ready development

## ✨ Key Features

### Project Management

- **Add/Edit/Delete Projects** — Manage multiple projects with custom run commands
- **Real-time Log Console** — View live stdout/stderr from each project
- **One-Click Run/Stop** — Control project processes instantly

### Smart Utilities

- **System Tray Integration** — Minimize to tray; quick access via icon menu
- **Port Management** — Save and open project ports directly in your browser
- **Desktop Notifications** — Get alerts for process status changes
- **Auto-start on Windows** — Optional auto-launch on system login

### User Experience

- **Dark & Light Themes** — Choose your preferred color scheme
- **Cross-Platform** — Works on Windows, macOS, and Linux
- **Lightweight & Fast** — Minimal resource usage, instant startup

## 🚀 Quick Start

### Installation

1. **Download** the latest installer for your platform:

   - Windows: `DevPulse-Setup-<version>-x64.exe`
   - macOS: `DevPulse-<version>.dmg` (coming soon)
   - Linux: `devpulse-<version>.AppImage` (coming soon)

2. **Run the installer** and follow the setup wizard

3. **Launch DevPulse** from your applications menu

### First Run

1. **Add a Project**

   - Click "Add Project" button
   - Choose your project folder
   - Enter the command to start your project (e.g., `npm run dev`, `flutter run`)
   - Select the framework type (optional)
   - Enter the port number if applicable
   - Click "Save"

2. **Start Your Project**

   - Click the "Run" button next to your project
   - View real-time logs in the console

3. **Configure Settings**
   - Open Settings (gear icon)
   - Toggle notifications, system tray, auto-start as needed
   - Choose your preferred theme

## 💻 Supported Frameworks

DevPulse works with **any** command-based project. Common frameworks include:

- **Frontend**: React, Vue, Angular, Next.js, Vite, Svelte
- **Backend**: Node.js, Python (Flask/Django), Go, Rust
- **Mobile**: Flutter, React Native
- **Desktop**: Electron, Qt
- **Custom Scripts**: Any bash/batch command

## 📋 Requirements

- **Windows 10/11** (primary platform)
- **macOS 10.15+** (experimental)
- **Linux** (GTK) - Ubuntu 20.04+ recommended
- **100 MB** disk space
- **.NET Runtime 5.0+** (Windows, pre-installed on most modern systems)

## 🛠️ Advanced Usage

### Environment Variables

Set custom environment variables for each project to customize build/run behavior.

### Custom Commands

Support for complex commands with pipes and redirects:

```
npm run build && npm run serve
python manage.py runserver
```

### Keyboard Shortcuts

- `Ctrl+N`: Add new project
- `Ctrl+K`: Search projects
- `Ctrl+,`: Open settings

## 📦 Installation Methods

### Windows

#### Classic EXE Installer (Recommended)

1. Download: `DevPulse-Setup-<version>-x64.exe`
2. Run the installer and follow the setup wizard
3. DevPulse will be installed to `Program Files` and added to Start Menu
4. (Optional) Enable auto-start from Settings

**Uninstall**: Use Control Panel → Programs and Features, or right-click installer and select "Uninstall"

#### MSIX Package (Windows Store)

1. Download: `DevPulse-<version>.msix`
2. Right-click and select "Install" or use Microsoft Store
3. Follow the installation prompt

### macOS (Coming Soon)

Download the `.dmg` file and drag DevPulse to Applications folder.

### Linux (Coming Soon)

Download the `.AppImage` file, make it executable, and run it.

## 🔧 Troubleshooting

### App won't start

- Ensure .NET Runtime 5.0+ is installed
- Try reinstalling the application
- Check Windows Event Viewer for error details

### Notifications not showing

- Check Windows notification settings for DevPulse
- Ensure notifications are enabled in Settings

### Tray icon not visible

- Right-click taskbar → Taskbar Settings → Select icons to display in system tray
- Add DevPulse to the "Always Show" list

### Process won't stop

- Manually kill the process from Task Manager
- Restart DevPulse
- Report the issue on GitHub

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🐛 Bug Reports & Feature Requests

- **GitHub Issues**: https://github.com/Zulkifli1409/dev_pulse/issues]

## 🙏 Acknowledgments

Built with:

- [Flutter](https://flutter.dev/) — UI framework
- [Hive](https://github.com/isar/hive) — Local database
- [tray_manager](https://pub.dev/packages/tray_manager) — System tray integration
- [window_manager](https://pub.dev/packages/window_manager) — Window management

## 📊 Version History

### v1.0.0 — Release (2025-11-03)

- ✨ Initial stable release
- 🎯 Full Windows support
- 🐧 Experimental macOS and Linux support
- 🎨 Dark and light theme support
- 📱 System tray integration
- 🔔 Desktop notifications
- ⚙️ Auto-start functionality

## Contributing

Contributions are welcome! Please feel free to submit a pull request or open an issue for any suggestions or improvements.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
