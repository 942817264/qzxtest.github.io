<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>圣杯布局test</title>
    <!-- 1.两边固定,当中自适应
    2.当中列要完整显示
    3.当中列要优先加载 -->
    <style>
        body
        {
            width: 100%;
            height: 100%;
        }
        main
        {
            width: 100%;
            height: 60%;
            background-color: aqua;
        }
        header
        {
            width: 100%;
            height: 20%;
            background-color: gray;
        }
        footer
        {
            height: 20%;
            background-color: gray;
        }
        main
        {
            display: flex;
            
        }
        .left
        {
            background-color: brown;
            /* min-width: 200px; */
            width: 20%;
        }
        .middle
        {
            background-color: rgb(98, 87, 87);
           /* flex: 1; */
           /* width: 80%; */
        }
        .right
        {
            background-color: blue;
            /* min-width: 200px; */
            width: 20%;
        }

    </style>
</head>

<body>
<header>我是头部</header> 
<main>
    <section class="left">left</section>
    <section class="middle">middle</section>
    <section class="right">right</section>
</main>
<footer> 我是底部</footer> 
</body>
</html>
