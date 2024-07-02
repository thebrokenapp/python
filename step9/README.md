# Argument Unpacking

In this exercise we will cover one more input method you can use to pass variables to a script (script being
another name for your .py files). You know how you type python app.py to run the app.py file?
Well the app.py part of the command is called an ”argument.” What we’ll do now is write a script that
also accepts additional arguments
### Open any text editor (Notepad, Sublime text)
And write the following code

```python
from sys import argv

script, first, second, third = argv

print("The script is called:", script)
print("Your first variable is:", first)
print("Your second variable is:", second)
print("Your third variable is:", third)
```
On line 1 we have what’s called an ”import.” This is how you add features to your script from the Python
feature set. Rather than give you all the features at once, Python asks you to say what you plan to use.
This keeps your programs small.

They are called `modules` or `libraries`. Some are available in Python installations itself, while some are external libraries that we need install like `Flask` or `requests`

Save the file as `arguments.py`
You can name the file anything, but the extension must be `.py`
## Run the program
Open cmd and go to the location where you have saved the file and run:
```bash
 python arguments.py
```

## You should see some statements printed on your cmd
```bash
How old are you?
20
How tall are you?
5 ft
How much do you weigh?
50kg
So, you're 20 old, 5 ft tall and 50kg heavy.
```

