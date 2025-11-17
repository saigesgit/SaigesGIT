<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Bold & Colorful Test Site</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        
        body {
            font-family: 'Arial Black', Arial, sans-serif;
            background: linear-gradient(135deg, #667eea 0%, #764ba2 25%, #f093fb 50%, #4facfe 75%, #00f2fe 100%);
            min-height: 100vh;
            display: flex;
            flex-direction: column;
            align-items: center;
            padding: 20px;
        }
        
        header {
            background: linear-gradient(45deg, #ff6b6b, #feca57);
            padding: 30px;
            border-radius: 20px;
            margin-bottom: 30px;
            box-shadow: 0 10px 30px rgba(0,0,0,0.3);
            text-align: center;
            width: 100%;
            max-width: 800px;
        }
        
        h1 {
            color: white;
            font-size: 3em;
            text-shadow: 3px 3px 6px rgba(0,0,0,0.5);
            letter-spacing: 2px;
        }
        
        .content {
            background: rgba(255, 255, 255, 0.95);
            padding: 40px;
            border-radius: 20px;
            box-shadow: 0 15px 40px rgba(0,0,0,0.3);
            max-width: 800px;
            width: 100%;
        }
        
        h2 {
            color: #ff6b6b;
            font-size: 2em;
            margin-bottom: 20px;
            text-transform: uppercase;
        }
        
        p {
            font-size: 1.2em;
            line-height: 1.8;
            color: #333;
            margin-bottom: 20px;
            font-weight: bold;
        }
        
        .button-container {
            display: flex;
            gap: 20px;
            margin-top: 30px;
            flex-wrap: wrap;
            justify-content: center;
        }
        
        button {
            padding: 15px 30px;
            font-size: 1.2em;
            font-weight: bold;
            border: none;
            border-radius: 50px;
            cursor: pointer;
            transition: transform 0.2s, box-shadow 0.2s;
            text-transform: uppercase;
            letter-spacing: 1px;
        }
        
        .btn-red {
            background: linear-gradient(135deg, #ff6b6b, #ee5a6f);
            color: white;
        }
        
        .btn-green {
            background: linear-gradient(135deg, #48c6ef, #6f86d6);
            color: white;
        }
        
        .btn-yellow {
            background: linear-gradient(135deg, #feca57, #ff9ff3);
            color: white;
        }
        
        button:hover {
            transform: translateY(-3px);
            box-shadow: 0 10px 25px rgba(0,0,0,0.3);
        }
        
        .color-boxes {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(150px, 1fr));
            gap: 20px;
            margin-top: 30px;
        }
        
        .box {
            height: 150px;
            border-radius: 15px;
            display: flex;
            align-items: center;
            justify-content: center;
            color: white;
            font-size: 1.5em;
            font-weight: bold;
            text-shadow: 2px 2px 4px rgba(0,0,0,0.3);
            box-shadow: 0 5px 15px rgba(0,0,0,0.2);
        }
        
        .box1 { background: linear-gradient(135deg, #f093fb, #f5576c); }
        .box2 { background: linear-gradient(135deg, #4facfe, #00f2fe); }
        .box3 { background: linear-gradient(135deg, #43e97b, #38f9d7); }
        .box4 { background: linear-gradient(135deg, #fa709a, #fee140); }
    </style>
</head>
<body>
    <header>
        <h1>🎨 TEST WEBSITE 🎨</h1>
    </header>
    
    <div class="content">
        <h2>Welcome to the Bold & Colorful Zone!</h2>
        <p>This is a test website with vibrant colors and bold typography. Everything here is designed to catch your eye and make an impact!</p>
        <p>Click the buttons below to test interactivity:</p>
        
        <div class="button-container">
            <button class="btn-red" onclick="alert('🔴 Red Button Clicked!')">Click Me!</button>
            <button class="btn-green" onclick="alert('🔵 Blue Button Clicked!')">Press Here!</button>
            <button class="btn-yellow" onclick="alert('🟡 Yellow Button Clicked!')">Touch This!</button>
        </div>
        
        <div class="color-boxes">
            <div class="box box1">BOX 1</div>
            <div class="box box2">BOX 2</div>
            <div class="box box3">BOX 3</div>
            <div class="box box4">BOX 4</div>
        </div>
    </div>
</body>
</html>

<!--
**saigesgit/SaigesGIT** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

