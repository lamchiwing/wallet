<!DOCTYPE html>
<html lang="zh-HK">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>God Save The Wallet</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f9f9f9;
        }
        header {
            background-color: #222;
            color: white;
            padding: 10px 20px;
            text-align: center;
        }
        .menu {
            margin: 20px;
            text-align: center;
        }
        .dropdown {
            position: relative;
            display: inline-block;
        }
        .dropdown-content {
            display: none;
            position: absolute;
            background-color: #fff;
            box-shadow: 0 8px 16px rgba(0,0,0,0.2);
            min-width: 160px;
            z-index: 1;
        }
        .dropdown-content a {
            color: black;
            padding: 10px 15px;
            text-decoration: none;
            display: block;
        }
        .dropdown-content a:hover {
            background-color: #f1f1f1;
        }
        .dropdown:hover .dropdown-content {
            display: block;
        }
    </style>
</head>
<body>
    <header>
        <h1>God Save The Wallet</h1>
    </header>

    <div class="menu">
        <h2>Change Matchweek</h2>
        <div class="dropdown">
            <button>Matchweek 4</button>
            <div class="dropdown-content">
                <a href="#">第1周 (14 Sep - 15 Sep)</a>
                <a href="#">第2周 (21 Sep - 22 Sep)</a>
                <a href="#">第3周 (28 Sep - 29 Sep)</a>
                <a href="#">第4周 (5 Oct - 6 Oct)</a>
                <!-- Add more weeks as necessary -->
                <a href="#">第38周</a>
            </div>
        </div>
        <p>Fan Polls</p>
    </div>
</body>
</html>
