<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Gente Bailando</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 20px;
            background-color: #f0f0f0;
        }
        h1 {
            text-align: center;
            color: #333;
        }
        .container {
            max-width: 1200px;
            margin: 0 auto;
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 20px;
            padding: 20px;
        }
        .dance-card {
            background: white;
            border-radius: 10px;
            padding: 15px;
            box-shadow: 0 2px 5px rgba(0,0,0,0.1);
            text-align: center;
        }
        .dance-card img {
            width: 100%;
            max-width: 300px;
            height: auto;
            border-radius: 5px;
        }
        .dance-card h3 {
            margin: 10px 0;
            color: #444;
        }
        .dance-card p {
            color: #666;
        }
    </style>
</head>
<body>
    <h1>Estilos de Baile</h1>
    
    <div class="container">
        <div class="dance-card">
            <img src="https://source.unsplash.com/random/300x300/?salsa-dancing" alt="Bailarines de Salsa">
            <h3>Salsa</h3>
            <p>La salsa es un baile dinámico y apasionado que combina ritmos latinos con movimientos elegantes.</p>
        </div>

        <div class="dance-card">
            <img src="https://source.unsplash.com/random/300x300/?ballet" alt="Ballet">
            <h3>Ballet</h3>
            <p>El ballet es una forma de danza artística que requiere gracia, precisión y años de entrenamiento.</p>
        </div>

        <div class="dance-card">
            <img src="https://source.unsplash.com/random/300x300/?hip-hop-dance" alt="Hip Hop">
            <h3>Hip Hop</h3>
            <p>El hip hop es un estilo de baile urbano conocido por sus movimientos energéticos y creativos.</p>
        </div>

        <div class="dance-card">
            <img src="https://source.unsplash.com/random/300x300/?contemporary-dance" alt="Danza Contemporánea">
            <h3>Danza Contemporánea</h3>
            <p>La danza contemporánea combina elementos de varios estilos para crear expresiones artísticas únicas.</p>
        </div>
    </div>
</body>
</html>

