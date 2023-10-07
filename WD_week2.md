<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="styles.css">
    <title>Blog Page</title>
</head>
<body>
    <header>
        <h1>Welcome to Motion Cut</h1>
    </header>
    
    <!-- Blog Post 1: Mobile -->
    <article class="blog-post">
        <h2>Mobile</h2>
        <img src="C:\Users\vamsi\Desktop\Iphone.jpg" alt="Mobile Image">
        <h2>Description</h2>
       <p class="description">
            Mobile phones have become an indispensable part of our lives. They offer seamless communication, high-resolution displays, powerful processors, and versatile cameras. In this blog post, we explore the latest mobile phone trends and features.
        </p>
        <a href="#" class="download-button">Free Download</a>
    </article>

    <!-- Blog Post 2: Ice Cream -->
    <article class="blog-post">
        <h2>Ice Cream</h2>
        <img src="C:\Users\vamsi\Desktop\Ice.jpg" alt="Ice Cream Image">
         <h2>Description</h2>
        <p class="description">
            Ice cream is a delightful treat loved by people of all ages. In this blog post, we dive into the world of ice cream, from classic flavors to unique recipes. Join us in exploring the sweet and creamy world of ice cream!
        </p>
        <a href="#" class="download-button">Free Download</a>
    </article>
    
    <section class="testimonials">
        <h2>Review</h2>
        
        <div class="testimonial">
            <h3>Keerthi</h3>
            <p>
                "I loved the Mobile blog post! It provided valuable insights about the latest mobile phones."
            </p>
        </div>
        
        <div class="testimonial">
            <h3>Kartheek</h3>
            <p>
                "The Ice Cream blog post had amazing ice cream recipes. I can't wait to try them all!"
            </p>
        </div>
    </section>
</body>
</html
{
    margin: 0;
    padding: 0;
}

{
    text-align: center;
    background-color: #007bff;
    padding: 20px;
    color: #fff;
}

h1 {
    font-size: 28px;
}

{
    margin: 20px;
    padding: 20px;
    background-color: #f0f0f0;
    border: 1px solid #ccc;
    border-radius: 5px;
    text-align: center;
}

h2 {
    font-size: 24px;
}

img {
    max-width: 100%;
    height: auto;
    margin: 20px 0;
}

.description {
    font-size: 16px;
    margin-bottom: 20px;
}
{
    display: inline-block;
    padding: 10px 20px;
    background-color: #007bff;
    color: #fff;
    text-decoration: none;
    border-radius: 5px;
    transition: background-color 0.3s ease-in-out;
}

.download-button:hover {
    background-color: #0056b3;
}

 {
    margin: 20px;
    padding: 20px;
    background-color: #f0f0f0;
    border: 1px solid #ccc;
    border-radius: 5px;
    text-align: center;
}

h3 {
    font-size: 18px;
    margin-bottom: 10px;
}

.testimonial p {
    font-size: 16px;
    margin-bottom: 20px;
}
