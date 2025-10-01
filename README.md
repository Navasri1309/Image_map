# Ex04 Places Around Me
# Date:01.10.2025
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
```
<html>
    <head>
        <title>My City</title>
    </head>
    <body bgcolor="green">
        <h1 align="center">
        <font color="sky blue"><b>THANDALAM</b></font>
        </h1>
        <center>
            <img src="map.png" usemap="My City" height="600" width="1000">
            <map name="My City">
            <area target="" alt="saveetha engineering college" title="saveetha engineering college" href="sec.html" coords="897,36,693,79" shape="rect">
            <area target="" alt="SIMATS engineering" title="SIMATS engineering" href="simats.html" coords="420,426,624,419,623,467,425,471" shape="poly">
            <area target="" alt="saveetha medical college hospital" title="saveetha medical college hospital" href="smc.html" coords="333,675,78" shape="circle">
            <area target="" alt="saveetha college of nursing" title="saveetha college of nursing" href="snc,html" coords="133,387,17,497" shape="rect">
            <area target="" alt="saveetha college of allied health sciences" title="saveetha college of allied health sciences" href="scahs.html" coords="520,532,693,446,701,593" shape="poly">
            </map>
        </center>
    </body>
</html>

sec.html

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
        <img src="c:\Users\B.NAVASRI\Downloads\SEC.jpg" usemap="#Mycity" height="610" width="1000">
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
        <img src="c:\Users\B.NAVASRI\Downloads\simats.png" usemap="#Mycity" height="610" width="1000">
        </center>
        <p align="justify">
        <font face="Georgia" size="5">
            SIMATS Engineering, part of Saveetha Institute in Chennai, is a top-ranked, NAAC A++ accredited institution offering cutting-edge
            programs in AI, Data Science, Mechanical, and more. It’s globally recognized for sustainability, ranks 45th in India (NIRF 2025),
            and provides hands-on learning, modern labs, and strong placements with top companies like TCS and Infosys.
        </p>
    </body>
</html>

smc.html

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
        <img src="c:\Users\B.NAVASRI\Downloads\smc.png" usemap="#Mycity" height="610" width="1000">
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

scn.html

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
        <img src="c:\Users\B.NAVASRI\Downloads\Nursing.avif" usemap="#Mycity" height="610" width="1000">
        </center>
        <p align="justify">
        <font face="Georgia" size="5">
            Saveetha College of Nursing in Chennai is a top-ranked institution offering B.Sc, M.Sc, Post Basic B.Sc, and Ph.D programs in nursing. 
            It provides hands-on clinical training at its own 1200-bed hospital, modern campus facilities, and international learning opportunities.
            Accredited with NAAC A++ and approved by the Indian Nursing Council, it combines academic excellence with practical experience for a global nursing career.
        </p>
    </body>
</html>

scahs.html

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
        <img src="c:\Users\B.NAVASRI\Downloads\scahs.webp" usemap="#Mycity" height="610" width="1000">
        </center>
        <p align="justify">
        <font face="Georgia" size="5">
            Saveetha College of Allied Health and Science in Chennai offers top-tier programs in fields like Medical Lab Technology, 
            Radiology, and Operation Theatre Technology. Backed by a 2000-bed hospital, students receive hands-on clinical training 
            and access to modern labs. Accredited with NAAC A++, it blends academic rigor with real-world healthcare experience.
        </p>
    </body>
</html>


```
# OUTPUT
![alt text](<Screenshot 2025-10-01 123858.png>)

![alt text](<Screenshot 2025-10-01 124024.png>)

![alt text](<Screenshot 2025-10-01 124106.png>)

![alt text](<Screenshot 2025-10-01 124159.png>)

![alt text](<Screenshot 2025-10-01 124239.png>)

![alt text](<Screenshot 2025-10-01 124319.png>)

# RESULT
The program for implementing image maps using HTML is executed successfully.
