<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Minha Jornada no Desenvolvimento - Portfólio</title>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Orbitron:wght@400;700&display=swap');
        
        body {
            background-color: black;
            color: white;
            font-family: 'Orbitron', sans-serif;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            height: 100vh;
            text-align: center;
            overflow: hidden;
        }
        
        .neon-text {
            font-size: 2.0rem;
            font-weight: bold;
            text-shadow: 0 0 5px rgba(255, 255, 255, 0.8), 0 0 10px rgba(255, 255, 255, 0.6);
            white-space: nowrap;
            overflow: hidden;
            opacity: 0;
            transition: opacity 1.2s ease-in-out;
        }
        
        .sub-text {
            font-size: 1.0rem;
            color: #ff69b4;
            opacity: 0;
            text-shadow: 0 0 5px rgba(255, 105, 180, 0.6);
            margin-top: 15px;
            transition: opacity 0.2s ease-in-out;
        }
        
        .icons {
            margin-top: 20px;
            display: flex;
            gap: 20px;
            opacity: 0;
            transition: opacity 1.5s ease-in-out;
        }
        
        .icons img {
            width: 50px;
            height: 50px;
            transition: transform 0.3s;
        }
        
        .icons img:hover {
            transform: scale(1.1);
        }
    </style>
</head>
<body>
    <div class="neon-text" id="main-text">Portfólio em construção</div>
    <div class="sub-text" id="sub-text">Me acompanhe no Github e LinkedIn!</div>
    <div class="icons" id="icons">
        <a href="https://github.com/mariclaradev" target="_blank">
            <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/github/github-original.svg" alt="GitHub">
        </a>
        <a href="https://www.linkedin.com/in/maria-clara-silva374/" target="_blank">
            <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/linkedin/linkedin-original.svg" alt="LinkedIn">
        </a>
    </div>
    
    <script>
        // Faz o primeiro texto aparecer
        setTimeout(() => {
            document.getElementById("main-text").style.opacity = "1";
        }, 500);

        // Faz o segundo texto e os ícones aparecerem após o primeiro
        setTimeout(() => {
            document.getElementById("sub-text").style.opacity = "1";
            document.getElementById("icons").style.opacity = "1";
        }, 2500);
    </script>
</body>
</html>
