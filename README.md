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

## COMMAND AND OUTPUT

<img width="511" height="121" alt="image" src="https://github.com/user-attachments/assets/da1cd2ad-7c80-4d8e-9e74-1c0e6bc6bccc" />


Remove the directory "my-folder"

## COMMAND AND OUTPUT

<img width="548" height="221" alt="image" src="https://github.com/user-attachments/assets/cf0f94fc-3592-4b9e-91f6-87506a688b78" />


Create the file Rose.txt

## COMMAND AND OUTPUT

<img width="538" height="310" alt="image" src="https://github.com/user-attachments/assets/439411e5-82d7-4315-8236-950911b89602" />


Create the file hello.txt using echo and redirection

## COMMAND AND OUTPUT
<img width="553" height="103" alt="image" src="https://github.com/user-attachments/assets/afdbfb31-6d85-48b2-8cdd-c99b4a6de3b0" />


Copy the file hello.txt into the file hello1.txt

## COMMAND AND OUTPUT
<img width="557" height="55" alt="image" src="https://github.com/user-attachments/assets/0aed3fa7-7234-4be4-8629-36d45e00a312" />


Remove the file hello1.txt

## COMMAND AND OUTPUT
<img width="497" height="200" alt="image" src="https://github.com/user-attachments/assets/d32121a7-3a64-4506-a122-b7bc570d3a69" />


List out the file hello1.txt in the current directory

## COMMAND AND OUTPUT
<img width="545" height="658" alt="image" src="https://github.com/user-attachments/assets/49d26c65-f667-4647-8e55-2dc0992584ab" />


List out all the associated file extensions 

## COMMAND AND OUTPUT
<img width="558" height="663" alt="image" src="https://github.com/user-attachments/assets/2a25dd29-0608-40ed-8c49-d09b8dcdd385" />


Compare the file hello.txt and rose.txt

## COMMAND AND OUTPUT
<img width="541" height="172" alt="image" src="https://github.com/user-attachments/assets/8d4ee56a-f2e1-4b21-a07d-2ae8ba97e020" />


## Exercise 2: Advanced Batch Scripting
Create a batch file named on the desktop. The batch file need to have a variable assigned with a desired name for ex. name="John" and display as "Hello, John".





## OUTPUT

<img width="442" height="82" alt="image" src="https://github.com/user-attachments/assets/1530f0e1-4e54-400c-9519-ea50066129c0" />


Create a batch file  on the desktop that checks whether a user-input number is odd or not. The script should:
Prompt the user to enter a number.
Calculate the remainder when the number is divided by 2.
Display whether the number is odd or not.
Ask the user if they want to check another number.
Repeat the process if the user enters Y, and exit with a thank-you message if the user enters N.
Handle invalid inputs for the continuation prompt (Y/N) gracefully.



## OUTPUT

<img width="521" height="335" alt="image" src="https://github.com/user-attachments/assets/6ffa06bf-8e00-4874-9472-15ac7ac6faed" />



Write a batch file that uses a FOR loop to iterate over a sequence of numbers (1 to 5) and displays each number with the label Number:. The output should pause at the end.




## OUTPUT
<img width="487" height="182" alt="image" src="https://github.com/user-attachments/assets/44f2c1a1-f2a9-423e-87fd-e187015b3280" />




Write a batch script to check whether a file named sample.txt exists in the current directory. If the file exists, display the message sample.txt exists. Otherwise, display sample.txt does not exist. Pause the script at the end to view the result.

Instructions:
Use the IF EXIST conditional statement.
Make sure the script works for files located in the same directory as the batch file.
Use pause to keep the command window open after displaying the message.
Expected Output (if the file exists):

## OUTPUT
<img width="565" height="165" alt="image" src="https://github.com/user-attachments/assets/02af4d32-025b-48fb-b182-2b244fe6d2a7" />


Write a batch script that displays a simple menu with three options:
Say Hello – Displays the message Hello, World!
Create a File – Creates a file named newfile.txt with the content This is a new file
Exit – Exits the script with a goodbye message
The script should repeatedly display the menu until the user chooses to exit. Use goto statements to handle menu navigation.


## OUTPUT

<img width="525" height="617" alt="image" src="https://github.com/user-attachments/assets/27506515-797e-4956-80da-99a561fd6ae1" />


# RESULT:
The commands/batch files are executed successfully.

