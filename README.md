# Todo List

## Prerequisites
You will need a JDK installed on your computer to be able to compile and run this program and possibly an IDE if you wish to run this file from within a project.

## Instillation and Running the Program
This assignment is all contained within one file (TodoList.java), so instillation will be straight forward. You will have a few different options to choose from:

### 1. Copy and paste the code into your IDE
Make sure you have a Java project open and an associated JDK. You should then create a Java class titled "TodoList.java" and then paste the code from the corresponding file in this repository. If you do have any other files in this project, make sure that this is the only class with a main method. You may now run the program through your IDE.

### 2. Save the file to a Java project
In order to do this without git, you will have to the home page of the repo and click the button with a down arrow and that says "Code". This should be a green button. Then click download as zip. You may then extract and drag the file "TodoList.java" file into the src folder within your Java project or copy it there through command line by using the command:
```
cp <File Location> <Destination Directory>
```

### 3. Run the program through command line
First you must download the Java file from this repository. You will have to the home page of the repo and click the button with a down arrow and that says "Code". This should be a green button. Then click download as zip. Extract the "TodoList.java" to a directory that is convenient for you. Open up an instance of a command line program and navigate to the directory that you placed the Java file in by doing:
```
cd <Desination Directory>
```
Before running the program, you must compile it by doing:
```
javac TodoList.java
```
You may now run the program with the command:
```
java TodoList
```
Make sure you don't have any file extensions after "TodoList" when trying to run the program.

## Operation
On start you will be taken to the main menu of the program where you will have access to the following commands: 
```
add
```
The add command will allow you to add items to your todo list. Just type a task and press enter. Once you are done adding tasks, type "back" to be taken back to the main menu.
```
see
```
The see command will display your todo list with all of your tasks on it. If the list is empty, the program will let you know and tell you to use the add command to begin adding tasks.
```
clear
```
The clear command will remove all of the tasks that you have added to the list or notify you if the list is already empty.
```
stop
```
The stop command will simply end the program and display an ending message.