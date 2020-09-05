# Linux Concepts
## 1. Difference between commands and shell
* Commands are just text you type in the terminal. They are case-sensitive.  
* After hit "enter", the meaning of the command will be interpreted by a computer program called the shell (Like the translator). Different shells can interpret the same command in different ways. The most popular shell is bash shell.  
* Terminal is just like the window of the shell, the place where we could type command.

## 2. Command Structure
* Commands (i.e. the commandName below) are just little programs installed in your computers.   
After the shell knows which program you want to run, it will search in shell "Path" -- the list of folders contains these programs, the folders could be shown by **`echo $PATH`**. The folder containing the specific command could be shown by **`which commandName`**.   
The shell will search the program from the very left folder until it finds the path stores the program.   
If the shell cannot find the command, it will show your "commandName: command not found" error.  
If there are multiple folders containing this program, the one in the first folder (the left one) will be used.  
* General command structure:   
**commandName (-option) (input)**
    * both option and input could be optional.
    * option could be a chain of options: -abcd == -bacd (order does not matter), but long format of options, such as --longFormat1 --longFormat2 must be separate.
    * number of the combination of (-option) (input) could be a lot, such as, 
    **`cal -A 1 -B 1 12 2020`**, but it will depends on commands.
    * options modify a command's behaviour.
    * Each command behaves very different. 

## 3. Manual Structure

| First Header  | Second Header |
| ------------- | ------------- |
| Content Cell  | Content Cell  |
| Content Cell  | Content Cell  |
    
    
