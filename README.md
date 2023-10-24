# VIT Student Accommodation
[![Open Source Love svg1](https://badges.frapsoft.com/os/v1/open-source.svg?v=103)](#)
[![GitHub Forks](https://img.shields.io/github/forks/AtharvaKulkarniIT/VIT_Student_Accomodation-in-c.svg?style=social&label=Fork&maxAge=2592000)](https://www.github.com/AtharvaKulkarniIT/VIT_Student_Accomodation-in-c/fork)
[![GitHub Issues](https://img.shields.io/github/issues/AtharvaKulkarniIT/VIT_Student_Accomodation-in-c.svg?style=flat&label=Issues&maxAge=2592000)](https://www.github.com/AtharvaKulkarniIT/VIT_Student_Accomodation-in-c/issues)
[![contributions welcome](https://img.shields.io/badge/contributions-welcome-brightgreen.svg?style=flat&label=Contributions&colorA=red&colorB=black	)](#)

This program is designed to manage the accommodation of students at VIT . It allows you to input student details, search for specific students, display records, calculate NCGPA (Normalized Cumulative Grade Point Average), and perform room allotment during the counseling process.The code uses arrays, structures, file handling , merge sort and linked lists to manage student records and hash tables (arrays of pointers to `struct hash`) to organize students by branch and slot for efficient data storage and retrieval.

## Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Introduction

The program uses a hash-based data structure to store and manage student records, with a focus on the branch-wise distribution of students. It calculates NCGPA for students and helps in room allotment during counseling.

## Features

- Input student details from a text file.
- Search for a specific student by Roll No.
- Display student records branch-wise.
- Calculate NCGPA for all students.
- Perform room allotment during counseling based on student ranks.

## Usage

1. Clone the repository:
   ```
   git clone https://github.com/AtharvaKulkarniIT/VIT-Student-Accommodation-in-c.git
   ```
   ```

   cd VIT-Student-Accommodation
   ```

3. Compile and run the program:
 ```  
   gcc -o main main.c
```
```
   ./main
   ```

3. Follow the on-screen instructions to perform various tasks like data retrieval, NCGPA calculation, and room allotment during counseling.

## Contributing

Contributions to this project are welcome. If you want to contribute, please open an issue or create a pull request. Ensure that you follow the code of conduct and contribute according to the guidelines.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
