# Using-MGT-Consoles
customizations for the new employee's laptop
Go to search on the Taskbar, Type in MMC(Microsoft Management Console) & Launch
I select Yes to the User Account Control (UAC) to protect  the system against misuse of administrative privileges by rogue software
Go to File>Addorremovesnap-in>Add DiskManagement>Finish
                            >Add Group Policy>Finish
                            >Add Task sceduler>OK 
                            ![adding snap-in](https://github.com/user-attachments/assets/9178dc1e-d3e3-4184-a826-329481eeb5c0)
Go to File menu>save AS>Desktop 🖥 
# Changing Drive Letters to prevent conflict and various Mapped Network Drives
Double click Custome tools on Desktop> Yes>Disk Management> RightClick Drive C>Explore
Right click CD ROM 0>Change letter and path>Change>select a different letter Z>OK>Yes
![DVD Z](https://github.com/user-attachments/assets/812ceaac-0c7f-402e-a9ee-491e46b56d25)
![DVD O to DVD Z](https://github.com/user-attachments/assets/38981539-b778-47b6-8885-873065d1e2fb)

# configuring Security to prevent Staff on using recycle Bin 
Group Policy>User configuration>Administrative> Double click Remove Recycle bin>Enabled
![enabling remove recycle bin](https://github.com/user-attachments/assets/aea262e2-ab61-4bf7-a75c-9017c45d9582)

Update registry by making information visibvle on Desktop 🖥 
Registry editor> HKEY_CURRENT_USER>Control Panel>select Desktop>PaintDesktopVersion>Change 0 t0 1> Apply changes 
