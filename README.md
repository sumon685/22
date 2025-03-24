# 22
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Eid Mubarak Animation</title>
    <style>
        body {
            background-color: #f8f8f8;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            flex-direction: column;
        }
        h1 {
            font-size: 2rem;
            color: #28a745;
        }
    </style>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/lottie-web/5.9.6/lottie.min.js"></script>
</head>
<body>
    <h1>🌙✨ Eid Mubarak! ✨🌙</h1>
    <div id="animation-container" style="width: 300px; height: 300px;"></div>
    
    <script>
        lottie.loadAnimation({
            container: document.getElementById('animation-container'),
            renderer: 'svg',
            loop: true,
            autoplay: true,
            path: 'https://assets10.lottiefiles.com/packages/lf20_hvwncszg.json' // ঈদ এনিমেশন লিংক
        });
    </script>
</body>
</html>
