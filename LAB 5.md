# Lab 5: Process Management and Package Management  

## 📌 Objective  
Learn how to manage system processes using `ps`, `top`, and `kill` commands and handle software installation using `dnf`.  

## 🛠️ Steps  

### 1️⃣ **View Running Processes**  
Use the following commands to list active processes:  

```bash
ps aux    # Display all running processes  
top       # Interactive real-time process viewer  
```

### 2️⃣ **Kill a Process**  
Find the process ID (PID) and terminate it:  

```bash
ps aux | grep process_name   # Find PID of a process  
kill <PID>                  # Kill process by PID  
kill -9 <PID>               # Force kill a process  
```

### 3️⃣ **Manage Software Using `dnf`**  
#### 🔹 Install a package:  
```bash
sudo apt install package_name
```
#### 🔹 Update package lists:  
```bash
sudo apt update
```
#### 🔹 Remove a package:  
```bash
sudo apt remove package_name
```

## 🖼️ **Screenshots**  
![image](https://github.com/user-attachments/assets/1d243a96-7c60-4bb9-b136-23f81069f20a)

![image](https://github.com/user-attachments/assets/206bfc83-3eaa-4009-9099-4e0052cf842a)

![image](https://github.com/user-attachments/assets/73dc4b2a-35b4-44ad-a11a-c385dcacb339)

![image](https://github.com/user-attachments/assets/76772c00-2de4-4a9e-bdbc-ad718f6dc54e)

![image](https://github.com/user-attachments/assets/3de4a878-a703-4cb3-b345-3aeedf3aaf2a)
