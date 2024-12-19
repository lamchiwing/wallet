<!DOCTYPE html>
<html lang="zh-HK">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>周數</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f9f9f9;
        }
        header {
            background-color: #f9f9f9;
            color: white;
            padding: 10px 20px;
            text-align: center;
        }
        .menu {
            margin: 20px;
            text-align: right;
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
        <h1>數據足球</h1>
    </header>

     <div class="menu">
        <h2>選擇周數</h2>
        <div class="dropdown">
            <button>Matchweek</button>
            <div class="dropdown-content">
                <a href="#" onclick="showContent(5)">第5周 (21 Sep - 23 Sep)</a>
                <a href="#" onclick="showContent(6)">第6周 (28 Sep - 01 Oct)</a>
                <a href="#" onclick="showContent(7)">第7周 (05 Oct - 07 Oct)</a>
                <a href="#" onclick="showContent(8)">第8周 (19 Oct - 22 Oct)</a>
                <a href="#" onclick="showContent(9)">第9周 (26 Oct - 28 Oct)</a>  
                <a href="#" onclick="showContent(10)">第10周 (01 Nov - 05 Nov)</a>
                <a href="#" onclick="showContent(11)">第11周 (10 Nov - 11 Nov)</a>
                <a href="#" onclick="showContent(12)">第12周 (23 Nov - 26 Nov)</a>
                <a href="#" onclick="showContent(13)">第13周 (30 Nov - 02 Dec)</a>
                <a href="#" onclick="showContent(14)">第14周 (03 Dec - 05 Dec)</a>
                <a href="#" onclick="showContent(15)">第15周 (07 Dec - 09 Dec)</a>
                <a href="#" onclick="showContent(16)">第16周 (14 Dec - 16 Dec)</a>
                <a href="#" onclick="showContent(17)">第17周 (21 Dec - 22 Dec)</a>
            </div>
        </div>
    </div>
</body>
</html>
