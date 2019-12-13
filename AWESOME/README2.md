<!DOCTYPE html>
<html lang="en">
<head>
  <title>CONTACT</title>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0/css/bootstrap.min.css" integrity="sha384-Gn5384xqQ1aoWXA+058RXPxPg6fy4IWvTNh0E263XmFcJlSAwiGgFAW/dAiS6JXm" crossorigin="anonymous">
</head>
  
  
  <style>
    /* Remove the navbar's default margin-bottom and rounded borders */ 
    .navbar {
      margin-bottom: 0;
      border-radius: 0;
    }
    
    /* Set height of the grid so .sidenav can be 100% (adjust as needed) */
    .row.content {height: 450px}
    
    /* Set gray background color and 100% height */
    .sidenav {
      padding-top: 20px;
      background-color: #f1f1f1;
      height: 100%;
    }
    
    /* Set black background color, white text and some padding */
    footer {
      background-color: #555;
      color: white;
      padding: auto;
      text-align: auto;
    color: #eeeeee;
    border-top: 1px solid red;
    height: 80px;  /* footer height */
    padding-top: 20px;
    display: block;
    margin-top: 20px; /* space between content and footer */
    box-sizing: border-box;
    position: relative;
    width: 100%;
    }
   
    
    /* On small screens, set height to 'auto' for sidenav and grid */
    @media screen and (max-width: 767px) {
      .sidenav {
        height: auto;
        padding: 15px;
      }
      .row.content {height:auto;}  
    }
body {font-family: Arial, Helvetica, sans-serif;}
* {box-sizing: border-box;}

input[type=text], select, textarea {
  width: 100%;
  padding: 12px;
  border: 1px solid #ccc;
  border-radius: 4px;
  box-sizing: border-box;
  margin-top: 6px;
  margin-bottom: 16px;
  resize: vertical;
}

input[type=submit] {
  background-color: #4CAF50;
  color: white;
  padding: 12px 20px;
  border: none;
  border-radius: 4px;
  cursor: pointer;
}

input[type=submit]:hover {
  background-color: #45a049;
}

.container {
  border-radius: 5px;
  background-color: #f2f2f2;
  padding: 20px;
}
  </style>
</head>
<body>

  <nav class="navbar navbar-expand-lg navbar-light bg-dark">
    <ul class=navbar-nav>
        <li class="nav-item active">
            <p><a href="awesome.html" class=" nav-link text-white bg-dark">Home</a></p>
        </li>
        <li class="nav-item active">
            <p><a href="about.html" class=" nav-link text-white bg-dark">About Us</a></p>
        </li>
        <li class="nav-item active">
            <p><a href="contact.html" class=" nav-link text-white bg-dark">Contact Us</a></p>
        </li>
    </ul>
</nav>
  
<div class="container-fluid text-center">    
  <div class="row content">


<div class="container">
  <form action="/action_page.php">
    <label for="fname">First Name</label>
    <input type="text" id="fname" name="firstname" placeholder="Your name..">

    <label for="lname">Last Name</label>
    <input type="text" id="lname" name="lastname" placeholder="Your last name..">

    <label for="city">city</label>
    <select id="city" name="city">
      <option value="HYDERABAD">HYDERABAD</option>
      <option value="BANGLORE">BANGLORE</option>
      <option value="MUMBAI">MUMBAI</option>
    </select>

    <label for="subject">Subject</label>
    <textarea id="subject" name="subject" placeholder="Write something.." style="height:50px";></textarea>

    <input type="submit" value="Submit">
  </form>
</div>
</hr>
<hr>
<div class="col">
  <img src="map.png" alt="user ceo image" class="border-radius:10px float-center"/>                            
</div>
</hr>
<div>
<footer class="container-fluid text-auto">
  Apple was founded by Steve Jobs, Steve Wozniak, and Ronald Wayne in April 1976 to develop and sell Wozniak's Apple I personal computer.This makes sense only if you are active within that network and have solid editorial standards about what you’re sharing.
    
</footer></div>
<script src="https://code.jquery.com/jquery-3.2.1.slim.min.js" integrity="sha384-KJ3o2DKtIkvYIK3UENzmM7KCkRr/rE9/Qpg6aAZGJwFDMVNA/GpGFF93hXpG5KkN" crossorigin="anonymous"></script>
        <script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.12.9/umd/popper.min.js" integrity="sha384-ApNbgh9B+Y1QKtv3Rn7W3mgPxhU9K/ScQsAP7hUibX39j7fakFPskvXusvfa0b4Q" crossorigin="anonymous"></script>
        <script src="https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0/js/bootstrap.min.js" integrity="sha384-JZR6Spejh4U02d8jOt6vLEHfe/JQGiRRSQQxSfFWpi1MquVdAyjUar5+76PVCmYl" crossorigin="anonymous"></script>
</body>
</html>
