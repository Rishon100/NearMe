# Ex04 Places Around Me
## Date: 23/11/2024

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
       <title> My City </title>
   </head>
    <body>
      <h1 align="center">
        <font color="black"> <b> V RISHON ANAND (24900460) </b> </font>
      </h1>
      <center>
      <img src="map7.png" usemap="#MyCity" >
      <map name="MyCity">
        <area target="" alt="Velachery" title="Velachery" href="velachery.html" coords="482,90,688,185" shape="rect">
    <area target="" alt="Holiday Inn" title="Holiday Inn" href="holidayinn.html" coords="1108,59,96" shape="circle">
    <area target="" alt="Ram Nagar" title="Ram Nagar" href="ramnagar.html" coords="493,213,399,148,369,293,467,298" shape="poly">
    <area target="" alt="Kaiveli" title="Kaiveli" href="kaiveli.html" coords="483,293,530,258,607,281,597,331,571,383,522,411,468,429,430,382,445,334" shape="poly">
    <area target="" alt="The Chennai Silks" title="The Chennai Silks" href="chennai_silks.html" coords="513,188,676,261" shape="rect">
    </map>      
    </body>
</html>
 
 chennai_silks.html

 <!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body bgcolor="red">
    <h1 align="center">The Chennai Skils</h1>
    <p>Its founder Thiru. A. Kulandaivel Mudaliar, who was living in a village near Avinashi, entered the business in 1962. However its first textile shop was started in Tirupur in 1991 as "Kumaran Silks" later renamed as "The Chennai Silks" in 2001.</p>
</body>
</html>

holidayinn.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body bgcolor="purple">
    <h1 align="center">Holiday Inn</h1>
    <p>Holiday Inn is the preferred choice for business travelers to Chennai. Major IT Parks like RMZ, SP infocity , World trade center, DLF downtown, TIDEL Park, Ramanujan IT City and Ascendas IT Park are all within a 10-minute drive from the hotel. Additionally, key tourist attractions in Chennai, such as Chennai Lighthouse (9.8 km) and Guindy National Park (7.8 km), are easily accessible. Chennai's popular Marina Beach (11.3 km) and Akkarai Beach (10.6 km) are also conveniently located nearby.</p>
</body>
</html>

kaiveli.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body bgcolor="pink">
    <h1 align="center">Kaiveli</h1>
    <p>Pincode of KAIVELI VELACHERYTAMBARAM MAIN ROAD VELACHERI VELACHERY MAMBALAM GUINDY CHENNAI TAMIL NADU 600042 Pincode.net.in.</p>
</body>
</html>

ramnagar.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body bgcolor="blue">
    <h1 align="center">Ram Nagar</h1>
    <p>Ram Nagar North Extension is an neighbourhood in Alaiamman Nagar, Madipakkam, Chennai south, Chennai, Chennai District, Tamil Nadu, India.

        Madipakkam (0.0 Km), Adambakkam (2.88 Km), Keelakattalai (2.95 Km), Velachery (3.15 Km), Nanganallur (3.61 Km) are the nearby areas to Ram Nagar North Extension.
        
        Sri Ambal Nagar, Chittibabu Nagar, Thirusulam, Nemilicherry, Chennai, Meenambakkam, Meenampakkam are the nearby cities to Ram Nagar North Extension.</p>
</body>
</html>

velachery.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body bgcolor="cyan">
    <h1 align="center">Velachery</h1>
    <p>Velachery is a neighborhood of Chennai. It is located in the southern part of the Chennai city sharing borders with Guindy in the north, Taramani in the east, Perungudi in the south-east, Pallikaranai in the south, Madipakkam in south-west, Adambakkam in the west and north-west. It is the headquarters of Velachery taluk and straddles the boundary between Chennai and Kancheepuram districts.</p>
</body>
</html>


```

## OUTPUT
![alt text](<Screenshot 2024-11-23 190956.png>)
![alt text](<Screenshot 2024-11-23 150443.png>)
![alt text](<Screenshot 2024-11-23 150458.png>)
![alt text](<Screenshot 2024-11-23 150606.png>)
![alt text](<Screenshot 2024-11-23 150627.png>)
![alt text](<Screenshot 2024-11-23 150654.png>)

## RESULT
The program for implementing image maps using HTML is executed successfully.
