# Event Planner

![Java](https://img.shields.io/badge/Java-17-blue)
![License](https://img.shields.io/badge/License-MIT-green)

## Overview
The Event Planner is a command-line application for personal event management. It provides secure user authentication and full CRUD (Create, Read, Update, Delete) functionality for managing personal plans and events.

## Key Features
- 🔐 Secure user authentication (sign up/sign in)
- ✏️ Create, view, and delete personal plans
- 💾 Persistent data storage using text files
- 📝 Simple and intuitive command-line interface
- 🛡️ Input validation for usernames, emails, and passwords

## Technical Stack
- **Language**: Java
- **Data Storage**: 
  - `data_base.txt` - stores user credentials
  - `[username].txt` - stores individual user plans
- **Dependencies**: Pure Java (no external libraries required)

## Installation & Usage

### Prerequisites
- Java Development Kit (JDK) 17 or later
- Basic command-line knowledge

### Running the Application
1. Clone the repository or download the source files
2. Compile the program:
   ```bash
   javac Main.java
  "

   Run the application:

```bash
java Main
```
File Structure
```
event-planner/
├── Main.java                # Main application file
├── data_base.txt            # User credentials database
├── [username].txt           # Individual user plan files
```
##Usage Guide

Authentication
- 1) Sign Up:
- Create a new account with unique username and email.
 - Password requirements:
- Minimum 4 characters.
- Must contain at least one letter.
- Spaces are not allowed
------------------------
- 2) Sign In:
- Access your existing account
- Enter your username and password
------------------------
- 3) Plan Management
- Create Plan:
- Add new items to your personal plan
------------------------
- 4) View Plan:
- List all items in your current plan with numbering
------------------------
- 5) Delete Plan Item:
- Remove specific items by their number
------------------------
- 6) Exit:
- Safely exit the application

#  Data Storage Format
User Credentials (data_base.txt)
```
username email password
username2 email2 password2
```
# User Plans ([username].txt)
```
Plan item 1
Plan item 2
Another important task
```
- Error Handling
- The application includes robust error handling for:
- File operations (creation, reading, writing)
- User input validation
- Duplicate username/email detection
- Password requirements enforcement
---------------------------------------
- Limitations
- Basic text-based interface
- No encryption for stored passwords
- Single-user mode (no shared plans)
---------------------------------------
- Future Enhancements
- Add plan item editing functionality
- Implement password encryption
- Add date/time tracking for plan items
- Develop graphical user interface (GUI)
- --------------------------------------
PRESENTATION ---> (https://www.canva.com/design/DAGk7ATptec/P8WQY-pz87qzfXnQTZz0vA/edit?utm_content=DAGk7ATptec&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton)

