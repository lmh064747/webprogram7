<!DOCTYPE html>
<html lang="ko">
<head>
    <meta charset="UTF-8">
    <title>Layout Practice</title>
    <style>
        * { margin: 0; padding: 0; }
        body { font-family: sans-serif; }

        .container {
            width: 1080px;
            margin: 0 auto;
            overflow: hidden;
        }

        header.container {
            padding: 20px 0;
        }

        .nav-wrapper {
            border-top: 1px solid #e4e7e8;
            border-bottom: 1px solid #e4e7e8;
            margin-bottom: 8px;
        }

        .gnb {
            float: left;
            list-style: none;
            padding: 8px 10px;
            background-color: #1a5d1a;
            color: white;
            font-size: 12px;
        }

        .gnb li {
            float: left;
            padding: 0 5px;
        }

        .rank {
            float: right;
            list-style: none;
            padding: 8px 10px;
            background-color: #ffff00;
            font-size: 12px;
            font-weight: bold;
        }

        .content-area {
            margin-bottom: 8px;
        }

        .left {
            float: left;
            width: 740px;
            height: 428px;
            background-color: red;
        }

        .right {
            float: right;
            width: 332px;
            height: 428px;
            background-color: blue;
        }

        .footer {
            height: 80px;
            background-color: yellow;
            clear: both;
        }
    </style>
</head>
<body>

    <header class="container">
        <h1>Logo</h1>
    </header>

    <div class="container nav-wrapper">
        <ul class="gnb">
            <li>메일</li>
            <li>카페</li>
            <li>블로그</li>
            <li>쇼핑</li>
            <li>사전</li>
            <li>뉴스</li>
            <li>증권</li>
            <li>부동산</li>
            <li>지도</li>
        </ul>
        <ul class="rank">
            <li>실시간 검색 순위</li>
        </ul>
    </div>

    <div class="container content-area">
        <div class="left"></div>
        <div class="right"></div>
    </div>

    <div class="container">
        <div class="footer"></div>
    </div>

</body>
</html>
