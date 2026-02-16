# Install-and-Configure-Splunk

### Objective: 

The objective is install and configure Splunk on Ubuntu machine.

### Requirements:

- System: Ubuntu
- Splunk Enterprise (Free version for local setup)
- Terminal(Command Line Access)

### Steps:

### 1. Download Splunk Enterprise

- Get the Download Link:

  - Visit the official Splunk Download Page.

  - Select the Linux tab and choose the .deb package.

  - Click "Copy wget link"
    

<img width="1120" height="780" alt="1 Ubuntu" src="https://github.com/user-attachments/assets/e142a1e8-5e36-49b8-9839-0fa2fac6d3ba" />



- Open **Terminal** and download Splunk using `wget`

<img width="1120" height="780" alt="3 UB" src="https://github.com/user-attachments/assets/03eade3c-6302-4dc4-8c46-5e89a7bdd54a" />

### 2. Once downloaded, install Splunk

`sudo -dpkg -i splunk_package_name.deb`

<img width="1120" height="780" alt="5u" src="https://github.com/user-attachments/assets/ff4eaeb2-ff5c-4514-a738-d61558eee361" />

### 3. Starts the Splunk service 

`sudo /opt/splunk/bin/splunk start`

If an error occurs, 2nd command can be used to start Splunk

<img width="1120" height="780" alt="8U" src="https://github.com/user-attachments/assets/752f9f4e-df2d-4dbb-9436-a8d726c7ab31" />

### 4. Check if Splunk is running

`/opt/splunk/bin/splunk status`

<img width="1120" height="780" alt="12U" src="https://github.com/user-attachments/assets/120bda12-e1e0-41d8-9cb6-b822de65f1ca" />

### 5. Open port 8000

`sudo ufw allow 8000/tcp`

<img width="1120" height="780" alt="14U" src="https://github.com/user-attachments/assets/fd79cd9a-05e5-4fd9-82bc-25da7dc9a3cc" />

### 6. Check VM's IP

`ifconfig`

<img width="1120" height="780" alt="13U" src="https://github.com/user-attachments/assets/1f5c3346-6bb4-4a5e-ac84-0cff5f0661db" />

### 7. Open a web browser and go to:

`http://<your-VM-IP>:8000`

<img width="1120" height="780" alt="15U" src="https://github.com/user-attachments/assets/16189175-d44a-476b-beb4-0705004684ac" />


<img width="1120" height="780" alt="20U" src="https://github.com/user-attachments/assets/7c405f37-8a43-420e-a4cc-0e4a3885a0af" />


<img width="1120" height="780" alt="17U" src="https://github.com/user-attachments/assets/cac60122-5a27-491a-ac83-4d51a58289d9" />




