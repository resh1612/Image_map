# Ex04 Places Around Me
# Date:2.12.2024
# AIM
To develop a website to display details about the places around my house.

# DESIGN STEPS
## STEP 1
Create a Django admin interface.

## STEP 2
Download your city map from Google.

## STEP 3
Using <map> tag name the map.

## STEP 4
Create clickable regions in the image using <area> tag.

## STEP 5
Write HTML programs for all the regions identified.

## STEP 6
Execute the programs and publish them.

# CODE
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Germany States Map</title>
    <style>
        
        img { 
            height: 319px;
            width: 314px; 
            border: 2px solid rgb(22, 20, 20); 
        }


        body {
            text-align: center;
            font-family: Arial, sans-serif;
            background-image: url(germanybg.jpg);

        }

        
        h1 {
            font-size: 24px;
            margin-top: 20px;
        }
    </style>
</head>
<body>

    <h1>TOP TOURISTS SPOTS IN STATES OF GERMANY</h1>
    
    <!-- Image Map -->
    <img src="germany.jpg" usemap="#image-map" alt="Map of Germany">

    <!-- Image Map Generated by http://www.image-map.net/ -->
    <map name="image-map">
        <!-- Bavaria (Bayern) -->
        <area target="_blank" alt="Bayern" title="Bayern" href="i-map.html" coords="232,219,168,292" shape="rect">
        
        <!-- Saarland -->
        <area target="_blank" alt="Saarland" title="Saarland" href="i-map3.html" coords="86,225,25" shape="circle">
        
        <!-- Saxony (Sachsen) -->
        <area target="_blank" alt="Sachsen" title="Sachsen" href="i-map5.html" coords="186,203,239,142" shape="rect">
        
        <!-- Baden-Württemberg -->
        <area target="_blank" alt="Baden" title="Baden" href="i-map2.html" coords="85,300,140,255" shape="rect">
    </map>

</body>
</html>

<!DOCTYPE html>
<html>
<head>
    <title>BAYERN</title>
    <h1>BAYERN</h1>
  <style>
    body{ 
        background-color: beige;
    }
    h1{
        font-size: 80px;
        color: #131212;
        text-align: center;
    }
    
    
    .bayern {
      display: flex;
      align-items: center;
      justify-content: space-around; /* Added space-between */
    }
    
    .bayern img {
      width: 100%; /* Changed to 100% */
      height: 500px; /* Same height */
      object-fit: cover;
      border-radius: 10px;
      box-shadow: 0 0 10px rgba(0, 0, 0, 0.2);
    }
    
    .img-box {
      width: 30%; /* Adjusted width */
      height: auto; 
      text-align: center;
      margin: 20px; /* Increased margin */
    }
    
    .img-box p {
      font-size: 30px;
      padding: 10px;
      color: #131212; 
    }
  </style>
</head>
<body>
  <div class="bayern">
    <div class="img-box">
      <img src="bayern1.jpg">
      <p>BMW Museum</p>
    </div>
    <div class="img-box">
      <img src="bayren2.jpg">
      <p>Neuschwanstein Castle</p>
    </div>
    <div class="img-box">
      <img src="bayern3.jpg">
      <p>Olympiapark München</p>
    </div>
  </div>
</body>
</html>

<!DOCTYPE html>
<html>
<head>
    <title>Saarland</title>
    <h1>SAARLAND</h1>
  <style>
    body{ 
        background-color: beige;
    }
    h1{
        font-size: 80px;
        color: #131212;
        text-align: center;
    }
    
    
    .bayern {
      display: flex;
      align-items: center;
      justify-content: space-around; /* Added space-between */
    }
    
    .bayern img {
      width: 100%; /* Changed to 100% */
      height: 500px; /* Same height */
      object-fit: cover;
      border-radius: 10px;
      box-shadow: 0 0 10px rgba(0, 0, 0, 0.2);
    }
    
    .img-box {
      width: 30%; /* Adjusted width */
      height: auto; 
      text-align: center;
      margin: 20px; /* Increased margin */
    }
    
    .img-box p {
      font-size: 30px;
      padding: 10px;
      color: #131212; 
    }
  </style>
