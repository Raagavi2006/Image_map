# Ex04 Places Around Me
# Date:04.11.2024
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
imagemap.html
<html>
    <head>
        <title>Image Mapping</title>
    </head>
    <body>
        <style>
            img{
                width: 1500px;
            }
        </style>
        <img src="map.jpg" usemap="#mapping"/>
        <map name="mapping">
            <area shape="poly" coords="283,331,373,328,377,372,288,373" href="fc.html" title="Food Court">
            <area shape="poly" coords="512,395,627,391,632,446,519,440" href="saveetha.html" title="Saveetha">
            <area shape="poly" coords="744,267,927,258,935,324,742,318" href="evp1.html" title="EVP Cinemas">
            <area shape="poly" coords="690,444,864,444,855,510,679,504" href="queensland.html" title="Queens Land">
            <area shape="poly" coords="465,898,651,894,652,953,464,963" href="royal.html" title="Royal Chitiran">
        </map>
    </body>
</html>

evp1.html
<html>
    <head>
        <title>EVP Cinemas</title>
    </head>
    <center>
        <img src="evp.jpg" height="150px" width="150px">
    </center><hr>
    <body style="background-color: bisque;">
        <style>
            p{
                font-size: x-large;
                font-family: 'Trebuchet MS', 'Lucida Sans Unicode', 'Lucida Grande', 'Lucida Sans', Arial, sans-serif;
            }
            li{
                font-size: x-large;
                font-family: 'Trebuchet MS', 'Lucida Sans Unicode', 'Lucida Grande', 'Lucida Sans', Arial, sans-serif;
            }
        </style>
    <h1>About</h1>
    <p>
        Feel the action come alive with ICE, IMAX, and 4DX Screens. 
        Book Your Tickets Now! Enjoy the Latest Movies with Great Deals on Movie Tickets. 
        Book Tickets! Book Movie Tickets. Check Showtimes Near You. Pre-Book F&B. View Trailers. Ultimate Movie Experience.
    </p>
    <h1>Now Showing</h1>
    <ul class="Now Showing">
        <li>Amaran</li>
        <li>Pushpa 2</li>
        <li>Lucky Baskar</li>
        <li>Sorgavasal</li>
        <li>ZEBRA</li>
    </ul>
    <h1>Coming Soon</h1>
    <ul class="Coming Soon">
        <li>Kraven The Hunter</li>
        <li>Miss You</li>
        <li>HERETIC</li>
        <li>The lord of the Rings</li>
        <li>Zero se Restart</li>
    </ul>
    <h1>Contact Us</h1>
        <p1 style="font-family: 'Trebuchet MS', 'Lucida Sans Unicode', 'Lucida Grande', 'Lucida Sans', Arial, sans-serif; font-size: larger;">Address :- <br>Santhosha Nagar, Chennai - Bangalore, National Highway, Chembarambakkam, Tamil Nadu 600123.<br>
            🕿 :- 044 7777 5544
        </p1>
        <h3 style="font-family: 'Trebuchet MS', 'Lucida Sans Unicode', 'Lucida Grande', 'Lucida Sans', Arial, sans-serif;">2024 &copy; All rights reserved</h3>
    </body>
</html>

royal.html
<html>
    <head>
        <title>Royal Chitiran</title>
        <center>
            <img src="royal.jpg" width="500px" height="300px">
        </center>
    </head>
    <body>
        <style>
            p{
                font-size: x-large;
            }
            li{
                font-size: x-large;
            }
        </style>
        <h1>About</h1>
        <p>
            Chokhi Dhani Chennai offers a unique Rajasthani-themed experience with folk dance, puppet shows, camel rides, mehndi artists, and lac bangle makers.
             Visitors can enjoy cultural performances and entertainment suitable for all ages. 
             The venue features various activities such as camel rides, bullock cart rides, and pottery making. However, some feedback suggests that the food could be improved in terms of taste and variety.
        </p>
        <h1>Why you should go</h1>
        <ol class="Why you should go">
            <li>Experience authentic North Indian culture</li>
            <li>Engage in fun activities like camel rides, dance shows, and pottery</li>
            <li>Enjoy a variety of entertainment options suitable for all age groups</li>
        </ol>
        <h1>Know Before you go</h1>
        <p>
            💡Visit early to avoid crowds; aim to arrive by 4 PM.<br>
            💡Be cautious during rainy seasons as many outdoor activities may be affected.<br>
            💡Try the snacks and jaljeera while enjoying folk dances and rides.<br>
            💡Consider bringing your own food or eating elsewhere if concerned about dining quality.
        </p>
        <h1>Address</h1>
        <p>
            Keblur road,Bengaluru - Chennai Hwy,<br>
            near queensland theme park,Sriperumpudhur,<br>
            Chennai,Mevalurkupam,Tamil Nadu<br>
            602117,India
        </p>
        <h1>Contact Us</h1>
        <p>🕿 :- +91 80 6784321</p>
    </body>
