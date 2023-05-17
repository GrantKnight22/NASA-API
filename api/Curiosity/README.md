# NASA Rover Image API Python Project 🚀
#### This is a Python project that utilizes NASA's Rover Image API to retrieve and display images captured by various Mars rovers. The project demonstrates the concepts of inheritance and encapsulation through the implementation of classes.

**Project Structure 💻**

The project consists of the following files:

- api.py: Contains the main classes and logic for interacting with the NASA Rover Image API.

Dependencies
This project requires the following dependencies to be installed:
- requests: A library for making HTTP requests.
- OS: The os dependency in Python is a module that provides a portable way of using operating system-dependent functionality.

## **Abstraction**

  examples:
    `get_photos()`
    `download_photos()`
    `main()`

The `get_rover_data()` function abstracts the process of making an HTTP request to retrieve data about the rovers from the NASA API. It hides the implementation details of the request and JSON parsing, providing a high-level interface to retrieve the rover data.

The `get_photos()` function abstracts the process of fetching photos for a specific rover, sol (Martian day), and camera. It handles the HTTP request, checks for errors, and returns the retrieved photo data.

![alt text](RHAZ.jpg)

The `download_photos()` function abstracts the process of downloading an image given its URL and saving it to a specified path. It encapsulates the low-level details of handling the file download and writing the content to disk.
