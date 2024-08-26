# Cloning your first repo, tinkering with python, and navigating Markdown in Jupyter Notebook

For this assignment, you are going to:

1. write a very simple python program from the command line; and
2. learn how to work with Markdown in Jupyter Notebooks
3. submit your first assignment in GitHub Classroom

## Writing a simply python program from the command line

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

This will open an environment in your default web browser. You can open the provided Jupyter Notebook titles 'Working with Markdown in Jupyter Notebooks.ipynb'. Work through this notebook to learn how to use Markdown. This will help you keep notes about your computational physics work.

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


