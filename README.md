# Age Calculator 🕒

A beginner-friendly Python script that calculates your age based on your birth year — and optionally, your birth month.

## Features

- Fetches the current year and month from your PC
- Asks for your birth year (with error handling)
- Optional: counts months for a more precise age
- Beginner-readable and fully commented

## How It Works

1. The script gets the current date from your computer using Python’s `datetime` module.
2. You are asked to enter your birth year.
3. The program checks if the year is valid (not in the future).
4. Then, you choose whether you want your age in:
   - Only years  
   - Years and months
5. It calculates your age accordingly and prints the result.

## Example

```bash
please enter the year you were born: 2000
do you want to count in the months as well?
if so please answer yes or no... yes
please enter the month you are born in... 10
you are 24 years and 10 months old!

Requirements

    Python 3.x

No external libraries needed.
How to Run

    Clone the repository or download the Python file.

    Open a terminal and run:

python age_calculator.py

License

This project is open-source and free to use.
