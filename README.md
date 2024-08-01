- 👋 Hi, I’m @firmecomoungato
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...
- 😄 Pronouns: ...
- ⚡ <!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Esteban Oñate - Subir Juegos</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #000000;
            color: #FFFFFF;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: #ff0000;
            padding: 20px;
            text-align: center;
        }
        header h1 {
            margin: 0;
        }
        main {
            padding: 20px;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 80vh;
        }
        .upload-section {
            background-color: #0000ff;
            padding: 20px;
            border-radius: 10px;
            text-align: center;
        }
        .upload-section input[type="file"] {
            margin-top: 10px;
            color: #000000;
        }
        .upload-section input[type="submit"] {
            margin-top: 10px;
            background-color: #ff0000;
            color: #FFFFFF;
            border: none;
            padding: 10px 20px;
            cursor: pointer;
        }
    </style>
</head>
<body>
    <header>
        <h1>Esteban Oñate</h1>
        <p>Sube tus juegos aquí</p>
    </header>
    <main>
        <section class="upload-section">
            <h2>Subir Archivos de Juegos</h2>
            <form action="/upload" method="post" enctype="multipart/form-data">
                <input type="file" name="gameFile" id="gameFile" required>
                <br>
                <input type="submit" value="Subir">
            </form>
        </section>
    </main>
</body>
</html>
