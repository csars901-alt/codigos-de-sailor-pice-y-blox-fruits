# codigos-de-sailor-pice-y-blox-fruits
se actualizara cada cierto tiempo
<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8">
<title>Anime Gamer Hub</title>

<style>
body {
    margin: 0;
    font-family: Arial, sans-serif;
    background: #0d0d0d;
    color: white;
}

header {
    background: linear-gradient(90deg, #ff00ff, #00ffff);
    padding: 20px;
    text-align: center;
    font-size: 35px;
    font-weight: bold;
    text-shadow: 0 0 15px black;
}

nav {
    background: #111;
    padding: 10px;
    text-align: center;
}

nav a {
    color: #00ffff;
    margin: 15px;
    text-decoration: none;
    font-weight: bold;
}

nav a:hover {
    color: #ff00ff;
}

.section {
    padding: 20px;
}

.card {
    background: #1a1a1a;
    margin: 20px auto;
    padding: 20px;
    width: 80%;
    border-radius: 15px;
    box-shadow: 0 0 20px #00ffff;
    transition: 0.3s;
}

.card:hover {
    transform: scale(1.05);
    box-shadow: 0 0 30px #ff00ff;
}

button {
    background: #00ffff;
    border: none;
    padding: 10px 20px;
    color: black;
    font-weight: bold;
    border-radius: 10px;
    cursor: pointer;
}

button:hover {
    background: #ff00ff;
    color: white;
}

.hidden {
    display: none;
}

footer {
    background: #111;
    text-align: center;
    padding: 10px;
    margin-top: 20px;
}
</style>
</head>

<body>

<header>🔥 ANIME GAMER HUB 🔥</header>

<nav>
    <a href="#sailor">Sailor Piece</a>
    <a href="#blox">Blox Fruits</a>
</nav>

<div class="section" id="sailor">
    <div class="card">
        <h2>⚓ Sailor Piece</h2>
        <p>Encuentra frutas, códigos y tips para subir rápido.</p>

        <button onclick="mostrar('sailorInfo')">Ver más</button>

        <div id="sailorInfo" class="hidden">
            <p>🔥 Mejores frutas: Kitsune, Dragon, Leopard</p>
            <p>🎯 Tip: Farmear bosses y usar códigos para XP</p>
        </div>
    </div>
</div>

<div class="section" id="blox">
    <div class="card">
        <h2>🍈 Blox Fruits</h2>
        <p>Todo sobre frutas, niveles y farmeo.</p>

        <button onclick="mostrar('bloxInfo')">Ver más</button>

        <div id="bloxInfo" class="hidden">
            <p>🔥 Mejores frutas: Leopard, Dough, Dragon</p>
            <p>⚡ Tip: Usa x2 XP y sube en bosses</p>
        </div>
    </div>
</div>

<footer>
© 2026 Anime Gamer Hub 😎
</footer>

<script>
function mostrar(id) {
    let elemento = document.getElementById(id);
    if (elemento.classList.contains("hidden")) {
        elemento.classList.remove("hidden");
    } else {
        elemento.classList.add("hidden");
    }
}
</script>

</body>
</html>
