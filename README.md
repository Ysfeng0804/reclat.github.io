<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>R'eclat</title>
    <link href="https://fonts.googleapis.com/css?family=Roboto&display=swap" rel="stylesheet">
    <link href="https://fonts.googleapis.com/css?family=Roboto+Condensed&display=swap" rel="stylesheet">
    <link rel="stylesheet" type="text/css" href="style.css">
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
        <p>Timeless Jewelry Creations</p>

        <!-- 添加新的导航按钮 -->
        <div id="nav-icon">
            <img src="menu-icon.png" alt="Menu Icon"/> <!-- 使用你想要的菜单icon -->
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
        <section id="about">
            <h2>Welcome to R'eclat</h2>
            <p>R'eclat, based in Singapore, specializes in crafting elegant, timeless, and high-quality jewelry pieces. Our passionate designers use both classic and modern techniques, creating unique masterpieces that capture the essence of beauty and sophistication.</p>
            <p>From shimmering diamonds to vibrant gemstones, our thoughtfully curated collections cater to your individual style, ensuring that you find the perfect jewelry for every occasion. Explore our offerings and indulge in the artistry of R'eclat.</p>
        </section>

        <section id="vision">
            <h2>Our Vision</h2>
            <p>To redefine luxury by weaving personal stories and unparalleled craftsmanship into every piece of jewelry.</p>
        </section>

        <section id="mission">
            <h2>Our Mission</h2>
            <p>R’éclat is committed to curating a personal journey for each customer, transforming their visions and emotions into wearable art that stands the test of time.</p>
        </section>

        <section id="collections">
            <h3>Featured Collection</h3>
            <div class="gallery">
                <div class="gallery-item">
                    <img src="images/product1.png" alt="Product 1">
                    <p>Product 1</p>
                </div>
                <div class="gallery-item">
                    <img src="images/product2.png" alt="Product 2">
                    <p>Product 2</p>
                </div>
                <div class="gallery-item">
                    <img src="images/product3.png" alt="Product 3">
                    <p>Product 3</p>
                </div>
                <div class="gallery-item">
                    <img src="images/product4.png" alt="Product 4">
                    <p>Product 4</p>
                </div>
                <div class="gallery-item">
                    <img src="images/product5.png" alt="Product 5">
                    <p>Product 5</p>
                </div>
                <div class="gallery-item">
                    <img src="images/product6.png" alt="Product 6">
                    <p>Product 6</p>
                </div>
                <div class="gallery-item">
                    <img src="images/product7.png" alt="Product 7">
                    <p>Product 7</p>
                </div>
                <div class="gallery-item">
                    <img src="images/product8.png" alt="Product 8">
                    <p>Product 8</p>
                </div>
                <div class="gallery-item">
                    <img src="images/product9.png" alt="Product 9">
                    <p>Product 9</p>
                </div>
                <div class="gallery-item">
                    <img src="images/product10.png" alt="Product 10">
                    <p>Product 10</p>
                </div>
            </div>
        </section>

        <section id="custom-design">
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

        <section id="digital-presence">
            <h2>Digital Presence</h2>
            <p>Recognizing the importance of digital connectivity in today’s world, R’éclat provides an online platform...</p>
        </section>

        <section id="contact">
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
            <p>Alternatively, you can also email us at: <a href="mailto:info@example.com">info@example.com</a></p>
        </section>
    </main>

    <footer>
        &copy; R'eclat, 2022. All Rights Reserved.
    </footer>
</body>
</html>
