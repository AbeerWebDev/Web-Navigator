# Web-Navigator
This project does not have a live demo. Kindly view the JS files in the repository, and or clone the repository.

## Table of Content
* General Information
* Technologies Used
* Features
* Installation and Setup Instructions
* Usage
* Project Status
* Room for Improvement
* Acknowledgements
* Contact

## General Information
This project, Web Navigator, simulates the navigational operations of a web browser such as :  opening a new web page, navigating back a page, and going forward a page.

### Purpose of this project
To implement stacks in a real life example.

## Technologies Used
* JavaScript
* Node.js

## Features
* A back page.
* A next page.
* A current page.
* Helper methods.
* Prompts for user input.
* A Stack class.
* A Node class.
* A LinkedList class.

## Installation and Setup Instructions

Clone down this repository. In terminal type `node script.js` then follow instructions.

## Usage

**New Page**
* When we open a new page, we push the previous page on the backPages stack. When we revisit an old page and then visit a new page from there, we clear any content in the nextPages stack.

**Back Page**
* When we revisit a back page, we push the current page on the nextPages stack. Like the back button and the next button on a web browser, if the backPages stack is empty, the back operation is disabled and will be enabled only when the stack has content.

**User Input Prompts**
 * User input is required to: enter a new page to be visited, navigate backward or forward a page, and to quit the program.

**Display of User Information**

* Other than quitting, all operations display information about the current page and the top element of the two stacks.

**Quit Page**
* An option for the user to quit the prompts.

## Project Status
Project is: Completed

## Room for Improvement
* Add CSS file for a smoother user experience.

## Acknowledgements
* Many thanks to Codecademy.

## Contact
Created by Abeer Ahmed [LinkedIn profile](https://www.linkedin.com/in/abeerdev/) - feel free to contact me.

