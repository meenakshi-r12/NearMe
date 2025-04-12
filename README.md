# Ex04 Places Around Me
## Date: 12.4.25

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
        <title>
            My City
        </title>
    </head>

    <body>
        <h1 align="center" style="background-color: aquamarine;font-style: italic;font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;">
            ANNA NAGAR
        </h1>
        <h2 align="center" style="background-color: blanchedalmond;font-style: oblique;font-family: 'Courier New', Courier, monospace;">
            NANDA KISHOR S P
        </h2>\
        <img src="map.png" usemap="#MyCity" height="750" width="1335">
        <map name="MyCity">
            <area target="" alt="VR MALL" title="VR MALL" href="vrmall.html" coords="542,526,702,585" shape="rect">
            <area target="" alt="ROHINI THEATRE" title="ROHINI THEATRE" href="rohini.html" coords="479,625,682,689" shape="rect">
            <area target="" alt="SARAVANA STORES" title="SARAVANA STORES" href="saravana.html" coords="634,120,64" shape="circle">
            <area target="" alt="CHENNAI RAIL MUSEUM" title="CHENNAI RAIL MUSEUM" href="museum.html" coords="896,136,60" shape="circle">
            <area target="" alt="MMM HOSPITAL" title="MMM HOSPITAL" href="mmmhospital.html" coords="316,473,495,400" shape="rect">
        </map>
    </body>
</html>




vrmall.html


<html>
<head>
    <title>VR Mall Anna Nagar</title>
</head>
<body style="font-family: Arial, sans-serif; background-color: lightcoral; text-align: center; color:white;">

    <h1 style="color: darkblue;">VR Mall Anna Nagar</h1>

    <p>
        VR Mall, located in the vibrant neighborhood of Anna Nagar, Chennai, is more than just a shopping destination. 
        Opened in 2018, this state-of-the-art lifestyle hub quickly became a landmark, redefining the shopping and entertainment experience for residents and visitors alike.
    </p>
    <p>
        Built with a vision to create a community-centered space, VR Mall integrates modern architecture with cultural heritage. 
        The mall spans over a vast area, featuring a mix of national and international brands, ensuring something for everyone. 
        From high-end fashion boutiques to budget-friendly outlets, it caters to a diverse audience.
    </p>
    <p>
        A unique aspect of VR Mall is its commitment to art and culture. 
        The space regularly hosts events, exhibitions, and live performances, making it a hub for creativity and community engagement. 
        The mall's atrium often showcases artistic installations, giving visitors a chance to appreciate contemporary art while they shop.
    </p>
    <p>
        The food court at VR Mall is a culinary paradise, offering a wide variety of cuisines to tantalize your taste buds. 
        From traditional South Indian dishes to global favorites, it ensures a delightful dining experience. 
        The mall also features several fine-dining restaurants for those who prefer a more sophisticated setting.
    </p>
    <p>
        One of the standout features of VR Mall is its multiplex cinema. 
        Equipped with cutting-edge technology and luxurious seating, it offers an unparalleled movie-watching experience. 
        Whether you're catching the latest blockbuster or enjoying a classic film, the VR Mall cinema guarantees entertainment at its best.
    </p>
    <p>
        Beyond shopping and entertainment, VR Mall also provides a range of services designed to enhance the visitor experience. 
        These include valet parking, wheelchair accessibility, and a dedicated children's play area. 
        It is a family-friendly space where parents can shop while their kids enjoy supervised activities.
    </p>
    <p>
        Since its inception, VR Mall has also been actively involved in sustainability initiatives. 
        The mall incorporates eco-friendly practices, such as efficient waste management and energy-saving systems, to minimize its environmental impact. 
        This commitment to sustainability has earned it recognition and awards within the retail industry.
    </p>
    <p>
        Over the years, VR Mall has become a symbol of Anna Nagar modernization and growth. 
        It has transformed the neighborhood into a bustling commercial and recreational hub, attracting visitors from across Chennai and beyond. 
        Whether you're a local or a tourist, VR Mall offers a memorable experience that combines shopping, entertainment, and community spirit.
    </p>
    <p>
        Visit VR Mall today to discover why it is more than just a mall, it is a destination that celebrates life, culture, and creativity in the heart of Chennai.
    </p>

</body>
</html>



saravana.html



<html>
<head>
    <title>Saravana Stores</title>
