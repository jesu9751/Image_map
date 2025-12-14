# Ex04 Places Around Me
# Date:
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
gmap.html
<html>
    <head>
        <title style="color:red">
            south india map 
        </title>
    </head>
    <body>
        <h1 align="center">
            <font color="red"><i>Saveetha Map</i></font>
        </h1>
        <h2 align="center">
            <font color="green"><b>CLICK THE PLACE TO LEARN ABOUT IT</b></font>
        </h2>
        <center>
        <img src="map.png" usemap="#mapu pa" height="630" width="1250">
        <map name="mapu pa">
            <area shape="rect" coords="832,150,1075,119" href="saveetha.html" alt="">
            <area shape="rect" coords="710,423,637,638" href="simats.html" alt="">
            <area shape="rect" coords="132,496,268,654" href="savnur.html" alt="">
            <area shape="rect" coords="627,770,837,734" href="sahe.html" alt="">
        </map>
        </center>
    </body>
</html>

sahe.html
<html>
    <head>'
        <title>Microsoft</title>
    </head>
    <body align="center" bgcolor="grey">
        <h1 align="centre">
        <font color="black"><b>SAVEETHA COLLEGE OF ALLIED HEALTH SCIENCES</b></font>
        </h1>
        <h3 align="center">
        <font color="black"> THANDALAM</font>
        </h3>
        <center>
        <img src="nur.jpg" usemap="#Mycity" height="500" width="800">
        </center>
        <p align="justify">
        <font face="Georgia" size="5">
            Saveetha College of Allied Health and Science in Chennai offers top-tier programs in fields like Medical Lab Technology, 
            Radiology, and Operation Theatre Technology. Backed by a 2000-bed hospital, students receive hands-on clinical training 
            and access to modern labs. Accredited with NAAC A++, it blends academic rigor with real-world healthcare experience.
        </p>
    </body>
</html>

saveetha.html
<html>
    <head>'
        <title>Microsoft</title>
    </head>
    <body align="center" bgcolor="pink">
        <h1 align="centre">
        <font color="auqa"><b>SAVEETHA ENGINEERING COLLEGE</b></font>
        </h1>
        <h3 align="center">
        <font color="auqa"> THANDALAM</font>
        </h3>
        <center>
        <img src="saveetha.jpg" usemap="#Mycity" height="300" width="500">
        </center>
        <p align="justify">
        <font face="Georgia" size="5">
            Saveetha Engineering College, located in Chennai, Tamil Nadu, is a premier institution known for its commitment to academic excellence  and innovation
            in engineering education. Established in 2001, the college is part of the Saveetha Group of Institutions and is affiliated with Anna University. 
            It offers a wide range of undergraduate and postgraduate programs in engineering and technology, supported by state-of-the-art laboratories, 
            modern infrastructure, and a vibrant campus life. With a strong emphasis on research, industry collaboration, and holistic development,
            Saveetha Engineering College nurtures students to become skilled professionals and responsible global citizens.

        </p>

    </body>
</html>
saveethamed.html
<html>
    <head>'
        <title>Microsoft</title>
    </head>
    <body align="center" bgcolor="violet">
        <h1 align="centre">
        <font color="auqa"><b>SAVEETHA MEDICAL COLLEGE HOSPITAL</b></font>
        </h1>
        <h3 align="center">
        <font color="auqa"> THANDALAM</font>
        </h3>
        <center>
        <img src="saveetha med.jpg" usemap="#Mycity" height="500" width="800">
        </center>
        <p align="justify">
        <font face="Georgia" size="5">
            Saveetha Medical College and Hospital (SMCH) in Chennai is a top-ranked,
            NAAC A++ accredited institution offering MBBS, MD/MS, DM/MCh, and Ph.D programs.
            Its 2000-bed super-specialty hospital provides advanced clinical training and
            healthcare services. Known for cutting-edge infrastructure, high patient volume, 
            and research-driven education, SMCH blends academic excellence with real-world medical experience.

        </p>
    </body>
</html>
savnur.html
<html>
    <head>'
        <title>Microsoft</title>
    </head>
    <body align="center" bgcolor="sky blue">
        <h1 align="centre">
        <font color="auqa"><b>SAVEETHA COLLEGE OF NURSING</b></font>
        </h1>
        <h3 align="center">
        <font color="auqa"> THANDALAM</font>
        </h3>
        <center>
        <img src="nu.webp" usemap="#Mycity" height="500" width="800">
        </center>
        <p align="justify">
        <font face="Georgia" size="5">
            Saveetha College of Nursing in Chennai is a top-ranked institution offering B.Sc, M.Sc, Post Basic B.Sc, and Ph.D programs in nursing. 
            It provides hands-on clinical training at its own 1200-bed hospital, modern campus facilities, and international learning opportunities.
            Accredited with NAAC A++ and approved by the Indian Nursing Council, it combines academic excellence with practical experience for a global nursing career.
        </p>
    </body>
</html>
simats.html
<html>
    <head>'
        <title>Microsoft</title>
    </head>
    <body align="center" bgcolor="purple">
        <h1 align="centre">
        <font color="black"><b>SIMATS ENGINEERING</b></font>
        </h1>
        <h3 align="center">
        <font color="black"> THANDALAM</font>
        </h3>
        <center>
        <img src="simats.jpg" usemap="#Mycity" height="500" width="800">
        </center>
        <p align="justify">
        <font face="Georgia" size="5">
            SIMATS Engineering, part of Saveetha Institute in Chennai, is a top-ranked, NAAC A++ accredited institution offering cutting-edge
            programs in AI, Data Science, Mechanical, and more. It’s globally recognized for sustainability, ranks 45th in India (NIRF 2025),
            and provides hands-on learning, modern labs, and strong placements with top companies like TCS and Infosys.
        </p>
    </body>
</html>

</html>
# OUTPUT

![alt text](1.png)
![alt text](<Screenshot 2025-12-14 200353.png>)
![alt text](<Screenshot 2025-12-14 200353.png>)
![alt text](<Screenshot 2025-12-14 200442.png>)
![alt text](<Screenshot 2025-12-14 200507.png>)



# RESULT
The program for implementing image maps using HTML is executed successfully.