</head>
<body>
  <div class="bayern">
    <div class="img-box">
      <img src="saaarland1.jpg">
      <p>Saarpolygon</p>
    </div>
    <div class="img-box">
      <img src="saarland2.jpg">
      <p>Saarbrücken</p>
    </div>
    <div class="img-box">
      <img src="saarland3.jpg">
      <p>Saar Historical Museum</p>
    </div>
  </div>
</body>
</html>

<!DOCTYPE html>
<html>
<head>
    <title>Sachsen</title>
    <h1>SACHSEN</h1>
  <style>
    body{ 
        background-color: beige;
    }
    h1{
        font-size: 80px;
        color: #131212;
        text-align: center;
    }
    
    
    .bayern {
      display: flex;
      align-items: center;
      justify-content: space-around; /* Added space-between */
    }
    
    .bayern img {
      width: 100%; /* Changed to 100% */
      height: 500px; /* Same height */
      object-fit: cover;
      border-radius: 10px;
      box-shadow: 0 0 10px rgba(0, 0, 0, 0.2);
    }
    
    .img-box {
      width: 30%; /* Adjusted width */
      height: auto; 
      text-align: center;
      margin: 20px; /* Increased margin */
    }
    
    .img-box p {
      font-size: 30px;
      padding: 10px;
      color: #131212; 
    }
  </style>
</head>
<body>
  <div class="bayern">
    <div class="img-box">
      <img src="sachsen1.jpg">
      <p> Zwinger Palace</p>
    </div>
    <div class="img-box">
      <img src="sachsen.jpg">
      <p> Moritzburg Castle</p>
    </div>
    <div class="img-box">
      <img src="sachsen3.jpg">
      <p> Pillnitz Palace and Gardens</p>
    </div>
  </div>
</body>
</html>

<!DOCTYPE html>
<html>
<head>
    <title>Baden-Württemberg</title>
    <h1>BADEN-WURTTEMBERG</h1>
  <style>
    body{ 
        background-color: beige;
    }
    h1{
        font-size: 80px;
        color: #131212;
        text-align: center;
    }
    
    
    .bayern {
      display: flex;
      align-items: center;
      justify-content: space-around; /* Added space-between */
    }
    
    .bayern img {
      width: 100%; /* Changed to 100% */
      height: 500px; /* Same height */
      object-fit: cover;
      border-radius: 10px;
      box-shadow: 0 0 10px rgba(0, 0, 0, 0.2);
    }
    
    .img-box {
      width: 30%; /* Adjusted width */
      height: auto; 
      text-align: center;
      margin: 20px; /* Increased margin */
    }
    
    .img-box p {
      font-size: 30px;
      padding: 10px;
      color: #131212; 
    }
  </style>
</head>
<body>
  <div class="bayern">
    <div class="img-box">
      <img src="baden1.jpg">
      <p>Freiburg Cathedral</p>
    </div>
    <div class="img-box">
      <img src="bayern2.jpg">
      <p>Europa-Park</p>
    </div>
    <div class="img-box">
      <img src="baden3.jpg">
      <p>Sigmaringen Castle</p>
    </div>
  </div>
</body>
</html>


# OUTPUT
![image](https://github.com/user-attachments/assets/46acea64-d65d-4312-b230-b8d857427f10)
![WhatsApp Image 2024-12-06 at 23 25 16_400c8156](https://github.com/user-attachments/assets/9a1e45f2-15c4-4bbb-80de-a3754ff7e151)
![image](https://github.com/user-attachments/assets/9f1b4bea-b6af-4c5d-9208-cf53ff7d9a28)
![WhatsApp Image 2024-12-06 at 23 25 47_1e5704e1](https://github.com/user-attachments/assets/7a17099d-7733-4142-8cad-ca02a8c26c30)
![image](https://github.com/user-attachments/assets/c118349e-11e4-480a-9637-6ef4074580c0)
![WhatsApp Image 2024-12-06 at 23 28 27_5d9155ef](https://github.com/user-attachments/assets/f205946d-350f-48a8-87c3-6d0105642576)
![image](https://github.com/user-attachments/assets/5f357192-896e-4c29-aebd-37a26cf3f74e)
![WhatsApp Image 2024-12-06 at 23 26 19_4943fcf3](https://github.com/user-attachments/assets/624ec663-5552-4b39-984e-1a75d2293202)


# RESULT
The program for implementing image maps using HTML is executed successfully.
