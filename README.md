# Ex04 Places Around Me
## Date: 10-12-2024

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
            <font color="blue"><b>VELLORE</b></font>
        </h1>
        <h2 align="center">
            <font color="red"><b>DHANUS KARTHI S [24005701]</b></font> </h2>
        <h3 align="center">
            <img src="map.html.png" usemap="#image-map" width="1473" height="700">
            <map name="image-map">
                <area target="" alt="Vellore Institute of Technology" title="Vellore Institute of Technology" href="vit.html" coords="745,41,877,91" shape="rect">
                <area target="" alt="Palamathi Temple" title="Palamathi Temple" href="palamathitemple.html" coords="812,547,978,607" shape="rect">
                <area target="" alt="Palamathi Hills" title="Palamathi Hills" href="palamathihills.html" coords="785,615,932,641" shape="rect">
                <area target="" alt="Vellore fort" title="Vellore fort" href="vellorefort.html" coords="580,362,769,396" shape="rect">
                <area target="" alt="goldentemple" title="golgentemple" href="golden temple.png" coords="1156,500,1330,561" shape="rect">
            </map>
      </h3>
    </body>
</html>

hospital.html

<html>
    <head>
        <title>
            HOSPITAL
        </title>
    </head>
    <body bgcolor="pink">
        <h1 align="center">
            <font color="red"><b>VELLORE</b></font>

        </h1>
        <h3 align="center">
            <font color="green"><b>CHRISTIAN MEDICAL COLLEGE</b></font>
        </h3>
        <center>
            <img src="hospital.png" 
        </center>
       <hr size="3" color="teal">
       <p align="justify" >
        <font face="Georgia" size="5">
            Christian Medical College, Vellore, widely known as CMC, Vellore, is a private, Christian minority community-run medical
             college and hospital in Vellore, Tamil Nadu, India. This institute includes a network of primary, secondary and tertiary 
             care hospitals.

            The institute, constituent college is affiliated with the Tamil Nadu Dr. M.G.R. Medical University.Founded in 1900 by 
            an American missionary, Dr Ida S. Scudder, CMC Vellore has brought many significant achievements to India, including 
            starting the first College of Nursing in 1946, performing the first reconstructive surgery for leprosy in the world (1948),
             performing the first successful open heart surgery in India (1961), performing the first kidney transplant in India (1971),
              performing first bone marrow transplantation (1986) in India and performing the first successful ABO incompatible kidney 
              transplant in India (2009).
        </font>
       </p>
    </body>
</html>

vellorefort.html

<body bgcolor="#E0FFFF">
    <h1 align="center">
        <font color="red">
            VELLORE
        </font>
    </h1>
    <h2 align="center">
        <font color="purple">
            Vellore fort
        </font>
    </h2>
    <hr>
    <h2>
        <center>
            <img src="vellore fort.jpg" width="424" height="119"
        </center>
        <hr>
        <li align="left">
            <font size="5">
                  It is famously associated with the Vellore Mutiny of 1806, which was a significant prelude to the Indian Rebellion of 1857. The mutiny was led by Indian soldiers (sepoys) against the British East India Company.        
                
         </font>
        </li>
        <li align="left">
            <font size="5">
                The fort is located in the center of Vellore city, Tamil Nadu. Its strategic location made it a key military stronghold in the region.
            </font>
        </li>
        <li align="left">
            <font size="5">
                Vellore Fort is one of the oldest forts in India, built during the Vijayanagara Empire in the 16th century. The fort played a key role in the region’s defense and has witnessed several significant historical events, especially during the rule of the Nayak dynasty and later the Mughal empire.  
            </font>
        </li>
        
    </h2>
</body>

</html>

palamathitemple.html

<html>

