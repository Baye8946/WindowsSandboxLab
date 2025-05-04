# WindowsSandboxLab

A self-contained PowerShell lab that uses Windows Sandbox to simulate desktop customization and productivity app setup — no Intune or Azure required.

## Features

- PowerShell script to customize desktop layout.
- Automatic app installation using Chocolatey.
- Mapped folder sharing from host to sandbox.
- Full reproducibility in isolated Windows Sandbox sessions.

## Requirements

- Windows 10/11 Pro or Enterprise.
- Hyper-V enabled.
- Windows Sandbox enabled.
- At least 8 GB RAM (recommended).

## 📁 Project Structure

## 🚀 How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/YOUR-USERNAME/WindowsSandboxLab.git
   ```

2. Map your working folder inside the sandbox:

   Edit SandboxConfig.wsb and update the <HostFolder> path
   
3. Run the sandbox:
Double-click SandboxConfig.wsb

## Reset
Close the Sandbox window. Everything is wiped automatically.

