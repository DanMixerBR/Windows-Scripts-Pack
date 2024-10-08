# Windows Scripts Pack

Collection of BAT and PowerShell scripts to automate processes in Windows. There are **20 scripts** in total, 16 scripts to run in any environment and 4 scripts for corporate environments.

See below which scripts are and their functionalities.

**Scripts for any environment:**

- "Clear cache.bat" clears the TEMP folder and restarts Windows Explorer. It can fix many issues like frozen taskbar and system slowness;
- "Driver Installer.bat" and "Driver Uninstaller.bat" install and uninstall system drivers;
- "Fix Keyboard.bat" enables the CTF Loader and fixes keyboard freezing when typing;
- "Fix Microsoft Outlook.bat" restores Outlook to its factory settings. Can fix startup issues and crashes when loading new messages;
- "Fix Num Lock key.bat" enables the Num Lock key and configures the system so that the key is enabled at startup;
- "Fix Office 365.bat" performs a quick repair of Microsoft Office without having to open the Control Panel;
- "Fix Office License.bat" updates Microsoft Office to an older version, fixing license error messages;
- "Fix Windows Time Zone.bat" enables and synchronizes Windows time, fixing issues such as "Time synchronization failed";
- "HD Repair.bat" checks and repairs errors on hard disk drive (HDD);
- "PC Info.bat" displays system and hardware information, including IP, hostname, and service tag;
- "Ping IP or website.bat" tests computer's connectivity to an IP address or website;
- "Reset network.bat" restarts the network adapter, renews the IP address, clears the DNS cache, and updates group policies. It can improve the loading of web pages;
- "Restore Win10 Context Menu.bat" restores the appearance of the Windows 10 Context Menu in Windows 11;
- "System repair.bat" uses the DISM and SFC tools to scan and repair system files that may be missing or corrupt;
- "Windows Program Update v2.bat" updates Windows programs and applications quickly and easily.

**Scripts for corporate environments:**

- "Check Windows Password Expiration v2.bat" checks the validity of the Windows password using the username;
- "Check Windows Password Expiration [by date].ps1" checks the validity of the password of all AD (Active Directory) users using dates;
- "AD Users with [Password never expires].ps1" displays a list of all AD users who have a lifetime password;
- "AD Users with [User must change password].ps1" displays a list of all AD users who are configured to change their password at the next logon.
