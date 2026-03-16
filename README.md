# US Bikeshare Data Explorer

This project is a simple command-line Python application that allows users to explore bikeshare data from three major U.S. cities: Chicago, New York City, and Washington.

The program asks the user to choose a city, month, and day of the week, then calculates useful statistics about bike trips. These include the most common travel times, popular stations, trip durations, and user demographics.

This project was created as part of the Udacity Git & GitHub course to practice working with Git, GitHub workflows, and basic data analysis in Python.

---

## How to Use the Project

### 1. Fork the repository

First, fork the original Udacity repository to your own GitHub account.  
This allows you to have your own remote repository where you can push your changes.

### 2. Clone the repository

Clone your fork to your local machine:

```bash
git clone https://github.com/maurorizzo/udacity_vc_project.git
```

Navigate into the project directory:

```bash
cd udacity_vc_project
```

---

### 3. Install dependencies

This project requires Python and the following libraries:

- pandas
- numpy

Install them with:

```bash
pip install pandas numpy
```

---

### 4. Run the program

Execute the script in your terminal:

```bash
python bikeshare_starter.py
```

The program will prompt you to select:

- a city
- a month
- a day of the week

After that, it will display several statistics based on the selected filters.

---

## Project Features

The script calculates several statistics about bikeshare usage.

### Travel Time Statistics

- Most common month
- Most common day of week
- Most common start hour

### Station Statistics

- Most frequently used start station
- Most frequently used end station
- Most common combination of start and end stations

### Trip Duration

- Total travel time
- Average travel time

### User Statistics

- Counts of user types
- Counts of gender
- Earliest birth year
- Most recent birth year
- Most common birth year

---

## Contribution Guidelines

This repository was created as part of a Udacity course project and is mainly intended for learning purposes.

If you would like to experiment with the project, feel free to fork the repository and build your own version. Possible improvements could include:

- adding data visualizations
- improving user input validation
- supporting additional cities
- restructuring the code for better modularity

---

## Credits

This project is based on the Udacity course materials.

Original project repository:  
https://github.com/udacity/post-your-work-project

The bikeshare datasets and initial project structure were provided by Udacity as part of the Git & GitHub course.

---

## Date Created

March 10, 2026