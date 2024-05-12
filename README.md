# Windows-basic-commands-batchscript
Ex08-Windows-basic-commands-batchscript
Developed by: OVIYA N
Register number:212223040140
# AIM:
To execute Windows basic commands and batch scripting

# DESIGN STEPS:

### Step 1:

Navigate to any Windows environment installed on the system or installed inside a virtual environment like virtual box/vmware 

### Step 2:

Write the Windows commands / batch file
Save each script in a file with a .bat extension.
Ensure you have the necessary permissions to perform the operations.
Adapt paths as needed based on your system configuration.
### Step 3:

Execute the necessary commands/batch file for the desired output. 




# WINDOWS COMMANDS:
## Exercise 1: Basic Directory and File Operations
Create a directory named "MyLab" on the desktop.


## COMMAND AND OUTPUT
'''
![image](https://github.com/Oviya49/Windows-basic-commands-batchscript/assets/153576803/cd6af351-fa9f-4e39-b570-c26635b80cce)
'''
Change to the "MyLab" directory and create an empty text file named "MyFile.txt" inside it.


## COMMAND AND OUTPUT
'''

![image](https://github.com/Oviya49/Windows-basic-commands-batchscript/assets/153576803/5144b463-a48e-4dfc-b384-83db032adde3)
'''
List the contents of the "MyLab" directory.


## COMMAND AND OUTPUT
'''
![image](https://github.com/Oviya49/Windows-basic-commands-batchscript/assets/153576803/b3f7613c-db67-45b0-b487-af094c0096ed)
'''
Copy "MyFile.txt" to a new folder named "Backup" on the desktop.

## COMMAND AND OUTPUT
'''
![image](https://github.com/Oviya49/Windows-basic-commands-batchscript/assets/153576803/6e906f85-7560-4745-b981-c82abedc8427)
'''
'''
![image](https://github.com/Oviya49/Windows-basic-commands-batchscript/assets/153576803/33a54265-a72d-4ed4-9a6f-3c1a5838dbf0)
'''
Move the "MyLab" directory to the "Documents" folder.


## COMMAND AND OUTPUT
'''
![image](https://github.com/Oviya49/Windows-basic-commands-batchscript/assets/153576803/c01efaed-2a1b-444c-a321-5c31b327db0d)
'''

## Exercise 2: Advanced Batch Scripting
Create a batch script named "BackupScript.bat" that creates a backup of files with the ".docx" extension from the "Documents" folder to a new folder named "DocBackup" on the desktop.
'''
@echo off
mkdir %userprofile%\Desktop\DocBackup
copy %userprofile%\Documents\*.docx %userprofile%\Desktop\DocBackup
echo Backup completed successfully!
'''
'''
@echo off
mkdir %userprofile%\Desktop\DocBackup
copy %userprofile%\Documents\*.docx %userprofile%\Desktop\DocBackup
del %userprofile%\Documents\*.docx
echo Backup and deletion completed successfully!
'''





## OUTPUT
'''
![image](https://github.com/Oviya49/Windows-basic-commands-batchscript/assets/153576803/250e8cbf-ac43-419b-9eb0-46496c32588a)

'''





# RESULT:
The commands/batch files are executed successfully.

