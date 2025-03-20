
# Workshop on Digital Forensics
Installation and Usage of Sleuth Kit & Autopsy
```
Register Number: 212222040121
Name: Praveen V
```
## Introduction
Digital forensics involves extracting and analyzing data from digital devices to investigate cybercrimes. Sleuth Kit and Autopsy are widely used open-source tools for forensic analysis.

## Installation Steps
### A. Installing Sleuth Kit & Autopsy on Windows
1.Download Autopsy
- Visit Autopsy Official Website and download the latest version.
- Double-click the downloaded file and follow the on-screen instructions.
![{660CA88E-DE17-4556-89B5-38945EF3AA31}](https://github.com/user-attachments/assets/d5cf2c90-4fc9-453e-93ff-ef64378dd232)

2.Installation Process
- Launch Autopsy to check if it works correctly.
  ![Screenshot 2025-03-20 112320](https://github.com/user-attachments/assets/cc1fe43b-5c38-448b-b04c-611d7303273c)
  
- Choose Directory
  ![Screenshot 2025-03-20 112332](https://github.com/user-attachments/assets/6571866c-21af-4314-8ae2-ed372625a4e7)
  
- Give install
  ![Screenshot 2025-03-20 112339](https://github.com/user-attachments/assets/15efe313-01bb-4a21-a8ec-5b15afd66a20)
  ![Screenshot 2025-03-20 112358](https://github.com/user-attachments/assets/8abf07cf-8382-4a93-bd01-754b220af25e)

- Successfully installed
  ![Screenshot 2025-03-20 112447](https://github.com/user-attachments/assets/394e94bf-99d2-4af6-a070-fa64f09879b4)

- Autopsy Interface
  ![Screenshot 2025-03-19 222716](https://github.com/user-attachments/assets/3f8dfb03-55b2-4553-8475-de3595a56ff0)

## B. Installing Sleuth Kit Separately (Optional)
Download Sleuth Kit from www.sleuthkit.org/sleuthkit/download.php.
![{FAC04ED6-02D9-4D2A-A73C-CDADA79B7939}](https://github.com/user-attachments/assets/216ff656-18eb-497f-a795-3ca4112e758c)

Extract and install it manually if needed.
Add the installation directory to the system PATH for easy command-line access.
![{297520CA-14A7-4A4D-8C03-99E190C2C345}](https://github.com/user-attachments/assets/af8d1960-bab6-4810-9778-616f2305f52f)

## Using Autopsy to Analyze a Disk or Folder
## 1.Launch Autopsy and Set Up a New Case:

- Run Autopsy as Administrator.

- Click Create New Case.
![Screenshot 2025-03-19 222716](https://github.com/user-attachments/assets/4028e969-add1-46c4-beb2-3f336c7dcd3d)

- Enter a case name (e.g., Autopsy1).
- Select a location for the case folder → Click Next → Finish.
  ![Screenshot 2025-03-19 223051](https://github.com/user-attachments/assets/2b476fe0-199c-4c25-96c2-63c78183bb6f)
- Add optional information
  ![Screenshot 2025-03-19 223141](https://github.com/user-attachments/assets/45ff54d1-1967-4671-8dbb-a865f55f0316)


## 2.Add the Partition as Evidence:

- Click Add Data Source → Choose Host.
   ![Screenshot 2025-03-19 223322](https://github.com/user-attachments/assets/3ad0612b-655b-406c-ab63-95912238b112)


- Select Local Disk → Click Next.
   ![Screenshot 2025-03-19 223337](https://github.com/user-attachments/assets/8ed1cda5-f34d-491b-8255-c59c62eadaa0)


- Choose Disk → Select the VHD drive (Drive1).
  ![Screenshot 2025-03-19 224001](https://github.com/user-attachments/assets/773c5a67-49c8-421c-b0be-8a19a0e173c8)


- Click Next → Keep the default settings → Click Finish.
  ![Screenshot 2025-03-19 224106](https://github.com/user-attachments/assets/3feb68c2-3a3a-4e21-b3b8-11f4dfac0990)


- Allow Autopsy to process the disk.
## C. Running the Analysis
1.Start processing the disk or folder.

2.Wait for Autopsy to generate reports.

3.Analyze deleted files, metadata, and hidden data in the results.

## Using Sleuth Kit from Command Line
### A. Ckecking sleuthkit Version
```
sh
fls -V
```
![Screenshot 2025-03-20 114536](https://github.com/user-attachments/assets/b266d5a0-845f-428e-b16d-bf573d26ce5b)

### B. Lists partition layout
```
sh
mmls
```
![Screenshot 2025-03-20 115503](https://github.com/user-attachments/assets/f341a4af-2ff7-421b-a603-0cdace2321fa)

### C. Lists files and directories
```
sh
fls
```
![Screenshot 2025-03-20 115721](https://github.com/user-attachments/assets/73dfede6-f37b-4673-9405-bc66ca64f2ab)

## Conclusion
By following these steps, you can install Sleuth Kit & Autopsy and analyze a disk or folder from the C drive. These tools help in digital investigations, allowing forensic experts to recover and analyze digital evidence.

