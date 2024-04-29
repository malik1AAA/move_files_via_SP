Move Files Power Automate Flow Documentation
Overview:
This repository contains the documentation and resources for the Move Files Power Automate Flow. The flow is designed to automatically move all files from one folder to another folder in response to the creation of an Excel file in a specified folder. The flow is triggered by the creation of the Excel file and moves the files from a source folder to a destination folder.

Components:
Power App (Canvas App)
The Power App provides a user-friendly interface for users to specify the source and destination folders and upload the Excel file. The app contains the following fields:

Source: Input field for specifying the source folder.
Destination: Input field for specifying the destination folder.
Upload File: Button to upload the Excel file.
Power Automate Flow:
The Power Automate Flow is triggered by the creation of an Excel file in the specified folder. It reads the contents of the Excel file and moves all files from the source folder to the destination folder.

GitHub Repository Structure:
Move-Files-Power-Automate-Flow/
│
├── README.md
├── PowerApp/
│   ├── MoveFilesApp.msapp
│   └── Screens/
│       ├── HomeScreen.png
│       ├── UploadScreen.png
│       └── ConfirmationScreen.png
│
└── PowerAutomateFlow/
    ├── MoveFilesFlow.png
    └── MoveFilesFlow.zip
