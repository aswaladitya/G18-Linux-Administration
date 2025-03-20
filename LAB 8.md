# Lab 8: Shell Scripting Basics  

## 📌 Objective  
Write shell scripts to print system information, perform basic mathematical calculations with user input, and use redirection operators.  

## 🛠️ Steps  

### 1️⃣ **Print System Information**  
Run the following shell script to display system details:  

```bash
#!/bin/bash
echo "System Information:"
lscpu
```

### 2️⃣ **Perform Basic Mathematical Calculation with User Input**  
Use the following script to take two numbers as input and perform an operation:  

```bash
#!/bin/bash
read -p "Enter first number: " num1
read -p "Enter an operator (+, -, *, /): " op
read -p "Enter second number: " num2
echo "Result: $((num1 $op num2))"
```

### 3️⃣ **Use Redirection Operators**  
Store command output in a file using redirection:  

```bash
ls -l > output.txt
```

## 🖼️ **Screenshots**  
![image](https://github.com/user-attachments/assets/f312ac9e-2812-4fd8-8ee3-65cb0d2be358)


![image](https://github.com/user-attachments/assets/3ec97594-c8ea-4cc3-8c73-58bab2d44703)

