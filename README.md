<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>싸이월드 감성 깃허브</title>
    <style>
        body {
            margin: 0;
            font-family: 'Arial', sans-serif;
            background-color: #f8f8f8;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
        }
        .container {
            width: 800px;
            height: 600px;
            border: 5px solid #ccc;
            background-color: #ffffff;
            display: flex;
            flex-direction: row;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        }
        .sidebar {
            width: 200px;
            background-color: #eef3ff;
            border-right: 3px solid #ccc;
            padding: 10px;
            box-sizing: border-box;
        }
        .sidebar img {
            width: 100%;
            border-radius: 5px;
        }
        .menu {
            margin-top: 20px;
        }
        .menu a {
            display: block;
            text-decoration: none;
            color: #333;
            padding: 10px;
            margin-bottom: 5px;
            background-color: #f0f0f0;
            border: 1px solid #ddd;
            text-align: center;
            border-radius: 5px;
            font-size: 14px;
        }
        .menu a:hover {
            background-color: #dce6ff;
        }
        .content {
            flex: 1;
            padding: 20px;
            box-sizing: border-box;
        }
        .header {
            font-size: 18px;
            margin-bottom: 20px;
        }
        .pixel-content {
            width: 100%;
            height: 100%;
            background-image: url('https://via.placeholder.com/600x400');
            background-size: cover;
            border: 3px solid #ddd;
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="sidebar">
            <img src="https://via.placeholder.com/150" alt="Profile">
            <div class="menu">
                <a href="#">Home</a>
                <a href="#">Profile</a>
                <a href="#">Photo</a>
                <a href="#">Board</a>
                <a href="#">Visitor</a>
            </div>
        </div>
        <div class="content">
            <div class="header">👋 싸이월드 감성 소개</div>
            <div class="pixel-content">
                <!-- 여기에 콘텐츠 추가 -->
            </div>
        </div>
    </div>
</body>
</html>

