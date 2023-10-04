- 👋 Hi, I’m @Juuanma15
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
Juuanma15/Juuanma15 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
<!DOCTYPE html>
<html>
<head>
    <title>Generador de Rutas de Actividades</title>
</head>
<body>
    <header>
        <h1>Bienvenido a RutaApp</h1>
        <p>Tu aplicación para descubrir nuevas aventuras</p>
    </header>

    <section>
        <h2>Genera tu Ruta</h2>
        <form>
            <label for="lugar">Lugar:</label>
            <input type="text" id="lugar" name="lugar" required><br><br>

            <label for="filtros">Filtros:</label>
            <select id="filtros" name="filtros">
                <option value="cultural">Cultural</option>
                <option value="aventura">Aventura</option>
                <option value="gastronomia">Gastronomía</option>
                <option value="naturaleza">Naturaleza</option>
            </select><br><br>

            <input type="submit" value="Generar Ruta">
        </form>
    </section>

    <section>
        <h2>Tu Ruta Personalizada</h2>
        <div id="ruta-generada">
            <!-- Aquí se mostrará la ruta generada por la aplicación -->
        </div>
    </section>

    <footer>
        <p>&copy; 2023 RutaApp - Todos los derechos reservados</p>
    </footer>
</body>
</html>
