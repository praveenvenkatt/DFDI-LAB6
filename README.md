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


## Metadata Extraction using ExifTool
### Step 1:Install ExifTool (if not already installed):
```
sudo apt update
sudo apt install libimage-exiftool-perl
```
### Step 2: Navigate to the directory of the file:
![Screenshot 2025-04-23 210512](https://github.com/user-attachments/assets/122cd3c4-ca61-4185-919f-f6a1c8e878ee)


### Step 3: Run ExifTool on a file (e.g., praveen.jpeg):
![{493BFA21-680A-4530-AAA1-1E12EE06A3A4}](https://github.com/user-attachments/assets/adb84e10-3e9c-4af1-b92d-1684e94adfe2)

### Step 4: Export metadata to a text file (optional):
![{5AAF7492-20E3-455C-9CF6-1FE0804E9442}](https://github.com/user-attachments/assets/9a94502c-9931-4c76-b6fd-4caa5ca52579)



### Step 4: Look for key details:
• Creation Date

• Modification Date

• Encoding Process

• Permissions


## OUTPUT:
# A. Using ExifTool – for file metadata

 Install:
```
sudo apt update
sudo apt install exiftool -y
```
 Extract metadata from a file:
```
exiftool image.jpg
```
 Batch process a folder:
```
exiftool -r /path/to/folder
```
Useful flags:

-G: Show metadata group

-time:all: Show only timestamps

-GPSLatitude -GPSLongitude: Extract GPS data

![image](https://github.com/user-attachments/assets/75dc64ee-7af7-4765-9ecf-0ee8eafec4af)

# install log2timeline
```
sudo apt install plaso -y
```
```
sudo apt install steghide -y
```
# Embed data
```
steghide embed -cf /home/kali/Downloads/wallpaper.jpg -ef /home/kali/Downloads/secret.txt
```
![image](https://github.com/user-attachments/assets/47166c87-4abe-4226-9529-141f1f602ec9)

Extract hidden data:
```
steghide extract -sf hidden.jpg
```
![image](https://github.com/user-attachments/assets/f7d8e853-d26b-4226-93f2-ccd5d73b9de3)

# Using binwalk – for file analysis

```
sudo apt install binwalk -y
binwalk suspicious.jpg
```
![image](https://github.com/user-attachments/assets/7fcc7fe9-bf17-47e5-9405-3800b294a7ea)


## RESULT:
Metadata was successfully extracted, timeline analysis was completed, and hidden data was identified using steganography tools.

