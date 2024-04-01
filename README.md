# Ex04 Places Around Me
## Date: 01-04-2024
## Name: Suriya Pravin M
## Roll.No: 212223230223
## Dept: AI&DS

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
        <title>MAP APP</title>
    </head>
    <body>
        <h1 align="center">Thoothukudi</h1>
        <h2 align="center"> Suriya Pravin(212223230223)</h2>
        <center>
            <img src="Screenshot 1.png" usemap="#image-map">

            <map name="image-map">
                <area target="" alt="Anadavar Night Club" title="Anadavar Night Club" href="poratta.html" coords="662,557,295,643" shape="rect">
                <area target="" alt="Velavan Hyper Market" title="Velavan Hyper Market" href="Market.html" coords="761,224,82" shape="circle">
                <area target="" alt="Alagar Public School" title="Alagar Public School" href="school.html" coords="869,726,1010,704,1069,729,1001,757,937,757" shape="poly">
                <area target="" alt="Thoothukudi Horbour" title="Thoothukudi Horbour" href="Horbour.html" coords="600,362,97" shape="circle">
                <area target="" alt="VOC College" title="VOC College" href="VOC_college.html" coords="865,394,1042,468" shape="rect">
</center>
</map>
    </body>
</html>
```
```
Horbour.html

<html>
    <head>
        <title>My City</title>
    </head>
    <body bgcolor="black">
        <h1 align="center">
        <font color="gold"><b>Thoothukudi</b></font>
        </h1>
        <h3 align="center">
        <font color="blue"><b>Thoothukudi Horbour</b></font>
        </h3>
        <hr size="3" color="cyan">
        <p align="justify">
        <font face="Georgia" size="5" color="white">It is one of the 13 major ports in India. It was declared to be a major port on 11 July 1974. It is the second largest port in Tamil Nadu and third largest container terminal in India. V.O. Chidambaranar Port is an artificial port.This is the third international port in Tamil Nadu and it is second all-weather port. All V.O. Chidambaranar Port Authority's traffic handling has crossed 10 million tons from 1 April to 13 September 2008, registering a growth rate of 12.08 per cent, surpassing the corresponding previous year handling of 8.96 million tons.

        </font>
        </p>
    </body>
</html>
```
```
School.html

<html>
    <head>
        <title>My City</title>
    </head>
    <body bgcolor="Green">
        <h1 align="center">
        <font color="purple"><b>Thoothukudi</b></font>
        </h1>
        <h3 align="center">
        <font color="blue"><b>Alagar Public School</b></font>
        </h3>
        <hr size="3" color="cyan">
        <p align="justify">
        <font face="Georgia" size="5">Alagar Public School is Top CBSE School in Thoothukudi City, We are an institute that offers a broad and balanced inculcation- academic, artistic, practical, and physical – so that all our students can totally explore their skills and passion in their immature years. Our committed teachers, for whom teaching is interesting, energetic, and challenging the students to full intensity, this rewarding work merges both hard work & smart work and fun; they help students while gradually teaching them the skills to learn from each other and to study individually. Our Shcool is Best School in Thoothukudi, Tamilnadu.

        </font>
        </p>
    </body>
</html>
```
```
VOC_College.html

<html>
    <head>
        <title>My City</title>
    </head>
    <body bgcolor="bronze">
        <h1 align="center">
        <font color="silver"><b>Thoothukudi</b></font>
        </h1>
        <h3 align="center">
        <font color="white"><b>V.O. Chidambaram College</b></font>
        </h3>
        <hr size="3" color="cyan">
        <p align="justify">
        <font face="Georgia" size="5">
            V.O. Chidambaram College is situated in Thoothukkudi, the southern city of Tamil Nadu. It has been established in the year 1951. This college was founded by Mr. Kulapathi APC Veerabhau. It is a college of arts and science stream. It is a Public Educational Institute. The college has been affiliated to Manonmaniam Sundaranar University, Tirunelveli. It has been recognized by the University Grants Commission (UGC) and has been accredited Grade A by National Assessment and Accreditation Council (NAAC) with 3.31 points. The college is managed by V.O Chidambaram Educational Society. The college campus is spread around on 60 acres of land. It offers undergraduate, postgraduate, and research courses. The admissions in this college is sought only on merit basis.

        </font>
        </p>
    </body>
</html>

```
```
Market.html
<html>
    <head>
        <title>My City</title>
    </head>
    <body bgcolor="Silver">
        <h1 align="center">
        <font color="Black"><b>Thoothukudi</b></font>
        </h1>
        <h3 align="center">
        <font color="Red"><b>Velavan Hyper Market</b></font>
        </h3>
        <hr size="3" color="cyan">
        <p align="justify">
        <font face="Georgia" size="5">
            Supermarkets are large-scale retail establishments that specialise in necessities and convenience items, offering a wide range of products such as fresh meat, produce, dairy, baked goods, and more. They have become an integral part of our landscape and weekly schedules, with many people shopping at supermarkets every week. They offer a vast selection of products, giving consumers more options for the same item. Customers can find almost all their daily necessities in one place, saving time and effort. They often offer lower prices compared to other retail stores, making them an attractive option for consumers. <br>
        </font>
        </p>
    </body>
</html>
```
```
Porotta.html
<html>
    <head>
        <title>My City</title>
    </head>
    <body bgcolor="cyan">
        <h1 align="center">
        <font color="gold"><b>Thoothukudi 
        </b></font>
        </h1>
        <h3 align="center">
        <font color="blue"><b>Andavar Night Club</b></font>
        </h3>
        <hr size="3" color="cyan">
        <p align="justify">
        <font face="Georgia" size="5">
            Best in Hotel:
            1. Andavar night club is located in Polpettai East, Thoothukudi
            2. One of the famous and best place in Tuticorin for tasty parotta and gravy
            3. The food is served us in banana leaf 
            4. Service are good
            5. The hotel is neat and good
            6. The hotel have all non-veg recipes
            7. They are haveing many side dishes for parotta(vicci / fry parotta) 
            8. Bike parking facilities are good
            9. Afternoon lunch also available ( biriyani , parotta and gravy)

            Other dishes<br>
            1. Chicken gravy (both boiler chicken and naattu koli )
            2. Mutton masala 
            3. Chicken 65 
            4. Chicken fry 
            5. Mutton chukka 
            6. Dosai 
            7. Idiappam 
            8. Omlet 
            9. Half boil 
            10. Mutton brain gravy/ fry 
            11. Koththu parotta 
            12. kaadai 
            13. Chicken biriyani

        </font>
        </p>
    </body>
</html>
```

## OUTPUT





## RESULT
The program for implementing image maps using HTML is executed successfully.
