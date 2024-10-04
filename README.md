<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Glow Up estilo Jennieism: Moda, Skincare, Maquillaje e Instagram">
    <title>Glow Up estilo Jennieism</title>
    <style>
        body {
            background-color: #f0f0f0;
            color: #000;
            font-family: 'Arial', sans-serif;
            margin: 0;
            padding: 0;
            background-image: url('stars-background.jpg'); /* Fondo con estrellas */
            background-repeat: no-repeat;
            background-size: cover;
        }

        header {
            background-color: #000;
            color: #fff;
            text-align: center;
            padding: 30px;
            position: relative;
        }

        h1 {
            font-size: 3em;
            font-family: 'Georgia', serif;
            margin: 0;
        }

        nav {
            background-color: #fff;
            padding: 15px;
            border-bottom: 2px solid #000;
        }

        nav ul {
            list-style: none;
            padding: 0;
            text-align: center;
        }

        nav ul li {
            display: inline-block;
            margin: 0 15px;
        }

        nav ul li a {
            text-decoration: none;
            color: #000;
            font-size: 1.2em;
            font-weight: bold;
        }

        .section {
            display: none;
            padding: 20px;
            max-width: 900px;
            margin: 20px auto;
            background-color: #fff;
            border-radius: 10px;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
            position: relative;
        }

        .decor-stars {
            position: absolute;
            top: 10px;
            right: 10px;
            font-size: 2em;
            color: #6F4C3E; /* Estrellas marrones */
        }

        footer {
            text-align: center;
            padding: 20px;
            background-color: #000;
            color: #fff;
        }

        footer a {
            color: #fff;
            text-decoration: none;
            margin: 0 10px;
        }

        ul {
            list-style: none;
            padding-left: 20px;
        }

        ul li::before {
            content: '★';
            margin-right: 10px;
            color: #6F4C3E; /* Estrellas marrones */
        }
    </style>
    <script>
        function showSection(sectionId) {
            var sections = document.querySelectorAll('.section');
            sections.forEach(function(section) {
                section.style.display = 'none';  // Oculta todas las secciones
            });
            document.getElementById(sectionId).style.display = 'block';  // Muestra solo la sección clickeada
        }
    </script>
