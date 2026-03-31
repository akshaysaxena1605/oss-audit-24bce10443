# oss-audit-24bce10443
# Open Source Audit - Linux Kernel

**Student Name:** Akshay Saxena
**Registration Number:** 24BCE10443
**Chosen Software:** Linux Kernel

## Script Descriptions
1. **Script 1 (System Identity Report):** Displays system info, kernel version, uptime, and the GPL v2 license message.
2. **Script 2 (Package Inspector):** Checks if a specified package is installed and provides a philosophical note based on its name.
3. **Script 3 (Disk Auditor):** Audits permissions and sizes of key system directories using a loop.
4. **Script 4 (Log Analyzer):** Reads a log file, counts occurrences of a specific keyword, and outputs the last 5 matching lines.
5. **Script 5 (Manifesto Generator):** Interactively prompts the user with questions to generate a personalized open-source philosophy text file.

## Instructions to Run on Linux (Ubuntu/WSL)
1. Clone the repository to your local machine.
2. Ensure the scripts are executable by running: `chmod +x *.sh`
3. Run each script using `./` (e.g., `./script1_system_identity.sh`).
4. **Note:** Script 3 and Script 4 may require `sudo` privileges to read system directories and log files (e.g., `sudo ./script3_disk_auditor.sh` and `./script4_log_analyzer.sh /var/log/dpkg.log install`).

## Dependencies
* A Linux environment (Ubuntu/WSL)
* Bash shell
* Standard GNU core utilities (`awk`, `grep`, `du`, `dpkg`)
