 # VIRTUAL MACHINE CREATION IN LINUX

#### REG NUMBER: 212223040025
#### NAME: BASKAR J

## AIM

To Install Virtualbox / VMware Workstation and execute basic Linux commands like pwd, mkdir, ls, date, cat, and writing a Bash script to perform arithmetic operations and read a file from the terminal.

## PROBLEM STATEMENT

Manually executing basic Linux tasks like file management, navigation, and arithmetic operations can be inefficient. This experiment aims to automate these tasks using Bash scripting, including:
1. Displaying the current directory, files, and system date.
2. Reading and displaying file contents.
3. Performing basic arithmetic operations.

## REQUIREMENTS
- Oracle VM VirtualBox Manager
- Kali Linux
- Mousepad (Text Editor)
- Terminal

## ALGORITHM
 ### Step 1: 
 Open the terminal in Kali Linux.
 ### Step 2:
 Use basic Linux commands to navigate and manage files.
 ### Step 3:
 Create a Bash script using Mousepad.
 ### Step 4:
 Write a script that performs arithmetic operations and reads a file.
 ### Step 5:
 Make the script executable.
 ### Step 6:
 Run the script and observe the output.
 
## COMMANDS

###  Execute Basic Linux Commands in the Terminal
#### Check the Current Working Directory
```
pwd
```
#### Create a New Directory
```
mkdir my_experiment
```

#### Navigate into the Directory
```
cd my_experiment
```
#### List the Files in the Directory
```
ls
```

#### Write Some Text into the File
```
echo "Hello, this is a test file." > myfile.txt
```

#### Read the File Contents
```
cat myfile.txt
```
#### Get the Current Date and Time
```
date
```

###  Writing a Bash Script in Mousepad
#### Open Mousepad
```
mousepad script.sh &
```

#### Write the Bash Script

```
#!/bin/bash 

echo "Current Directory:"
pwd

echo "Files in this directory:"
ls

echo "Current Date and Time:"
date

read -p "Enter first number: " num1
read -p "Enter second number: " num2

sum=$((num1 + num2))
diff=$((num1 - num2))
prod=$((num1 * num2))
quot=$((num1 / num2))
rem=$((num1 % num2))

echo "Sum: $sum"
echo "Difference: $diff"
echo "Product: $prod"
echo "Quotient: $quot"
echo "Remainder: $rem"


```
####  Make the Script Executable
```
chmod +x script.sh
```

#### Run the Script
```
./script.sh
```

## OUTPUT

Configuration of Kali Linux on Oracle Virtual Box :

![image](https://github.com/user-attachments/assets/83f47f18-6b45-4f19-8068-7bb8b1baf013)

![image](https://github.com/user-attachments/assets/37d6897f-243c-4d54-8de5-94a9bbff069f)

![image](https://github.com/user-attachments/assets/886e2da0-20e9-4aee-9d95-ff49b2034739)

![image](https://github.com/user-attachments/assets/800125e2-db71-4106-bba4-3654ed8a2168)

![image](https://github.com/user-attachments/assets/80eaea48-c5cd-469d-944a-4c608c6875e4)

![image](https://github.com/user-attachments/assets/65b2acbf-4d79-461f-afce-c729077a3e27)

## RESULT
Thus, this experiment helped in understanding the fundamentals of Linux commands and Bash scripting for automation and system management.

  


