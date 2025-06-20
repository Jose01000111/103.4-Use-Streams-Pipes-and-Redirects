# 🧪 Lab: 103.4 Use Streams, Pipes, and Redirects

## 📘 What I did in this lab
I explored how to redirect input and output, pipe data between commands, use command substitution with xargs, and duplicate output using tee. Each technique was tested with practical examples to reinforce its use.

I’ve included some helpful links to guide you through the lab and for studying afterward:

[EXAM OBJECTIVE 103.4](https://www.lpi.org/our-certifications/exam-101-102-objectives/#103.4_Use_streams.2C_pipes_and_redirects)

[OBJ. 103.4 NOTES]()

[OBJ. 103.4 LAB]()

---

## 1️⃣ Redirecting Standard Input, Output, and Error

🔹Redirect STDOUT to a file

🔹Redirect STDERR to a file

🔹Redirect both STDOUT and STDERR to a file

🔹Redirect STDIN from a file

![gLT0iqL](https://github.com/user-attachments/assets/858937ad-aaeb-4e7a-8eea-df723cf8d524)

## 2️⃣ Pipe the Output of One Command to the Input of Another

🔹View only the first 5 lines of a directory listing

![ZMaiw2W](https://github.com/user-attachments/assets/2e26eda5-01ee-42d0-90eb-90247c61916b)

🔹Count the number of .conf files in /etc

![w0630JD](https://github.com/user-attachments/assets/d78f10c7-75cc-427a-8bec-c3e3220b34a3)

## 3️⃣ Use the Output of One Command as Arguments to Another

🔹Delete all .bak files in a directory

🔹Count the number of lines in each .txt file

![zLiTEGZ](https://github.com/user-attachments/assets/fa2ebc8b-ed45-4e01-be48-5af1ead9b2e9)

> ⚠️ **Disclaimer:**  
> I'm currently using **CentOS** 🐧 and my system does **not contain any `.bak` files** 📁 by default.  
> Any examples or commands involving `.bak` files may need to be **adjusted** 🛠️ or **skipped** 🚫 accordingly.

## 4️⃣ Send Output to Both STDOUT and a File

🔹List processes and save + view them simultaneously

![zW5MW7Z](https://github.com/user-attachments/assets/a6d7e479-cf5f-4d22-8b8d-bff2aa903a08)

🔹Chain commands with tee and grep

![8Q7TdKv](https://github.com/user-attachments/assets/df8a1119-cf51-43a9-a72a-a1bc08f3af5e)

![f2N9CKi](https://github.com/user-attachments/assets/f3cee10b-cf7a-4875-9c52-93f7f7f8fc31)

## 📒 What I Learned
This lab taught me how to manipulate command output like a pro 💻, using redirection and pipes to automate tasks and chain tools efficiently. I also learned how tee and xargs can supercharge workflows by duplicating output or executing commands dynamically. 🧠🛠️