</head>
<body style="font-family: 'Helvetica', sans-serif; background-color: teal; color: indigo; padding: 20px;">

    <h1 style="color: blanchedalmond; text-align: center;">Saravana Stores</h1>

    <p style="font-size: 1.2em; text-align: justify; line-height: 1.6;">
        Saravana Stores is one of Chennai's most iconic and popular retail chains, known for its extensive range of products and exceptional value. 
        Established in the 1960s, the store has grown from a small shop to a massive multi-store complex, offering everything from clothing and accessories to home goods and electronics.
    </p>

    <p style="font-size: 1.2em; text-align: justify; line-height: 1.6;">
        The flagship store, located on the busy Usman Road in T. Nagar, is a shopping paradise for both locals and tourists. 
        Known for its wide variety of products, Saravana Stores is a one-stop destination for almost anything you need, from trendy apparel to gold jewelry, home appliances, kitchenware, and more.
    </p>

    <p style="font-size: 1.2em; text-align: justify; line-height: 1.6;">
        Saravana Stores is particularly famous for its vast collection of traditional and modern clothing. 
        The store stocks an impressive range of sarees, salwar kameez, lehengas, and ethnic wear, making it a go-to spot for weddings, festivals, and other special occasions. 
        The clothing section is not just limited to Indian wear, as the store also offers a variety of Western clothing options for men, women, and children.
    </p>

    <p style="font-size: 1.2em; text-align: justify; line-height: 1.6;">
        The store's jewelry section is another highlight, offering a wide selection of gold and silver jewelry, including traditional and contemporary designs. 
        Whether you're looking for a simple chain or an elaborate bridal set, Saravana Stores has something for every budget and taste.
    </p>

    <p style="font-size: 1.2em; text-align: justify; line-height: 1.6;">
        Apart from clothing and jewelry, Saravana Stores also offers a diverse range of products in categories like electronics, kitchenware, toys, home décor, and even health and beauty items. 
        With such a wide selection, the store appeals to people from all walks of life, whether they're looking to buy daily essentials or splurge on a luxury item.
    </p>

    <p style="font-size: 1.2em; text-align: justify; line-height: 1.6;">
        The customer experience at Saravana Stores is also noteworthy. The staff is generally helpful, and the store is well-organized, making it easy to browse through the various sections. 
        However, the store's immense popularity often leads to crowded shopping floors, especially during peak hours or festival seasons, which can be a challenge for some shoppers.
    </p>

    <p style="font-size: 1.2em; text-align: justify; line-height: 1.6;">
        Over the years, Saravana Stores has built a loyal customer base, with many returning for the competitive pricing and wide range of products. 
        The store's constant reinvestment into expanding its offerings and updating its collections has made it a shopping landmark in Chennai.
    </p>

    <p style="font-size: 1.2em; text-align: justify; line-height: 1.6;">
        Whether you're looking for a stylish outfit for a wedding, a gift for a loved one, or just daily essentials at a great price, Saravana Stores remains one of the top choices for shoppers in Chennai. 
        Its reputation for variety, value, and convenience makes it a must-visit destination for anyone in the city.
    </p>

</body>
</html>



rohini.html



<html>
<head>
    <title>Rohini Theatre - Chennai</title>
</head>
<body style="font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif; background-color: lightgray; text-align: center; color: black;">

    <h1 style="color: darkred;">Rohini Theatre - Chennai</h1>

    <p>
        Rohini Theatre, located in Koyambedu, Chennai, is one of the city's most iconic cinema halls, known for its rich history and modern facilities. 
        Established in 1980, the theatre has been a part of Chennai's cultural fabric for over four decades, evolving from a single-screen cinema to a state-of-the-art multiplex.
    </p>
    <p>
        Originally designed as a traditional movie hall, Rohini Theatre began its journey by screening some of Tamil cinema's greatest classics. 
        Over the years, it gained a reputation for delivering exceptional movie-watching experiences, becoming a favorite destination for film enthusiasts in Chennai.
    </p>
    <p>
        In 2015, the theatre underwent a massive renovation to keep up with the changing times. 
        The transformation included upgrading its infrastructure, sound systems, and seating, while retaining the charm that loyal patrons had come to love. 
        Today, it boasts multiple screens equipped with cutting-edge Dolby Atmos sound, 4K projection, and luxurious seating arrangements.
    </p>
    <p>
        Rohini Theatre is particularly known for its grand premieres and first-day-first-show celebrations. 
        Fans of Tamil cinema flock to the theatre to celebrate the release of major blockbusters, often accompanied by festive decorations, live music, and the energy of an enthusiastic crowd.
    </p>
    <p>
        Despite modern upgrades, the theatre has managed to preserve its nostalgic charm. 
        The spacious lobby and retro-inspired design elements reflect its history, creating a unique blend of the old and the new. 
        The management's dedication to maintaining this balance is part of what makes Rohini Theatre stand out.
    </p>
    <p>
        Another highlight of Rohini Theatre is its affordability. 
        Unlike many high-end multiplexes, the theatre continues to offer reasonable ticket prices, making it accessible to a wide audience. 
        This commitment to affordability has earned it the love and loyalty of generations of Chennai residents.
    </p>
    <p>
        Apart from movies, Rohini Theatre occasionally hosts special screenings and events, such as film festivals and charity shows. 
        These initiatives contribute to the cultural and social life of the city, reinforcing the theatre's role as more than just a place to watch movies.
    </p>
    <p>
        The theatre is conveniently located near the Koyambedu bus terminus, making it easily accessible for visitors from different parts of Chennai. 
        Ample parking facilities and a range of nearby eateries add to the convenience, making it a perfect outing spot for families and friends.
    </p>
    <p>
        Over the years, Rohini Theatre has become a symbol of Chennai's love for cinema. 
        It continues to attract moviegoers with its blend of tradition and innovation, offering a cinematic experience that is both nostalgic and modern.
    </p>
    <p>
        If you're looking for a place to experience the magic of movies in Chennai, Rohini Theatre is the perfect destination. 
        Step in to witness the legacy of one of the city's most cherished cultural landmarks.
    </p>

