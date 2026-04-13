# POEPART1.1
#  Cybersecurity Awareness Chatbot

##  Overview

The Cybersecurity Awareness Chatbot is a console-based application developed in C#. Its purpose is to educate users about basic cybersecurity concepts such as phishing, password safety, and safe browsing.

The chatbot provides an interactive experience by responding to user questions, personalizing responses using the user’s name, and guiding users toward safer online behavior.

---

## Objectives

* Create an interactive chatbot using C#
* Provide cybersecurity awareness to users
* Demonstrate the use of classes and methods
* Enhance user experience with a structured console interface
* Implement input validation and user-friendly responses

---

##  Features

### Personalization

* Prompts the user to enter their name
* Uses the name in all responses for a more engaging experience

###  Interactive Chat System

* Responds to user inputs such as:

  * “How are you?”
  * “What is your purpose?”
  * “What can I ask you about?”

###  Cybersecurity Topics Covered

* **Phishing Awareness**

  * Identifying suspicious emails and scams
* **Password Safety**

  * Creating strong and secure passwords
* **Safe Browsing**

  * Avoiding unsafe websites and downloads

### Enhanced Console UI

* Colored text for better readability
* Section headers and dividers
* Structured and visually appealing output
* Typing effect to simulate conversation

###  Input Handling

* Detects keywords in user input
* Provides relevant responses
* Handles unknown inputs gracefully

###  Exit Option

* Users can type `exit` to end the program

---

##  Program Structure

The application is divided into multiple classes:

### 1. `Program`

* Entry point of the application
* Handles the main loop and user interaction

### 2. `BotResponses`

* Contains all chatbot response methods
* Handles different cybersecurity topics

### 3. `InputHandler`

* Processes user input
* Determines which response method to call

### 4. `UIHelper`

* Handles typing effect
* Improves user interface presentation

---

##  How to Run the Program

1. Open the project in Visual Studio
2. Build the solution
3. Run the program
4. Enter your name when prompted
5. Ask questions related to cybersecurity
6. Type `exit` to quit the application

---

##  Example Questions

* What is phishing?
* How do I create a strong password?
* How are you?
* What is your purpose?
* Tell me about safe browsing

---

##  Input Validation

If the chatbot does not understand a question, it will respond with a message asking the user to rephrase and suggest valid topics.

---

##  Future Improvements

* Add a quiz system to test user knowledge
* Include more cybersecurity topics (e.g., malware, social engineering)
* Implement a graphical user interface (GUI)
* Add voice response for all chatbot outputs
* Improve natural language processing for better understanding

---

##  Conclusion

This project demonstrates the use of object-oriented programming, user interaction, and basic cybersecurity education in a structured and user-friendly way.

The chatbot provides a simple yet effective tool for promoting safe online practices.

---
