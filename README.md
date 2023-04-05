# Flutter Prep

This is a Bash script that automates the installation and setup of Flutter development environment on macOS and Linux. It first installs Homebrew package manager if it is not already installed and sets up the PATH environment variable accordingly. Then it installs required dependencies including Java, Android Studio, Visual Studio Code, and FVM (Flutter Version Manager) using Homebrew. Finally, it installs the stable version of Flutter using FVM and runs the flutter doctor command to check the setup status. The script checks for existing installations and only installs missing components to avoid redundant installations. Overall, this script simplifies the Flutter setup process and saves developers time and effort.


## Install

```sh
curl -fsSl https://raw.githubusercontent.com/shan-shaji/flutter-prep/main/flutter-prep | /bin/bash
```