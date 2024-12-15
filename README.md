# Date:25-11-2024
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
    <title>Event Registration</title>
    <link rel="stylesheet" href="event.css">
</head>
<body>
    <!-- Section 1: Registration Form -->
    <div class="container" id="form-section">
        <div class="header">
            <img src="college-logo.png" alt="College Logo" class="logo">
            <span class="code">TNEA CODE 1216</span>
        </div>
        <div class="form-content">
            <div class="circle">id8</div>
            <h2>Welcome to <span>id8 Event</span></h2>
            <p>Create an account with us & enjoy all exciting event</p>
            <form>
                <input type="text" placeholder="Full Name" required>
                <input type="email" placeholder="E-mail" required>
                <div class="flex-inputs">
                    <input type="date" placeholder="Date of Birth">
                    <input type="tel" placeholder="Phone Number">
                </div>
                <input type="text" placeholder="College name" required>
                <p class="terms">By creating your account you can confirm that you accept our <a href="#">Terms of Use & Privacy policy</a></p>
                <button type="submit" class="btn">create Account</button>
            </form>
            <p class="signin">Have an Account? <a href="#">Sign in</a></p>
        </div>
    </div>

    <!-- Section 2: Upcoming Event -->
    <div class="container" id="event-section">
        <div class="event-header">
            <h2>Upcoming Event <span>in October</span></h2>
            <div class="qr-code"><img src="Screenshot (92).png" alt="QR Code"></div>
        </div>
        <div class="event-info">
            <img src="food emojy.jpg" alt="Event Logo">
            <h3>Dhaka Food Festival</h3>
            <button class="btn">View Event</button>
            <p class="small-text">Lot of Events are conducting from our College. Come and <a href="#">join us</a></p>
            <p class="registration">Registration Fee <span>For All : 300</span></p>
        </div>
    </div>

    <!-- Section 3: Food Section -->
    <div class="container" id="food-section">
        <div class="food-content">
            <div class="food-box">
                <img src="food7.jpg" alt="Pancakes">
                <p>Have a taste and <span>enjoy the moment</span> with your friend</p>
            </div>
            <div class="food-box">
                <img src="food3.jpg" alt="Fries">
                <p>You can <span>order the food</span> what you want</p>
            </div>
            <div class="food-box">
                <img src="food2.jpg" alt="Sushi">
                <p>We are providing <span>parcels too!</span></p>
            </div>
        </div>
    </div>
</body>
</html>

#Css
    * {
        margin: 0;
        padding: 0;
        box-sizing: border-box;
        font-family: Arial, sans-serif;
    }
    
    body {
        display: flex;
        justify-content: space-around;
        flex-wrap: wrap;
        background-color: #f8f8f8;
        color: #333;
    }
    .container {
        width: 300px;
        background: #fff;
        border-radius: 12px;
        box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
        padding: 20px;
        margin: 20px;
    }
    
     .header {
        display: flex;
        justify-content: space-between;
        align-items: center;
        margin-bottom: 20px;
    }
    
     .logo {
        height: 50px;
    }
    
     .code {
        font-weight: bold;
        font-size: 12px;
        color: #4a4a4a;
    }
    
    .circle {
        background-color: #e0e0e0;
        color: #555;
        text-align: center;
        border-radius: 50%;
        width: 50px;
        height: 50px;
        line-height: 50px;
        font-weight: bold;
        margin: 0 auto 10px;
    }
    
    h2 span {
        color: orange;
    }
    
    form input,
    form button {
        width: 100%;
        padding: 8px;
        margin: 8px 0;
        border: 1px solid #ccc;
        border-radius: 5px;
    }
    
    .flex-inputs {
        display: flex;
        gap: 10px;
    }
    
    .terms {
        font-size: 12px;
        color: #666;
    }
    
    .btn {
        background-color: orange;
        border: none;
        color: white;
        padding: 8px;
        border-radius: 5px;
        cursor: pointer;
    }
    
    .signin {
        text-align: center;
        font-size: 12px;
    }
    
    a {
        color: orange;
        text-decoration: none;
    }
    .event-header h2 {
        font-size: 20px;
        margin-bottom: 10px;
    }
    
    .event-header span {
        color: orange;
    }
    
    .event-info {
        text-align: center;
    }
    
    .event-info img {
        width: 80px;
        margin-bottom: 10px;
    }
    
    .registration {
        font-weight: bold;
        margin-top: 10px;
    }
    
    .qr-code img {
        width: 60px;
        margin-top: 10px;
    }
    
    .small-text {
        font-size: 12px;
    }
    
    /* Section 3 - Food Section */
    .food-content {
        display: flex;
        flex-direction: column;
        gap: 15px;
    }
    
    .food-box {
        text-align: center;
    }
    
    .food-box img {
        width: 100%;
        border-radius: 5px;
        margin-bottom: 5px;
    }
    
    .food-box span {
        color: orange;
        font-weight: bold;
    }

```

# OUTPUT:
![Screenshot (95)](https://github.com/user-attachments/assets/b8efd476-2649-4cb5-aa5f-59248cbd40cf)

# RESULT:
The program to design, develop and deploy a web application for event registration is completed successfully.
