# clinica-optometria.
# Crear el archivo index.html con el código de la página web
html_content = """<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Clínica de Optometría</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }
        header {
            background: #0077b6;
            color: white;
            text-align: center;
            padding: 1rem;
        }
        nav {
            display: flex;
            justify-content: center;
            background: #0096c7;
            padding: 0.5rem;
        }
        nav a {
            color: white;
            margin: 0 15px;
            text-decoration: none;
        }
        .container {
            max-width: 1200px;
            margin: auto;
            padding: 20px;
            text-align: center;
        }
        footer {
            background: #0077b6;
            color: white;
            text-align: center;
            padding: 1rem;
            position: relative;
            bottom: 0;
            width: 100%;
        }
    </style>
</head>
<body>
    <header>
        <h1>Clínica de Optometría</h1>
        <p>Especialistas en el control de la miopía con Myopia Master</p>
    </header>
    
    <nav>
        <a href="#inicio">Inicio</a>
        <a href="#servicios">Servicios</a>
        <a href="#membresias">Membresías</a>
        <a href="#contacto">Contacto</a>
    </nav>
    
    <div class="container" id="inicio">
        <h2>Bienvenidos a nuestra clínica</h2>
        <p>Brindamos atención especializada para el control de la miopía con la mejor tecnología disponible.</p>
    </div>
    
    <div class="container" id="servicios">
        <h2>Nuestros Servicios</h2>
        <p>Evaluación optométrica avanzada, control y prevención de la miopía con Myopia Master.</p>
    </div>
    
    <div class="container" id="membresias">
        <h2>Membresías y Beneficios</h2>
        <p>Accede a descuentos, consultas ilimitadas y regalos exclusivos al unirte a nuestros planes.</p>
    </div>
    
    <div class="container" id="contacto">
        <h2>Contacto</h2>
        <p>📍 Dirección: Quito, Ecuador</p>
        <p>📞 Teléfono: +593 123 456 789</p>
        <p>📧 Email: info@clinicamiopia.com</p>
    </div>
    
    <footer>
        <p>&copy; 2025 Clínica de Optometría - Todos los derechos reservados</p>
    </footer>
</body>
</html>
"""

# Guardar el archivo
file_path = "/mnt/data/index.html"
with open(file_path, "w", encoding="utf-8") as file:
    file.write(html_content)

# Devolver la ruta del archivo para descarga
file_path
