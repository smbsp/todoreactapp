# To Do List - React

It is a simple to do list bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Description

The main purpose of a to-do is to help organize tasks, so learning to effectively use them will benefit you by improving your time management abilities and decreasing your stress levels.

## Installation

Clone the repository and run the following commands.

```bash
npm install
npm run start
```

## Demo
Find a small video link [here](https://drive.google.com/file/d/1ICgYdgcQeOA_Sut2FGBX5aR5PeAHzFDC/view?usp=sharing).

## Things I learnt #BUIDLing this application

I set up my Windows machine to use Ubuntu 20.04 LTS and run bash terminal in Windows. Isn't that cool? 

I have tried to consolidate the step by step process to set up your development environment with reference links below. Hope that helps you get to speed. 

1. **WSL**: Windows Subsystem for Linux is a compatibility layer for running Linux binary executables natively on Windows 10 and Windows Server 2019. Please note this is not available for earlier versions of Windows OS. You can read the official docs [here](https://docs.microsoft.com/en-us/windows/wsl/install-win10). Some important commands for WSL with description are furnished below.

```bash
lsb_release -a : Details of the Linux distro currently running
ll /mnt : Find your local drives mounted under the /mnt folder. Example usage would be cd /mnt/c to access c:\
Run Linux binaries from the Windows Command Prompt (CMD) or PowerShell using wsl <command> (or wsl.exe <command>).
```

2. **Installing Node.js via WSL**: Once you run linux binaries on Windows, you need to download and configure other development tools. Read on how to install Node via WSL [here](https://gist.github.com/noygal/6b7b1796a92d70e24e35f94b53722219). I faced a permission denied issue while trying to install node. You can read about the resolution [here](https://stackoverflow.com/questions/56204010/permission-denied-while-installing-node-on-wsl-using-nvm).

3. **Installing and Configuring VS code**:  Once you download VS Code, it should automatically detect your WSL installation and suggest an extension called "Remote WSL". You can read about it [here](https://medium.com/@fiqriismail/setup-wsl-on-windows-10-for-your-javascript-development-with-visual-studio-code-f63f75841e5f). You'll find that the VS code terminal is now running bash command line.

4. **Setting up Git and GitHub using VS code**: Finally connect your GitHub account to VS code to instantly push the changes. This [video](https://www.youtube.com/watch?v=Fk12ELJ9Bww) succinctly explains the process. If have worked in large enterprises and do not have a good knowledge of GitHub, [this article](https://towardsdatascience.com/getting-started-with-git-and-github-6fcd0f2d4ac6) might help.