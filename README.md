<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title> La Plata Celulares | Reparación y Venta de Celulares</title>
    <style>
        body {
            font-family: 'Segoe UI', sans-serif;
            margin: 0;
            padding: 0;
            background: #f2f2f2;
            color: #333;
        }

        header {
            background-color: #2c3e50;
            color: white;
            padding: 20px 10px;
            text-align: center;
        }

        nav {
            background-color: #34495e;
            text-align: center;
            padding: 10px;
        }

        nav a {
            color: white;
            text-decoration: none;
            margin: 0 15px;
            font-weight: bold;
        }

        section {
            padding: 40px 20px;
            max-width: 1000px;
            margin: auto;
        }

        h2 {
            color: #2c3e50;
        }

        ul {
            list-style: none;
            padding: 0;
        }

        li {
            padding: 5px 0;
        }

        .galeria {
            display: flex;
            flex-wrap: wrap;
            justify-content: space-around;
            gap: 20px;
        }

        .producto {
            background: white;
            border: 1px solid #ddd;
            border-radius: 5px;
            width: 200px;
            text-align: center;
            padding: 10px;
        }

        .producto img {
            width: 100%;
            height: auto;
            border-radius: 5px;
        }

        form {
            background: white;
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0 0 5px rgba(0,0,0,0.1);
        }

        input, textarea {
            width: 100%;
            padding: 10px;
            margin: 8px 0;
            border: 1px solid #ccc;
            border-radius: 4px;
        }

        button {
            background-color: #27ae60;
            color: white;
            border: none;
            padding: 10px 15px;
            border-radius: 5px;
            cursor: pointer;
        }

        button:hover {
            background-color: #2ecc71;
        }

        footer {
            background-color: #2c3e50;
            color: white;
            text-align: center;
            padding: 15px;
        }

        .social-icons a {
            margin: 0 10px;
            color: white;
            text-decoration: none;
        }

        .whatsapp-btn {
            position: fixed;
            bottom: 20px;
            right: 20px;
            background-color: #25D366;
            color: white;
            border-radius: 50%;
            padding: 15px;
            font-size: 24px;
            text-decoration: none;
            box-shadow: 0 2px 5px rgba(0,0,0,0.3);
        }

        .whatsapp-btn:hover {
            transform: scale(1.1);
        }
    </style>
</head>
<body>

    <header>
        <h1>Tecnocel</h1>
        <p>Reparación y Venta de Celulares</p>
    </header>

    <nav>
        <a href="#servicios">Servicios</a>
        <a href="#ventas">Ventas</a>
        <a href="#contacto">Contacto</a>
    </nav>

    <section id="servicios">
        <h2>Servicios de Reparación</h2>
        <ul>

            <li>Cambio de pantallas rotas</li>
            <li>Reemplazo de batería</li>
            <li>Reparación de puertos de carga</li>
            <li>Problemas de software y actualizaciones</li>
        </ul>
    </section>

    <section id="ventas">
        <h2>Teléfonos en Venta 2214949001</h2>
        <div class="galeria">
            <div class="producto">
                <img src="https://via.placeholder.com/200x200?text=Redmi A5" alt="Redmi A5">
                <p>iPhone 12 - $500</p>
            </div>
            <div class="producto">
                <img src="https://via.placeholder.com/200x200?text=Motorola G55" alt=" Motorola G55">
                <p>Samsung Galaxy S21 - $450</p>
            </div>
            <div class="producto">
                <img src="https://via.placeholder.com/200x200?text=Redmi 14C" alt="Redmi 14C">
                <p>Motorola G30 - $200</p>
            </div>
        </div>
    </section>

    <section id="contacto">
        <h2>Contacto</h2>
        <form action="mailto:tu-email@ejemplo.com" method="POST" enctype="text/plain">
            <input type="text" name="nombre" placeholder="Celulares La Plata 2014" required>
            <input type="email" name="email" placeholder="celulareslaplta2014@hotmail.com" required>
            <textarea name="mensaje" rows="4" placeholder="Tu mensaje..." required></textarea>
            <button type="submit">Enviar</button>
        </form>
    </section>

    <!-- Botón de WhatsApp -->
    <a 
        class="whatsapp-btn" 
        href="https://wa.me/5492214949001" 
        target="_blank" 
        title="Contáctanos por WhatsApp">
        💬
    </a>

    <footer>
        <p>&copy; Celulares La Plata 2014 | Todos los derechos reservados</p>
        <div class="social-icons">
            <a href="https://facebook.com" target="celulareslaplata2014@hotmail.com">Facebook</a> |
            <a href="https://instagram.com" target="/laplatacelulares?igshid=hsu2zwci7hlh">Instagram</a>
        </div>
    </footer>

</body>
</html>
