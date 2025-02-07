# 🚀 Bash Scripts to Make Your Life Easier  

This repository contains simple yet useful Bash scripts to automate daily tasks and improve productivity.  

## 📌 openCloseApp  
A script that automatically **opens** a desired application when your computer connects to a specific WiFi network and **closes** it when disconnected.  

### 🔧 How It Works  
- Monitors your WiFi connection.  
- Opens the specified application when connected to your **home WiFi** (or any WiFi you set).  
- Closes the application when the WiFi is no longer detected.  

### 🛠 Setup Instructions  
1. **Edit the script:**  
   - Replace `"<yourHomeWifi>"` with your WiFi network name.  
   - Replace `"NAMEOFYOURAPP"` with the application's name.  

2. **Exit script***
   - make the script executable
 ```
 chmod +x openCloseApp
 ```  
3. **Schedule the script to run every 5 minutes using `crontab`:**  
   - open a terminal and type:  
```
crontab -e
```
  ### Then add the following line:
  ```
    */5 * * * * /path/to/your/folder/openCloseApp
  ```
4. Save and exit the edior and your Done!
   
