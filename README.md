<!DOCTYPE html>

<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Día de Muertos y La Catrina</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

    body {
        font-family: 'Georgia', serif;
        background: linear-gradient(135deg, #1a0033 0%, #4a0e4e 50%, #ff6b35 100%);
        color: #fff;
        line-height: 1.8;
    }

    header {
        background: rgba(0, 0, 0, 0.7);
        padding: 3rem 2rem;
        text-align: center;
        border-bottom: 5px solid #ff6b35;
        position: relative;
        overflow: hidden;
    }

    header::before {
        content: "💀";
        position: absolute;
        font-size: 150px;
        opacity: 0.1;
        left: 10%;
        top: -20px;
        animation: float 6s ease-in-out infinite;
    }

    header::after {
        content: "🌺";
        position: absolute;
        font-size: 100px;
        opacity: 0.1;
        right: 10%;
        bottom: -10px;
        animation: float 4s ease-in-out infinite reverse;
    }

    @keyframes float {
        0%, 100% { transform: translateY(0px) rotate(0deg); }
        50% { transform: translateY(-20px) rotate(5deg); }
    }

    h1 {
        font-size: 3.5rem;
        margin-bottom: 1rem;
        text-shadow: 3px 3px 6px rgba(0, 0, 0, 0.8);
        background: linear-gradient(45deg, #ff6b35, #f7931e, #ffd700);
        -webkit-background-clip: text;
        -webkit-text-fill-color: transparent;
        background-clip: text;
    }

    .subtitle {
        font-size: 1.3rem;
        color: #ffd700;
        font-style: italic;
        text-align: center;
    }

    .container {
        max-width: 1200px;
        margin: 0 auto;
        padding: 3rem 2rem;
    }

    .section {
        background: rgba(255, 255, 255, 0.95);
        color: #2c1810;
        padding: 3rem;
        margin: 2rem 0;
        border-radius: 20px;
        box-shadow: 0 10px 40px rgba(0, 0, 0, 0.4);
        transition: transform 0.3s ease, box-shadow 0.3s ease;
    }

    .section:hover {
        transform: translateY(-5px);
        box-shadow: 0 15px 50px rgba(255, 107, 53, 0.4);
    }

    h2 {
        color: #4a0e4e;
        font-size: 2.5rem;
        margin-bottom: 1.5rem;
        border-bottom: 3px solid #ff6b35;
        padding-bottom: 0.5rem;
    }

    h3 {
        color: #ff6b35;
        font-size: 1.8rem;
        margin: 2rem 0 1rem 0;
    }

    p {
        margin-bottom: 1.5rem;
        font-size: 1.1rem;
        text-align: justify;
    }

    .highlight {
        background: linear-gradient(120deg, #fff4e6 0%, #ffe4cc 100%);
        padding: 2rem;
        border-left: 5px solid #ff6b35;
        border-radius: 10px;
        margin: 2rem 0;
        font-style: italic;
    }

    .altar-elements {
        display: grid;
        grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
        gap: 1.5rem;
        margin: 2rem 0;
    }

    .element-card {
        background: linear-gradient(135deg, #fff4e6 0%, #ffe4cc 100%);
        padding: 1.5rem;
        border-radius: 15px;
        border: 2px solid #ff6b35;
        transition: transform 0.3s ease;
    }

    .element-card:hover {
        transform: scale(1.05);
        box-shadow: 0 5px 20px rgba(255, 107, 53, 0.3);
    }

    .element-card h4 {
        color: #4a0e4e;
        font-size: 1.4rem;
        margin-bottom: 0.5rem;
    }

    .catrina-section {
        background: linear-gradient(135deg, #4a0e4e 0%, #6b1e6b 100%);
        color: #fff;
    }

    .catrina-section h2 {
        color: #ffd700;
        border-bottom-color: #ffd700;
    }

    .footer {
        text-align: center;
        padding: 2rem;
        background: rgba(0, 0, 0, 0.8);
        margin-top: 3rem;
        font-size: 1.1rem;
    }

    .emoji {
        font-size: 2rem;
        display: inline-block;
        animation: spin 3s linear infinite;
    }

    @keyframes spin {
        0%, 100% { transform: rotate(-10deg); }
        50% { transform: rotate(10deg); }
    }

    .imagen-decorativa {
        width: 100%;
        max-width: 600px;
        height: 400px;
        margin: 2rem auto;
        display: block;
        border-radius: 15px;
        box-shadow: 0 10px 30px rgba(0, 0, 0, 0.3);
        object-fit: cover;
        border: 5px solid #ff6b35;
        transition: transform 0.3s ease, box-shadow 0.3s ease;
    }

    .imagen-decorativa:hover {
        transform: scale(1.05);
        box-shadow: 0 15px 40px rgba(255, 107, 53, 0.5);
    }

    @media (max-width: 768px) {
        h1 {
            font-size: 2.5rem;
        }

        .section {
            padding: 1.5rem;
        }

        h2 {
            font-size: 2rem;
        }
    }
</style>


</head>
<body>
    <header>
        <h1>🌺 Día de Muertos 💀</h1>
        <p class="subtitle">Una Celebración de Vida y Memoria</p>
    </header>


<div class="container">
    <div class="section">
        <h2>El Día de Muertos</h2>
        <p>
            El Día de Muertos es una de las tradiciones más emblemáticas y significativas de México, reconocida por la UNESCO como Patrimonio Cultural Inmaterial de la Humanidad. Esta celebración, que se lleva a cabo los días 1 y 2 de noviembre, representa una fusión única entre las creencias prehispánicas y las tradiciones católicas traídas por los españoles durante la conquista.
        </p>
        <p>
            A diferencia de otras culturas donde la muerte se ve con temor o tristeza, en México se celebra con alegría, color y música. Los mexicanos creen que durante estos días, las almas de los difuntos regresan del más allá para visitar a sus seres queridos, disfrutar de sus comidas favoritas y convivir con los vivos.
        </p>

        <div class="highlight">
            <p><strong>💀 "La muerte no nos roba los seres amados. Al contrario, nos los guarda y nos los inmortaliza en el recuerdo"</strong></p>
        </div>

        <h3>Orígenes Prehispánicos</h3>
        <p>
            La tradición del Día de Muertos tiene raíces que se remontan a más de 3,000 años en las culturas mesoamericanas como los aztecas, mayas, purépechas, nahuas y totonacas. Para estas civilizaciones, la muerte no era el final de la existencia, sino una transición hacia otra forma de vida.
        </p>
        <p>
            Los aztecas dedicaban no uno, sino varios meses a la celebración de sus muertos. La diosa Mictecacíhuatl, conocida como la "Dama de la Muerte", era la encargada de cuidar los huesos de los difuntos y presidir las festividades.
        </p>

        <h3>Elementos del Altar de Muertos</h3>
        
        <img src="data:image/jpeg;base64,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" alt="Altar de Día de Muertos tradicional" class="imagen-decorativa">
        
        <div class="altar-elements">
            <div class="element-card">
                <h4>🕯️ Velas y Veladoras</h4>
                <p>Iluminan el camino para que las almas encuentren su regreso a casa.</p>
            </div>
            <div class="element-card">
                <h4>🌼 Flor de Cempasúchil</h4>
                <p>Su color naranja intenso y aroma guían a los espíritus hacia el altar.</p>
            </div>
            <div class="element-card">
                <h4>💀 Calaveras de Azúcar</h4>
                <p>Representan la muerte de manera alegre y colorida, a menudo con nombres.</p>
            </div>
            <div class="element-card">
                <h4>🍞 Pan de Muerto</h4>
                <p>Pan dulce tradicional que simboliza el cuerpo de los difuntos.</p>
            </div>
            <div class="element-card">
                <h4>🖼️ Fotografías</h4>
                <p>Imágenes de los seres queridos fallecidos a quienes se dedica el altar.</p>
            </div>
            <div class="element-card">
                <h4>💧 Agua</h4>
                <p>Para calmar la sed de las almas después de su largo viaje.</p>
            </div>
            <div class="element-card">
                <h4>🧂 Sal</h4>
                <p>Purifica el alma y evita que se corrompa en su viaje de ida y vuelta.</p>
            </div>
            <div class="element-card">
                <h4>🍽️ Comida Favorita</h4>
                <p>Platillos que disfrutaba el difunto en vida, preparados con amor.</p>
            </div>
        </div>
    </div>

    <div class="section catrina-section">
        <h2>🎭 La Catrina: Icono de México</h2>
        
        <img src="https://images.unsplash.com/photo-1635322966219-b75ed372eb01?w=800&q=80" alt="La Catrina mexicana" class="imagen-decorativa">
        
        <h3>Origen e Historia</h3>
        <p>
            La Catrina es uno de los símbolos más reconocibles de México en todo el mundo, pero su origen es relativamente reciente. Esta elegante calavera fue creada en 1912 por el caricaturista e ilustrador mexicano José Guadalupe Posada, originalmente conocida como "La Calavera Garbancera".
        </p>
        <p>
            Posada creó esta imagen como una sátira social durante el Porfiriato, una época en la que muchos mexicanos renegaban de sus raíces indígenas y aspiraban a adoptar costumbres europeas. El término "garbancera" se refería a las personas que, aunque eran de origen humilde (vendían garbanzos), pretendían aparentar un estatus social más alto.
        </p>

        <h3>La Transformación de Diego Rivera</h3>
        <p>
            Fue el muralista Diego Rivera quien inmortalizó y transformó a la Calavera Garbancera en "La Catrina" que conocemos hoy. En 1947, Rivera la incluyó en su mural "Sueño de una tarde dominical en la Alameda Central", vistiéndola con un elegante sombrero de plumas al estilo europeo y un boa de plumas.
        </p>
        <p>
            Rivera la colocó en el centro del mural, acompañada de él mismo cuando era niño y de su esposa Frida Kahlo. Esta representación consolidó a La Catrina como símbolo de la identidad mexicana y de la inevitable igualdad que trae la muerte, sin importar la clase social.
        </p>

        <h3>Significado y Simbolismo</h3>
        <p>
            La Catrina representa varios conceptos importantes en la cultura mexicana:
        </p>
        <div class="highlight">
            <p><strong>La Muerte como Igualadora:</strong> Sin importar riqueza, belleza o poder, todos compartimos el mismo destino final.</p>
            <p><strong>Crítica Social:</strong> Una burla a quienes niegan sus raíces y pretenden ser lo que no son.</p>
            <p><strong>Celebración de la Muerte:</strong> La capacidad mexicana de reírse de la muerte y enfrentarla con humor.</p>
            <p><strong>Identidad Nacional:</strong> Un símbolo de orgullo por las tradiciones mexicanas y su visión única de la muerte.</p>
        </div>

        <h3>La Catrina en la Actualidad</h3>
        <p>
            Hoy en día, La Catrina se ha convertido en un ícono cultural que trasciende fronteras. Durante las celebraciones del Día de Muertos, miles de personas se pintan el rostro como catrinas y catrines, usando maquillaje elaborado que combina elementos de calavera con flores, colores vibrantes y diseños artísticos.
        </p>
        <p>
            La imagen de La Catrina se encuentra en artesanías, pinturas, esculturas, disfraces y todo tipo de expresiones artísticas. Se ha convertido en embajadora de la cultura mexicana y del Día de Muertos alrededor del mundo, representando la manera única en que México honra y celebra a sus muertos.
        </p>
    </div>



</body>
</html>
