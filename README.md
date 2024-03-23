# Ex04 Places Around Me
## Date: 22-03-2024

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
map.html
```
<html>
    <head>
        <title>CHENNAI</title>
    </head>
    <body bgcolor="lightblue">
        <h1> CHENNAI CITY</h1>
        <h3>Name: MOHAMMED PARVEZ S</h3>
        <h3>Reg no:212223040113</h3>
        <img src="map.png" usemap="#image-map">

<map name="image-map">
    <area target="" alt="The Madras Medical Hospital" title="The Madras Medical Hospital" href="mmm.html" coords="624,395,73" shape="circle">
    <area target="" alt="Apollo Hospital Chennai" title="Apollo Hospital Chennai" href="apollo.html" coords="1102,562,90" shape="circle">
    <area target="" alt="Marina Beach" title="Marina Beach" href="marina.html" coords="1329,663,66" shape="circle">
    <area target="" alt="Kapaleeshwarar Temple" title="Kapaleeshwarar Temple" href="temple.html" coords="1230,774,65" shape="circle">
    <area target="" alt="Fort St George Museum" title="Fort St George Museum" href="museum.html" coords="1364,419,92" shape="circle">
</map>
    </body>
</html>
```
temple.html
```
<html>
    <head>
        <title>My City</title>
    </head
    <body bgcolor="grey">
        <h1 align="center">
        <font color="gold"><b>CHENNAI</b></font>
        </h1>
        <h3 align="center">
        <font color="red"><b>Kapaleeshwarar Temple</b></font>
        </h3>
        <hr size="3" color="black">
        <p align="justify">
        <font face="Georgia" size="5">
            The Kapaleeshwarar Temple is a Hindu temple dedicated to the god Shiva located in Mylapore, Chennai in the Indian state of Tamil Nadu. The temple was built ..
           





        </font>
        </p>
    </body>
</html>
```
marina.html
```
<html>
    <head>
        <title>My City</title>
    </head>
    <body bgcolor="lightgreen">
        <h1 align="center">
        <font color="black"><b>CHENNAI</b></font>
        </h1>
        <h3 align="center">
        <font color="maroon"><b>marina Beach</b></font>
        </h3>
        <hr size="3" color="black">
        <p align="justify">
        <font face="Georgia" size="5">
            Marina Beach, or simply the Marina, is a natural urban beach in Chennai, Tamil Nadu, India, along the Bay of Bengal. The beach runs from near Fort St.





        </font>
        </p>
    </body>
</html>
```
museum.html
```<html>
    <head>
        <title>My City</title>
    </head>
    <body bgcolor="yellow">
        <h1 align="center">
        <font color="black"><b>CHENNAI</b></font>
        </h1>
        <h3 align="center">
        <font color="red"><b>Fort St George Museum</b></font>
        </h3>
        <hr size="3" color="black">
        <p align="justify">
        <font face="Georgia" size="5">
            Fort St. George is a fortress at the coastal city of Chennai, India. Founded in 1639, it was the first English fortress in India.
           





        </font>
        </p>
    </body>
</html>
```
apollo.html
```
<html>
    <head>
        <title>My City</title>
    </head>
    <body bgcolor="pink ">
        <h1 align="center">
        <font color="black"><b>CHENNAI</b></font>
        </h1>
        <h3 align="center">
        <font color="red"><b>Apollo Hospital Chennai</b></font>
        </h3>
        <hr size="3" color="black">
        <p align="justify">
        <font face="Georgia" size="5">
            Apollo Hospitals, Greams Road Chennai, the flagship hospital of the Apollo Group was established in 1983. Revolutionizing the healthcare sector, the hospital ...
           





        </font>
        </p>
    </body>
</html>
```
mmm.html
```
<html>
    <head>
        <title>My City</title>
    </head>
    <body bgcolor="lightblue">
        <h1 align="center">
        <font color="black"><b>CHENNAI</b></font>
        </h1>
        <h3 align="center">
        <font color="red"><b>The Madras Medical Hospital</b></font>
        </h3>
        <hr size="3" color="red">
        <p align="justify">
        <font face="Georgia" size="5">
            We Are MMM Hospital India's leading speciality hospital. ... The Madras Medical Mission is an organization inspired by the missionary zeal of Bishop Zachariah Mar ...
           





        </font>
        </p>
    </body>
</html>
```


## OUTPUT

![alt text](<Screenshot 2024-03-23 093659.png>) ![alt text](<Screenshot 2024-03-23 093711.png>) ![alt text](<Screenshot 2024-03-23 093722.png>) ![alt text](<Screenshot 2024-03-23 093732.png>) ![alt text](<Screenshot 2024-03-23 093747.png>) ![alt text](<Screenshot 2024-03-23 093816.png>)





## RESULT
The program for implementing image maps using HTML is executed successfully.
