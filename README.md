# BIC21203 Lab 4A - JavaScript

## Student details
- **Name:** PIRRAVIIN A/L MANIMARAN
- **Student ID:** CI240058
- **GitHub repository:** To be added after the repository is created.

## Overview
This repository contains three small interactive webpages demonstrating JavaScript DOM selection, functions, conditional statements, loops, element creation, and event listeners.

## Folder structure
- `Q1/index.html` — Interactive Text Changer
- `Q2/index.html` — Smart Number Validator
- `Q3/index.html` — Dynamic Number Generator
- `screenshots/` — Add genuine screenshots captured while testing each question.

## How to run
1. Download or clone this repository.
2. Open the relevant `index.html` file in a web browser.
3. Follow the test instructions below.

## Question 1 — Interactive Text Changer
The page initially displays “Welcome to my website!”. Click **Change Message**. The paragraph should change to “Hello there!”.

## Question 2 — Smart Number Validator
Enter a value and click **Check**. Test the following:
| Input | Expected message |
|---|---|
| `5` | The number is lower than 10 |
| `10` | The number is equal to 10 |
| `15` | The number is higher than 10 |
| `abc` | Please enter a valid number! |
| Empty or spaces only | Please enter a valid number! |
| `10.5` | The number is higher than 10 |

## Question 3 — Dynamic Number Generator
Click **Generate**. The ordered list should contain “The number is 1” through “The number is 5”. Click the button again to verify that the list does not duplicate.

## Screenshots / test evidence
Capture your own screenshots after running each page in a browser. Save them in the `screenshots/` folder, for example:
- `screenshots/q1-output.png` — show the changed message after clicking the button.
- `screenshots/q2-output.png` — show representative validation output. For complete evidence, capture the different input cases or include them in a test table in your report.
- `screenshots/q3-output.png` — show the generated list after clicking Generate, ideally after clicking it more than once to verify there are no duplicates.

**Important:** Screenshots have not been included yet. Add genuine screenshots from your own tests before submitting.

## Reflection
This lab helped me practise selecting HTML elements using JavaScript DOM methods and responding to user actions with event listeners. I used a function to change paragraph content, conditional statements to validate numeric input, and a `for` loop to generate list items. I also learned to clear existing list content before regenerating it to avoid duplicates. Testing different inputs helped me check that the pages behave as expected.

## Before submission
- [ ] Add screenshots captured from your browser.
- [ ] Create the GitHub repository and upload these files.
- [ ] Replace the repository placeholder in this README with the real GitHub URL.
- [ ] Add the real GitHub URL to the final PDF.
- [ ] Check the lecturer's instructions and submit the PDF through AUTHOR or the specified LMS.
