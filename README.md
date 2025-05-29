# LogMe Updater

LogMe Updater is a simple update mechanism for the LogMe executable. It automatically checks for the latest version of `LogMe.exe` and updates it when a new version is found. The tool is designed to help ensure that users always have the latest version of LogMe running without needing to manually download and install updates.

## Features

- **Automatic Version Checking**: Compares the local version with the latest remote version.
- **Update Notification**: If a new version is available, it will automatically download and replace the existing executable.
- **Graceful Shutdown**: Before updating, it checks if the `LogMe.exe` process is running and terminates it safely.
- **Message Box for Updates**: If an update is found, a message box will notify the user.
