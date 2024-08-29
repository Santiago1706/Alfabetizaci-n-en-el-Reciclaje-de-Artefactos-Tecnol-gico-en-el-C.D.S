# Alfabetizaci-n-en-el-Reciclaje-de-Artefactos-Tecnol-gico-en-el-C.D.S

<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Alfabetización en el Reciclaje de Artefactos Tecnológico en el C.D.S</title>
    <link rel="icon" type="image/png" href="https://i.pinimg.com/originals/99/47/ef/9947ef6c76e8a40da1ef4d7a5d281809.png">
    <style>

 body {
            font-family: 'Arial', sans-serif;
            margin: 0;
            padding: 0;
            background: linear-gradient(135deg, #f9d423, #ff4e50);
            color: #333;
            overflow-x: hidden;
        }
        header {
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 20px;
            background-color: rgba(255, 255, 255, 0.8);
            backdrop-filter: blur(10px);
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
            position: sticky;
            top: 0;
            z-index: 1000;
            transition: background-color 0.3s;
        }

.video-container {
    max-width: 600px;
    margin: 0 auto;
    background-color: #fff;
    padding: 20px;
    border-radius: 8px;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
}

iframe {
    width: 100%;
    height: auto;
    border: none;
    border-radius: 8px;
}

.video-citation {
    margin-top: 15px;
    font-size: 0.9em;
    color: #333;
}

.video-citation p {
    margin: 0;
}

.video-citation a {
    color: #007bff;
    text-decoration: none;
}

.video-citation a:hover {
    text-decoration: underline;
}

.video-citation i {
    font-style: italic;
}

        .logo {
            font-size: 1.8em;
            font-weight: bold;
            color: #ff4e50;
        }
        nav ul {
            list-style: none;
            display: flex;
            margin: 0;
            padding: 0;
        }
        nav ul li {
            margin-left: 20px;
        }
        nav ul li a {
            text-decoration: none;
            color: #333;
            font-weight: bold;
            padding: 10px 15px;
            transition: color 0.3s, background 0.3s;
        }
        nav ul li a:hover {
            color: #ff4e50;
            background-color: #fff3f3;
            border-radius: 5px;
        }
        .hero {
            height: 100vh;
            display: flex;
            justify-content: center;
            align-items: center;
            text-align: center;
            color: white;
            background-image: url('https://ideogram.ai/assets/image/lossless/response/xorXp0atR2Wa5inlzG_LQA');
            background-size: cover;
            background-position: center;
            position: relative;
            animation: fadeIn 2s ease-in-out;
        }
        .hero::before {
            content: '';
            position: absolute;
            top: 0;
            left: 0;
            right: 0;
            bottom: 0;
            background-color: rgba(0, 0, 0, 0.4);
            z-index: 1;
        }
        .hero h1 {
            font-size: 4em;
            margin: 0;
            text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.5);
            z-index: 2;
            position: relative;
        }
        .hero p {
            font-size: 1.5em;
            margin-top: 10px;
            text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.5);
            z-index: 2;
            position: relative;
        }
        @keyframes fadeIn {
            from {
                opacity: 0;
            }
            to {
                opacity: 1;
            }
        }
        .section {
            padding: 60px 20px;
            background-color: white;
            color: #333;
            text-align: center;
            transition: background-color 0.3s;
        }
        .section h2 {
            font-size: 2.5em;
            margin-bottom: 20px;
            color: #ff4e50;
        }
        .section p {
            font-size: 1.2em;
            line-height: 1.6;
            max-width: 800px;
            margin: 0 auto;
        }
        .section:nth-of-type(even) {
            background-color: #f7f7f7;
        }
        .portfolio {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            margin-top: 40px;
        }
        .portfolio-item {
            width: 300px;
            margin: 15px;
            background-color: white;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            border-radius: 10px;
            overflow: hidden;
            transition: transform 0.3s, box-shadow 0.3s;
        }
        .portfolio-item img {
            width: 100%;
            height: 200px;
            object-fit: cover;
        }
        .portfolio-item:hover {
            transform: translateY(-10px);
            box-shadow: 0 6px 12px rgba(0, 0, 0, 0.15);
        }
        .portfolio-item h3 {
            font-size: 1.5em;
            margin: 15px;
            color: #ff4e50;
        }
        .portfolio-item p {
            font-size: 1em;
            margin: 0 15px 15px;
            color: #666;
        }
 .testimonials {
    display: flex;
    justify-content: space-around;
    margin-top: 40px;
    flex-wrap: wrap;
}

