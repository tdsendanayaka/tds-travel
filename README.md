# tds-travel<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>TDs Travel & Tours</title>
    <style>
        body {
            background-color: #0e0e0e;
            color: #ffffff;
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
        }
        header {
            text-align: center;
            padding: 50px 20px 20px 20px;
        }
        header h1 {
            color: #00bcd4;
            font-size: 2.5em;
            margin-bottom: 10px;
        }
        section {
            max-width: 800px;
            margin: 0 auto;
            padding: 20px;
            background: #1c1c1c;
            border-radius: 10px;
            box-shadow: 0 0 15px rgba(0, 188, 212, 0.2);
        }
        h2 {
            color: #00bcd4;
        }
        .comment-section {
            margin-top: 40px;
            padding: 20px;
            background: #141414;
            border-radius: 10px;
            box-shadow: 0 0 10px rgba(255,255,255,0.1);
        }
        footer {
            text-align: center;
            padding: 30px 0;
            color: #777;
        }
    </style>
</head>
<body>
    <header>
        <h1>TDs Travel & Tours</h1>
        <p>Welcome to my personal travel space!</p>
    </header>

    <section id="about">
        <h2>About TDs Travel</h2>
        <p>Hello! I’m Tharindu Dhananjaya, the creator behind TDs Travel & Tours — your one-stop destination for handcrafted travel accessories, inspiring destinations, and unforgettable travel stories.</p>
        <p>Follow my journey, explore creative handmade bags, and get inspired to travel more with style!</p>
    </section>

    <!-- 🗨️ Facebook Comment Section -->
    <section class="comment-section">
        <h2>💬 Leave a Comment (via Facebook)</h2>
        <p>Login with Facebook to share your thoughts and connect with TDs Travel community!</p>

        <!-- Facebook SDK -->
        <div id="fb-root"></div>
        <script async defer crossorigin="anonymous"
            src="https://connect.facebook.net/en_US/sdk.js#xfbml=1&version=v18.0" nonce="ABC123">
        </script>

        <!-- Comment Plugin -->
        <div class="fb-comments"
            data-href="https://tdsendanayaka.github.io/tds-travel/"
            data-width="100%"
            data-numposts="5"
            data-colorscheme="dark">
        </div>
    </section>

    <footer>
        <p>© 2025 TDs Travel & Tours | Designed by Tharindu Dhananjaya</p>
    </footer>
</body>
</html>
