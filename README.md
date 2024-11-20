<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portafolio de Diseño de Carros</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            overflow-x: hidden;
        }

        header {
            background-color: rgba(0, 0, 0, 0.8);
            padding: 20px 0;
            text-align: center;
            color: #fff;
            position: relative;
            z-index: 2;
        }

        header h1 {
            margin: 0;
            font-size: 2.5em;
        }
        .navegador .left, .navegador .right {
            display: flex;
            align-items: center;
        }
        nav {
            background-color: rgba(0, 0, 0, 0.9);
            overflow: hidden;
            z-index: 2;
            position: relative;
            text-align: center;
        }

        nav a {
            color: #fff;
            padding: 14px 20px;
            text-decoration: none;
            display: inline-block;
        }

        nav a:hover {
            background-color: #575757;
        }

        .container {
            max-width: 1200px;
            margin: 20px;
            padding: 20px;
            background: rgba(255, 255, 255, 0.336);
            position: relative;
            z-index: 2;
        }

        .background {
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background: linear-gradient(to top, #222, #333);
            z-index: 1;
            overflow: hidden;
        }

        .car {
            position: absolute;
            width: 100px;
            height: 50px;
            background: red;
            border-radius: 10px;
            animation: moveCar 8s linear infinite;
        }

        .car:nth-child(1) {
            top: 30%;
            animation-duration: 6s;
            background: #00bfff;
        }

        .car:nth-child(2) {
            top: 50%;
            animation-duration: 10s;
            background: #ff5733;
        }

        .car:nth-child(3) {
            top: 70%;
            animation-duration: 12s;
            background: #ffd700;
        }

        @keyframes moveCar {
            0% {
                left: -120px;
            }
            100% {
                left: 110%;
            }
        }

        footer {
            text-align: center;
            padding: 20px 0;
            background-color: rgba(0, 0, 0, 0.8);
            color: #fff;
            position: relative;
            z-index: 2;
        }
    </style>
</head>
<body>
    <div class="background">
        <div class="car"></div>
        <div class="car"></div>
        <div class="car"></div>
    </div>
    <header>
        <a href="https://ucsp.edu.pe/" target="_blank" ><img style="margin: 20px;" src="https://cs.ucsp.edu.pe/img/logo-ucsp.png" height="45" width="100 " alt="Logo UCSP"></a>
        <h1 style="margin: 10px;">DIOMAR MAMANI PACORI</h1>
        <div class="navegador">
            <nav>
                <a href="#about">Sobre mí</a>
                <a href="#projects">Proyectos</a>
                <a href="#contact">Compañeros</a>
                <a href="https://ucsp.edu.pe/carreras/administracion-negocios/" target="_blank">Carrera</a>
                <a href="https://issuu.com/ucsp/docs/malla-administracion-2024" target="_blank">Malla Curricular</a>
            </nav>
        </div>
    </header>
    <div class="container">
        <section id="about">
            <h2>Sobre mí</h2>
            <p>Nombre completo: Diomar Mamani Pacori</p>
            <p>Residencia: Arequipa, Perú</p>
            <p>Centro de Estudios: Universidad Católica San Pablo</p>
            <p>Profesor: Ernesto Cuadro Vargas</p>
        </section>
        <section id="projects">
            <h2>Cursos</h2>
            <p>Pensamiento Computacional</p>
        </section>
        <section id="contact">
            <h2>Compañeros</h2>
            <p><a href="https://eduardomaque.github.io/Eduardo-Sebastian-Mendoza-Maque/" target="_blank">Eduardo Sebastian Mendoza Maque</a></p>
            <p><a href="https://saccbrc-06.github.io/SebastianCastillo.github-io/" target="_blank">Sebastián Adriano castillo carpio</a></p>
            <p><a href="http://rommyna.github.io " target="_blank">Rommyna zuñiga</a></p>
            <p><a href="https://eduardoucsp.github.io/Eduardo-Fabian-Tapia-Rodriguez-Page.github.io/" target="_blank">Eduardo Fabián Tapia Rodríguez</a></p> 
            <p><a href="https://madymads.github.io/" target="_blank">Madai Maricel Rodriguez Vilca</a></p> 
            <p><a href="https://marielaesmeraldaperaltaramos.github.io/Mariela-Esmeralda-Peralta-Ramos/" target="_blank">Mariela Peralta</a></p>
            <p><a href="https://fabian0rtiz.github.io/Fabian-Marcelo-Ortiz-Molina/" target="_blank">Fabian Marcelo Ortiz Molina</a></p> 
            <p><a href="https://danvizcarra.github.io/franciscovizcarra.github.io/" target="_blank">Daniel Francisco Vizcarra Cárdenas</a></p> 
            <p><a href="https://leonardoloayza.github.io/" target="_blank">Leonardo Andre Loayza Paucar</a></p>
            <p><a href="https://ultrones09.github.io/Gadiel-Mateo-Gonzalez-Pamo/" target="_blank">Gadiel Mateo González Pamo</a></p>
            <p><a href="https://fernandaraquelcruzponce.neocities.org/" target="_blank">Fernanda Raquel Cruz Ponce</a></p>
            <p><a href="https://yadhirayurikhocoyuritirado.github.io/yadhirayurikhocoyuri/" target="_blank">Yadhira Yurikho Coyuri Tirado</a></p> 
            <p><a href="https://flabiatunquipa.github.io/mi-pagina-personal/" target="_blank">Flabia Stephanie Tunquipa Paripancca</a></p>
            <p><a href="https://allisonsantandermamani.neocities.org/" target="_blank">Allison Sirene Hadassa Santander Mamani </a></p>
            <p><a href="https://andreasanchezaliaga.github.io/Andrea-Alexandra-S-nchez-Aliaga/" target="_blank">Andrea Alexandra Sánchez Aliaga</a></p> 
            <p><a href="https://salvaramen.github.io/" target="_blank">Salvador Jesús Ramos Mendoza</a></p>
            <p><a href="https://carlosarturovalerosacaky.github.io/" target="_blank">Carlos Arturo Valero Sacaky</a></p>
            <p><a href="https://ayleneyn.github.io/AYLEN-ELENA-YUCRA-NINA/" target="_blank">Aylen Yucra Nina</a></p>
            <p><a href="https://nicolegaldos.neocities.org/" target="_blank">Nicole Alexandra Galdós Champi</a></p>
            <p><a href="https://inal723f.github.io/Carlos-Daniel-Torres-Barreda/" target="_blank">Carlos Daniel Torres Barreda</a></p>
            <p><a href="https://rodrigoguevarahuertaucsp.netlify.app/" target="_blank">Rodrigo Guevara Huerta</a></p>
            <p><a href="https://diegoguzmanucsp.s3.us-east-1.amazonaws.com/index.html" target="_blank">Diego Martín Guzmán Rojas</a> </p>
            <p><a href="https://valeriamayta.github.io/" target="_blank">Valeria Andrea Mayta Butilier</a></p>
            <p><a href="https://aniballa.github.io/Anibal-Lajo-Atayupanqui/" target="_blank">Anibal Lajo Atayupanqui</a></p>
        </section>
    </div>
    <footer>
        <p>&copy; 2024 Juan Pérez. Todos los derechos reservados.</p>
    </footer>
</body>
</html>
