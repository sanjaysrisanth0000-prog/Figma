# Ex09 Event Registration Web Application
# Date:
# AIM:
To design, develop and deploy a web application for event registration.

# DESIGN STEPS:
## Step 1:
Create a new frame.

## Step 2:
Select any one preset size of your choice.

## Step 3:
Select the shapes you need.

## Step 4:
Import images as needed.

## Step 5:
Create pages based on your need and link them.

## Step 6:
Validate the HTML and CSS code.

## Step 6:
Publish the website in the given URL.

# DESIGN TOOL:
Figma

# CODE:
```
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Hostel Fest - Saveetha Engineering College</title>
</head>
<body>

<!-- Card 1: Login/Register -->
<div class="card fest-section">
    <img src="saveetha_logo.png" alt="Saveetha Logo" class="logo">
    <h3>Hostel Fest</h3>
    <button>Login</button><br>
    <button>Register</button>
</div>

<!-- Card 2: Events List -->
<div class="card fest-section">
    <h3>Fest Events</h3>
    <ul>
        <li>Volley Ball</li>
        <li>Basket Ball</li>
        <li>Throw Ball</li>
        <li>Badminton</li>
        <li>Foot Ball</li>
    </ul>
</div>

<!-- Card 3: Registration Form -->
<div class="card form-section" style="background:url('3.jpg') no-repeat center/cover;
    <h3>Event Registration Form</h3> color:white;">
    <input type="text" placeholder="Name">
    <input type="number" placeholder="Age">
    <input type="text" placeholder="Gender">
    <input type="text" placeholder="Reg.No">
    <button>Events to Register</button><br>
    <button style="background:red;">REGISTER</button>
</div>

<!-- Card 4: Thank You -->
<div class="card thankyou">
    <img src="logo.png" alt="Saveetha Logo" class="logo">
    <h3>THANK YOU<br>FOR REGISTRATION</h3>
    <p class="contact">Contact us</p>
    <p>sec@gmail.com</p>
    <div class="footer">00000 111111</div>
</div>

</body>
</html>
```
#style.css
```


<style>
    body {
        font-family: 'Poppins', sans-serif;
        background-color: #fff5f5;
        display: flex;
        justify-content: center;
        align-items: flex-start;
        flex-wrap: wrap;
        gap: 30px;
        padding: 20px;
    }

    .card {
        width: 210px;
        background: white;
        border-radius: 10px;
        box-shadow: 0 4px 12px rgba(0,0,0,0.1);
        overflow: hidden;
        text-align: center;
    }

    .card img.logo {
        width: 100%;
        background: #fff;
        padding: 5px;
    }

    h2, h3 {
        color: #004aad;
        margin: 10px 0;
    }

    button {
        background-color: #004aad;
        color: white;
        border: none;
        padding: 8px 20px;
        border-radius: 5px;
        cursor: pointer;
        margin: 5px;
    }

    button:hover {
        background-color: #007bff;
    }

    .fest-section {
        background: linear-gradient(to bottom, #d1ecff, #ffffff);
        padding: 15px;
    }

    .fest-section ul {
        text-align: left;
        padding-left: 25px;
        line-height: 1.8;
        color: #333;
    }

    .form-section input {
        width: 80%;
        margin: 5px auto;
        padding: 7px;
        border: 1px solid #ccc;
        border-radius: 5px;
        display: block;
    }

    .thankyou {
        padding: 20px;
    }

    .thankyou p {
        margin: 5px 0;
    }

    .thankyou .contact {
        color: blue;
        text-decoration: underline;
        cursor: pointer;
    }

    .footer {
        font-size: 13px;
        color: #333;
        margin-top: 10px;
    }



</style>
```
# OUTPUT:
<img width="481" height="765" alt="Screenshot 2025-10-06 233639" src="https://github.com/user-attachments/assets/cbff83ee-9698-4466-a220-208216068504" />
<img width="470" height="776" alt="Screenshot 2025-10-06 233702" src="https://github.com/user-attachments/assets/932a5513-e1aa-418c-bec0-43378b299160" />
<img width="407" height="807" alt="Screenshot 2025-10-06 233718" src="https://github.com/user-attachments/assets/f38b8be0-9d4d-40ac-84c5-500116acfdb9" />
<img width="452" height="796" alt="Screenshot 2025-10-06 233734" src="https://github.com/user-attachments/assets/d080591a-d798-4065-ad8d-5445f9baaa82" />




# RESULT:
The program to design, develop and deploy a web application for event registration is completed successfully.