.testimonial {
    width: 300px;
    margin: 15px;
    padding: 20px;
    background-color: white;
    border-radius: 10px;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
}

.testimonial img {
    width: 160px;
    height: 160px;
    /* Elimina border-radius y clip-path para mantener la imagen rectangular */
    margin-bottom: 105px;
}

.testimonial p {
    font-size: 1.1em;
    line-height: 1.6;
    color: #555;
}

.testimonial h3 {
    margin-top: 10px;
    font-size: 1.3em;
    color: #ff4e50;
}
        .contact-form {
            max-width: 600px;
            margin: 0 auto;
            padding: 20px;
            background-color: white;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            border-radius: 10px;
        }
        .contact-form h2 {
            margin-bottom: 20px;
            font-size: 2em;
            color: #ff4e50;
        }
        .contact-form input,
        .contact-form textarea {
            width: 100%;
            padding: 10px;
            margin-bottom: 20px;
            border: 1px solid #ccc;
            border-radius: 5px;
            font-size: 1em;
        }
        .contact-form button {
            padding: 10px 20px;
            border: none;
            background-color: #ff4e50;
            color: white;
            font-size: 1.2em;
            cursor: pointer;
            border-radius: 5px;
            transition: background-color 0.3s;
        }
        .contact-form button:hover {
            background-color: #e03e3e;
        }
        footer {
            background-color: #333;
            color: white;
            padding: 40px 20px;
            text-align: center;
            position: relative;
        }
        footer p {
            margin: 0;
            font-size: 0.9em;
        }
        .map-container {
            width: 100%;
            height: 400px;
            background-color: #f7f7f7;
            margin-top: 40px;
        }
        iframe {
            width: 100%;
            height: 100%;
            border: none;
        }
        @media (max-width: 768px) {
            .hero h1 {
                font-size: 2.5em;
            }
            .hero p {
                font-size: 1.2em;
            }
            nav ul {
                flex-direction: column;
                align-items: center;
            }
            nav ul li {
                margin-left: 0;
                margin-top: 10px;
            }
            .portfolio,
            .testimonials {
                flex-direction: column;
                align-items: center;
            }
            .portfolio-item,
            .testimonial {
                width: 90%;
                margin: 10px 0;
            }
        }
      </style>
</head>
<body>

    <!-- Aquí va el contenido HTML de la página -->
    <header>
        <div class="logo"><div>
            <img src="https://colegiodivinosalvadorcali.edu.co/images/fixed/ESCUDO OFICIAl.png" alt="" width="80px" height="80px">
        </div>
</div>
        <nav>
               <ul>
                <li><a href="#inicio">Inicio</a></li>
                <li><a href="#Resumen">Resumen</a></li>
                <li><a href="#Problematica">Problematica</a></li>
                <li><a href="#Introducción">Introducción</a></li>
                <li><a href="#Resultados">Resultados</a></li>
                <li><a href="#Limitaciones-Problematica">Limitaciones-Problematica</a></li>
                <li><a href="#Referencias">Referencias</a></li>
            </ul>
        </nav>
        <div class="logo"><div>
            <img src="https://i.pinimg.com/originals/99/47/ef/9947ef6c76e8a40da1ef4d7a5d281809.png" alt="" width="80px" height="80px">
        </div>
