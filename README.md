# payroll_system_1

A simple Java-based payroll system demonstrating **inheritance** and **polymorphism**. This project models employees in an organization with different roles, such as `Developer` and `Manager`, and calculates their salaries based on their experience.

## Features

- **Base Class**: `Employee`  
  Represents a general employee with a base salary and an experience factor.

- **Subclasses**:
  - `Developer`: Inherits from `Employee` and calculates a higher salary based on a developer-specific formula.
  - `Manager`: Inherits from `Employee` and calculates an even higher salary tailored for managers.

- **Polymorphism**:  
  Demonstrates runtime method overriding for calculating salaries based on the actual object type.

File Structure
PayrollSystem/
├── src/
│   ├── Employee.java
│   ├── Developer.java
│   ├── Manager.java
│   └── PayrollSystem.java
├── README.md
└── .gitignore
MIT License

Copyright (c) 2025 Love Chauhan

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.


