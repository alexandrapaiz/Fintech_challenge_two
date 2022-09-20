# Loan Qualifier Application

In this program, users will be able to input their data dynamically through the Fire CLI library to get matched with qualifying loans.

---
## Technologies

Describe the technologies required to use your project such as programming languages, libraries, frameworks, and operating systems. Be sure to include the specific versions of any critical dependencies that you have used in the stable version of your project.

This code was built using Python 3.7. The operating system is sys. The pathlib API is used. The CLI used is Fire. Questionairy is a python library used in this application.

---

## Installation Guide

In this section, you should include detailed installation notes containing code blocks and screenshots.
Install the following: pip intsall fire, pip install qustionairy, and the other two are already included in python. 

To install within the app, they are written as:
#import sys
#from pathlib import Path
#import fire
#import questionary
---

## Usage

This section should include screenshots, code blocks, or animations explaining how to use your project.

1. Open `app.py` and import `fire`at the top of the file.

2. At the bottom of `app.py`, replace the `run()` function with the `if __name__ == "__main__":` declaration. Move the call to the `run()` function inside the conditional.

    > **Hint** Be sure to test your code by running your program from the command line (Terminal or Git Bash). In the next steps, you'll refactor the function call to incorporate dynamic input from the CLI.

3. Remove the parentheses from `run()` and pass the function reference to `fire.Fire()`.

4. To accept dynamic input for the user's `credit_score` variable, complete the following steps:

    * Inside the `run()` function, comment out the variable `credit_score = 750`.

    * Pass the variable `credit_score` into the `run()` function as a parameter.

    * In your CLI, run the program using the following syntax: `python app.py --credit_score=750`

    * Confirm that your program returns the same variables for the monthly debt-to-income and loan-to-value ratios as well as the number of qualifying loans.

5. Refactor your code using the preceding steps to dynamically take in the values for the variables `debt`, `income`, and `home_value`.
    > `python app.py --credit_score=750 --debt=5000`.

---

## Contributors

In this section, list all the people who contribute to this project. You might want recruiters or potential collaborators to reach you, so include your contact email and, optionally, your LinkedIn or Twitter profile.

Alexandra Paiz created this code, all of it derived from the Columbia Fintech Bootcamp.

---

## License

When you share a project on a repository, especially a public one, it's important to choose the right license to specify what others can and can't with your source code and files. Use this section to include the license you want to use.

Liscence: MIT Liscence