</div>
    </header>

    <section class="hero" id="inicio">
        <div>
            <h1>Alfabetización en el Reciclaje de Artefactos Tecnológico en el C.D.S</h1>
            <p>Santiago Laiseca Hoyos</p>
        </div>
    </section>

    <section class="section" id="Resumen">
        <h2>Resumen</h2>
        <p>El sector educativo del C.D.S.C.D.S. enfrenta el reto de abordar la falta de utilidad del área de tecnología e informática en el reciclaje tecnológico, lo que pone en riesgo el medio ambiente y la salud pública. Aunque existen empresas que recolectan desechos tecnológicos, no se les da una reutilización adecuada, afectando la sostenibilidad ambiental. La educación sobre el reciclaje de artefactos tecnológicos es crucial para formar individuos conscientes del impacto ambiental. </p>

<p>Para abordar esta problemática, se propone una metodología que incluya observaciones, encuestas y entrevistas a docentes, estudiantes, padres y directivos del C.D.S. Esto permitirá evaluar el impacto de las estrategias implementadas y crear conciencia sobre la importancia del reciclaje tecnológico. La falta de capacitación docente y material educativo está generando una insuficiencia en las capacidades técnicas y logísticas para gestionar adecuadamente los residuos. Es fundamental que las instituciones educativas, especialmente la comunidad del C.D.S. en Cali, asuman un papel activo en la promoción de prácticas sostenibles de reciclaje tecnológico para asegurar un futuro más sostenible.</p>
 
    </section>

    <section class="section" id="Problematica">
        <h2>Problematica</h2>
<h3>Definición del probloma</h3>
 <p>El C.D.S. enfrenta el reto de mejorar la educación y la práctica del reciclaje tecnológico, ya que la falta de capacitación en esta área pone en riesgo el medio ambiente y la salud de su comunidad. Actualmente, los docentes no están preparados para enseñar sobre reciclaje con tecnología, y hay una carencia de materiales educativos y conciencia sobre el tema tanto en la escuela como en los hogares. Además, no se cuenta con la infraestructura adecuada para manejar los residuos tecnológicos de manera sostenible.</p>    
       <h3>Formulación del problema</h3>
<p>En nuestra actualidad se presenta un gran consumo de artefactos tecnológicos en la sociedad, en el cual las personas tienen un consumo constante para tener una vida más fácil y sencilla. Lo que no tenemos en cuenta es la manera de cómo lograr reutilizar o reciclar dichos artefactos.</p>
 
<h3>Sistematización del problema</h3>
 
<Li>¿Cómo ejecutar un diagnóstico que demuestre el conocimiento sobre el impacto del reciclaje en el ambiente?</Li>
 
<li>¿De qué manera se puede realizar una guía de aprendizaje sobre materiales reciclados para la construcción de artefactos?</li>
 
<li>¿Cómo ejecutar un entorno educativo positivo para que sea un apoyo positivo en las actividades realizadas?</li>

       </section>

    <section class="section" id="Introducción">
        <h2>Introducción</h2>
        <div class="portfolio">
            <p>La basura tecnológica es un problema ambiental que afecta al planeta y la salud de sus habitantes, y esta situación empeora debido a la falta de conocimiento en los estudiantes del C.D.S. sobre los efectos de la tecnología en la sociedad y el medio ambiente <b>(Ministerio de Educación y Cultura, 2020).</b> Es esencial que los estudiantes comprendan que la tecnología, aunque beneficiosa, también puede tener efectos negativos, y desarrollen una conciencia crítica y responsable al evaluar su impacto <b>(CEPAL, 2020).</b></p>

<p>Se propone que los estudiantes participen en charlas con expertos sobre el uso cotidiano de dispositivos tecnológicos, fomentando una reflexión profunda sobre sus efectos <b>(Ministerio de Tecnologías de la Información y las Comunicaciones, s.f.).</b> Además, se plantea la recolección de datos a través de encuestas para involucrar a la comunidad del C.D.S. y promover un sentido de pertenencia y responsabilidad hacia el reciclaje tecnológico.</p>

