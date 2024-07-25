<!DOCTYPE html>
<html lang="vi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Trang cá nhân của Nguyễn</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
            width: 100%;
            height: 100%;
        }
        header {
            background: #333;
            color: #fff;
            padding: 20px 0;
            text-align: center;
        }
        nav {
            display: flex;
            justify-content: center;
            background: #444;
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
        }
        nav a {
            color: #fff;
            padding: 14px 20px;
            text-decoration: none;
            text-transform: uppercase;
            letter-spacing: 1px;
        }
        nav a:hover {
            background: #555;
        }
        .container {
            max-width: 1100px;
            margin: auto;
            padding: 20px;
        }
        .container > section {
            margin-bottom: 20px;
            background: #fff;
            padding: 20px;
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
        }
        .container > section h2 {
            margin-top: 0;
        }
        footer {
            background: #333;
            color: #fff;
            text-align: center;
            padding: 10px 0;
            position: fixed;
            bottom: 0;
            width: 100%;
            box-shadow: 0 -2px 4px rgba(0, 0, 0, 0.1);
        }
        @media (max-width: 768px) {
            nav {
                flex-direction: column;
            }
            nav a {
                padding: 10px;
                text-align: center;
            }
        }
    </style>
</head>
<body>
    <header>
        <h1>Trang cá nhân của Nguyễn</h1>
    </header>
    <nav>
        <a href="#home">Trang Chủ</a>
        <a href="#about">Giới Thiệu</a>
        <a href="#projects">Dự Án</a>
        <a href="#contact">Liên Hệ</a>
    </nav>
    <div class="container">
        <section id="home">
            <h2>Chào mừng đến với trang cá nhân của tôi</h2>
            <p>Đây là nơi tôi chia sẻ về bản thân và những dự án tôi đã thực hiện.</p>
        </section>
        <section id="about">
            <h2>Giới Thiệu</h2>
            <p>Xin chào, tôi là Nguyễn. Tôi là một người đam mê công nghệ và yêu thích anime. Tôi cũng sắp có một bé gái.</p>
        </section>
        <section id="projects">
            <h2>Dự Án</h2>
            <ul>
                <li>Dự án 1: Thiết kế website cá nhân</li>
                <li>Dự án 2: Ứng dụng quản lý công việc</li>
                <li>Dự án 3: Phân tích dữ liệu với Python</li>
            </ul>
        </section>
        <section id="contact">
            <h2>Liên Hệ</h2>
            <p>Bạn có thể liên hệ với tôi qua email: nguyen@example.com</p>
        </section>
    </div>
    <footer>
        <p>&copy; 2024 Nguyễn. All rights reserved.</p>
    </footer>
</body>
</html>
