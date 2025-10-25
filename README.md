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
<img width="831" height="308" alt="image" src="https://github.com/user-attachments/assets/1de2d6a0-44f1-4c80-84eb-5d8391a3b455" />

Remove the directory "my-folder"

## COMMAND AND OUTPUT

<img width="1121" height="481" alt="image" src="https://github.com/user-attachments/assets/c3f6dd64-7bf8-4966-8958-e0a2495650b7" />

Create the file Rose.txt

## COMMAND AND OUTPUT

<img width="1065" height="471" alt="image" src="https://github.com/user-attachments/assets/1efff10a-87e9-40c1-b270-0462b53cd8e3" />

Create the file hello.txt using echo and redirection

## COMMAND AND OUTPUT
<img width="1128" height="123" alt="image" src="https://github.com/user-attachments/assets/0f383c5a-41f1-4345-96e6-7717ee6b96b4" />

Copy the file hello.txt into the file hello1.txt

## COMMAND AND OUTPUT
<img width="1135" height="171" alt="image" src="https://github.com/user-attachments/assets/b01825cf-8f03-42ea-a931-89646d338842" />

Remove the file hello1.txt

## COMMAND AND OUTPUT
<img width="1082" height="297" alt="image" src="https://github.com/user-attachments/assets/406a5775-0b66-43b8-827b-d1c0af782605" />

List out the file hello1.txt in the current directory

## COMMAND AND OUTPUT
<img width="635" height="887" alt="image" src="https://github.com/user-attachments/assets/a4ccf57e-1fbb-4401-b8ea-e23089034a99" />

List out all the associated file extensions 

## COMMAND AND OUTPUT
<img width="670" height="887" alt="image" src="https://github.com/user-attachments/assets/87a4deab-7406-405d-a4df-fbc8bfada9cf" />


Compare the file hello.txt and rose.txt

## COMMAND AND OUTPUT
<img width="647" height="153" alt="image" src="https://github.com/user-attachments/assets/2257d79c-afce-40fc-a651-03fddae68cba" />

## Exercise 2: Advanced Batch Scripting
Create a batch file named on the desktop. The batch file need to have a variable assigned with a desired name for ex. name="John" and display as "Hello, John".





## OUTPUT

<img width="791" height="103" alt="image" src="https://github.com/user-attachments/assets/a2da35fe-7794-4862-a90a-bb203b462fe7" />


Create a batch file  on the desktop that checks whether a user-input number is odd or not. The script should:
Prompt the user to enter a number.
Calculate the remainder when the number is divided by 2.
Display whether the number is odd or not.
Ask the user if they want to check another number.
Repeat the process if the user enters Y, and exit with a thank-you message if the user enters N.
Handle invalid inputs for the continuation prompt (Y/N) gracefully.



## OUTPUT


<img width="758" height="261" alt="image" src="https://github.com/user-attachments/assets/78549779-114c-4a62-8da4-6bbf66ba1107" />


Write a batch file that uses a FOR loop to iterate over a sequence of numbers (1 to 5) and displays each number with the label Number:. The output should pause at the end.




## OUTPUT


<img width="792" height="227" alt="image" src="https://github.com/user-attachments/assets/6f80f21a-6c59-4ed2-bc1c-a731a514453b" />


Write a batch script to check whether a file named sample.txt exists in the current directory. If the file exists, display the message sample.txt exists. Otherwise, display sample.txt does not exist. Pause the script at the end to view the result.

Instructions:
Use the IF EXIST conditional statement.
Make sure the script works for files located in the same directory as the batch file.
Use pause to keep the command window open after displaying the message.
Expected Output (if the file exists):

## OUTPUT

<img width="760" height="108" alt="image" src="https://github.com/user-attachments/assets/48f4755f-253b-4ca6-9d42-039203c7573d" />

Write a batch script that displays a simple menu with three options:
Say Hello – Displays the message Hello, World!
Create a File – Creates a file named newfile.txt with the content This is a new file
Exit – Exits the script with a goodbye message
The script should repeatedly display the menu until the user chooses to exit. Use goto statements to handle menu navigation.


## OUTPUT

<img width="818" height="502" alt="image" src="https://github.com/user-attachments/assets/1c594ec7-ded9-4f1e-83c8-637a6da9c70b" />


# RESULT:
The commands/batch files are executed successfully.

