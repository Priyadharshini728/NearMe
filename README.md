# Ex04 Places Around Me
## Date: 05-05-2025

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
map.html

<html>
<head>
<title>My City</title>
</head>
<body>
<h1 align="center">
<font color="red"><b>ARAKKONAM</b></font>
</h1>
<h3 align="center">
<font color="blue"><b> PRIYADHARSHINI P (212224040252)</b></font>
</h3>
<center>
    <img src="map.jpg" usemap="#map" width="1391" height="768">

    <map name="map">
      <area shape="rect" coords="410,185,700,305" href="home.html" title="ARAKKONAM JUNCTION">
      <area shape="rect" coords="203,86,393,203" href="busstand.html" title="ARAKKONAM BUS STAND">
      <area shape="rect" coords="-1095,565,1095,585" href="theatre.html" title="SINDHU CINEMAS">
      <area shape="rect" coords="760,700,850,720" href="ins.html" title="INS Rajali Arakkonam">
      <area shape="rect" coords="22,312,135,473" href="office.html" title="Agricultural office">
    </map>
</center>
</body>
</html>



office.html

<html>
<head> 
    <title>My Home Town</title> 
</head> 
    <body bgcolor="pink"> 
    <h1 align="center"> 
    <font color="red"><b>AGRICULTURAL OFFICE </b></font> 
    </h1> 
    <h3 align="center"> 
    <font color="blue"><b>A place in Ranipet</b></font> 
    </h3> 
    <hr size="3" color="red"> 
    <p align="justify"> 
    <font face="Georgia" size="5"> 
        The federal department that administers programs that provide services to farmers (including research and soil conservation and efforts to stabilize the farming economy); created in 1862.

    </p> 
    </body> 
</html>


busstand.html

<html>
<head> 
    <title>My Home Town</title> 
</head> 
    <body bgcolor="pink"> 
    <h1 align="center"> 
    <font color="red"><b>ARAKKONAM BUS STAND </b></font> 
    </h1> 
    <h3 align="center"> 
    <font color="blue"><b>A place in Ranipet</b></font> 
    </h3> 
    <hr size="3" color="red"> 
    <p align="justify"> 
    <font face="Georgia" size="5"> 
        Arakkonam Bus Stand is a key transportation hub located in Arakkonam, Ranipet district, Tamil Nadu. Classified as a Grade B bus stand, it features 29 bus bays, facilitating efficient boarding and alighting for passengers.
    </p> 
    </body> 
</html>


home.html

<html>
<head> 
    <title>My Home Town</title> 
</head> 
    <body bgcolor="pink"> 
    <h1 align="center"> 
    <font color="red"><b>ARAKKONAM JUNCTION</b></font> 
    </h1> 
    <h3 align="center"> 
    <font color="blue"><b>A place in Ranipet</b></font> 
    </h3> 
    <hr size="3" color="red"> 
    <p align="justify"> 
    <font face="Georgia" size="5"> 
        It is one of the oldest railway stations in India, located on the first railway line in South India. It is located on the Guntakal–Chennai Egmore section of Mumbai–Chennai 


    </p> 
    </body> 
</html>


theatre.html

<html>
<head> 
    <title>My Home Town</title> 
</head> 
    <body bgcolor="pink"> 
    <h1 align="center"> 
    <font color="red"><b>SINDHU theatre </b></font> 
    </h1> 
    <h3 align="center"> 
    <font color="blue"><b>A place in Ranipet</b></font> 
    </h3> 
    <hr size="3" color="red"> 
    <p align="justify"> 
    <font face="Georgia" size="5"> 
        Sindhu Cinemas is a popular movie theatre located in Arakkonam, Tamil Nadu. Situated on SH 126 in Arakkonam North, it offers a comfortable viewing experience with modern amenities. The theatre screens a variety of films, primarily in Tamil, and features 2D formats. Ticket prices range from ₹100 for Executive seats to ₹150 for Box seats. 
    </p> 
    </body> 
</html>


ins.html

<html>
<head> 
    <title>My Home Town</title> 
</head> 
    <body bgcolor="pink"> 
    <h1 align="center"> 
    <font color="red"><b>INS Rajali </b></font> 
    </h1> 
    <h3 align="center"> 
    <font color="blue"><b>A place in Ranipet</b></font> 
    </h3> 
    <hr size="3" color="red"> 
    <p align="justify"> 
    <font face="Georgia" size="5"> 
        INS Rajali, also known as Arakkonam Naval Air Station, is an Indian Naval Air Station located near Arakkonam in Tamil Nadu, India. It's the fifth Naval Air Station of the Indian Navy, commissioned on March 11, 1992. The station is known for its long runway, which is the longest military runway in Asia
    </p> 
    </body> 
</html>


```


## OUTPUT

![alt text](<Screenshot 2025-05-05 225240.png>)

![alt text](<Screenshot 2025-05-05 225658.png>)

![alt text](<Screenshot 2025-05-05 225731.png>)

![alt text](<Screenshot 2025-05-05 225745.png>)

![alt text](<Screenshot 2025-05-05 225808.png>)

![alt text](<Screenshot 2025-05-05 225830.png>)




## RESULT
The program for implementing image maps using HTML is executed successfully.