</head>
<body>

    <header>
        <h1>Jennieism: Glow Up y Belleza</h1>
        <p>Explora los secretos de belleza y estilo inspirados en Jennie Kim de BLACKPINK.</p>
    </header>

    <nav>
        <ul>
            <li><a href="#" onclick="showSection('introduccion')">Introducción</a></li>
            <li><a href="#" onclick="showSection('belleza')">Belleza</a></li>
            <li><a href="#" onclick="showSection('moda')">Moda</a></li>
            <li><a href="#" onclick="showSection('skincare')">Skincare</a></li>
            <li><a href="#" onclick="showSection('tiendas')">Tiendas</a></li>
            <li><a href="#" onclick="showSection('instagram')">Instagram</a></li>
        </ul>
    </nav>

    <!-- Sección de Introducción -->
    <div id="introduccion" class="section">
        <h2>Introducción</h2>
        <div class="decor-stars">★</div>
        <p>Jennieism es una tendencia que sigue el estilo y actitud de Jennie Kim, integrante de BLACKPINK. Este movimiento cultural se ha expandido más allá de la moda y la belleza, convirtiéndose en una filosofía de vida que promueve la autoconfianza, el autocuidado y la autenticidad. A lo largo de los años, Jennie ha destacado no solo por su talento musical, sino también por su capacidad para influir en la estética contemporánea. Su estilo personal es una mezcla de influencias que van desde la alta costura hasta la moda de calle, lo que hace que su imagen sea tanto accesible como aspiracional.</p>
        <p>El glow up que representa Jennieism no se limita al aspecto físico; también implica un crecimiento personal y emocional. A través de su presencia en redes sociales, Jennie comparte su día a día, lo que inspira a millones de fanáticos a abrazar su individualidad y expresarse sin miedo. Este movimiento ha generado una comunidad vibrante de seguidores que buscan no solo verse bien, sino también sentirse bien en su piel, convirtiendo la belleza en una experiencia holística.</p>
    </div>

    <!-- Sección de Belleza -->
    <div id="belleza" class="section">
        <h2>Belleza: Maquillaje</h2>
        <div class="decor-stars">★</div>
        <p>El maquillaje de Jennie es emblemático por su enfoque en la naturalidad y el resalte de los rasgos únicos de cada persona. Para lograr un look inspirado en Jennieism, es fundamental centrarse en la preparación de la piel y la elección de productos que potencien la belleza natural. A continuación, te presentamos una guía detallada para conseguir ese maquillaje fresco y sofisticado que la caracteriza:</p>
        <ul>
            <li><strong>Piel:</strong> Antes de aplicar cualquier producto, es esencial preparar la piel. Usa un limpiador suave seguido de un tónico hidratante. Aplica una base ligera o BB cream que unifique el tono de la piel, y complementa con corrector en áreas que necesiten un poco más de cobertura. El acabado debe ser luminoso, así que considera utilizar un iluminador en las zonas altas del rostro.</li>
            <li><strong>Ojos:</strong> Los ojos son una parte clave del look. Jennie suele optar por sombras en tonos cálidos o neutros. Aplica una sombra clara en el párpado y una sombra más oscura en la línea de las pestañas para dar profundidad. El delineado debe ser sutil; un lápiz marrón puede funcionar para un efecto más suave. Finaliza con una buena capa de máscara de pestañas que abra la mirada.</li>
            <li><strong>Labios:</strong> En cuanto a los labios, Jennie prefiere tonos nude o rosados. Para un acabado jugoso, usa un bálsamo labial con color o un gloss. La clave es mantener los labios hidratados y naturales, evitando acabados mate demasiado pesados.</li>
            <li><strong>Rubor:</strong> El rubor debe ser aplicado con suavidad, optando por tonos que imiten un rubor natural, como los rosas o duraznos. Coloca el rubor en las mejillas y difumínalo hacia las sienes para un acabado radiante.</li>
        </ul>
        <p>Recuerda que la belleza no se trata solo de los productos que aplicas, sino de la confianza con la que los llevas. Un buen estado de ánimo y la aceptación personal son esenciales para reflejar el glow up al estilo Jennie.</p>
    </div>

    <!-- Sección de Moda -->
    <div id="moda" class="section">
        <h2>Moda: Elegancia Minimalista</h2>
        <div class="decor-stars">★</div>
        <p>El estilo de Jennie es la perfecta amalgama entre la elegancia clásica y las tendencias contemporáneas. Conocida por su habilidad para mezclar piezas básicas con elementos más llamativos, Jennie nos enseña que la moda no tiene que ser complicada para ser impactante. Aquí hay una guía completa para recrear su estilo:</p>
        <ul>
            <li><strong>Prendas básicas:</strong> La base de cualquier look de Jennie incluye prendas atemporales y versátiles. Busca blusas blancas, camisetas de algodón y jeans bien ajustados. Optar por una paleta de colores neutros como negro, blanco, gris y beige es esencial para facilitar la mezcla y combinación de diferentes piezas.</li>
            <li><strong>Accesorios llamativos:</strong> Una de las claves del estilo de Jennie es el uso de accesorios que transforman un look simple en algo espectacular. Considera invertir en un collar de cadena dorada, pendientes grandes o un bolso de diseñador. Estos detalles aportan un toque de lujo a cualquier atuendo y son perfectos para destacar en cualquier ocasión.</li>
            <li><strong>Calzado:</strong> Desde botas de cuero hasta tacones elegantes, el calzado de Jennie siempre complementa su look```html
            <li><strong>Calzado:</strong> Desde botas de cuero hasta tacones elegantes, el calzado de Jennie siempre complementa su look. Las zapatillas deportivas de marcas de lujo son una elección común que añade un aire casual y chic a sus conjuntos, mientras que los tacones siempre se reservan para ocasiones más formales, donde el toque de sofisticación es esencial.</li>
            <li><strong>Vestidos y faldas:</strong> No te olvides de los vestidos y faldas que Jennie elige, generalmente en cortes que favorecen su figura. Faldas de cintura alta y vestidos de línea A son opciones ideales que aportan un aire femenino y moderno. Elige patrones simples o colores sólidos para mantener la elegancia.</li>
        </ul>
        <p>Para replicar el estilo de Jennie, recuerda que menos es más. La clave está en seleccionar piezas que resalten tu figura y que te hagan sentir segura y cómoda.</p>
    </div>

    <!-- Sección de Skincare -->
    <div id="skincare" class="section">
        <h2>Skincare: Cuidado de la Piel al Estilo Jennie</h2>
        <div class="decor-stars">★</div>
        <p>La piel radiante de Jennie es el resultado de un régimen de cuidado que enfatiza la hidratación y la limpieza. Aquí hay una rutina detallada que puedes seguir para conseguir una piel similar:</p>
        <ul>
            <li><strong>Limpiar:</strong> El primer paso esencial es limpiar el rostro. Utiliza un limpiador suave que elimine la suciedad y el maquillaje sin despojar a la piel de sus aceites naturales. Realiza esta limpieza tanto por la mañana como por la noche.</li>
            <li><strong>Tónico:</strong> Aplica un tónico después de la limpieza para equilibrar el pH de la piel. Busca tónicos que contengan ingredientes naturales como el agua de rosas o el extracto de té verde, que son conocidos por sus propiedades calmantes e hidratantes.</li>
            <li><strong>Suero:</strong> Un suero con vitamina C o ácido hialurónico puede aportar luminosidad y una hidratación profunda. Este paso es clave para obtener una piel jugosa y brillante.</li>
            <li><strong>Hidratante:</strong> Escoge una crema hidratante que se adapte a tu tipo de piel. La piel de Jennie se caracteriza por su apariencia suave y radiante, por lo que es esencial mantenerla bien hidratada.</li>
            <li><strong>Protección Solar:</strong> No olvides aplicar protector solar diariamente. Este es un paso fundamental en cualquier rutina de skincare, ya que protege la piel de los dañinos rayos UV que pueden causar envejecimiento prematuro y manchas solares.</li>
        </ul>
        <p>Además de seguir esta rutina, asegúrate de beber suficiente agua y mantener una dieta equilibrada rica en frutas y verduras. El cuidado de la piel es tanto interno como externo, y ambos aspectos son esenciales para lograr el glow up deseado.</p>
    </div>

    <!-- Sección de Tiendas -->
    <div id="tiendas" class="section">
        <h2>Tiendas: Dónde Conseguir Tu Look Jennie</h2>
        <div class="decor-stars">★</div>
        <p>Si deseas replicar el estilo de Jennie, aquí tienes una lista de tiendas donde puedes encontrar ropa y productos de belleza inspirados en su estilo:</p>
        <h3>Ropa</h3>
        <ul>
            <li><a href="https://www.hm.com" target="_blank">H&M</a> - Moda accesible y contemporánea, ideal para piezas básicas y atemporales.</li>
            <li><a href="https://www.nastygal.com" target="_blank">Nasty Gal</a> - Para looks atrevidos y únicos que destacan en cualquier ocasión.</li>
            <li><a href="https://www.asos.com" target="_blank">ASOS</a> - Variedad de marcas y estilos para todas las ocasiones, perfectas para mezclar y combinar.</li>
        </ul>
        <h3>Maquillaje</h3>
        <ul>
            <li><a href="https://www.sephora.com" target="_blank">Sephora</a> - Productos de belleza de alta gama, donde encontrarás todo lo necesario para recrear el maquillaje de Jennie.</li>
            <li><a href="https://www.macys.com" target="_blank">Macy's</a> - Amplia selección de cosméticos y cuidado de la piel de varias marcas reconocidas.</li>
            <li><a href="https://www.ulta.com" target="_blank">Ulta Beauty</a> - Ofertas en productos de belleza y cuidado personal, ideal para encontrar lo que necesitas a buen precio.</li>
        </ul>
        <h3>Skincare</h3>
        <ul>
            <li><a href="https://www.theordinary.com" target="_blank">The Ordinary</a> - Tratamientos de skincare efectivos y accesibles, perfectos para lograr una piel radiante.</li>
            <li><a href="https://www.cerave.com" target="_blank">CeraVe</a> - Productos dermatológicos recomendados para la hidratación y cuidado diario.</li>
            <li><a href="https://www.kiehls.com" target="_blank">Kiehl's</a> - Cuidado de la piel de lujo con ingredientes naturales, ideales para mantener la salud de la piel.</li>
        </ul>
    </div>

    <!-- Sección de Instagram -->
    <div id="instagram" class="section">
        <h2>Instagram: Inspírate con Jennie</h2>
        <div class="decor-stars">★</div>
        <p>Sigue a Jennie en Instagram para estar al tanto de sus últimos looks, productos de belleza y momentos personales. Su cuenta es una fuente inagotable de inspiración para quienes desean adoptar su estilo:</p>
        <ul>
            <li><strong>Instagram de Jennie:</strong> <a href="https://www.instagram.com/jennierubyjane/" target="_blank">@jennierubyjane</a></li>
            <li><strong>Estilistas y Makeup Artists:</strong> Busca cuentas de estilistas que han trabajado con Jennie para obtener tips y tendencias.</li>
            <li><strong>Otros Influencers:</strong> Sigue a influencers que se inspiran en Jennieism para obtener ideas sobre cómo incorporar su estilo en tu vida diaria.</li>
        </ul>
    </div>

    <footer>
        <p>&copy; 2024 Glow Up estilo Jennieism. Todos los derechos reservados.</p>
        <p><a href="#" onclick="showSection('introduccion')">Introducción</a> | <a href="#" onclick="showSection('belleza')">Belleza</a> | <a href="#" onclick="showSection('moda')">Moda</a> | <a href="#" onclick="showSection('skincare')">Skincare</a> | <a href="#" onclick="showSection('tiendas')">Tiendas</a> | <a href="#" onclick="showSection('instagram')">Instagram</a></p>
    </footer>
</body>
</html>
