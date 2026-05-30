# IP Allow List Management (Python)

## Overview

This project is a simple Python script that manages an IP allow list by removing unwanted IP addresses from a file. It is based on a training exercise.

## Purpose

Allow lists are used to control which IP addresses can access restricted systems. This script automates the process of updating the list by removing specific IPs.

## Note

The `allow_list.txt` file used in this project is a sample file created for learning purposes.

## How it Works

* Opens the file using `with open()`
* Reads the file using `.read()`
* Converts the data into a list using `.split()`
* Uses a `for` loop to check each IP in the remove list
* Removes matching IP addresses using `.remove()`
* Converts the list back to a string using `"\n".join()`
* Writes the updated data back to the file using `.write()`

## Skills Used

* Python file handling
* Working with lists and strings
* Loops and conditions