</body>
</html>



museum.html



<html>
<head>
    <title>Chennai Rail Museum</title>
</head>
<body style="font-family: Impact, Haettenschweiler, 'Arial Narrow Bold', sans-serif; background-color: mediumblue; color: burlywood; padding: 20px; font-style: italic;">

    <h1 style="color: azure; text-align: center;">Chennai Rail Museum</h1>

    <p style="font-size: 1.2em; text-align: justify; line-height: 1.6;">
        The Chennai Rail Museum, located in the heritage area of Perambur, is one of the most popular and informative museums in Chennai. 
        Established in 2002 by the Southern Railway, it offers a fascinating journey through the history of Indian Railways, showcasing the evolution of the railway system in the country.
    </p>

    <p style="font-size: 1.2em; text-align: justify; line-height: 1.6;">
        The museum is housed on an expansive campus, with displays of rare and historical locomotives, coaches, and other railway artifacts. 
        Visitors can witness how the Indian Railways system has transformed over the years, from its colonial beginnings to the modern-day advancements in technology and design.
    </p>

    <p style="font-size: 1.2em; text-align: justify; line-height: 1.6;">
        One of the highlights of the Chennai Rail Museum is its collection of vintage steam engines. 
        These majestic machines, some of which were once used in the British era, are meticulously preserved to give visitors a glimpse into the grandeur of early rail travel. 
        The museum also showcases several electric and diesel locomotives that were used in the mid-20th century.
    </p>

    <p style="font-size: 1.2em; text-align: justify; line-height: 1.6;">
        The museum's exhibits also include old railway station signs, historical documents, and models of trains that depict the changing design and technology of the Indian railways. 
        Visitors can learn about the different aspects of railway operations, including signaling, train schedules, and the important role trains have played in connecting India's vast and diverse regions.
    </p>

    <p style="font-size: 1.2em; text-align: justify; line-height: 1.6;">
        Another significant feature of the Chennai Rail Museum is the interactive gallery, where visitors, especially children, can engage in hands-on activities related to trains and rail systems. 
        The museum also hosts educational programs and workshops for students, making it an excellent educational resource.
    </p>

    <p style="font-size: 1.2em; text-align: justify; line-height: 1.6;">
        The museum grounds also feature a small toy train that takes visitors on a short ride around the campus, adding a fun and nostalgic touch to the visit. 
        This ride is especially popular among families with children, who enjoy the experience of riding a miniature train while learning about the history of railways.
    </p>

    <p style="font-size: 1.2em; text-align: justify; line-height: 1.6;">
        The Chennai Rail Museum is not just a place to admire old trains but also a celebration of the cultural significance of rail travel in India. 
        It stands as a testament to the pivotal role railways have played in shaping the country's economic, social, and cultural landscape.
    </p>

    <p style="font-size: 1.2em; text-align: justify; line-height: 1.6;">
        Whether you are a train enthusiast, history lover, or a family looking for an engaging day out, the Chennai Rail Museum offers a unique and enriching experience. 
        It is a must-visit for anyone interested in the legacy of Indian Railways and the stories behind its iconic trains.
    </p>

</body>
</html>



mmmhospital.html



