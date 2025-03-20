### **# Lab 3: Editing Files with Vim and Nano**  

## 📌 Objective  
Learn how to use `vim` and `nano` to edit files, utilize shell variables, and modify text efficiently.  

## 🛠️ Steps  
### **Editing Files in Nano Instead of Vim**  

If you want to perform the same text editing tasks in **Nano**, follow these steps:  

---

### **1️⃣ Open the File in Nano**  
```bash
nano editing_final_lab.txt
```

---

### **2️⃣ Use a Shell Variable to Open the File**  
```bash
lab_file="editing_final_lab.txt"
nano $lab_file
```

---

### **3️⃣ Remove the Last Seven Characters from the First Line**  
- Open the file in Nano.  
- Move the **cursor to the end of the first line** using the **Right Arrow (`→`)** key.  
- Press `CTRL + 6` (**Start Selection** mode).  
- Use the **Left Arrow (`←`)** key **seven times** to highlight the last 7 characters.  
- Press `CTRL + K` (**Cut/Delete Selection**).

- ![image](https://github.com/user-attachments/assets/d8979ace-0d9b-483d-98e6-e0f40d3f9905)


---

### **4️⃣ Preserve Only the First Four Characters of the First Line**  
- Move to the **beginning of the first line** (`CTRL + A`).  
- Press `CTRL + 6` (**Start Selection** mode).  
- Move **right four times** (`→ → → →`) to select the first four characters.  
- Press `ALT + T` (**Trim Unselected Text**).  

✅ This will remove everything after the first four characters of the first line.  

![image](https://github.com/user-attachments/assets/026bfd73-967a-40c5-878d-5510e10e3618)


---

### **5️⃣ Save and Exit**  
- Press `CTRL + X` (**Exit**).  
- Press `Y` (**Yes** to save changes).  
- Press `ENTER` (**Confirm file name**).  

---

## 🖼️ **Screenshot**  
![image](https://github.com/user-attachments/assets/902d316a-b893-4982-ba25-2fd9a06c4a7b)