<body bgcolor="#E0FFFF">
    <h1 align="center">
        <font color="red">
            VELLORE
        </font>
    </h1>
    <h2 align="center">
        <font color="purple">
            Palamathi temple
        </font>
    </h2>
    <hr>
    <h2>
        <center>
            <img src="palamathi temple.jpg" width="550" height="413"
        </center>
        <hr>
        <li align="left">
            <font size="4">
                Palamathi Hills offers stunning views of the surrounding Vellore region, including lush greenery, rolling hills, and picturesque landscapes. The area is perfect for photography, bird watching, and enjoying the serenity of nature.
            </font>
        </li>
        <li align="left">
            <font size="4">
                The Palamathi Dam, located near the hills, is another key attraction. The dam is built on the Palamathi River and is important for irrigation in the region
            </font>
        </li>
        <li align="left">
            <font size="4">
                The climate in Palamathi Hills is pleasant, with cooler temperatures compared to the plains of Vellore, especially during the summer months
            </font>
        
    </h2>
</body>

</html> 

palamathihills.html

<html>

<body bgcolor="#E0FFFF">
    <h1 align="center">
        <font color="red">
            VELLORE
        </font>
    </h1>
    <h2 align="center">
        <font color="purple">
           Palamathi hills
        </font>
    </h2>
    <hr>
    <h2>
        <center>
            <img src="palamathi hills.jpg" width="300" height="168"
        </center>
        <hr>
        <li align="left">
            <font size="5">
                Palamathi Hills offers stunning views of the surrounding Vellore region, including lush greenery, rolling hills, and picturesque landscapes. The area is perfect for photography, bird watching, and enjoying the serenity of nature.   
            </font>
        </li>
        <li align="left">
            <font size="5">
                The Palamathi Dam, located near the hills, is another key attraction. The dam is built on the Palamathi River and is important for irrigation in the region. Visitors can enjoy the peaceful atmosphere around the dam and take in views of the water and the surrounding hills.  
            </font>
        </li>
        <li align="left">
            <font size="5">
                The climate in Palamathi Hills is pleasant, with cooler temperatures compared to the plains of Vellore, especially during the summer months. This makes it a refreshing retreat for those seeking to escape the heat of the lowlands.  
            </font>
        </li>
    </h2>
</body>

</html>


vit.html

<html>

<body bgcolor="#E0FFFF">
    <h1 align="center">
        <font color="red">
            VELLORE
        </font>
    </h1>
    <h2 align="center">
        <font color="purple">
         VELLORE INSTITUE OF TECHNOLOGY
        </font>
    </h2>
    <hr>
    <h2>
        <center>
            <img src="VIT.png" width="800" height="400"
        </center>
        <hr>
        <li align="left">
            <font size="5">
                  VIT was founded in 1984 by Dr. G. Viswanathan, a former member of the Rajya Sabha, with the vision to provide world-class education in the fields of technology and engineering.
                  Initially established as VIT University, it was conferred university status by the Ministry of Human Resource Development, Government of India, in 2001.
                    
            </font>
        </li>
        <li align="left">
            <font size="5">
                  VIT is consistently ranked among the top private engineering universities in India  
            </font>
        </li>
        <li align="left">
            <font size="5">
                  In the NIRF (National Institutional Ranking Framework), VIT has been ranked highly in the categories of engineering and overall performance.  
            </font>
        </li>
        <li align="left">
            <font size="5">
                 VIT’s VITEEE (VIT Engineering Entrance Examination) is a widely recognized entrance exam for admission to undergraduate programs. 
            </font>
        </li>
    </h2>
</body>

</html>
```


## OUTPUT
![alt text](myproject/myapp/static/map.html.png)

![alt text](myproject/myapp/static/vellorefort.png)

![alt text](myproject/myapp/static/hospital.png)

![alt text](myproject/myapp/static/palamathitemple.png)

![alt text](myproject/myapp/static/palamathihills.png)

![alt text](myproject/myapp/static/vit.png)

## RESULT
The program for implementing image maps using HTML is executed successfully.
