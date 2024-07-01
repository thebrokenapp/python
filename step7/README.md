# Taking Inputs from User

So far everything in our code is running pre-configured. If we send this code to someone to use it (say a program for adding numbers) the user will have to make the change in the code to add the numbers that they want.
Obviously not everyone will like it!

Instead we should how to take input from users of the program
### Open any text editor (Notepad, Sublime text)
And write the following code

```python
print("How old are you?")
age = input()
print("How tall are you?")
height = input()
print("How much do you weigh?")
weight = input()
print(f"So, you're {age} old, {height} tall and {weight} heavy.")
```
Save the file as `taking_user_inputs.py`
You can name the file anything, but the extension must be `.py`
## Run the program
Open cmd and go to the location where you have saved the file and run:
```bash
 python taking_user_inputs.py
```

## You should see some statements printed on your cmd
```bash
How old are you?
20
How tall are you?
5.5 ft
How much do you weigh?
70kg
So, you're 20 old, 5.5 ft tall and 70kg heavy.
```

