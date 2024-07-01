# Variables and Printing Again


Let's practice more!

### Open any text editor (Notepad, Sublime text)
And write the following code

```python
my_name = 'Ankit'
my_age = 20 # not a lie
my_height = 74 # inches
my_weight = 140# lbs
my_eyes = 'Black'
my_teeth = 'White'
my_hair = 'Black'

print(f"Let's talk about {my_name}.")
print(f"He's {my_height} inches tall.")
print(f"He's {my_weight} pounds heavy.")
print("Actually that's not too heavy.")
print(f"He's got {my_eyes} eyes and {my_hair} hair.")
print(f"His teeth are usually {my_teeth} depending on the coffee.")
# this line is tricky, try to get it exactly right
total = my_age + my_height + my_weight
print(f"If I add {my_age}, {my_height}, and {my_weight} I get {total}.")
```
Save the file as `variables_and_printing.py`
You can name the file anything, but the extension must be `.py`
## Run the program
Open cmd and go to the location where you have saved the file and run:
```bash
 python variables_and_printing.py
```

## You should see some statements printed on your cmd
```bash
Let's talk about Ankit.
He's 74 inches tall.
He's 140 pounds heavy.
Actually that's not too heavy.
He's got Black eyes and Black hair.
His teeth are usually White depending on the coffee.
If I add 20, 74, and 140 I get 234.
```

