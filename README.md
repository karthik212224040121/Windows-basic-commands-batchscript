# Windows-basic-commands-batchscript
Ex08-Windows-basic-commands-batchscript

# AIM:
To execute Windows basic commands and batch scripting

# DESIGN STEPS:

### Step 1:

Navigate to any Windows environment installed on the system or installed inside a virtual environment like virtual box/vmware 

### Step 2:

Write the Windows commands / batch file . Save each script in a file with a .bat extension. Ensure you have the necessary permissions to perform the operations. Adapt paths as needed based on your system configuration.
### Step 3:

Execute the necessary commands/batch file for the desired output. 




# WINDOWS COMMANDS:
## Exercise 1: Basic Directory and File Operations
Create a directory named "my-folder"

<img width="481" height="111" alt="image" src="https://github.com/user-attachments/assets/649e23a5-c6a0-45c2-bfc3-8e7a84f7900c" />


## COMMAND AND OUTPUT

Remove the directory "my-folder"

<img width="499" height="105" alt="image" src="https://github.com/user-attachments/assets/75458665-74ab-4e53-a71f-da3b32150e47" />


## COMMAND AND OUTPUT

Create the file Rose.txt

<img width="806" height="494" alt="image" src="https://github.com/user-attachments/assets/94ae628f-7621-4291-b8e7-e9688da3b54d" />


## COMMAND AND OUTPUT

Create the file hello.txt using echo and redirection

<img width="787" height="139" alt="image" src="https://github.com/user-attachments/assets/323e566c-0775-479e-89ad-a3c327f4a323" />


## COMMAND AND OUTPUT

Copy the file hello.txt into the file hello1.txt

<img width="715" height="79" alt="image" src="https://github.com/user-attachments/assets/f738b371-3000-4036-a80d-ff13cd6820a1" />


## COMMAND AND OUTPUT

Remove the file hello1.txt

<img width="527" height="64" alt="image" src="https://github.com/user-attachments/assets/b1f26df4-3543-4fd8-88ee-fabb4c35dab2" />


## COMMAND AND OUTPUT

List out the file hello1.txt in the current directory

<img width="530" height="231" alt="image" src="https://github.com/user-attachments/assets/55d1b8f2-c18b-44a3-a1d8-424f3ac38616" />


## COMMAND AND OUTPUT

List out all the associated file extensions 

<img width="490" height="1029" alt="image" src="https://github.com/user-attachments/assets/e1301bcc-2a92-468c-9f5f-2d297ed95bd0" />


## COMMAND AND OUTPUT


Compare the file hello.txt and rose.txt

<img width="540" height="199" alt="image" src="https://github.com/user-attachments/assets/ad3bd7eb-df2a-42e6-93be-14f08cc307a1" />

## COMMAND AND OUTPUT

## Exercise 2: Advanced Batch Scripting
Create a batch file named on the desktop. The batch file need to have a variable assigned with a desired name for ex. name="John" and display as "Hello, John".





## OUTPUT

<img width="616" height="142" alt="image" src="https://github.com/user-attachments/assets/cf1f6fda-35e5-4146-a90e-e8f7d1e442b0" />




Create a batch file  on the desktop that checks whether a user-input number is odd or not. The script should:
Prompt the user to enter a number.
Calculate the remainder when the number is divided by 2.
Display whether the number is odd or not.
Ask the user if they want to check another number.
Repeat the process if the user enters Y, and exit with a thank-you message if the user enters N.
Handle invalid inputs for the continuation prompt (Y/N) gracefully.



## OUTPUT

<img width="657" height="413" alt="image" src="https://github.com/user-attachments/assets/0fde79b1-65f6-49a9-9aea-259f6e0c6eb3" />




Write a batch file that uses a FOR loop to iterate over a sequence of numbers (1 to 5) and displays each number with the label Number:. The output should pause at the end.




## OUTPUT

<img width="451" height="236" alt="image" src="https://github.com/user-attachments/assets/db1305e3-4ad6-41c6-bc91-b670534e968f" />





Write a batch script to check whether a file named sample.txt exists in the current directory. If the file exists, display the message sample.txt exists. Otherwise, display sample.txt does not exist. Pause the script at the end to view the result.

Instructions:
Use the IF EXIST conditional statement.
Make sure the script works for files located in the same directory as the batch file.
Use pause to keep the command window open after displaying the message.
Expected Output (if the file exists):

## OUTPUT

<img width="602" height="300" alt="image" src="https://github.com/user-attachments/assets/2849168a-3c5b-425f-82bf-64659e34e42c" />



Write a batch script that displays a simple menu with three options:
Say Hello – Displays the message Hello, World!
Create a File – Creates a file named newfile.txt with the content This is a new file
Exit – Exits the script with a goodbye message
The script should repeatedly display the menu until the user chooses to exit. Use goto statements to handle menu navigation.


## OUTPUT

<img width="710" height="415" alt="image" src="https://github.com/user-attachments/assets/bc9edd91-24b3-45c1-860d-6b03f2a7b9dc" />




# RESULT:
The commands/batch files are executed successfully.