<p>Este proyecto busca que los estudiantes del C.D.S. se conviertan en personas más responsables en el manejo de la tecnología, contribuyendo al desarrollo de una sociedad más consciente y comprometida con el medio ambiente y el bienestar social.</p>
        </div>
    </section>

    <section class="section" id="Resultados">
        <h2>Resultados</h2>
        <div class="testimonials">
            
            <div class="testimonial">
                <img src="https://i.pinimg.com/originals/46/79/1d/46791d15dd477b7ef65e21ff326bfae3.png" alt="Testimonio 2">
                 <h3>Grado</h3>
                <p>"El diseño que crearon para nuestra empresa superó nuestras expectativas. ¡Altamente recomendados!"</p>
               
            </div>

            <div class="testimonial">
                <img src="https://i.pinimg.com/originals/b5/04/e9/b504e9ea980d2a3119f98ae09c150ae1.png" alt="Testimonio 3">
                <h3>Edad</h3>
                <p>"El diseño que crearon para nuestra empresa superó nuestras expectativas. ¡Altamente recomendados!"</p>
                
            </div>

            <div class="testimonial">
                <img src="https://i.pinimg.com/originals/e3/92/58/e39258eddae6f1ff6183aaea80c4694a.png" alt="Testimonio 1">
                
                <h3>¿Con qué frecuencia suele deshacerse de dispositivos electrónicos como teléfonos móviles, computadoras o tabletas?</h3>
<p>"Trabajar con este equipo ha sido una experiencia increíble. Su creatividad y atención al detalle son incomparables."</p>

            </div>
            

<section class="section" id="Limitaciones-Problematica">
<h2>Limitaciones -  Problematica</h2>
<h3>Tamaño de la muestra:</h3> <p>Uno de los problemas del estudio fue el tamaño de la muestra, ya que esta fue relativamente pequeña, lo que no permite tener un mayor panorama. Además, algunos estudiantes.</p>
<h3>Diseño transversal:</h3> <p>El diseño transversal del estudio no permite analizar los cambios a largo plazo, puesto que solo toma datos en un punto específico. Con un diseño longitudinal, se podría analizar cómo, y no solo en el momento de la práctica, cómo la basura tecnológica va evolucionando poco a poco, como es el caso de este proyecto.</p>
<h3>Variables no controlables:</h3> <p>El proyecto buscaba principalmente entender las problemáticas de la basura tecnológica en los colegios; sin embargo, hubo algunas variables que no se pudieron controlar, lo que claramente genera un cambio en los resultados.</p>
<h3>Limitaciones de la basura tecnológica:</h3><p> Debido a que el proyecto se realiza a un nivel micro, no se manejan algunos instrumentos, aunque se podrían realizar exámenes digitales o escritos, con el objetivo de clasificar el nivel de alfabetización sobre la basura tecnológica en la institución.</p>
<h3>Recomendaciones</h3>
<h3>Tamaño de la muestra:</h3> <p>Se recomienda a futuras investigaciones seleccionar una muestra más amplia con el objetivo de poder obtener resultados más diversos, tener un panorama más grande con el que trabajar y entender como las diferencias entre cada individuo son influyentes en el estudio.</p>
<h3>Diseño del proyecto:</h3> <p>Considerar el uso de un diseño longitudinal para estudiar la evolución que presenta la alfabetización de los estudiantes para darle un uso adecuado a los artefactos tecnológicos. Esto permitiría entender mejor las tasas de aprendizaje con la basura tecnológica en tecnología e informática de los individuos que forman parte de la muestra.</p>
<h3>Instrumentaría:</h3> <P>En este caso no fue necesario el uso de elementos externos o instrumentaría profesional.</P>

   </section>



