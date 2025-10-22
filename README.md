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

<img width="600" height="149" alt="image" src="https://github.com/user-attachments/assets/19ecbf61-e08c-4b68-bfdd-6cfbee7ff3e5" />


## COMMAND AND OUTPUT

Remove the directory "my-folder"

<img width="653" height="123" alt="image" src="https://github.com/user-attachments/assets/0a461ad8-4da0-48ca-be83-e555a322ad4e" />


## COMMAND AND OUTPUT

Create the file Rose.txt

<img width="1001" height="591" alt="image" src="https://github.com/user-attachments/assets/e3a28790-745e-4645-ada2-fa60e51f9314" />


## COMMAND AND OUTPUT

Create the file hello.txt using echo and redirection

<img width="925" height="164" alt="image" src="https://github.com/user-attachments/assets/f93c4213-4fc6-428d-bafd-ab6cbb2dc0c8" />


## COMMAND AND OUTPUT

Copy the file hello.txt into the file hello1.txt

<img width="928" height="116" alt="image" src="https://github.com/user-attachments/assets/5926c49c-3e2a-45ff-9f5d-ad330e6ae4b9" />


## COMMAND AND OUTPUT

Remove the file hello1.txt

<img width="611" height="63" alt="image" src="https://github.com/user-attachments/assets/c448f5b1-23a0-43c5-9031-edbf9c728425" />


## COMMAND AND OUTPUT

List out the file hello1.txt in the current directory

<img width="675" height="269" alt="image" src="https://github.com/user-attachments/assets/d3334ff7-b985-43e8-8569-d0bb10e78c0f" />


## COMMAND AND OUTPUT

List out all the associated file extensions 

<img width="462" height="976" alt="image" src="https://github.com/user-attachments/assets/0ae9dbb4-d18f-4924-9ef7-9042a0a694e3" />


## COMMAND AND OUTPUT

Compare the file hello.txt and rose.txt

<img width="609" height="243" alt="image" src="https://github.com/user-attachments/assets/2b770768-a798-4815-a9b3-20a6f1859102" />


## COMMAND AND OUTPUT

## Exercise 2: Advanced Batch Scripting
Create a batch file named on the desktop. The batch file need to have a variable assigned with a desired name for ex. name="John" and display as "Hello, John".

## OUTPUT

<img width="513" height="172" alt="image" src="https://github.com/user-attachments/assets/7939a45d-028a-4687-aae0-2e14f27031f2" />




Create a batch file  on the desktop that checks whether a user-input number is odd or not. The script should:
Prompt the user to enter a number.
Calculate the remainder when the number is divided by 2.
Display whether the number is odd or not.
Ask the user if they want to check another number.
Repeat the process if the user enters Y, and exit with a thank-you message if the user enters N.
Handle invalid inputs for the continuation prompt (Y/N) gracefully.

## OUTPUT

<img width="779" height="507" alt="image" src="https://github.com/user-attachments/assets/a6925c9a-330e-40c6-8559-0b8645d23db0" />




Write a batch file that uses a FOR loop to iterate over a sequence of numbers (1 to 5) and displays each number with the label Number:. The output should pause at the end.

## OUTPUT

<img width="510" height="290" alt="image" src="https://github.com/user-attachments/assets/ac623465-b6f4-450a-a5a2-80d9783736de" />





Write a batch script to check whether a file named sample.txt exists in the current directory. If the file exists, display the message sample.txt exists. Otherwise, display sample.txt does not exist. Pause the script at the end to view the result.

Instructions:
Use the IF EXIST conditional statement.
Make sure the script works for files located in the same directory as the batch file.
Use pause to keep the command window open after displaying the message.
Expected Output (if the file exists):

## OUTPUT

<img width="755" height="384" alt="image" src="https://github.com/user-attachments/assets/215ca8e0-47ad-47bb-8361-9b9193a898c2" />





Write a batch script that displays a simple menu with three options:
Say Hello – Displays the message Hello, World!
Create a File – Creates a file named newfile.txt with the content This is a new file
Exit – Exits the script with a goodbye message
The script should repeatedly display the menu until the user chooses to exit. Use goto statements to handle menu navigation.


## OUTPUT

<img width="868" height="522" alt="image" src="https://github.com/user-attachments/assets/388014e5-26c4-4421-9244-cec840282dd4" />




# RESULT:
The commands/batch files are executed successfully.

