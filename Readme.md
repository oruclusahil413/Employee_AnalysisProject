# Employee Salary Tracker

A Python-based Employee Management and Salary Analytics project designed to manage employee information, track salary changes, record promotions, and analyze workforce data.

The project is being developed step by step using Object-Oriented Programming, CSV file handling, Pandas, NumPy, and Matplotlib.

## Project Overview

The main goal of this project is to build an employee management system that can store employee information, manage salaries, track career progression, and provide useful insights through data analysis and visualization.

The project will combine Python programming concepts with practical data analytics techniques.

## Development Roadmap

The project is divided into several parts. Each part will introduce new functionality and build upon the previous implementation.

### PART 1 — Object-Oriented Programming (Current Stage)

Build the foundation of the project using Python OOP.

**Planned and implemented functionality:**
- Create an Employee class.
- Define employee attributes such as name, level, and salary.
- Use constructors and special methods (`__init__`, `__str__`, `__repr__`).
- Implement properties, getters, and setters.
- Add input validation using `isinstance()` and custom exceptions.
- Define base salaries for different employee levels.
- Implement salary validation.
- Add promotion rules and prevent invalid level changes.

**Main concepts:** Classes, Objects, Encapsulation, Properties, Getters, Setters, and Exception Handling.

### PART 2 — Employee Management System

Expand the project to manage multiple employees and their employment information.

**Planned functionality:**
- Add new employees.
- Assign unique employee IDs.
- Update employee information.
- Search and filter employees.
- Manage departments and job positions.
- Promote employees and update their salaries.
- Record employee departures and terminations.
- Track active and inactive employees.

**Goal:** Build a complete employee management system rather than working with individual Employee objects.

### PART 3 — CSV Integration and Data Storage

Introduce CSV files to store employee information permanently.

**Planned functionality:**
- Save employee records into CSV files.
- Load existing employees when the program starts.
- Update records without losing existing information.
- Maintain separate files for employee information, salary history, and employment events.

**Planned CSV files:**

| File | Purpose |
|---|---|
| employees.csv | General employee information |
| salary_history.csv | Salary and promotion history |
| employment_events.csv | Hiring, promotion, and termination records |

**Goal:** Make employee data persistent and prepare it for further analysis.

### PART 4 — Salary and Employment History

Develop a system to track changes over time instead of storing only current employee information.

**Planned functionality:**
- Record every salary change.
- Track previous and current salary levels.
- Calculate salary increases.
- Record promotion dates.
- Calculate employee working periods.
- Maintain employment history.

**Goal:** Build a reliable historical dataset that can be used for future analytics.

### PART 5 — Data Analysis with Pandas

Use Pandas to process, organize, and analyze employee and salary datasets.

**Planned analysis:**
- Calculate average, minimum, and maximum salaries.
- Compare salaries between departments.
- Analyze salary differences across employee levels.
- Calculate salary growth percentages.
- Analyze employee working periods.
- Identify promotion patterns.
- Analyze employee turnover.
- Filter and group employee records.

**Goal:** Extract meaningful information from the collected employee data.

### PART 6 — Numerical Analysis with NumPy

Introduce NumPy for numerical calculations and statistical analysis.

**Planned functionality:**
- Calculate statistical measures.
- Analyze salary distributions.
- Calculate percentage changes.
- Compare salary growth across employees.
- Perform numerical operations on employee datasets.

**Goal:** Improve the numerical analysis capabilities of the project.

### PART 7 — Data Visualization with Matplotlib

Create visual representations of the analyzed data.

**Planned visualizations:**
- Employee salary growth over time.
- Salary distribution across departments.
- Salary comparisons between employee levels.
- Employee tenure distribution.
- Promotion frequency and salary increases.
- Employee hiring and termination trends.
- Department-level workforce comparisons.

**Goal:** Turn raw employee data into understandable charts and visual reports.

### PART 8 — Final Analytics and Project Improvement

Combine all previous components into a complete project.

**Planned improvements:**
- Organize the project into separate Python modules.
- Improve error handling and data validation.
- Add automated tests.
- Create reusable data analysis functions.
- Develop comprehensive analytical reports.
- Improve documentation.
- Prepare the project for GitHub portfolio presentation.

**Final Goal:** Build a complete employee management and salary analytics system using Python and its data science libraries.

## Technologies and Libraries

| Technology | Purpose |
|---|---|
| Python | Main programming language |
| Object-Oriented Programming | Project structure and employee management |
| CSV | Data storage |
| Pandas | Data manipulation and analysis |
| NumPy | Numerical and statistical calculations |
| Matplotlib | Data visualization |
| Jupyter Notebook | Data analysis and experimentation |
| Git & GitHub | Version control and project development |

## Project Status

**Currently in development.**

The project starts with the implementation of the Employee class and its salary management logic. Additional functionality will be introduced gradually throughout the development process.

## Final Objective

The ultimate objective is to create a practical Python project that combines software development, employee management, data processing, statistical analysis, and data visualization in one system.