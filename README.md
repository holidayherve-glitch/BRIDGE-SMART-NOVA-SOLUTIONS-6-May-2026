# BRIDGE-SMART-NOVA-SOLUTIONS-6-May-2026
Smart Nova Solutions — Linux File System Project

What is it?
A structured file system built on Google Cloud Shell simulating a real company server for Smart Nova Solutions, a tech company based at Kigali Innovation City, Rwanda.

Purpose
To practice real Linux system administration skills by building, organizing and documenting a company file system using terminal commands only — no clicking, no graphical tools.

Folder Structure
smartnova/
├── backup/
│   └── engineers.txt
├── company/
│   └── info.txt
├── logs/
│   └── server_info.txt
├── projects/
│   ├── completed.txt
│   └── current.txt
└── staff/
    ├── admins.txt
    └── engineers.txt

What Each Folder Contains
FolderFileContentcompany/info.txtCompany name, location, founded year, servicesstaff/engineers.txt3 engineer names and rolesstaff/admins.txt2 admin namesprojects/current.txt2 ongoing projectsprojects/completed.txt1 completed projectlogs/server_info.txtAuto-generated server databackup/engineers.txtCopy of engineers file

Key Commands Used
CommandPurposemkdir -pCreate nested folderscat >Create files with content>>Append live server output to filecpCopy file to backupfindVerify all files existtreeVisualize folder structurewc -lCount total files

Special Features

server_info.txt is automatically generated using the >> operator — not typed manually
Contains real live server data: date, hostname, system info, uptime, username
File count verified with find | wc -l returning exactly 7 files





✅ This project demonstrates real Linux skills used by junior system administrators in the industry.
