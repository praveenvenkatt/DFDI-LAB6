# Metadata-Extraction-using-ExifTool-log2timeline-and-Hidden-Data-Search-using-Steganography-Tools
## AIM:
To extract metadata, perform timeline analysis, and search for hidden data using forensic tools like ExifTool, log2timeline, and steganography detection tools.

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
![{0C96D7A8-9ED2-40F8-94D4-129237C09713}](https://github.com/user-attachments/assets/7bb22c15-0eb9-4560-9ca7-8b66fee2f9ff)


### 2.Using zsteg(For PNG files)
#### Step 1: Install Ruby + zsteg:
```
sudo apt install ruby
sudo gem install zsteg
```

#### Step 2: Run zsteg on a PNG:




### 3.Using binwalk
#### Step1: Install binwalk:
```
sudo apt install binwalk
```

#### Step 2: Scan for embedded files:
#### Step 3: Extract all hidden files:

### 4.Using strings (for quick hidden text):








## RESULT:
Metadata was successfully extracted, timeline analysis was completed, and hidden data was identified using steganography tools.