</html>

queensland.html
<html>
    <head>
        <title>Queens Land</title>
        <center>
            <img src="ql.jpg" width="500px" height="200px">
        </center>
    </head>
    <body>
        <style>
            p{
                font-size: x-large;
            }
            li{
                font-size: x-large;
            }
        </style>
        <h1>General Information</h1>
        <p>
            Queens Land is a theme park in Poonamallee, Chennai, India, covering 70 acres (28 hectares). It opened in August 2003.
            The park is located by the Chennai-Bangalore Trunk Road between Sriperumpudhur and Poonamalle. 
            There is parking for cars. Buses are available from Guindy and T. Nagar. 
            All buses going to Sriperumpudhur from Chennai stop at Queens Land.
        </p>
        <h1>Rides</h1>
        <p>
            There are 51 rides, 33 for adults and 18 for children. 
            A child may go on some adult rides if accompanied by an adult. The rides include: Free Fall Tower, and Super waves. 
            There are some water rides, which operate during afternoon hours. There are also separate swimming pools for women. 
            They offer variety of dry and wet rides for their customers.

It's one of the most exciting spot for youth to spend time with their friends and family.<br>
Some of the rides are listed below,
        </p>
        <ul class="Rides">
            <li>Queens's Express</li>
            <li>Himalayan Water Ride</li>
            <li>Water Slides</li>
            <li>Wave Pool</li>
            <li>Lazy River</li>
            <li>Rain Dance</li>
            <li>Break Dance</li>
            <li>Columbus</li>
            <li>Octopus</li>
            <li>Dragon Coaster</li>
            <li>Go-Karting</li>
            <li>Top Spin</li>
            <li>Disco Dancer</li>
            <li>Tower Drop</li>
        </ul>
        <h1>Incidents</h1>
        <p>
            The park was closed for few weeks in 2008 due to a collision that resulted in the death of an 11-year-old girl while she was riding in a water boat in the lake.[1] <br>
            Seven employees were arrested in connection with the death.

On 18 June 2019, 12 people were injured when the cables holding the right platform of the free fall tower snapped while the ride was descending, causing the riders to plunge 10 feet (3.0 m) to the ground. 
First aid was administered and no serious injuries were sustained.[2]<br> Following the incident, the park has been ordered to close indefinitely due to ride safety concerns.[3]
        </p>
        <h1>Contact Us</h1>
        <p>🕿 :- +91 44 66789234</p>
    </body>
</html>

