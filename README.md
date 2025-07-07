# Admission_Enquiry_Form
## Date: 07.07.2025
## Objective:
To design a simple Admission Enquiry Form using basic HTML that collects student details such as name, contact, program of interest, and a message for further communication.

## Tasks:
#### 1. Set Up the HTML Structure:
Use ```<!DOCTYPE html>```, ```<html>```, ```<head>```, and ```<body>``` tags to define the document structure.
Set the ```<title>``` as "Admission Enquiry Form".

#### 2. Add a Page Heading:
Use ```<h1>``` to title the page as “Admission Enquiry”.

#### 3. Create the Form Layout:
Use the ```<form>``` tag to wrap all input elements. Set method="post" for structure.

#### 4. Add Input Fields:
Include the following fields using appropriate HTML elements:

Full Name

Email Address

Phone Number 

Program of Interest 

Message

#### 5. Add Submit and Reset Buttons:
Use submit and reset at the bottom of the form.

#### 6. Use HTML-only:
No CSS or JavaScript is to be included. Focus on structure and accessibility.

## HTML Code:
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Saveetha Engineering College - Admission Enquiry</title>
</head>
<body>
    <h1>Saveetha Engineering College</h1>
    <h2>Admission Enquiry Form</h2>
    <form >
        <label for="name">Full Name : </label>
        <input type="text" name="name" required><br><br>

        <label for="email">Email Address : </label>
        <input type="email" name="email" required><br><br>

        <label for="number">Mobile number : </label>
        <input type="number" name="number" required><br><br>

        <label for="gender">Email Address : </label><br>
        <input type="radio" name="gender" required>Male<br>
        <input type="radio" name="gender" required>Female
        <br><br>

        <label for="date">Date of Birth : </label>
        <input type="date" name="date"><br><br>

        <label for="name">DEPT : </label>
        <select name="dept">
           
            <option>ECE</option>
            <option>EEE</option>
            <option>MECH</option>
            <option>CSE</option>
            <option>IT</option>
            <option>AIML</option>
            <option>AIDS</option>
        </select><br><br>

        <label for="academic">Academic Qualifications</label><br>
        <textarea name="academic" cols="25" row="15" placeholder="Enter your academic qualification"></textarea>
        <br><br>

        <label for="Address">Address</label><br>
        <textarea name="Address" cols="25" row="15" placeholder="Enter your Address"></textarea>
        <br><br>

        <label for="mode">Mode of Contact : </label><br>
        <input type="checkbox" name="mode">Email<br>
        <input type="checkbox" name="mode">Phone

        <br><br>
        <button>Submit</button>
        <br><br>

        
        <button type="reset" >Reset</button>
    </form>
</body>
</html>
```
## Live Web Page:
https://nmrohith.github.io/Admission_Enquiry_Form/
## Output:
![Screenshot 2025-07-07 142100](https://github.com/user-attachments/assets/b4cd67bb-fcf8-4c96-b090-174bce1a43bb)

## Result:
An Admission Enquiry Form using HTML that collects student details and message for institutional follow-up is successfully created using semantic and readable HTML.
