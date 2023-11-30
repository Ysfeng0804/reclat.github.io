
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>R'eclat</title>
    <link href="https://fonts.googleapis.com/css?family=Roboto&display=swap" rel="stylesheet">
    <link href="https://fonts.googleapis.com/css?family=Roboto+Condensed&display=swap" rel="stylesheet">
    <link rel="stylesheet" type="text/css" href="style.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css" crossorigin="anonymous">
    <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.5.1/jquery.min.js"></script>
</head>
<body>

    <script>
    $(document).ready(function(){
        // 用于切换导航的显示和隐藏
        $("#nav-icon").click(function() {
            $("#mobile-nav").slideToggle("slow");
        });

        // 检测窗口resize事件
        $(window).resize(function() {
            // 如果窗口宽度大于1024
            if ($(window).width() > 800) {
            // 确保导航可见
            $("#main-nav").show();
            }
        });
    });
    </script>

    <header id="home">
        <h1>R'eclat</h1>
        <p class="subtitle">Timeless Jewelry Creations</p>

        <!-- 添加新的导航按钮 -->
        <div id="nav-icon">
            <i class="fa-solid fa-bars"></i>
        </div>

        <!-- 添加新的导航按钮 -->
        <div id="mobile-nav">
            <div> <a href="#home">Home</a></div>
            <div> <a href="#about">About</a></div>
            <div> <a href="#vision">Vision</a></div>
            <div> <a href="#mission">Mission</a></div>
            <div> <a href="#collections">Collections</a></div>
            <div> <a href="#custom-design">Custom Design</a></div>
            <div> <a href="#digital-presence">Digital Presence</a></div>
            <div> <a href="#contact">Contact</a></div>
        </div>

    </header>

    <nav id="main-nav">
        <a href="#home">Home</a>
        <a href="#about">About</a>
        <a href="#vision">Vision</a>
        <a href="#mission">Mission</a>
        <a href="#collections">Collections</a>
        <a href="#custom-design">Custom Design</a>
        <a href="#digital-presence">Digital Presence</a>
        <a href="#contact">Contact</a>
    </nav>

    <main>
        <section id="about" class="container">
            <h2>Welcome to R'eclat</h2>
            <p>R'eclat, headquartered in the vibrant city of Singapore, is renowned for its exceptional craftsmanship in creating elegant, timeless, and high-quality jewelry pieces. Our dedicated team of skilled designers and artisans seamlessly blend traditional and contemporary techniques to forge distinctive masterpieces that embody the quintessence of beauty, luxury, and sophistication.</p>
            <p>Our exquisite collections encompass a diverse array of precious materials, ranging from the alluring sparkle of carefully selected diamonds to the rich hues of ethically-sourced gemstones. We take immense pride in offering a wide variety of designs that cater to the unique tastes and preferences of our discerning clientele. At R'eclat, we believe that the perfect piece of jewelry has the power to elevate any occasion, be it a momentous celebration or an intimate expression of love.</p>
            <p>As you embark on a journey through our carefully curated collections, prepare to be captivated by the unparalleled artistry and attention to detail that radiate from each R'eclat creation. With a relentless pursuit of excellence, we strive to exceed your expectations and deliver a truly personalized and luxurious experience that will leave you longing for more.</p>
            <p>Discover the world of R'eclat, where the fusion of tradition and innovation culminates in an unforgettable symphony of elegance, refinement, and unparalleled craftsmanship.</p>
        </section>

        <section id="vision" class="container">
            <h2>Our Vision</h2>
            <p>To redefine luxury by weaving personal stories and unparalleled craftsmanship into every piece of jewelry, R'eclat creates not just ornaments but timeless symbols of individuality and passion. Each design is an intricate tapestry of memories and dreams, meticulously crafted to capture the essence of the wearer's unique journey. Our master artisans blend age-old techniques with contemporary innovation, infusing every gemstone and metal with a soulful narrative. At R'eclat, luxury is more than opulence; it's a personal and intimate experience, where every shimmering piece tells a story, your story.</p>
        </section>

        <section id="mission" class="container">
            <div>
                <h2>Our Mission</h2>
                <p>R’éclat is dedicated to curating a uniquely personal journey for each customer, transforming their individual visions and deepest emotions into wearable art that not only stands the test of time but also resonates with their innermost self. Our approach intertwines the personal narratives and aspirations of our clients with the exemplary skill of our artisans, creating pieces that are not merely jewelry, but deeply meaningful expressions of one’s personal story and identity. In every curve, gemstone, and brush of metal, R’éclat captures the essence of moments and memories, crafting heirlooms that transcend mere fashion to become timeless treasures, intimately connected to the wearer's life and legacy.</p>
            </div>
        </section>

        <section id="collections" class="container">
            <h2>Featured Collection</h2>
            <div class="gallery">
                <div class="gallery-item">
                    <img src="images/product1.jpg" alt="Product 1">
                    <p>Product 1</p>
                </div>
                <div class="gallery-item">
                    <img src="images/product2.jpg" alt="Product 2">
                    <p>Product 2</p>
                </div>
                <div class="gallery-item">
                    <img src="images/product3.jpg" alt="Product 3">
                    <p>Product 3</p>
                </div>
                <div class="gallery-item">
                    <img src="images/product4.jpg" alt="Product 4">
                    <p>Product 4</p>
                </div>
                <div class="gallery-item">
                    <img src="images/product5.jpg" alt="Product 5">
                    <p>Product 5</p>
                </div>
                <div class="gallery-item">
                    <img src="images/product6.jpg" alt="Product 6">
                    <p>Product 6</p>
                </div>
                <div class="gallery-item">
                    <img src="images/product7.jpg" alt="Product 7">
                    <p>Product 7</p>
                </div>
                <div class="gallery-item">
                    <img src="images/product8.jpg" alt="Product 8">
                    <p>Product 8</p>
                </div>
                <div class="gallery-item">
                    <img src="images/product9.jpg" alt="Product 9">
                    <p>Product 9</p>
                </div>
                <div class="gallery-item">
                    <img src="images/product10.jpg" alt="Product 10">
                    <p>Product 10</p>
                </div>
                <div class="gallery-item">
                    <img src="images/product11.jpg" alt="Product 11">
                    <p>Product 11</p>
                </div>
                <div class="gallery-item">
                    <img src="images/product12.jpg" alt="Product 12">
                    <p>Product 12</p>
                </div>
            </div>
        </section>

        <section id="custom-design" class="container">
            <h2>Custom Design Services</h2>
            <div class="custom-design-container">
                <p>At R'eclat, we offer custom design services to create personalized jewelry pieces tailored to your unique style and taste. Our experienced artisans use their craftsmanship and expertise to bring your vision to life by selecting the finest materials and using innovative design techniques.</p>
                <p>To take advantage of our custom design services and receive a one-of-a-kind piece of jewelry, follow these simple steps:</p>
                <ol>
                    <li>Contact us to schedule a consultation with our designers.</li>
                    <li>Share your vision, preferences, and budget during the consultation.</li>
                    <li>Our designers will create a design sketch and provide a price quote for your approval.</li>
                    <li>Upon approval, we will create your custom piece using the highest quality materials and craftsmanship.</li>
                </ol>
                <p>Start your journey to exceptional style by creating a unique piece of jewelry that reflects your personality and showcases your individuality. For more information or to schedule a consultation, please <a href="#contact">contact us</a>.</p>
            </div>
        </section>

        <section id="digital-presence" class="container">
            <h2>Digital Presence</h2>
            <p>Recognizing the importance of digital connectivity in today’s world, R’éclat provides an online platform...</p>
        </section>

        <section id="contact" class="container">
            <h2>Contact Us</h2>
            <p>If you have any questions or concerns, please feel free to reach out by filling out the form below:</p>
            <div class="contact-container">
                <form class="contact-form" action="#" method="POST">
                    <input type="text" name="name" placeholder="Your name" required>
                    <input type="email" name="email" placeholder="Your email" required>
                    <textarea name="message" rows="6" cols="40" placeholder="Your message" required></textarea>
                    <input type="submit" value="Send Message">
                </form>
            </div>
            <p>Alternatively, you can also email us at: <a href="mailto:info@reclat.co">info@reclat.co</a></p>
        </section>
    </main>

    <footer>
        <!-- 添加带图标的按钮组 -->
        <div class="btn-group">
            <a href="https://www.facebook.com/" target="_blank"><i class="fab fa-facebook-f"></i></a>
            <a href="https://www.twitter.com/" target="_blank"><i class="fab fa-twitter"></i></a>
            <a href="https://www.instagram.com/" target="_blank"><i class="fab fa-instagram"></i></a>
        </div>
        &copy; R'eclat, 2023. All Rights Reserved.
    </footer>
</body>
</html>