<html>
<head>
    <title>Madras Medical Mission Hospital</title>
</head>
<body style="font-family: 'Trebuchet MS', 'Lucida Sans Unicode', 'Lucida Grande', 'Lucida Sans', Arial, sans-serif; background-color: aquamarine; color:goldenrod; padding: 20px;">

    <h1 style="color: green; text-align: center;">Madras Medical Mission Hospital</h1>

    <p style="font-size: 1.2em; text-align: justify; line-height: 1.6;">
        The Madras Medical Mission (MMM) Hospital, located in Mogappair, Chennai, is one of India's premier healthcare institutions, renowned for its excellence in medical care and research. 
        Established in 1987 as a non-profit charitable organization, the hospital has grown into a multi-specialty facility providing world-class healthcare services to patients from across the globe.
    </p>

    <p style="font-size: 1.2em; text-align: justify; line-height: 1.6;">
        The hospital was founded with a mission to combine compassion, quality care, and advanced medical technology. 
        Over the years, it has become synonymous with excellence in medical treatment, particularly in the fields of cardiology, nephrology, and critical care.
    </p>

    <p style="font-size: 1.2em; text-align: justify; line-height: 1.6;">
        The Cardiac Centre at Madras Medical Mission is one of its most celebrated departments, offering cutting-edge treatments for heart diseases. 
        The hospital has performed thousands of successful cardiac surgeries, including pediatric heart surgeries, making it a trusted name in cardiovascular care. 
        Its specialized team of cardiologists and cardiac surgeons are among the best in the country.
    </p>

    <p style="font-size: 1.2em; text-align: justify; line-height: 1.6;">
        MMM's Institute of Reproductive Medicine and Women's Health is another hallmark of the hospital. 
        It offers advanced treatments for infertility, high-risk pregnancies, and women's health concerns. 
        With state-of-the-art facilities and a patient-centered approach, the institute has brought hope to countless families.
    </p>

    <p style="font-size: 1.2em; text-align: justify; line-height: 1.6;">
        The hospital is also well-known for its Nephrology and Urology departments. 
        The comprehensive care provided here includes kidney transplants, dialysis, and minimally invasive surgeries. 
        The team's expertise and the hospital's infrastructure ensure the best outcomes for patients with renal conditions.
    </p>

    <p style="font-size: 1.2em; text-align: justify; line-height: 1.6;">
        Beyond its medical expertise, Madras Medical Mission is deeply committed to research and education. 
        The hospital has a dedicated research center that focuses on developing innovative treatments and improving existing medical practices. 
        It also conducts training programs for medical professionals, fostering the next generation of healthcare providers.
    </p>

    <p style="font-size: 1.2em; text-align: justify; line-height: 1.6;">
        The hospital is equipped with modern amenities, including fully digital ICUs, advanced imaging facilities, and a 24/7 emergency department. 
        Its patient-friendly services include comfortable rooms, an efficient appointment system, and a highly responsive nursing staff. 
        These factors contribute to making every patient's experience as stress-free as possible.
    </p>

    <p style="font-size: 1.2em; text-align: justify; line-height: 1.6;">
        Madras Medical Mission is also actively involved in community outreach programs. 
        Through health camps, awareness drives, and free treatments for underprivileged sections of society, the hospital stays true to its mission of serving humanity with compassion.
    </p>

    <p style="font-size: 1.2em; text-align: justify; line-height: 1.6;">
        With a legacy spanning decades, Madras Medical Mission Hospital continues to set benchmarks in healthcare, driven by its vision of offering holistic, patient-focused medical care. 
        It remains a beacon of hope for patients seeking quality treatment and compassionate service.
    </p>

</body>
</html>
```

## OUTPUT

![Screenshot (6)](https://github.com/user-attachments/assets/89da1963-a3c8-4fe8-a1d6-5f7f917dd578)


![Screenshot (7)](https://github.com/user-attachments/assets/2ee1a079-f0c5-402f-bc26-da8dbd590655)


![Screenshot (8)](https://github.com/user-attachments/assets/b9e794ff-9e3e-40d9-a620-ab307e0be26b)


![Screenshot (9)](https://github.com/user-attachments/assets/f1e7018c-c75a-48db-8d2b-a7b1c58bccc3)


![Screenshot (10)](https://github.com/user-attachments/assets/0b0c5da4-05c7-4aa6-a425-4c2fbe4777c3)


![Screenshot (11)](https://github.com/user-attachments/assets/c1902be2-f4fb-4680-8bff-d5a29115488d)

## RESULT
The program for implementing image maps using HTML is executed successfully.
