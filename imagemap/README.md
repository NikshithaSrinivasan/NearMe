# Ex04 Places Around Me
## Date: 01/05/2025

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
```python
Map.html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>IMAGE MAP</title>
</head>
<body>
<img src="map.jpg" usemap="#image-map">

<map name="image-map">
    <area target="" alt="AKT Mandapam" title="AKT Mandapam" href="imap1.html" coords="418,74,63" shape="circle">
    <area target="" alt="Olala" title="Olala" href="imap2.html" coords="1191,159,50" shape="circle">
    <area target="" alt="Post office" title="Post office" href="imap3.html" coords="1046,258,44" shape="circle">
    <area target="" alt="Bank" title="Bank" href="imap4.html" coords="688,192,59" shape="circle">
    <area target="" alt="Temple" title="Temple" href="imap5.html" coords="959,386,66" shape="circle">
</map>
</body>
</html>
Imap1.html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>AKT MARRIAGE HALL</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      background-color:violet;
      color: #333;
    }
    header {
      background-color:palevioletred;
      color: white;
      padding: 10px 0;
      text-align: center;
    }
    header h1 {
      margin: 0;
      font-size: 2.5rem;
    }
    main {
      padding: 20px;
      text-align: center;
    }
    .image-container img {
      max-width: 100%;
      height: 500;
      width: 1000;
      border-radius: 10px;
      box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
    }
    .description {
      margin-top: 20px;
      font-size: 1.2rem;
      line-height: 1.6;
    }
    footer {
      background-color: #333;
      color: white;
      padding: 20px 0;
      text-align: center;
      margin-top: 20px;
    }
    footer a {
      color: #ff6f61;
      text-decoration: none;
    }
    footer a:hover {
      text-decoration: underline;
    }
  </style>
</head>
<body>
  <header>
    <h1>AKT MARRIAGE HALL</h1>
    <p>Your one-stop shop for amazing stickers!</p>
  </header>
  <main>
    <div class="image-container">
      <img src="akt mandabam.jpg" height="500" width="800" alt="A collection of emotions">
    </div>
    <div class="description">
      <p>
        AKT marriage hall is a venue specifically designed to host wedding ceremonies and receptions. It typically includes spacious seating arrangements, a stage for the bride and groom, dining areas, and often decorative lighting and floral arrangements. Marriage halls vary in size and amenities, catering to both intimate gatherings and large celebrations. They provide a convenient and organized setting for couples and their families to celebrate one of the most important events in their lives.
      </p>
      <p>
        Explore our collection today and find the perfect stickers to express your personality and style!
      </p>
    </div>
  </main>
  <footer>
    <p>Email: <a href="mailto:contact@AKT Marriage.com">contact@AKT Marriage.com</a></p>
    <p>Phone: 9632587410</p>
    <p>Follow us on social media for updates</p>
  </footer>
</body>
</html>
Imap2.html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>OLALA JUICE AND SNACKS</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: beige;
        }
        header {
            background-color: burlywood;
            color: white;
            padding: 15px 0;
            text-align: center;
        }
        .container {
            padding: 20px;
            max-width: 800px;
            margin: auto;
        }
        .description {
            margin: 20px 0;
        }
        img {
            width: 100%;
            height: auto;
            border-radius: 10px;
        }
        .contact {
            background-color:wheat;
            padding: 15px;
            border-radius: 10px;
            margin-top: 20px;
        }
        .contact h3 {
            margin-top: 0;
        }
        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 10px 0;
            margin-top: 20px;
        }
    </style>
</head>
<body>

<header>
    <h1>OLALA JUICE AND SNACKS</h1>
</header>

<div class="container">
    <img src="olala.jpg" alt="olala Center Image">
    <div class="description">
        <h2>About Us</h2>
        <p>
            OLALA juice and snacks shop is a small eatery that offers a variety of fresh fruit juices, smoothies, and light snacks. These shops are popular for their quick service and refreshing menu, which often includes items like sandwiches, samosas, fries, and healthy bites. They are ideal for a quick break or a light meal, especially in busy areas like markets, schools, or office zones. Cleanliness, freshness, and affordability are key attractions of such shops.
        </p>
    </div>
    
    <div class="contact">
        <h3>Contact Us</h3>
        <p><strong>Address:</strong> Chennai Highways,Elavanasur kottai</p>
        <p><strong>Phone:</strong> 9874563210</p>
        <p><strong>Email:</strong> support@olalajuiceandsnacks.com</p>
        <p><strong>Working Hours:</strong> Mon-Fri: 8:00 AM - 6:00 PM, Sat: 9:00 AM - 3:00 PM</p>
    </div>
</div>
</body>
</html>
Imap3.html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>POST OFFICE</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: skyblue;
        }
        header {
            background-color: #2b6cb0;
            color: #fff;
            padding: 20px 10px;
            text-align: center;
        }
        .container {
            padding: 20px;
        }
        .image-container {
            text-align: center;
            margin-bottom: 20px;
        }
        .image-container img {
            max-width: 100%;
            height: auto;
            border-radius: 10px;
        }
        .description {
            font-size: 18px;
            line-height: 1.6;
            margin-bottom: 20px;
        }
        .contact-section {
            background-color: #e2e8f0;
            padding: 20px;
            border-radius: 10px;
        }
        .contact-section h2 {
            margin-top: 0;
        }
        .contact-section p {
            margin: 5px 0;
        }
        footer {
            text-align: center;
            padding: 10px;
            background-color: #2b6cb0;
            color: white;
            position: fixed;
            bottom: 0;
            width: 100%;
        }
    </style>
</head>
<body>

<header>
    <h1>ELAVANASUR POST OFFICE</h1>
</header>

<div class="container">
    <div class="image-container">
        <img src="post office.jpg" alt="Post Office">
    </div>

    <div class="description">
        <p>Post office is a government-operated facility that provides mail and parcel delivery services to the public. It also offers various other services such as selling stamps, money orders, and sometimes banking services. Post offices play a vital role in connecting people and businesses, especially in remote or rural areas. They are essential for the communication and logistical needs of a country. </p>
    </div>

    <div class="contact-section">
        <h2>Contact Us</h2>
        <p><strong>Address:</strong>Salem Main Road,Elavanasur Kottai</p>
        <p><strong>Phone:</strong>9654871202</p>
        <p><strong>Email:</strong> info@ekottaipostoffice.com</p>
        <p><strong>Office Hours:</strong> Monday to Friday, 9:00 AM - 2:00 PM</p>
    </div>
</div>
</body>
</html>
Imap4.html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>CENTRAL BANK OF INDIA</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: Arial, sans-serif;
            background-color:darkgrey;
            color: #333;
        }

        header {
            background-color: #333;
            color:darkgray;
            padding: 20px;
            display: flex;
            justify-content: space-between;
            align-items: center;
        }

        header .header-logo .logo {
            width: 150px;
        }

        header nav ul {
            list-style: none;
            display: flex;
        }

        header nav ul li {
            margin: 0 15px;
        }

        header nav ul li a {
            text-decoration: none;
            color:white;
            font-weight: bold;
        }

        header nav ul li a:hover {
            color: #ff6347;
        }

        
        main {
            padding: 20px;
            text-align: center;
        }
        .image-container img {
            max-width: 100%;
            height: auto;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
        }
        .description {
            margin-top: 20px;
            font-size: 1.2rem;
            line-height: 1.6;
        }
        .description {
            font-size: 18px;
            line-height: 1.6;
            margin-bottom: 20px;
        }
        .contact {
            background-color:darkgrey;
            padding: 40px;
            text-align: center;
            margin-top: 40px;
        }

        .contact ul {
            list-style: none;
            padding: 0;
        }

        .contact ul li {
            font-size: 18px;
            margin-bottom: 10px;
        }

        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 10px;
            margin-top: 50px;
        }

        footer p {
            font-size: 14px;
        }
    </style>
</head>

<body>
    <header>
        <h1>CENTRAL BANK OF INDIA</h1>
        <p>Your trusted financial service.</p>
    </header>
    <main>
        <div class="image-container">
          <img src="central bank.jpg" height="500" width="700">
        </div>
        <div class="description">
          <p>
            The Central Bank of India is one of the oldest and most prominent public sector banks in India, established in 1911. It offers a wide range of financial services, including savings and current accounts, loans, and investment options. Headquartered in Mumbai, the bank plays a key role in supporting the country’s economic development, especially through its focus on rural and small-scale sectors. As a government-owned bank, it ensures trust, stability, and accessibility for millions of customers across India.
          </p>
        </div>
      </main>
    <section id="contact" class="contact">
        <h2>Contact Us</h2>
        <p>If you have any questions or need assistance, feel free to get in touch with us:</p>
        <ul>
            <li><strong>Phone:</strong>9512365870</li>
            <li><strong>Email:</strong> support@cbi.com</li>
            <li><strong>Address:</strong>Durugam road,Elavanasur Kottai</li>
        </ul>
    </section>

    <!-- Footer Section -->
    <footer>
        <p>&copy; Central Bank of India.All rights reserved.</p>
    </footer>
</body>
</html>
Imap5.html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>SRI ARTHANAREERSWARAR TEMPLE</title>
    <style>
       * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: Arial, sans-serif;
            background-color:bisque;
            color: #333;
        }

        /* Header Section */
        header {
            background-color:crimson;
            color: white;
            padding: 20px;
            text-align: center;
        }

        header h1 {
            font-size: 36px;
            margin-bottom: 10px;
        }

        header p {
            font-size: 20px;
        }

        main {
            padding: 20px;
            text-align: center;
        }
        .image-container img {
            max-width: 100%;
            height: auto;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
        }
        .description {
            margin-top: 20px;
            font-size: 1.2rem;
            line-height: 1.6;
        }
        .contact {
            background-color:darksalmon;
            padding: 40px;
            text-align: center;
            margin-top: 40px;
        }

        .contact h2 {
            font-size: 28px;
            color: #e63946;
            margin-bottom: 20px;
        }

        .contact ul {
            list-style: none;
            padding: 0;
            font-size: 18px;
        }

        .contact ul li {
            margin-bottom: 10px;
        }

        /* Footer Section */
        footer {
            background-color:crimson;
            color: white;
            text-align: center;
            padding: 10px;
            margin-top: 50px;
        }

        footer p {
            font-size: 14px;
        }
    </style>
</head>
<body>
    <header>
        <h1>SRI ARTHANAREERSWARAR TEMPLE</h1>
    </header>
    <main>
        <div class="image-container">
          <img src="sivan koil.jpg" alt="Shivan Temple">
        </div>
        <div class="description">
          <p>
            Lord Shiva temple is a sacred place of worship dedicated to Lord Shiva, one of the principal deities in Hinduism. These temples often feature a Shiva Lingam as the central idol, symbolizing the god's divine energy and presence. Devotees visit to offer prayers, perform rituals like abhishekam (ritual bathing), and seek blessings for peace, strength, and prosperity. Many Shiva temples are known for their serene atmosphere, intricate architecture, and spiritual significance, especially during festivals like Maha Shivaratri.
          </p>
        </div>
      </main>
</body>
</html>
```

## OUTPUT
![alt text](<Screenshot 2025-05-01 215143.png>)

![alt text](<Screenshot 2025-05-01 215157.png>)

![alt text](<Screenshot 2025-05-01 215210.png>)

![alt text](<Screenshot 2025-05-01 215249.png>)

![alt text](<Screenshot 2025-05-01 215259.png>)

![alt text](<Screenshot 2025-05-01 215344.png>)

![alt text](<Screenshot 2025-05-01 215356.png>)

![alt text](<Screenshot 2025-05-01 215409.png>)

![alt text](<Screenshot 2025-05-01 215423.png>)

![alt text](<Screenshot 2025-05-01 215433.png>)

![alt text](<Screenshot 2025-05-01 215441.png>)




## RESULT
The program for implementing image maps using HTML is executed successfully.
