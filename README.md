# NutriFit: A Simple Health & Nutrition Calculator

## Overview
NutriFit is a simple Python program that runs in the terminal and lets you calculate four
common health numbers — **BMI**, **BMR**, **TDEE**, and **Body Fat Percentage** — from one
menu, instead of looking up separate calculators online.

## Features
- **BMI Calculator** – enter your height and weight, get your BMI and whether you're
  underweight, healthy weight, overweight, or obese.
- **BMR Calculator** – enter your gender, height, weight and age to get your Basal Metabolic
  Rate (calories your body burns at rest).
- **TDEE Calculator** – same as BMR but also asks your activity level and gives your total
  daily calorie needs.
- **Body Fat Percentage Calculator** – enter your category (Adult male / Adult female / Boy /
  Girl), height, weight and age to get an estimated body fat %.
- Menu keeps repeating so you can try different calculators without restarting the program.

## Technologies / Tools Used
- Python 3 (just the standard input()/print() — no extra libraries needed)
- Terminal / command line

## Steps to Install & Run
1. **Install Python 3** (skip this if you already have it):
   - Download it from [python.org/downloads](https://www.python.org/downloads/) and install it.
   - Check it worked by opening a terminal (Command Prompt / PowerShell on Windows, Terminal on
     Mac/Linux) and typing:
     ```
     python3 --version
     ```
     If that doesn't work, try `python --version` instead — some systems use `python` for
     Python 3.

2. **Get the code onto your computer.** You can do this either by cloning with git, or by just
   downloading the file:
   - **Option A — clone with git:**
     ```
     git clone https://github.com/just-divy/health-metrics-engine.git
     cd health-metrics-engine
     ```
   - **Option B — download without git:** go to
     [github.com/just-divy/health-metrics-engine](https://github.com/just-divy/health-metrics-engine),
     click the green **Code** button → **Download ZIP**, then unzip it and open a terminal
     inside that unzipped folder.

3. **Run the program** from inside that folder:
   ```
   python3 12.py
   ```
   (If `python3` doesn't work on your system, try `python 12.py` instead.)

4. **Use it:** type a number from the menu (`1`–`4` to run a calculator, `0` to exit), then
   answer the prompts it asks for (height, weight, age, etc.).

## Instructions for Testing
I tested it manually by running each option with normal values and checking the answer with a
calculator:
- **BMI**: tried values just above and below 18.5 / 24.9 / 29.9 to check the classification.
- **BMR**: ran the same height/weight/age as both `male` and `female` to check the formulas are
  different.
- **TDEE**: ran the same details through all five activity levels to check the numbers change.
- **Body Fat**: tried each of the four categories once.

> Note: right now the program expects you to type things exactly as shown (like `male`,
> `Adult male`) and it doesn't check for wrong/invalid input, so typing letters where a number
> is expected will crash it. This is listed as a known issue in the project report.

## Screenshots
![image alt](https://github.com/just-divy/Nutrifit-Project/blob/main/Code1.png)
![image alt](https://github.com/just-divy/Nutrifit-Project/blob/main/Code2.png)
![image alt](https://github.com/just-divy/Nutrifit-Project/blob/main/Output.png)

## Project Files
- `12.py` — the main program (menu + all four calculators)
- `statement.md` — problem statement and scope
- `README.md` — this file
