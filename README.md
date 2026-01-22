# Regex Matcher App (Mini Regex101 Clone) 

A simple Flask-based web application that clones the core functionality of **regex101.com**.  
Users can enter a **Test String** and a **Regular Expression (Regex Pattern)**, then the application displays all the matched strings instantly.

---

##  Features
 Accepts user input for:
- Test String (Text Area)
- Regex Pattern (Input Field)

 Displays:
- All matched strings found in the test string

 Error Handling:
- Shows an error message if the regex pattern is invalid

 Clean UI:
- Simple and user-friendly interface for testing regex patterns

---

##  Tech Stack
- **Backend:** Python, Flask  
- **Frontend:** HTML (Jinja2 Templates)  
- **Regex Engine:** Python `re` module  

---

##  How It Works
1. User enters a test string (paragraph/text).
2. User enters a regex pattern.
3. On clicking **Submit**, the app runs regex matching using Python.
4. The output section displays all matched results.

---

##  Example Inputs

###  Example 1: Phone Number Matching
**Test String:**
Call me at 9876543210 or 9123456780
**Regex Pattern:** \d{10}

**Output:**
- 9876543210  
- 9123456780  




