
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Vel syergen solution & services
</title>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@300;400;500;600;700&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Montserrat', sans-serif;
            margin: 0;
            padding: 0;
            line-height: 1.7;
            color: #333;
        }
        header {
            background: linear-gradient(135deg, #2c3e50, #34495e);
            color: white;
            text-align: center;
            padding: 3rem 0;
        }
        header h1 {
            margin-bottom: 0.5rem;
            font-weight: 600;
        }
        .container {
            max-width: 1200px;
            margin: 3rem auto;
            padding: 0 2rem;
        }
        .services-solutions {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 2rem;
            margin-bottom: 3rem;
        }
        .service-box {
            background: #fff;
            padding: 2rem;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            transition: transform 0.3s ease, box-shadow 0.3s ease;
            text-align: center;
        }
        .service-box:hover {
            transform: translateY(-8px);
            box-shadow: 0 6px 12px rgba(0, 0, 0, 0.15);
        }
        .service-box img {
            max-width: 100px;
            margin-bottom: 1.5rem;
            border-radius: 50%;
        }
        .service-box h3 {
            margin-bottom: 1rem;
            color: #2c3e50;
            font-weight: 500;
        }
        .about-us {
            margin-bottom: 3rem;
        }
        .about-us h2 {
            margin-bottom: 1.5rem;
            color: #2c3e50;
            font-weight: 600;
        }
        .about-us p {
            margin-bottom: 1.5rem;
        }
        .callback-section {
            background: #f4f4f4;
            padding: 3rem;
            border-radius: 10px;
        }
        .callback-section h2 {
            margin-bottom: 2rem;
            color: #2c3e50;
            font-weight: 600;
        }
        .callback-form label, .callback-form input, .callback-form textarea, .callback-form button {
            display: block;
            margin-bottom: 1rem;
            width: 100%;
            box-sizing: border-box;
        }
        .callback-form input, .callback-form textarea {
            padding: 1rem;
            border: 1px solid #ddd;
            border-radius: 5px;
        }
        .callback-form button {
            background: #2c3e50;
            color: white;
            padding: 1.2rem;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            transition: background 0.3s ease;
            font-weight: 500;
        }
        .callback-form button:hover {
            background: #34495e;
        }
        footer {
            background-color: #2c3e50;
            color: white;
            text-align: center;
            padding: 1.5rem 0;
        }
    </style>
</head>
<body>
    <header>
        <h1>Vel syergen solution & services</h1>
        <p>Your Innovative Solutions for a Better Future</p>
    </header>
    <div class="container">
        <section class="services-solutions">
            <div class="service-box">
                <img src="" alt=""en">
         <h3>Business  1</h3>
                <p>Detailed description of your first service and its benefits.</p>
            </div>
            <div class="service-box">
                <img src="service2.jpg" alt="Serice 2">
                <h3>Individuals 2</h3>
                <p>Detailed description of your second service and its benefits.</p>
            </div>
            <div class="service-box">
                              <img src="solution1.jpg" alt="Solution 1">

                <h3>Store & shop 1</h3>
                <p>Detailed description of your first solution and its benefits.</p>
            </div>
            <div class="service-box">
                <img src="solution2.jpg" alt="Solution 2">
                <h3>Solution 2</h3>
                <p>Detailed description of your second solution and its benefits.</p>
            </div>
        </section>
        <section class="about-us">
            <h2>About Us</h2>
            <p>Vel Syergen Solutions & Service: Your Partner for Growth & Efficiency.</p>
We empower businesses and individuals with comprehensive solutions, from strategic development to daily essentials. For businesses, we offer expert guidance in business development, management, analytics, and logistics, ensuring seamless operations from startup to scale. Our specialized services include research & development, office setup, and stock management.</p>
For individuals, we provide reliable home essential services, including vehicle maintenance, electronics repair, and personalized project support. We streamline your life with efficient scheduling and management.</p>
Vel Syergen delivers tailored solutions, driving your success with expertise and dedication.
            .</p>
            <p>Discover how we can help you achieve your goals and transform your vision into reality. Contact us today to learn more.</p>
        </section>
        <section class="callback-section">
            <h2>Request a Callback or Services</h2>
            <form action="/submit-form" method="post" class="callback-form">
                <label for="name">Name:</label>
                <input type="text" id="name" name="name" required>
                <label for="email">Email:</label>
                <input type="email" id="email" name="email" required>
                <label for="phone">Phone:</label>
                <input type="tel" id="phone" name="phone" required>
                <label for="message">Message/Services Needed:</label>
                <textarea id="message" name="message" rows="5" required></textarea>
                <button type="submit">Submit Request</button>
            </form>
        </section>
    </div>
    <footer>
        <p>&copy; 2024 Your Business Name. All rights reserved
        
        velsynergysolutions@gmail.com <P>
             </p>
    </footer>
    <script>
        //Optional Javascript to handle the form submission.
        //Note: you will need backend code to process the form data.
        const form = document.querySelector(".callback-form")
        form.addEventListener('submit', (event) => {
            //prevent the default submission.
            event.preventDefault();
            //Here, you would add code to send the data to your server.
            alert("Form Submitted! (This is a placeholder, you'll need backend code)");
            form.reset();
        });
    </script>
</bo
