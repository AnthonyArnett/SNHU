# Project Overview
This project is a grocery tracking system written in C++ for the fictional store **Corner Grocer.** The program reads daily purchase logs from an input file, tracks how often each item was sold, and provides output for management analysis. The program solves the problem of manually counting grocery purchases by automating the tracking, backing up of data, and providing visual frequency reports to support data-driven decision making.

## What I Did Well
* Encapsulated functionality into a dedicated class with clear responsibilities.
* Handled reading from and writing to files with proper error checking.
* Added in-line comments, clean naming conventions, and structured the project for easy navigation.
* Created an intuitive, repeatable menu with multiple functional options.
* Ensured data persistence by immediately saving a backup to _frequency.dat_ without user input.

## Future Enhancements
* I could enhance user input validation to handle cases where users enter invalid item names, special characters, or non-string input.
* Currently, item searches are case-sensitive. Converting input to lowercase would improve usability.
* Adding a separate error log file would make it easier to debug issues in production.
* For very large files, multithreading could be introduced for faster reading and writing operations.

## Most Challenging Problem
* Using C++ Maps Properly, especially ensuring insertion and lookup worked seamlessly and handling items not found in the map without causing runtime errors.
I overcame these challenges by reviewing C++ reference materials.

### Tools and Resources I Will Use More Often
* Cppreference
* Bookmarking documentation for STL containers (maps, vectors, etc.).

## Transferrable Skills
* File Handling in C++: A crucial skill for any application involving persistent storage.
* Data Structures: Using maps for frequency tracking.
* Program Design: Structuring programs with user-driven menus and handling program flow logically.
* Debugging and Error Handling: Catching and resolving file and user input errors.

## Maintainability, Readability, and Adaptability
To make the code readable and maintainable:
* I used descriptive names for variables, functions, and classes.
* Standard indentation, bracket use, and function ordering.
* In-line comments providing clear explanations for functions and major code blocks.
* Separated logic into header and implementation files, making it easier to expand or modify later.
