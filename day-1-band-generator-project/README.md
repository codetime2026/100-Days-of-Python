# Band Name Generator 🎸

## Overview

This is a simple Python program that generates a fun and personalized band name based on user input. It combines the name of the city you grew up in with the name of your pet to create a unique band name.

## How It Works

The program prompts the user to answer two questions:

1. What is the name of the city you grew up in?
2. What is the name of your pet?

It then combines these two inputs and displays them as your generated band name.

## Code Explanation

```python
print("Hello this is a band name generator.")
city = input("What is the name of the city you grew up in?\n")
pet = input("What is the name of your pet?\n")
print("This is your band name. " + city + " " + pet)
```

* `print(...)` displays messages to the user.
* `input(...)` collects user input from the keyboard.
* The final `print(...)` statement concatenates the two inputs with a space to form the band name.

## Requirements

* Python 3.x installed on your system

## How to Run

1. Save the code in a file, for example: `band_name_generator.py`
2. Open a terminal or command prompt.
3. Navigate to the directory where the file is saved.
4. Run the script using:

   ```
   python band_name_generator.py
   ```

## Example

```
Hello this is a band name generator.
What is the name of the city you grew up in?
Austin
What is the name of your pet?
Buddy
This is your band name. Austin Buddy
```

## Possible Improvements

* Add input validation to handle empty responses
* Format the output with capitalization
* Allow multiple pets or cities for more variations
* Add randomness for more creative band names

## License

This project is open-source and free to use for educational and personal purposes.
