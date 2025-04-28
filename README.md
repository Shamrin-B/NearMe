# Ex04 Places Around Me
## Date: 28.04.2025

## AIM
To develop a website to display details about the places around my house.

## DESIGN STEPS

### STEP 1
Create a Django admin interface.

### STEP 2
Download your city map from Google.

### STEP 3
Using ```<map>``` tag name the map.

### STEP 4
Create clickable regions in the image using ```<area>``` tag.

### STEP 5
Write HTML programs for all the regions identified.

### STEP 6
Execute the programs and publish them.

## CODE
```
MAP.HTML

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My city</title>
</head>
<body>
    <h1 align="center">
    <font color="black"><b>KALLAKURICHI</b></font>
    </h1>
    <h1 align="center">
     <font color="pink"><b>Shamrin.B</b></font>   
    </h1>  
    <center>
    <img src="map.png"  usemap="#Mycity" height="610" width="1450">
    <map name="Mycity">
    <area shape="circle"   coords="800,90,90" href="akt.html" title="A.K.T School">
    <area shape="circle"    coords="64,350,16" href="muttal.html" title="muttal">
    <area shape="circle"    coords="1150,150,47" href="forest.html" title="home">
    <area shape="circle"    coords="183,45,45"   href="v.html"      title="kalvarayan hill"
    </map>
    </center>  
</body>
</html>

MUTTAL.HTML

<head>
    <title>My Home Town</title>  
  </head>
  <body bgcolor="cyan">
    <h1 align="center"><html>

      <font color="red"><b>MUTTAL</b></font>
    </h1>  
    <h3 align="center">
      <font color="black"><b>KALLAKURICHI</b></font>
    </h3>
    
    <hr size="3" color="red">
    <center>
        <img src="image.png" height="200" width="200"
    </center>
    <p align="justify">
      <font face="Georgia" size="5">
        Muttal is a serene eco-tourism spot nestled amidst the Kalvarayan Hills. It features the picturesque Aaniavari Waterfalls and a tranquil lake where visitors can enjoy boating. 
        The park, developed by the Forest Department, also offers amenities like guest rooms and plans to introduce adventure activities such as kayaking and ziplining.
         It's a perfect destination for nature lovers and families looking for a peaceful retreat.

    </p>
  </body>
</html>

AKT.HTML

<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My School</title>
</head>
<body bgcolor="pink">
   <h1 align="center">
    <font color="black"><b>Neelamangalam</b></font>
   </h1> 
   <h2 align="center">
    <font><b>A.K.T School</b></font>
    </h2>
    <hr size="3" color="red">
    <center>
        <img src="akt.jpg" height="300" width="300">
    </center>
      <p align="justify">
        <font face="Georgia" size="5">
            A.K.T School is one of the best and most well-known schools in my district. It is recognized for its high standard of education and quality teaching.
            The best part of my life was my school life—it gave me unforgettable and precious moments filled with happiness.
       </font></p>     
</body>
</html>


V.HTML

<head>
    <title>My Home Town</title>  
  </head>
  <body bgcolor="yellow">
    <h1 align="center"><html>
  
      <font color="red"><b>Kalvarayan hills</b></font>
    </h1>  
    <h3 align="center">
      <font color="black"><b>KALLAKURICHI</b></font>
    </h3>
    
    <hr size="3" color="red">
    <center>
        <img src="=o.png" height="200" width="200"
    </center>
    <p align="justify">
      <font face="Georgia" size="5">
        The Kalvarayan Hills, part of Tamil Nadu's Eastern Ghats, are known for their scenic beauty, dense forests, and rich tribal culture.
         Spanning Kallakurichi and Salem districts, they rise up to 1,200 meters and are home to rivers, waterfalls like Periyar Falls, and diverse wildlife
         . The hills offer a peaceful climate and are important for biodiversity, making them a hidden gem for nature lovers and trekkers.
    </p>
  </body>
  </html>
  

  FOREST.HTML

<head>
      <title>My Home Town</title>  
    </head>
    <body bgcolor="lightblue">
      <h1 align="center"><html>

        <font color="red"><b>KALLAKURICHI</b></font>
      </h1>  
      <h3 align="center">
        <font color="black"><b>THIYAGADURGAM-My Home Town</b></font>
      </h3>
      
      <hr size="3" color="red">
      <p align="justify">
        <font face="Georgia" size="5">
             My favourite place is my home town.It is the place filled with happiness.I like my home very much.
             My hometown has a mountain with a historical background.

      </p>
    </body>
</html>

```
## OUTPUT

sham/mapapp/static/Screenshot 2025-04-28 214449.png

sham/mapapp/static/Screenshot 2025-04-28 214523 copy.png

sham/mapapp/static/Screenshot 2025-04-28 214540.png

sham/mapapp/static/Screenshot 2025-04-28 214623.png

sham/mapapp/static/Screenshot 2025-04-28 214757.png


## RESULT
The program for implementing image maps using HTML is executed successfully.
