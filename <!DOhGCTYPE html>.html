<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Canvas Animation</title>
    <style>
        body, html {
            margin: 0;
            padding: 0;
            overflow: hidden; /* 确保不出现滚动条 */
        }
    </style>
</head>
<body>
    <script>
        // 获取canvas元素并设置尺寸
        const canvas = document.createElement('canvas');
        document.body.appendChild(canvas);
        canvas.width = window.innerWidth;
        canvas.height = window.innerHeight;

        const ctx = canvas.getContext('2d');

        // 设置球体属性
        const numberOfSpheres = 50;
        const spheres = [];

        // 创建球体对象
        for (let i = 0; i < numberOfSpheres; i++) {
            spheres.push({
                x: Math.random() * canvas.width,
                y: Math.random() * canvas.height,
                vx: (Math.random() - 0.5) * 2,
                vy: (Math.random() - 0.5) * 2,
                size: Math.random() * 20 + 5,
                color: `rgb(${Math.floor(Math.random() * 255)}, ${Math.floor(Math.random() * 255)}, ${Math.floor(Math.random() * 255)})`
            });
        }

        // 绘制球体
        function drawSphere(sphere) {
            ctx.beginPath();
            ctx.arc(sphere.x, sphere.y, sphere.size, 0, 2 * Math.PI);
            ctx.fillStyle = sphere.color;
            ctx.fill();
        }

        // 更新球体位置
        function updateSphere(sphere) {
            sphere.x += sphere.vx;
            sphere.y += sphere.vy;
            
            // 碰到边界就反弹
            if (sphere.x < 0 || sphere.x > canvas.width) sphere.vx *= -1;
            if (sphere.y < 0 || sphere.y > canvas.height) sphere.vy *= -1;
        }

        // 动画循环
        function animate() {
            ctx.clearRect(0, 0, canvas.width, canvas.height);
            spheres.forEach(sphere => {
                updateSphere(sphere);
                drawSphere(sphere);
            });
            requestAnimationFrame(animate);
        }

        // 开始动画
        animate();
    </script>
</body>
</html>
