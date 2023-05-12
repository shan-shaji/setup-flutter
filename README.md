# Setup Flutter

This script automates the installation of all required tools to set up a new machine to start developing with Flutter.

## Prerequisites

* The machine should be running macOS or Linux (Ubuntu/Debian).
* The machine should have an active internet connection.
* curl should be installed.

## Steps to Run the Script

1. Open the terminal.
2. Run the following command:
 ```sh
curl -fsSl https://raw.githubusercontent.com/shan-shaji/setup-flutter/main/setup_flutter | /bin/bash
```

3. Wait for the script to complete. It may take some time depending on the speed of your internet connection.

## Support

If you encounter any issues while running the script, please create an issue on the [GitHub repository](https://github.com/shan-shaji/setup-flutter/issues).

## Failure and Success Cases

* If any of the prerequisites are not met, the script will exit with an appropriate error message.
* If any of the installations fail, the script will exit with an appropriate error message.
* If the script completes successfully, all required tools will be installed and the machine will be ready for Flutter development.

**Note:** This script will perform the following steps:

- Install Home Brew
- Install Snap - Linux
- Install Android Studio
- Install VS Code
- Install FVM
- Install Flutter default version

**Note**: The script does not install Xcode, JDK, or any other Android-related tools. You must have Xcode and JDK installed on macOS, and you need to configure Android Studio manually on both macOS and Linux.

**Note:** This script installs the stable version of Flutter. If you want to install a different version, you can do so using `fvm`. For more information on `fvm`, please refer to the [GitHub repository](https://github.com/leoafarias/fvm).

**Note:** This script sets up `fvm` and adds it to the PATH. You can use `fvm` to manage different versions of Flutter on the same machine.


## Troubleshooting

1. If you are facing this error when trying to run the script please try attatching `sudo` before the install script.

  ```sh
  Running in non-interactive mode because `stdin` is not a TTY.
  ==> Checking for `sudo` access (which may request your password)...
  Need sudo access on macOS (e.g. the user shan needs to be an Administrator)!
  /bin/bash: line 18: /opt/homebrew/bin/brew: No such file or directory
  ```

If you are facing any issues while using the script feel free to 
create an issue [here](https://github.com/shan-shaji/setup-flutter/issues).

## Background

The purpose of this project is to alleviate developers from the inconvenience of configuring Flutter and its related software when transitioning to a different device. 

