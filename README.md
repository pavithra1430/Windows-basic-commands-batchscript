# pavithra s
# 212223220072
# Windows-basic-commands-batchscript
 # Ex08-Windows-basic-commands-batchscript

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
![image](https://github.com/pavithra1430/Windows-basic-commands-batchscript/assets/168256810/27bf97fc-506e-4918-8bf8-bfc14476f382)
## COMMAND AND OUTPUT
Change to the "MyLab" directory and create an empty text file named "MyFile.txt" inside it. %userprofile%\Desktop\MyLab
![image](https://github.com/pavithra1430/Windows-basic-commands-batchscript/assets/168256810/d9c3496b-517e-44f5-bb8a-31d9cd8b0b53)
## COMMAND AND OUTPUT
List the contents of the "MyLab" directory.
%userprofile%\Desktop\MyLab
![image](https://github.com/pavithra1430/Windows-basic-commands-batchscript/assets/168256810/20ae10b8-ca61-4e7b-b0f1-df0be0e51016)
![image](https://github.com/pavithra1430/Windows-basic-commands-batchscript/assets/168256810/67fa9263-f9d3-4512-a74c-5c5570b52e5d)

## COMMAND AND OUTPUT
Copy "MyFile.txt" to a new folder named "Backup" on the desktop.
![image](https://github.com/pavithra1430/Windows-basic-commands-batchscript/assets/168256810/66d7502c-4c27-44a1-8e56-3902583bea5c)

## COMMAND AND OUTPUT
Move the "MyLab" directory to the "Documents" folder.
mkdir %userprofile%\Desktop\Backup mkdir %userprofile%\Desktop\Backup
![image](https://github.com/pavithra1430/Windows-basic-commands-batchscript/assets/168256810/ec031ad3-8696-47a4-ae7b-1083cdbc9621)
![image](https://github.com/pavithra1430/Windows-basic-commands-batchscript/assets/168256810/19af82ac-f29f-4bf6-ab05-595fac98da89)

## COMMAND AND OUTPUT
mv Myfile.txt %userprofile%\Documents
![image](https://github.com/pavithra1430/Windows-basic-commands-batchscript/assets/168256810/745a1dc8-47c9-4bde-9cdd-82a3f5d26385)
## Exercise 2: Advanced Batch Scripting
Create a batch script named "BackupScript.bat" that creates a backup of files with the ".docx" extension from the "Documents" folder to a new folder named "DocBackup" on the desktop.
@echo off mkdir %userprofile%\Desktop\DocBackup copy %userprofile%\Documents*.docx %userprofile%\Desktop\DocBackup echo Backup completed successfully!
## OUTPUT
![image](https://github.com/pavithra1430/Windows-basic-commands-batchscript/assets/168256810/90ebf661-4409-44a4-9eea-5f088b57f1c2)
# RESULT:
The commands/batch files are executed successfully.

