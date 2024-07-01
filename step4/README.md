# Variables in Python


In programming, a variable is nothing more than a name for something.
Variables are particularly important so that your code can run in `config-driven` approach.
Here’s how you use variables in Python:

### Open any text editor (Notepad, Sublime text)
And write the following code

```python
cars = 100
space_in_a_car = 4.0
drivers = 30
passengers = 90
cars_not_driven = cars - drivers
cars_driven = drivers
carpool_capacity = cars_driven * space_in_a_car
average_passengers_per_car = passengers / cars_driven
print("There are", cars, "cars available.")
print("There are only", drivers, "drivers available.")
print("There will be", cars_not_driven, "empty cars today.")
print("We can transport", carpool_capacity, "people today.")
print("We have", passengers, "to carpool today.")
```
Save the file as `variables.py`
You can name the file anything, but the extension must be `.py`
## Run the program
Open cmd and go to the location where you have saved the file and run:
```bash
 python variables.py
```

## You should see some statements printed on your cmd
```bash
There are 100 cars available.
There are only 30 drivers available.
There will be 70 empty cars today.
We can transport 120.0 people today.
We have 90 to carpool today.
```

