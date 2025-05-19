# Ex09 Event Registration Web Application
## Date:17/05/2025

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

```
Home Code 

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Celanza 2025 - Login</title>
  <style>
    body {
      margin: 0;
      padding: 0;
      font-family: Arial, sans-serif;
      background: linear-gradient(to bottom, #000000, #a7c0dc);
      height: 100vh;
      display: flex;
      justify-content: center;
      align-items: center;
      flex-direction: column;
      overflow: hidden;
    }

    .header {
      position: absolute;
      top: 0;
      width: 100%;
      background: #000000;
      color: white;
      padding: 10px 0;
      text-align: center;
    }

    .header img {
      height: 50px;
      vertical-align: middle;
    }

    .circle {
      position: absolute;
      top: 60px;
      width: 100%;
      height: 500px;
      background: radial-gradient(circle, #a45deb, #000000 60%);
      border-radius: 50%;
      transform: translateY(-40%);
      z-index: -1;
    }

    .buttons {
      margin-top: 300px;
      display: flex;
      flex-direction: column;
      gap: 20px;
    }

    .buttons button {
      padding: 12px 20px;
      border: none;
      cursor: pointer;
      background: #fff;
      color: #000;
      font-weight: bold;
      transition: transform 0.3s ease;
    }

    .buttons button:hover {
      transform: scale(1.1);
    }

    .ribbon {
      display: inline-block;
      padding: 12px 20px;
      background: white;
      color: black;
      clip-path: polygon(0 50%, 10% 0, 90% 0, 100% 50%, 90% 100%, 10% 100%);
      font-weight: bold;
      cursor: pointer;
    }

    .ribbon:hover {
      background: #eee;
    }
  </style>
</head>
<body>
  <div class="header">
    <img src="https://saveetha.ac.in/images/sec_logo.png" alt="Saveetha Logo" />
    <h2>CELANZA 2025</h2>
  </div>

  <div class="circle"></div>

  <div class="buttons">
    <button>LOGIN FORM</button>
    <div class="ribbon">REGISTER FORM</div>
  </div>
</body>
</html>

page 2

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Celanza School 24</title>
  <style>
    body {
      margin: 0;
      font-family: 'Segoe UI', sans-serif;
      background: linear-gradient(to bottom, #f72585, #7209b7);
      color: white;
    }

    .container {
      padding: 20px;
      max-width: 480px;
      margin: auto;
    }

    .header {
      text-align: center;
      background: #3a0ca3;
      padding: 20px;
      border-radius: 10px;
    }

    .header h1 {
      font-size: 2.5em;
      color: yellow;
      margin: 0;
    }

    .header h2 {
      font-size: 1.5em;
      margin: 0;
      color: white;
    }

    .event-info {
      display: flex;
      justify-content: space-around;
      background: white;
      color: black;
      border-radius: 10px;
      margin: 20px 0;
      padding: 10px;
      font-size: 0.9em;
    }

    .event-item {
      text-align: center;
    }

    .event-list {
      background: rgba(0, 0, 0, 0.2);
      border-radius: 10px;
      padding: 20px;
    }

    .event-list h3 {
      margin-top: 0;
      color: #ffd60a;
    }

    .event {
      background: #fff;
      color: #000;
      padding: 10px;
      margin: 10px 0;
      border-radius: 5px;
      font-weight: bold;
    }

    .footer {
      margin-top: 20px;
      background: yellow;
      color: #000;
      text-align: center;
      font-weight: bold;
      padding: 10px;
      border-radius: 10px;
    }
  </style>
</head>
<body>
  <div class="container">
    <div class="header">
      <h2>Saveetha Engineering College</h2>
      <p><strong>Affiliated to Anna University | Autonomous</strong></p>
      <h1>CELENZA</h1>
      <h2>School 24</h2>
    </div>

    <div class="event-info">
      <div class="event-item">
        <p><strong>📅</strong><br>17th Feb 2024</p>
      </div>
      <div class="event-item">
        <p><strong>⏰</strong><br>09:00 AM - 05:00 PM</p>
      </div>
      <div class="event-item">
        <p><strong>📍</strong><br>Nalli Arangam, SEC</p>
      </div>
    </div>

    <div class="event-list">
      <h3>Events:</h3>
      <div class="event">Solo Singing</div>
      <div class="event">Group Singing</div>
      <div class="event">Solo Dance</div>
      <div class="event">Group Dance</div>
      <div class="event">Debate (English & Tamil) - "Youth of India - Challenges and Expectations"</div>
      <div class="event">Painting Competition - Topic: AI Technologies</div>
      <div class="event">Short Film - Max 3 Min. (Any Topic, Non-Political)</div>
    </div>

    <div class="footer">
      LAKH WORTH CASH PRIZE
    </div>
  </div>
</body>
</html>

page 3

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Celanza 2025 Registration</title>
  <style>
    body {
      margin: 0;
      padding: 0;
      font-family: 'Segoe UI', sans-serif;
      background: url('https://i.imgur.com/Oie2mhA.jpg') no-repeat center center fixed;
      background-size: cover;
      color: white;
    }

    .header {
      background: rgba(0, 0, 0, 0.8);
      padding: 20px;
      text-align: center;
    }

    .header img {
      height: 40px;
      margin-right: 10px;
      vertical-align: middle;
    }

    .header h2 {
      display: inline;
      font-size: 1.5em;
      color: yellow;
    }

    .form-container {
      margin: 20px;
      background: rgba(0, 0, 0, 0.6);
      padding: 20px;
      border-radius: 10px;
    }

    .form-container input,
    .form-container select,
    .form-container button {
      width: 100%;
      padding: 12px;
      margin: 10px 0;
      border: none;
      border-radius: 5px;
      font-size: 1em;
    }

    .form-container input::placeholder {
      text-transform: uppercase;
    }

    .form-container button {
      background: white;
      color: black;
      font-weight: bold;
      cursor: pointer;
    }

    .form-container button:hover {
      background: #ddd;
    }
  </style>
</head>
<body>
  <div class="header">
    <img src="https://saveetha.ac.in/images/sec_logo.png" alt="Saveetha Logo" />
    <h2>CELANZA 2025</h2>
  </div>

  <div class="form-container">
    <form>
      <input type="text" placeholder="Enter your full name" required />
      <input type="text" placeholder="Register Number" required />
      <input type="text" placeholder="Your Gender" required />
      <input type="number" placeholder="Enter your age" required />
      <select required>
        <option value="">Select the event</option>
        <option value="solo_singing">Solo Singing</option>
        <option value="group_singing">Group Singing</option>
        <option value="solo_dance">Solo Dance</option>
        <option value="group_dance">Group Dance</option>
        <option value="debate">Debate (English/Tamil)</option>
        <option value="painting">Painting Competition</option>
        <option value="short_film">Short Film</option>
      </select>
      <button type="submit">CONFIRM</button>
    </form>
  </div>
</body>
</html>

page 4


<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Celanza 2025 - Thank You</title>
  <style>
    body {
      margin: 0;
      padding: 0;
      font-family: 'Segoe UI', sans-serif;
      background: black;
      background-image: url('https://i.imgur.com/UXD3Zn8.png'); /* Replace with actual hosted thank you background */
      background-size: cover;
      background-repeat: no-repeat;
      background-position: center;
      color: white;
      height: 100vh;
      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: center;
      text-align: center;
    }

    .header {
      position: absolute;
      top: 0;
      width: 100%;
      background: rgba(0, 0, 0, 0.8);
      padding: 20px 0;
      text-align: center;
    }

    .header img {
      height: 40px;
      vertical-align: middle;
    }

    .header h2 {
      display: inline;
      font-size: 1.5em;
      color: yellow;
      margin-left: 10px;
    }

    .thankyou {
      font-size: 3em;
      font-weight: bold;
    }

    .thankyou span {
      color: yellow;
    }
  </style>
</head>
<body>
  <div class="header">
    <img src="https://saveetha.ac.in/images/sec_logo.png" alt="Saveetha Logo" />
    <h2>CELANZA 2025</h2>
  </div>
  <div class="thankyou">
    Thank <span>You</span>
  </div>
</body>
</html>


```

## OUTPUT:

![alt text](<Screenshot 2025-05-19 100913.png>)

## RESULT:
The program to design, develop and deploy a web application for event registration is completed successfully.
