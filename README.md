# CSS-7-
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>CSS基础样式第7题</title>
    <style>
        .div-index{
            width: 600px;
            margin: 0 auto;
        }
        .div-index>div{
            margin-top: 30px;
        }
        .p-ct{
            border: 1px solid #cccccc;
            border-radius: 3px;
            line-height: 1.5;
            padding: 1px 16px;
        }
        .p-ct.p2{
            border: none;
            background-color: #ffe7e7;
            border-left: 6px solid #f44336;
            border-right: 7px solid #f44336;
            border-radius: 0;
        }
        .p-ct.p3{
            border: none;
            background-color: #ffffd7;
            border-top: 6px solid #ffeb3b;
            border-bottom: 7px solid #ffeb3b;
            border-radius: 0;
        }
        .p-ct.p4{
            background-color: #e7ffe7;
            border:1px solid #4CAF50;
            border-bottom: 7px solid #4CAF50;
            border-radius: 0;
        }
    </style>
</head>
<body>
    <div class="div-index">
        <div class="p-ct">
            <p class="p1">在饥人谷是一个快乐的大家庭，在这里我会一步一步实现自己的梦想，加油2017，加油自己</p>
        </div>
        <div class="p-ct p2">
            <p class="p2">在饥人谷是一个快乐的大家庭，在这里我会一步一步实现自己的梦想，加油2017，加油自己</p>
        </div>
        <div class="p-ct p3">
            <p class="p3">在饥人谷是一个快乐的大家庭，在这里我会一步一步实现自己的梦想，加油2017，加油自己</p>
        </div>
        <div class="p-ct p4">
            <p class="p4">在饥人谷是一个快乐的大家庭，在这里我会一步一步实现自己的梦想，加油2017，加油自己</p>
        </div>
        
    </div>
</body>
</html>
```
