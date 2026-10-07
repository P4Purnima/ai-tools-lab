# ai-tools-lab
AI Tools Lab

A Python-based lab project demonstrating the use of sorting algorithms and utility functions. This project is created as part of an Artificial Intelligence Tools and Applications Lab to practice Python programming, Git, GitHub, and basic software development workflows.

Project Description

AI Tools Lab is a collection of simple and useful Python programs developed for learning and experimentation.

The project currently focuses on:

Sorting algorithms such as Bubble Sort
Utility functions for common programming tasks
Simple and readable Python implementations
Version control using Git and GitHub

The project is designed to help students understand how Python programs can be organized, documented, and maintained using a GitHub repository.

Project Structure
ai-tools-lab/
│
├── README.md
├── hello.py
├── sorting.py
└── utils.py
Installation
1. Clone the Repository
git clone <repository-url>
2. Open the Project Directory
cd ai-tools-lab
3. Check Python Installation

Make sure Python is installed on your computer:

python --version

No external Python packages are required for the basic programs in this project.

Usage
Bubble Sort

The sorting.py file contains a Bubble Sort implementation that sorts a list of numbers in ascending order.

Example:

from sorting import bubble_sort

numbers = [50, 30, 40, 10, 20]

result = bubble_sort(numbers)

print(result)

Output:

[10, 20, 30, 40, 50]
Utility Functions

The utils.py module contains reusable utility functions for common programming tasks.

Example:

from utils import is_palindrome

result = is_palindrome("madam")

print(result)

Output:

True
How to Run

Individual Python files can be executed using:

python filename.py

For example:

python sorting.py
Contributors
Purnima Malhotra
License

This project is licensed under the MIT License.

The MIT License allows others to use, modify, and distribute the project while retaining the original copyright and license notice.

Learning Outcomes

Through this project, I learned:

Basic Python programming
Implementation of sorting algorithms
Creating and using utility functions
Organizing Python files in a project
Using Git for version control
Creating and managing a GitHub repository
Writing project documentation using Markdown
Using AI assistance for documentation