Ex04 Places Around Me

AIM:

To develop a website to display details about the places around my house.


DESIGN STEPS:

STEP 1:

Create a Django admin interface.

STEP 2:

Download your city map from Google.

STEP 3:

Using <map> tag name the map.

STEP 4:

Create clickable regions in the image using <area> tag.

STEP 5:

Write HTML programs for all the regions identified.

STEP 6:

Execute the programs and publish them.

CODE:
```
<!DOCTYPE html>
<html lang="en">

<head>
    <title>My Home Town</title>
</head>

<body>
    <h1 align="center">
        <font color="black">
            <b>MY HOME TOWN</b>
        </font>
    </h1>
    <h3 align="center">
        <font color="black">
            <b>PRAVEEN V (23013808)</b>
        </font>
    </h3>
    <center>
        <img src="map.png" usemap="#My Home Town" height="909px" width="1918px" />
        <map name="My Home Town">
            <area target="_blank" alt="SS Hyderabad briyani" title="SS Hyderabad briyani" href="SS Hyderabad briyani.html" coords="893,343,842,267" shape="rect">
            <area target="_blank" alt="PTR chellaiah chettiar marriage hall" title="PTR chellaiah chettiar marriage hall" href="PTR chellaiah chettiar marriage hall.html" coords="598,616,646,694" shape="rect">
            <area target="_blank" alt="Dominos Pizza" title="Dominos Pizza" href="Dominos Pizza.html" coords="483,626,532,699" shape="rect">
            <area target="_blank" alt="Arul jothi kalyana mandapam" title="Arul jothi kalyana mandapam" href="Arul jothi kalyana mandapam.html" coords="270,802,334,882" shape="rect">
            <area target="_blank" alt="Varahi  ammal temple ambattur" title="Varahi  ammal temple ambattur" href="Varahi  ammal temple ambattur.html" coords="324,697,370,770" shape="rect">
        </map>
    </center>
</body>

<!DOCTYPE html>
<html lang="en">

<head>
    <title>PTR chellaiah chettiar marriage hall</title>
</head>

<body bgcolor="lime">
    <h1 align="center">
        <font color="red"><b>PTR chellaiah chettiar marriage hall</b></font>
    </h1>
    <h3 align="center">
        <font color="blue"><b>PTR chellaiah chettiar marriage hall</b></font>
    </h3>
    <hr size="3" color="red" />
    <p align="justify">
        <font face="Georgia" size="5">
            PTR Chellaiya Chettiar Kalyana Mandapam, Ambattur, Chennai, is a capacious and budget-friendly destination
            to ring in your wedding and reception ceremonies with grandiose. Whether you are hosting a small party or a
            grand celebration, the venue is well-equipped to manage all your events seamlessly. Home to a gigantic
            banquet hall, this space is aptly curated for indoor functions. The hall is equipped with modern amenities
            and top-of-the-line technology to make sure that the executions are smooth and hassle-free. It can
            comfortably accommodate a large gathering for your functions.</font>
    </p>
</body>

</html>
<!DOCTYPE html>
<html lang="en">

<head>
    <title>SS Hyderabad briyani</title>
</head>

<body bgcolor="red">
    <h1 align="center">
        <font color="white"><b>ambattur</b></font>
    </h1>
    <h3 align="center">
        <font color="white"><b>SS Hyderabad briyani</b></font>
    </h3>
    <hr size="3" color="white" />
    <p align="justify">
        <font face="Georgia" size="5">
            S.Abdul Samad started selling homemade chicken biryani & chicken 65 from a small road side stall in
            broadway, Chennai. His hard work, perseverance and passion helped to stabilise his business increased in
            volume steadily over the years. What’s the secret to his taste recipes? It is his mother’s secret receipe
            which he cherishes to this day. This business was later conducted under the name and style of SS Hyderabad
            Biryani Pvt Ltd - a brand name which is very popular amongst all biryani lovers. The first eatery was
            started on a small scale in 1998 in Perambur with a seating capacity of 8. This eatery was so popular and
            led the way for starting a series of branches all over city.</font>
    </p>
</body>

</html>
<!DOCTYPE html>
<html lang="en">

<head>
    <title>Varahi ammal temple ambattur</title>
</head>

<body bgcolor="pink">
    <h1 align="center">
        <font color="red"><b>Varahi ammal temple ambattur</b></font>
    </h1>
    <h3 align="center">
        <font color="purple"><b>Varahi ammal temple ambattur</b></font>
    </h3>
    <hr size="3" color="red" />
    <p align="justify">
        <font face="Georgia" size="5">
            Mother Varahi Protects All Devotees Who are all Turn To Pray For Her Grace And Blessings. She Is An
            Extremely Powerful Goddess And Bestows The Following On Those Who Worship Her With Sincerity And Devotion.
            Worshiping varahi and believe her Varahi Matha eliminates Drishti, Dosha, wards off troubles from all kinds
            of evil spirits aimed at Her devotees, protects them from accidents.</font>
    </p>
</body>

</html>
<!DOCTYPE html>
<html lang="en">

<head>
    <title>Arul jothi kalyana mandapam</title>
</head>

<body bgcolor="yellow">
    <h1 align="center">
        <font color="red"><b>Arul jothi kalyana mandapam</b></font>
    </h1>
    <h3 align="center">
        <font color="blue"><b>Arul jothi kalyana mandapam</b></font>
    </h3>
    <hr size="3" color="navy blue" />
    <p align="justify">
        <font face="Georgia" size="5">
            Aruljothi Wedding Hall A/C holds weddings, family celebrations, social events and business meetings since
            1992. All this time the venue provides excellent service, modern conditions and an individual approach,
            which explains the high appreciation of customers. Located in the heart of Ambattur, Chennai, the site will
            provide the service at the proper level, so that you also appreciate the work.

            Elegant banquet halls
            Aruljothi Wedding Hall A/C provides 2 banquet rooms for events of medium size from 200 to 450 guests. In
            these halls you will find a modern and neat interior with a yellow finish. This is more suitable scenery,
            sustained in the Indian style. The decorator, working here, will help you determine the exact theme and
            create the necessary compositions, decorate the hall with them.</font>
    </p>
</body>

</html>
<!DOCTYPE html>
<html lang="en">

<head>
    <title>Dominos Pizza</title>
</head>

<body bgcolor="blue">
    <h1 align="center">
        <font color="red"><b>Dominos Pizza</b></font>
    </h1>
    <h3 align="center">
        <font color="white"><b>Dominos Pizza</b></font>
    </h3>
    <hr size="3" color="white" />
    <p align="justify">
        <font face="Georgia" size="5">
            Domino's is an American multinational pizza restaurant chain. Founded in 1960, the chain is owned by master
            franchisor Domino's Pizza, Inc. and led by CEO Russell Weiner. The corporation is Delaware-domiciled and
            headquartered at the Domino's Farms Office Park in Ann Arbor Township, near Ann Arbor, Michigan.As of 2018,
            Domino's had approximately 15,000 stores, with 5,649 in the United States, 1,500 in India, and 1,249 in the
            United
            Kingdom.Domino's has stores in over 83 countries and 5,701 cities worldwide..</font>
    </p>
</body>

</html>
```
OUTPUT:
![Screenshot (9)](https://github.com/praveenv23013808/NearMe/assets/145824728/b587c9a2-17f4-40be-8964-0daa8812d106)
![Screenshot (10)](https://github.com/praveenv23013808/NearMe/assets/145824728/c2fca8f2-ee18-4611-b402-542784f51668)
![Screenshot (11)](https://github.com/praveenv23013808/NearMe/assets/145824728/3e20f4e8-95ae-4bfc-ad94-cd493933cc24)
![Screenshot (12)](https://github.com/praveenv23013808/NearMe/assets/145824728/0e9aa0fa-46d3-434c-8e33-4936b323bee8)
![Screenshot (13)](https://github.com/praveenv23013808/NearMe/assets/145824728/78d674a6-33f0-4ec1-9f8b-279d3894fe06)



RESULT
The program for implementing image maps using HTML is executed successfully.
