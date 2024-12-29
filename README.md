# Ex09 Event Registration Web Application
## Date:

## AIM:
To design, develop and deploy a web application for event registration.

## DESIGN STEPS:

### Step 1:
Create a new frame.

### Step 2:
Select any one preset size of your choice.

### Step 3:
Select the shapes you need.

### Step 4:
Import images as needed.

### Step 5:
Create pages based on your need and link them.

### Step 6:

Validate the HTML and CSS code.

### Step 6:

Publish the website in the given URL.

## DESIGN TOOL:
Figma

## CODE:

<!DOCTYPE html>

<html lang="en">
  
<head>
    <meta charset="UTF-8">
  
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    
    <title>Saveetha College Event</title>
    
    <style>
    
        body {
        
            margin: 0;
            
            font-family: 'Arial', sans-serif;
            background-color: #1a1a2e;
            color: white;
        }
        .container {
            text-align: center;
            padding: 20px;
            background: url('https://wallpapercave.com/wp/wp5907304.jpg') no-repeat center center/cover;
            height: 100vh;
        }
        .header {
            background-color: #003366;
            padding: 10px;
        }
        .header h1, .header h2 {
            margin: 0;
            color: white;
        }
        .box {
            margin: 40px auto;
            width: 90%;
            max-width: 600px;
            background-color: rgba(0, 0, 0, 0.7);
            padding: 30px;
            border-radius: 10px;
        }
        .box h2 {
            font-size: 28px;
            margin-bottom: 20px;
        }
        .input-box {
            margin: 10px 0;
            display: flex;
            flex-direction: column;
        }
        .input-box label {
            font-size: 18px;
            margin-bottom: 8px;
        }
        .input-box input {
            padding: 10px;
            font-size: 16px;
            border-radius: 5px;
            border: none;
        }
        .btn {
            margin-top: 20px;
            padding: 15px;
            width: 100%;
            font-size: 18px;
            background-color: #4CAF50;
            color: white;
            border: none;
            border-radius: 5px;
            cursor: pointer;
        }
        .btn:hover {
            background-color: #45a049;
        }
        .event-list {
            display: flex;
            justify-content: space-around;
            margin: 20px 0;
        }
        .event-list div {
            padding: 10px 20px;
            border-radius: 5px;
            background-color: #ff5733;
            cursor: pointer;
        }
        .concert {
            margin: 40px 0;
            text-align: center;
        }
        .concert img {
            width: 60%;
            border-radius: 10px;
        }
        .qr-section {
            margin: 40px;
        }
        .rules {
            text-align: left;
            margin-top: 20px;
        }
        .rules ul {
            list-style: none;
            padding: 0;
        }
        .rules li {
            margin: 10px 0;
        }
        .register-btn {
            display: inline-block;
            margin: 20px;
            padding: 15px 30px;
            background-color: #ffcc00;
            color: black;
            font-weight: bold;
            border-radius: 5px;
            text-decoration: none;
        }
    </style>
</head>
<body>
    <div class="container">
        <!-- Screen 1 - Welcome Page -->
        <div class="box">
            <h2>Welcome</h2>
            <div class="input-box">
                <label for="name">Name:</label>
                <input type="text" id="name" placeholder="Enter your name">
            </div>
            <div class="input-box">
                <label for="reg">Rec. No:</label>
                <input type="text" id="reg" placeholder="Enter Registration No.">
            </div>
            <button class="btn">Login</button>
        </div>

        <!-- Screen 2 - Event Types -->
        <div class="box">
            <h2>Event Types</h2>
            <div class="event-list">
                <div>Technical</div>
                <div>Non-Technical</div>
            </div>
            <p>Explore various events ranging from coding, art, and group activities!</p>
        </div>

        <!-- Screen 3 - Concert Section -->
        <div class="concert">
            <h2>Alan Walker's Concert</h2>
            <img src="https://www.edmtunes.com/wp-content/uploads/2020/01/alan-walker-ignite.jpg" alt="Alan Walker Concert">
            <p>Alan's DJ, Singing, Laser Show, and more!</p>
        </div>

        <!-- Screen 4 - QR Code and Rules -->
        <div class="box qr-section">
            <h2>Scan and Register</h2>
            <img src="https://api.qrserver.com/v1/create-qr-code/?size=150x150&data=EventReg" alt="QR Code">
            <a href="#" class="register-btn">REGISTER NOW</a>
            <div class="rules">
                <h3>Rules:</h3>
                <ul>
                    <li>Only formal dress</li>
                    <li>No illegal activities</li>
                    <li>ID Card is a must</li>
                    <li>Maintain discipline</li>
                </ul>
            </div>
        </div>
    </div>
</body>
</html>
## OUTPUT:

![Screenshot 2024-12-29 094653](https://github.com/user-attachments/assets/3ea688b9-2a84-40e1-8130-b6dce3acf73a)



## RESULT:
The program to design, develop and deploy a web application for event registration is completed successfully.
