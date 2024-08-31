[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/6dJcL-Oy)
# Cloning your first repo, tinkering with vim and python, and navigating Markdown in Jupyter Notebook

For this assignment, you are going to:

1. Tinker with a text file using vim; 
2. write a very simple python program from the command line;
3. learn how to work with Markdown in Jupyter Notebooks;
4. submit your first assignment in GitHub Classroom.

## Tinkering with vim

To start working with the vim text editor, you can use the following command:

> vim data.txt

This opens the vim text editing environment and loads the file 'data.txt'. You can edit this file by entering 'insert' mode. To do so, you can type `i`. You should now be able to edit the text by using the arrow keys, delete/backspace, and the alphanumeric keys on your keyboard.

Let's add a line of text explaining what each column of the data set means. In this case we should add,

> T(K)  c_P(J/mol*K)

for the temperature in Kelvin, and the heat capacity at constant pressure per mol. We should add a line above that stating where the data was taken from. In this case, it was taken from the National Bureau of Standards and Technology (NIST). The specific resource was

'NIST Chemistry WebBook, SRD 69'

The web address for the data set is: 

'https://webbook.nist.gov/cgi/cbook.cgi?Source=1953DES876-880&Mask=2'

With that complete, let's line up all of the elements in the file and reorder the lines so that it goes from lowest temperature to highest temperature.

To complete the assignment, we need to exit 'insert' mode. This is achieved by entering `ESC`. Now we want to 'write' and 'quite' to complete our edits. This is done by typing `ESC`, then `:`, then `wq`, then `ENTER/RETURN`. This should take you back to the command line.

You can look at the contents of the edited file with the command

> cat data.txt

If you'd like to learn more about vim, you can search the web or try the following links:

[vim Documentation](https://www.vim.org/)
[Interactive vim Tutorial](https://openvim.com/)

## Writing a simple python program from the command line

We can write a program in python using the vim editor.

Open a file with vim for editing:

'vim hello-world.py'

push `i` to enter 'insert' mode

Add the following text:

> \# This program asks the user for their name and interest and prints the result to screen
> user_name = input("What is your name? ")
> user_interest = input("What are you interested in? ")
>
> print("My name is " + user_name + ", and I like " + user_interest + ".")

You can exit the 'insert' mode by pushing the `ESC` button. Now 'write' and 'quit' 'vim'. Push `ESC`, then `:`, then `wq` and `ENTER/RETURN`. This should bring you back to the command line.

You can run your program with the command 'python hello-world.py'.

## Using Markdown in Jupyter Notebook

Run Jupyter Notebook.

> jupyter noteboook

This will open an environment in your default web browser. You can open the provided Jupyter Notebook titled 'Working with Markdown in Jupyter Notebooks.ipynb'. Work through this notebook to learn how to use Markdown. This will help you keep notes about your computational physics work.

When you are done, navigate back to your terminal and type `CTRL+C` or `command+C` to exit Jupyter Notebook.

## Submitting your first assignment in Git Hub Classroom

With the above tasks complete, you can use the following series of commands to submit your assignment:

Check the status of the git environment:
> git status

Add any files or edits:
> git add .

Prepare your files for submission and write a note for yourself:
> git commit -m "completed hello-world assignment"

Submit your assignment:
> git push

Check that everything is in order:
> git status

You can continue to work on your files and follow this procedure to update your assignment, until the deadline for that assignment.


