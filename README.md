Overview

This project demonstrates how to use YAML files in Python to store and retrieve structured data. The application reads student information from a YAML file and provides functionality to display and filter the data based on GPA.

Prerequisites
pip install pyyaml


Ensure you have Python installed on your system. You also need to install the PyYAML package:

├── students.yaml   # YAML file containing student data
├── app.py          # Python script to process the data
└── README.md       # Project documentation


Expected Output

All Students:
Name: Alice, Age: 21, Major: Computer Science, GPA: 3.8
Name: Bob, Age: 22, Major: Mathematics, GPA: 3.5
Name: Charlie, Age: 20, Major: Physics, GPA: 3.9
Name: David, Age: 23, Major: Chemistry, GPA: 3.2
Name: Eva, Age: 21, Major: Computer Science, GPA: 3.7

Enter minimum GPA to filter students: 3.6

Students with GPA >= 3.6:
Name: Alice, Age: 21, Major: Computer Science, GPA: 3.8
Name: Charlie, Age: 20, Major: Physics, GPA: 3.9
Name: Eva, Age: 21, Major: Computer Science, GPA: 3.7
