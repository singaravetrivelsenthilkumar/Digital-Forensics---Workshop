# Workshop on Digital Forensics
Installation and Usage of Sleuth Kit & Autopsy
## Introduction
Digital forensics involves extracting and analyzing data from digital devices to investigate cybercrimes. Sleuth Kit and Autopsy are widely used open-source tools for forensic analysis.

## Installation Steps
### A. Installing Sleuth Kit & Autopsy on Windows
1.Download Autopsy
- Visit Autopsy Official Website and download the latest version.
2.Run the Installer
- Double-click the downloaded file and follow the on-screen instructions.
3.Verify Installation
- Launch Autopsy to check if it works correctly.
### B.Sleuth Kit tools are included with Autopsy.
B. Installing Sleuth Kit Separately (Optional)
Download Sleuth Kit from https://www.sleuthkit.org.
Extract and install it manually if needed.
Add the installation directory to the system PATH for easy command-line access.
## Using Autopsy to Analyze a Disk or Folder
### A. Creating a New Case
1.Open Autopsy and select "Create New Case."
2.Enter Case Name, Case Number, and Examiner Name.
3.Choose a location to save the case files.
### B. Adding a Data Source
1.Click "Add Data Source."
2.Choose the type of source:
- Logical Drive (C:\ drive)
- Specific Folder (C:\Users\Documents\ etc.)
3.Click Next and select forensic modules like:
- File Analysis
- Hash Lookup
- Keyword Search
## C. Running the Analysis
1.Start processing the disk or folder.
2.Wait for Autopsy to generate reports.
3.Analyze deleted files, metadata, and hidden data in the results.
## 4. Using Sleuth Kit from Command Line
### A. Listing Files in C Drive
```
sh
fls -r C:\
```
### B. Extracting File Content
```
sh
icat C:\path\to\file
```
### C. Viewing File System Details
```
sh
fsstat C:\
```
## 5. Conclusion
By following these steps, you can install Sleuth Kit & Autopsy and analyze a disk or folder from the C drive. These tools help in digital investigations, allowing forensic experts to recover and analyze digital evidence.

