# Cloud-Based File Storage System (Prototype)

Internship project – Cloud Computing, SmartED Innovations  
**Jafena U** | CSE-B | RMK Engineering College

A simple web prototype where a user can sign up, log in, upload a file, see it in a stored-files list, download it and delete it.

## Features
- Sign up and login with email validation
- Show / hide password
- Upload, download and delete files (PDF, PNG, JPG, TXT, DOCX, up to 10 MB)
- Each user sees only their own files
- Storage-used bar (50 MB demo limit)

## How to run
Open `index.html` in Chrome or Edge. No installation needed.

## Note
This is a prototype. Accounts are stored in the browser's localStorage and files in IndexedDB to simulate cloud storage. A real version would use a server and a cloud service such as AWS S3, Azure Blob or Google Cloud Storage.
