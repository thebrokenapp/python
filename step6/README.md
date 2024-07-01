# Strings and Text

In this exercise we create a bunch of variables with complex strings so you can see what they are for. A string is usually a bit of text you want to display to someone or ”export” out of the program you are
writing. Python knows you want something to be a string when you put either " (double-quotes) or '
(single-quotes) around the text. 

### Open any text editor (Notepad, Sublime text)
And write the following code

```python
types_of_people = 10
x = f"There are {types_of_people} types of people."
binary = "binary"
do_not = "don't"
y = f"Those who know {binary} and those who {do_not}."
print(x)
print(y)
print(f"I said: {x}")
print(f"I also said: '{y}'")
hilarious = False
joke_evaluation = "Isn't that joke so funny?! {}"
print(joke_evaluation.format(hilarious))
w = "This is the left side of..."
e = "a string with a right side."
print(w + e)
```
Save the file as `string_formatting.py`
You can name the file anything, but the extension must be `.py`
## Run the program
Open cmd and go to the location where you have saved the file and run:
```bash
 python strings_formatting.py
```

## You should see some statements printed on your cmd
```bash
There are 10 types of people.
Those who know binary and those who don't.
I said: There are 10 types of people.
I also said: 'Those who know binary and those who don't.'
Isn't that joke so funny?! False
This is the left side of...a string with a right side.
```

