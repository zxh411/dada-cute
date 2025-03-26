<!DOCTYPE html>
<html lang="zh-CN">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>见面邀请</title>
    <style>
        /* 保持之前的CSS样式不变 */
    </style>
</head>
<body>
    <div class="container">
        <a href="#meeting" class="meeting-link">要见面吗？</a>
    </div>
    
    <!-- 可选添加JavaScript交互 -->
    <script>
        document.querySelector('.meeting-link').addEventListener('click', function(e) {
            e.preventDefault();
            const responses = ["好啊！", "什么时候？", "在哪里？"];
            alert(responses[Math.floor(Math.random() * responses.length)]);
        });
    </script>
</body>
</html>