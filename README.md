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
<details open>
<summary>example</summary>

  
</details>
  examples:
    `get_photos()`
    `download_photos()`
    `main()`

The `get_rover_data()` function abstracts the process of making an HTTP request to retrieve data about the rovers from the NASA API. It hides the implementation details of the request and JSON parsing, providing a high-level interface to retrieve the rover data.

The `get_photos()` function abstracts the process of fetching photos for a specific rover, sol (Martian day), and camera. It handles the HTTP request, checks for errors, and returns the retrieved photo data.

![alt text](https://res.cloudinary.com/practicaldev/image/fetch/s--wpFwFAvR--/c_limit%2Cf_auto%2Cfl_progressive%2Cq_auto%2Cw_880/https://anvil.works/blog/img/photos-from-mars/perseverance.jpg)

The `download_photos()` function abstracts the process of downloading an image given its URL and saving it to a specified path. It encapsulates the low-level details of handling the file download and writing the content to disk.

## **Encapsulation**

  examples:
    `get_rover_data()`
    `get_photos()`
    `download_photos()`
    `main()`

The functions `get_rover_data()`, `get_photos()`, `download_photos()`, and `main()` encapsulate specific tasks or functionalities. They group related code together, making it modular and easier to manage. Each function encapsulates a specific operation, such as retrieving rover data, fetching photos, downloading photos, and orchestrating the main program flow.

Variables like `api_key`, `api_url`, `rover_data`, and path are also encapsulated within their respective scopes (global or local to functions) and are not directly accessible from outside. This encapsulation helps maintain data integrity and avoids unintended modifications.

## **Inheretence**

  examples:
    `get_photos()`
    `download_photos()`
    `main()`

In the given code, there is no explicit demonstration of inheritance. However heres an example of how it can be used.

Suppose I have a Rover class that represents a rover on Mars. The Rover class could have attributes such as `name`, `status`, and `max_sol`, as well as methods like `get_photos()` and `download_photos()`.

## *License*
This project is licensed under the MIT License. Feel free to use, modify, and distribute the code for personal or commercial purposes.
