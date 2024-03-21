# Ex04 Places Around Me
## Date: 21-03-2024

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
<html>
<head>
    <title>Nagercoil</title>
</head>
<body bgcolor="orange">

    <h1 align="center">Nagercoil</h1>
    <h2 align="center">ROHITH PREM S(212223040172)</h2>
<center>
<img src="map.png" usemap="#image-map">

<map name="image-map">
    <area target="" alt="Hotel Ganga" title="Hotel Ganga" href="ganga.html" coords="1212,519,1413,558" shape="rect">
    <area target="" alt="Pioneer Grand Palace" title="Pioneer Grand Palace" href="pioneer.html" coords="1433,461,1212,416" shape="rect">
    <area target="" alt="Medical College" title="Medical College" href="clg.html" coords="749,554,73" shape="circle">
    <area target="" alt="St Xavier's Catholic College of Engineering" title="St Xavier's Catholic College of Engineering" href="engine.html" coords="686,250,904,355" shape="rect">
    <area target="" alt="Restaurant" title="Restaurant" href="pearl.html" coords="980,503,1155,548" shape="rect">
</center>
</body>
</html>
```
```
ganga.html

<html>
    <head>
        <title>Hotel Ganga</title>
    </head>

    <body bgcolor="cyan">
        <h1 align="center"> <B>NAGERCOIL</B></h1>
        <h2 align="center"><b>Hotel Ganga</b> </h2>

        <hr color="white">

       
        <table align="center" cellspacing="10">
            <tr>
                <td>1.Hotel Ganga is ideally situated in a prime area of Nagercoil,
                     offering easy access to key attractions and transportation hubs in the city.</td>
                
            </tr>
            <tr>
                <td>2.This hotel provides comfortable and well-appointed rooms, 
                    ranging from standard to deluxe suites, ensuring a pleasant stay for guests.</td>
            </tr>

            <tr>
                <td>3.Guests can enjoy a range of facilities and amenities, including complimentary Wi-Fi, air-conditioned rooms,
                    round-the-clock room service, laundry facilities, and complimentary breakfast.</td>
            </tr>
        </table>
    </body>
</html>
```
```
pioneer.html

<html>
    <head>
        <title>Pioneer Grand Palace</title>
    </head>

    <body bgcolor="yellow">
        <h1 align="center"> <B>NAGERCOIL</B></h1>
        <h2 align="center"><b>Pioneer Grand Palace</b> </h2>

        <hr color="white">

       
        <table align="center" cellspacing="10">
            <tr>
                <td>1.Pioneer Grand Palace is strategically located in Nagercoil,
                     offering convenient access to prominent landmarks, shopping centers, and business districts within the city.</td>
                
            </tr>
            <tr>
                <td>2.The hotel features elegantly designed rooms and suites, 
                    furnished with modern amenities and luxurious comforts, catering to the diverse needs of guests.</td>
            </tr>

            <tr>
                <td>3.Guests can relax and enjoy the hotel's fitness center, 
                    swimming pool, and spa facilities for leisure during their stay.</td>
            </tr>
        </table>
    </body>
</html>
```

```
clg.html

<html>
    <head>
        <title> Govt Medical College</title>
    </head>

    <body bgcolor="red">
        <h1 align="center"> <B>NAGERCOIL</B></h1>
        <h2 align="center"><b>Govt Medical College</b> </h2>

        <hr color="white">

       
        <table align="center" cellspacing="10">
            <tr>
                <td>1.Kanyakumari Medical College is situated in a picturesque location in Kanyakumari district,
                     offering a serene and conducive environment for learning and medical practice.</td>
                
            </tr>
            <tr>
                <td>2.The college is equipped with modern facilities and infrastructure, including well-equipped classrooms, laboratories, libraries,
                     and research facilities, providing students with access to the latest resources and technologies .</td>
            </tr>

            <tr>
                <td>3.Students at Kanyakumari Medical College receive hands-on clinical training through rotations in affiliated hospitals and healthcare institutions, gaining practical experience in 
                    various medical specialties under the guidance of skilled clinicians and practitioners.</td>
            </tr>
        </table>
    </body>
</html>
```
```
engine.html

<html>
    <head>
        <title>Engineering College</title>
    </head>

    <body bgcolor="pink">
        <h1 align="center"> <B>NAGERCOIL</B></h1>
        <h2 align="center"><b> St. Xavier Engineering College </b> </h2>

        <hr color="white">

       
        <table align="center" cellspacing="10">
            <tr>
                <td>1.The college is likely situated in a convenient location 
                    within Kanyakumari district, providing easy access to transportation and amenities.</td>
                
            </tr>
            <tr>
                <td>2. St. Xavier Engineering College would likely feature modern infrastructure, including well-equipped classrooms, 
                    laboratories, workshops, and other facilities necessary for engineering education.
                    
                </td>
            </tr>

            <tr>
                <td>3.The college may offer placement assistance and career counseling services to help students 
                    secure internships and job opportunities in reputed companies and organizations.</td>
            </tr>
        </table>
    </body>
</html>

```
```
pearl.html

<html>
    <head>
        <title>Pearl Restaurant</title>
    </head>

    <body bgcolor="lightblue">
        <h1 align="center"> <B>NAGERCOIL</B></h1>
        <h2 align="center"><b>Pearl Restaurant</b> </h2>

        <hr color="white">

       
        <table align="center" cellspacing="10">
            <tr>
                <td>1.Pearl Restaurant is ideally situated in a convenient
                     location within Nagercoil, offering easy accessibility to locals and visitors alike.</td>
                
            </tr>
            <tr>
                <td>2.Pearl Restaurant specializes in serving a diverse range of cuisines, 
                    including authentic South Indian delicacies, seafood dishes, Chinese cuisine, and continental 
                    fare, catering to varying tastes and preferences.</td>
            </tr>

            <tr>
                <td>3.Pearl Restaurant prioritizes customer satisfaction, striving to exceed expectations with impeccable service, 
                    delectable cuisine, and a warm hospitality that keeps guests coming back for more.</td>
            </tr>
        </table>
    </body>
</html>
```




## OUTPUT
![alt text](<Screenshot (23).png>)
![alt text](<Screenshot (24).png>)
![alt text](<Screenshot (25).png>)
![alt text](<Screenshot (26).png>)
![alt text](<Screenshot (27).png>)
![alt text](<Screenshot (28).png>)

## RESULT
The program for implementing image maps using HTML is executed successfully.