<!-- Nueva sección de video de YouTube -->
 <section class="section" id="Video">
    <h2>Video</h2>
        
        <div class="video-container">
        <iframe width="560" height="315" src="https://www.youtube.com/embed/Dmm8r3eaJsQ" frameborder="0" allowfullscreen></iframe>
        <div class="video-citation">
            <p>Tu Club Tecnológico. (2021, 31 diciembre). <i>Basura electrónica</i> [Vídeo]. YouTube. <a href="https://www.youtube.com/watch?v=Dmm8r3eaJsQ" target="_blank">https://www.youtube.com/watch?v=Dmm8r3eaJsQ</a></p>
        </div>

        

 <div class="video-container">
        <iframe width="560" height="315" src="https://www.youtube.com/embed/2QM5R2xiip4" frameborder="0" allowfullscreen></iframe>
        <div class="video-citation">
            <p>Sociedad del conocimiento. (2021, 19 abril). <i>Alfabetización tecnológica</i> [Vídeo]. YouTube. <a href="https://www.youtube.com/watch?v=2QM5R2xiip4" target="_blank">https://www.youtube.com/watch?v=2QM5R2xiip4</a></p>
        </div>

    </div>

    </div>
    </section>
        </div>
    </section>        
        </div>
    </section>


 <section class="section" id="Referencias">
    <h2>Referencias</h2>

       <p>CEPAL. (2020). Cepal. Obtenido de <a href="https://www.cepal.org/sites/default/files/publication/files/45901/S2000401_es.pdf" target="_blank">https://www.cepal.org/sites/default/files/publication/files/45901/S2000401_es.pdf</a></p>
        <p>Flores, J. (18 de Enero de 2023). NATIONAL GEOGRAPHIC ESPAÑA. Obtenido de <a href="https://www.nationalgeographic.com.es/mundo-ng/peligros-basura-electronica_13239" target="_blank">https://www.nationalgeographic.com.es/mundo-ng/peligros-basura-electronica_13239</a></p>
        <p>Herrera, S. (13 de Mayo de 2024). Novalinea. Obtenido de <a href="https://novalinea1.com/promocion-del-reciclaje-en-escuelas/" target="_blank">https://novalinea1.com/promocion-del-reciclaje-en-escuelas/</a></p>
        <p>La Organización de las Naciones Unidas. (01 de Diciembre de 2021). Naturaliza. Obtenido de <a href="https://www.naturalizaeducacion.org/2021/12/01/educacion-ambiental-para-reducir-nuestra-basura-electronica/" target="_blank">https://www.naturalizaeducacion.org/2021/12/01/educacion-ambiental-para-reducir-nuestra-basura-electronica/</a></p>
        <p>Ministerio de Educación y Cultura. (2020). Obtenido de <a href="https://www.gub.uy/ministerio-educacion-cultura/sites/ministerio-educacion-cultura/files/documentos/publicaciones/ciencia_tecnologia_sociedad.pdf" target="_blank">https://www.gub.uy/ministerio-educacion-cultura/sites/ministerio-educacion-cultura/files/documentos/publicaciones/ciencia_tecnologia_sociedad.pdf</a></p>
        <p>Ministerio de Tecnologías de la Información y las Comunicaciones. (s.f.). Cudi.edu. Obtenido de <a href="https://cudi.edu.mx/primavera_2009/presentaciones/Anexo_impacto_de_TIC.pdf" target="_blank">https://cudi.edu.mx/primavera_2009/presentaciones/Anexo_impacto_de_TIC.pdf</a></p>
        <p>smowl Tech. (28 de Febrero de 2024). smowl. Obtenido de <a href="https://smowl.net/es/basura-electronica/" target="_blank">https://smowl.net/es/basura-electronica/</a></p>
    </section>
    <footer>
        <p>&copy; 2024 Santiago Laiseca - Reciclaje Tecnologico. Todos los derechos reservados.</p>
    </footer>
</body>
</html>
