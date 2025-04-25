
# USING AUTOPSY TO RETRIEVE THE DELETED FILES


## **Aim:**
Data recovery from unallocated space, using forensic tools(Autospy) to extract and analyze data.

## **Implementation steps:**

### **1. Copy Files to the Virtual Disk**  
- Open **File Explorer** → Go to the new drive (`C: or D:`), where the folder created in the New Virtual Disk
- Create a new folder (`Autospy`) and copy **images or files** into it.  

### **2. Delete the Files**  
- Select any one or two images → Press **Delete**.  
- Empty the **Recycle Bin** to permanently delete them.  

### **3. Recover Deleted Files Using Autopsy**  
### **Open Autopsy & Create a New Case** 

- Launch **Autopsy** and **Run as a administrator**  
- Click **Create New Case**.  

![](./images/a1.png)

- Enter a **Case Name** (e.g., `Autopsy1`).  
- Choose a **Case Folder** location.  
- Click **Next** → Click **Finish**.  

![image](https://github.com/user-attachments/assets/26bea7a9-18fe-4aad-99a0-c4772fb264ec)


### **Add the Virtual Disk as an Evidence Source**  
- Click **Add Data Source**  → **Select Host**

![](./images/a3.png)

- Select **Local Disk** → **next** 

![](./images/a4.png)

- Select Disk → **Choose the VHD drive (`Drive1`)**

![image](https://github.com/user-attachments/assets/a88c6d24-f9ea-47a4-bdca-7c0937673d3c)


- Click **Next** → Keep default settings → Click **Finish**.  
- Wait for Autopsy to process the disk.  

### **Recover Deleted Files**  
- Go to **File Views** (left panel).  

![image](https://github.com/user-attachments/assets/da97403b-2f0c-49f2-83d7-c9d034cbd97c)

- Click **Deleted Files** → Find your deleted images.  
- Right-click an image → Click **Extract File**.  

![image](https://github.com/user-attachments/assets/91e991ca-1319-4ec9-bcf2-dd3bac173493)


- Select a folder to see the recovered files (e.g., `C:\forensic`).  
- Image is recovered successfully.


## Output :
### Folder before deleting the files
![image](https://github.com/user-attachments/assets/b3bf5b17-918b-42d8-b3e1-c5952e638194)


### Folder after deleting the files
![image](https://github.com/user-attachments/assets/bd827fd2-94e3-4449-911c-0f9a547a4725)


### Folder after extracting the deleted images using autopsy


![image](https://github.com/user-attachments/assets/4aa48c63-6bf4-4b96-8acd-e85bf2235f7a)


## Result:
Successfully extracted the deleted files from unallocated space using the Autospy tool.
