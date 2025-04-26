# EX 6: Metadata Extraction using ExifTool log2timeline and Hidden Data Search using Steganography Tools
## AIM:
To extract metadata, perform timeline analysis, and search for hidden data using forensic tools like ExifTool, log2timeline, and steganography detection tools.

```
Register Number: 212222040121
Name: Praveen V
```

## DESIGN STEPS:
### Step 1:
Use exiftool to extract metadata from files such as images, documents, and videos.

### Step 2:
Use log2timeline and plaso to create and analyze event timelines from system logs and file metadata.

### Step 3:
Apply steganography detection tools like steghide, zsteg, or binwalk to uncover hidden data in media files.

## ANALYSING TOOLS
## A.Metadata Extraction using ExifTool
#### Step 1:Install ExifTool (if not already installed):
```
sudo apt update
sudo apt install libimage-exiftool-perl
```
#### Step 2: Navigate to the directory of the file:
![Screenshot 2025-04-23 210512](https://github.com/user-attachments/assets/122cd3c4-ca61-4185-919f-f6a1c8e878ee)


#### Step 3: Run ExifTool on a file (e.g., praveen.jpeg):
![{493BFA21-680A-4530-AAA1-1E12EE06A3A4}](https://github.com/user-attachments/assets/adb84e10-3e9c-4af1-b92d-1684e94adfe2)

#### Step 4: Export metadata to a text file (optional):
![{5AAF7492-20E3-455C-9CF6-1FE0804E9442}](https://github.com/user-attachments/assets/9a94502c-9931-4c76-b6fd-4caa5ca52579)

#### Step 5: Look for key details:
• Creation Date

• Modification Date

• Encoding Process

• Permissions




## B.Hidden Data Search using Steganography Tools

### 1. Using steghide
#### Step 1: Install steghide:
```
sudo apt install steghide
```
#### Step 2: Extract hidden data:
![{A9EE6D5B-27EE-46B2-A176-28D95F7DDDFF}](https://github.com/user-attachments/assets/d21b6136-e501-4326-81c4-7099732c967d)



### 2.Using zsteg(For PNG files)
#### Step 1: Install Ruby + zsteg:
```
sudo apt install ruby
sudo gem install zsteg
```

#### Step 2: Run zsteg on a PNG:
![{DEA3DD19-FE6F-44ED-B38B-E8235FC3AB74}](https://github.com/user-attachments/assets/ff647fa7-6b74-4f53-bddd-fa94fc1e290d)

### 4.Using strings (for quick hidden text):

#### Step1:  Create a text file to hide
![{C8E31D09-26F9-4E12-85B2-11887DA413B4}](https://github.com/user-attachments/assets/a3f7bd26-036f-4772-88dd-7df15e507691)

#### Step2: Use cat to append the text file to a JPEG\
![image](https://github.com/user-attachments/assets/70abee74-474d-4606-b365-9ea5c660199e)

#### Step3: Use strings to find the hidden message
![{1922A873-2EF1-4EE8-8589-20205D947064}](https://github.com/user-attachments/assets/cc94ed6b-7e4a-44f5-902d-7fa3e43ec415)










## RESULT:
Metadata was successfully extracted, timeline analysis was completed, and hidden data was identified using steganography tools.