saveetha.html
<html>
    <head>
        <title>Saveetha Engineering College</title>
        <center>
            <img src="logo.png" width="1500px" height="120px"><br><hr>
            <img src="sec.jpg" width="1000px" height="500px">
        </center>
    </head>
    <body>
        <style>
            p{
                font-size: x-large;
            }
            li{
                font-size: x-large;
            }
        </style>
        <h1>About Us</h1>
        <p>&nbsp;&nbsp;Welcome to SEC - Saveetha Engineering College (Autonomous), a distinguished institution established in 2001 under the visionary leadership of Dr. N. M. Veeraiyan— a committed medical professional and philanthropist par excellence. With over 35 years of unwavering commitment to excellence in education, our college has emerged as the forefront of engineering education and research.</p>
        <h1>Affiliation</h1>
        <ul class="Affiliation">
            <li>Autonomous Institution Affiliated with Anna University, Chennai.</li>
            <li>Approved by AICTE, New Delhi.</li>
            <li>NBA Accreditation for 5 Undergraduate Courses.</li>
            <li>SIRO Recognition by DSIR Government of India.</li>
            <li>An 'A' grade from NAAC.</li>
            <li>Ranked by NIRF.</li>
        </ul>
        <h1>Courses Offered</h1>
        <p>&nbsp;&nbsp;Our academic offerings include a variety of programs designed to prepare learners for the challenges of Industry 5.0. We offer full-time four-year B.E/B.Tech UG programs across 13 cutting-edge branches such as AI/DS,  AI/ML, CSE, IT, CSE (IoT), CSE (Cybersecurity), ECE, EEE, BME, Civil, Mechanical, Agricultural and Chemical Engineering.

          <br><br>  For those seeking advanced studies, we provide PG programs in M.E.VLSI, M.E.Software Engineering and MBA.
        </p>
        <h1>Placements</h1>
        <p>&nbsp;&nbsp;Saveetha Engineering College (SEC) has always been a favourite destination of recruitment for over 230+ Multinational companies and firms. Our focus on placement centers on creating new approaches to attract the best from the industry to our campus.</p>
        <ul class="Placements">
            <li>97% Placement in 2023 Batch.</li>
            <li>197 plus Multinational Company visited our Campus.</li>
            <li>1302 Placement Offers.</li>
            <li>Highest CTC of Rs. 34 Lakhs per annum.</li>
            <li>Average CTC of Rs. 5.36 Lakhs per annum.</li>
        </ul>
        <h1>Contact Us</h1>
        <p>🕿 :- +91 44 66789234<br> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;+91 44 77889944</p>
    </body>
</html>

fc.html
<html>
    <head>
        <title>Food Court</title>
    </head>
    <body>
        <style>
            p{
                font-size: x-large;
                font-family: 'Trebuchet MS', 'Lucida Sans Unicode', 'Lucida Grande', 'Lucida Sans', Arial, sans-serif;
            }
            td{
                font-size: xx-large;
                font-family: 'Trebuchet MS', 'Lucida Sans Unicode', 'Lucida Grande', 'Lucida Sans', Arial, sans-serif;
                text-align: center;
            }
        </style>
        <center>
            <img src="gavis kitchen.jpg" height="150px" width="150px">
        </center><br>
        <h1>About Us</h1>
        <p>
            Welcome to Gavi's Kitchen!

At Gavi's Kitchen, we believe great food brings people together. 
Since our journey began, we’ve been dedicated to serving delicious, high-quality meals that are fast, fresh, and full of flavor. 
Whether you’re craving juicy burgers, crispy fries, or refreshing drinks, we’re here to satisfy your hunger and delight your taste buds.
        </p>
        <h1>Our Commitment</h1>
        <p>
            Our commitment is simple to provide exceptional food, excellent service, and an experience that leaves you coming back for more.
             We source the finest ingredients, craft our recipes with care, and prioritize your happiness every step of the way.
        </p>
        <h1>Special Menu</h1>
        <table>
            <div class="food-menu">
                <tr>
                    <td><img src="burger.jpg" height="300px" width="300px"></td> 
                    <td><img src="spaghetti.jpg" height="300px" width="300px"></td> 
                    <td><img src="pasta.jpg" height="300px" width="300px"></td>
                    <td><img src="lasanga.jpg" height="300px" width="300px"></td>
                    <td><img src="pizza.jpg" height="300px" width="300px"></td>
                </tr>
                <br><tr></tr>
            <tr></tr>
            <tr>
                <td>Burger</td>
                <td>Spaghetti</td>
                <td>Pasta</td>
                <td>Lasagna</td>
                <td>Pizza</td>
            </tr><tr></tr>
            <br><tr></tr>
            <tr>
                <td>₹80</td>
                <td>₹138</td>
                <td>₹200</td>
                <td>₹300</td>
                <td>₹120</td>
            </tr>
        </div>
        </table>
        <h1>Contact Us</h1>
        <p>🕿 :- +91 44 66789234</p>
    </body>
</html>
```
# OUTPUT
ImageMap
![alt text](<raagavi/WEB 4-1.png>)

Saveetha
![alt text](<raagavi/WEB 4-2.1.png>)
![alt text](<raagavi/WEB 4- 2.2.png>)

EVP
![alt text](<raagavi/WEB 4-3.png>)

QueensLand
![alt text](<raagavi/WEB 4-4.png>)

Royal
![alt text](<raagavi/WEB 4-5.png>)

Food Court
![alt text](<WEB 4-6.png>)
# RESULT
The program for implementing image maps using HTML is executed successfully.
