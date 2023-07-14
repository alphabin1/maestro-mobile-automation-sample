# maestro-mobile-testing
Welcome to the automation testing for the Demo application using Maestro, a powerful mobile testing framework. This repository contains the necessary resources to perform ene-to-end testing on the Demo application.

## Pre-Requisites
Before getting started, ensure that you have thte following pre-requisites set up on your system:
    1. Install iTerm or Powershell on your machine.
    2. Install Android Studio for Android device emulation.
    3. Add ANDROID_HOME to your system environment variables. To verify if the setup is correct, open a terminal and run the command `adb --version`.
    4. Install Java JDK 11 and set JAVA_HOME. Verify the installation by running `java --version`.

## Installation
To create test cases using Maestro for mobile testing, follow the steps below:
    1. Open the Terminal or iTerm.
    2. Execute the following command to install Maestro\
```
 brew install Maestro
```
OR
```
curl -Ls "https://get.maestro.mobile.dev" | bash
```

## Upgrading the CLI
If you need to upgrade your Maestro CLI, simply run the installation script again:
```
curl -Ls "https://get.maestro.mobile.dev" | bash
```

## Connecting to Your Device
Maestro automatically detects any locally available emulators or physically connected USB devices.

## Execution
Follow the steps below to execute the test cases:
1. Navigate to the directory where you have created your test cases.
    ```
    cd maestro-automation
    ```
2. Execute the test cases using the below command:
    ```
    maestro test main.yaml
    ```

## Uninstalling Maestro
To uninstall Maestro from  your system, run the following command:
```
brew uninstall maestro
```

## Video of Execution
Check out the video below to see Maestro in action:

[![Maestro_Execution_Video](https://github.com/dhruvi-alphabin/mochawesome-describe-report-generator/assets/106430518/06dfdaaf-fb26-4d92-bf9e-36d940f80d5a)](https://github.com/dhruvi-alphabin/mochawesome-describe-report-generator/assets/106430518/ea3ec049-fdbe-4407-8a70-d202e361c614)

Feel free to explore and enhance your mobile automation testing using Maestro.
Happy testing!
