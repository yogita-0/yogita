<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<title>Happy Birthday 🌸</title>

<style>
body {
    margin: 0;
    height: 100vh;
    display: flex;
    justify-content: center;
    align-items: center;
    font-family: 'Segoe UI', sans-serif;
    background: linear-gradient(to right, #ffe6f0, #fff0f5);
}

.card {
    width: 350px;
    height: 500px;
    background: white;
    border-radius: 20px;
    text-align: center;
    box-shadow: 0 10px 25px rgba(0,0,0,0.2);
    padding: 20px;
    position: relative;
}

h1 {
    color: #e91e63;
    margin-top: 20px;
}

p {
    color: #555;
    font-size: 18px;
}

/* Flower decorations */
.flower {
    position: absolute;
    font-size: 30px;
    animation: float 4s infinite ease-in-out;
}

.flower1 { top: 10px; left: 10px; }
.flower2 { top: 10px; right: 10px; }
.flower3 { bottom: 10px; left: 10px; }
.flower4 { bottom: 10px; right: 10px; }

@keyframes float {
    0% { transform: translateY(0); }
    50% { transform: translateY(-10px); }
    100% { transform: translateY(0); }
}
</style>
</head>

<body>

<div class="card">
    <div class="flower flower1">🌸</div>
    <div class="flower flower2">🌼</div>
    <div class="flower flower3">🌷</div>
    <div class="flower flower4">🌹</div>

    <h1>🎂 Happy Birthday 🎉</h1>
    <p>May your day be filled with love, joy, and beautiful moments 🌸</p>
</div>

</body>
</html>
