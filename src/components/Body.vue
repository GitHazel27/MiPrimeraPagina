<script lang="ts" setup>
import fcaImage from '../assets/imagenes/FCA.jpg'
import prepaImage from '../assets/imagenes/prepa.jpeg'
import modeloImage from '../assets/imagenes/modelo.jpg'
import delsolImage from '../assets/imagenes/delSol.png'
import yoImage from '../assets/imagenes/yo1.png' 
import joyeriaImage from '../assets/imagenes/joyeria.jpeg'
</script>

<template>
    <main></main>
        <section id="inicio" class="hero">
            <div class="wrapper-inicio">
                <div class="inicio-yo">
                    <img :src="yoImage" alt="Foto de Hazel Silva Puerto" class="yo-image"/>
                </div>
                <div class="inicio-texto">
                ¡Hola, soy Hazel Silva!
                </div>
            </div>
        </section>
        <section id="sobre-mi" class="sobremi">
            <div class="wrapper">
                <h2>Sobre mí</h2>
                <p>Soy estudiante de la Licenciatura en Administración de Tecnologías de Información en la Universidad Autónoma de Yucatán. Tengo interés en el área de programación y en el desarrollo de soluciones mediante la tecnología.</p><p>Cuento con conocimientos en programación utilizando Java y Python, así como formación en Inteligencia Artificial y Microsoft Copilot.</p><p>Además de mi formación académica, cuento con experiencia en atención al cliente, ventas, inventarios y organización de productos. También soy responsable de un emprendimiento propio de joyería, experiencia que me ha permitido desarrollar habilidades de organización, comunicación, administración y atención al cliente.</p><p>Me considero una persona responsable, organizada, con facilidad para trabajar en equipo y con disposición para aprender constantemente.</p>
            </div>
        </section>
        <section id="educacion" class="educacion">
            <div class="wrapper">
                <h2>Educación</h2>
                <p>Formación enfocada en tecnologías de la información, administración y desarrollo de habilidades relacionadas con el entorno tecnológico.</p>
                <div class="tarjetas">
                    <div class="tarjeta">
                        <div class="tarjeta-imagen">
                            <img :src="fcaImage" alt="Logo de la UADY" />
                        </div>
                        <div class="tarjeta-contenido">
                            <h3>Facultad de Contaduría y Administración — UADY</h3>
                            <p>Licenciatura en Administración de Tecnologías de Información</p>
                            <p><i>Actualmente cursando</i></p>
                        </div>
                    </div>
                    <div class="tarjeta">
                        <div class="tarjeta-imagen">
                            <img :src="prepaImage" alt="Logo de la Preparatoria Abierta" />
                        </div>
                        <div class="tarjeta-contenido">
                            <h3>Preparatoria Abierta — Dirección de Educación Media Superior</h3>
                            <p>Educación Media Superior</p>
                            <p><i>2021 – 2023</i></p>
                        </div>
                    </div>
                    <div class="tarjeta">
                        <div class="tarjeta-imagen">
                            <img :src="modeloImage" alt="Logo de la Preparatoria Modelo" />
                        </div>
                        <div class="tarjeta-contenido">
                            <h3>Preparatoria Modelo</h3>
                            <p>Educación Media Superior</p>
                            <p><i>2019 – 2020</i></p>
                        </div>
                    </div> 
                </div>      
            </div>
        </section>
        <section id="experiencia" class="experiencia">
            <br><br><h2>Experiencia Laboral</h2>
            <div class="emprendimiento">
                <div class="emprendimiento-contenido">
                    <h3>EMPRENDIMIENTO DE JOYERÍA</h3>
                    <p>Actualmente soy responsable de un emprendimiento propio de joyería, lo que me ha permitido desarrollar habilidades de organización, comunicación, administración y atención al cliente.</p><br>
                    <h4>Principales actividades:</h4>
                    <ul>
                        <li>Atención y seguimiento a clientes.</li>
                        <li>Venta y promoción de productos.</li>
                        <li>Organización y control de inventario.</li>
                        <li>Preparación y presentación de productos.</li>
                        <li>Participación en bazares.</li>
                        <li>Organización de pedidos.</li>
                        <li>Administración de las actividades del emprendimiento.</li>
                    </ul>
                </div>
                <div class="emprendimiento-foto">
                    <img :src="joyeriaImage" alt="Imagen del emprendimiento de joyería" class="joyería-foto" />
                </div>
            </div>
            <div class="separador-experiencia" aria-hidden="true"></div>
            <div class="wrapper-experiencia">
                <div class="experiencia-contenido">
                    <h3>GRUPO COMERCIAL DSW, S.A. DE C.V.</h3>
                    <p><b>Auxiliar de Departamento — Enseres Menores</b></p>
                    <p><i>4 de septiembre de 2023 – 11 de diciembre de 2023</i></p><br>
                    <h4>Principales actividades:</h4>
                    <ul>
                        <li>Atención y orientación a clientes</li>
                        <li>Apoyo en ventas</li>
                        <li>Revisión y organización de inventario</li>
                        <li>Organización de productos en piso de venta</li>
                        <li>Mantenimiento del área de trabajo</li>
                        <li>Apoyo en actividades generales del departamento</li>
                    </ul>
                </div>
                <div class="experiencia-logo">
                    <img :src="delsolImage" alt="Logo de Del Sol" class="delsol-image"/>
                </div>
            </div>
        </section>
        <section id="habilidades" class="habilidades">
            <h2>Habilidades</h2>
            <div class="wrapper-habilidades">
                <div class="wrapper-habilidadestec">
                    <h3>HABILITADES TÉCNICAS</h3><br>
                    <ol>
                        <li>Java<br>Conocimientos de programación y desarrollo de programas utilizando Java.</li>
                        <li>Python<br>Conocimientos básicos de programación y desarrollo de programas utilizando Python.</li>
                        <li>Microsoft Copilot<br>Conocimientos adquiridos mediante cursos relacionados con Inteligencia Artificial y herramientas tecnológicas.</li>
                    </ol>
                </div>
                <div class="wrapper-habilidadesprof">
                    <h3>HABILIDADES PROFESIONALES</h3><br>
                    <ol>
                        <li>Atención al cliente<br>Capacidad para brindar atención, resolver dudas y mantener una comunicación adecuada con los clientes.</li>
                        <li>Ventas<br>Experiencia en promoción y venta de productos.</li>
                        <li>Trabajo en equipo<br>Capacidad para colaborar con otras personas y participar en actividades grupales.</li>
                        <li>Organización<br>Experiencia en organización de productos, inventarios, pedidos y actividades de un emprendimiento.</li>
                    </ol>
                </div>
            </div>
        </section>
</template>



<style scoped>
.hero {
    background-color: #ff097813;
    padding: 4rem 0 0;
    text-align: center;
}
.sobremi {
    padding: 4rem 0;
    text-align: center;
    border-width: 60px;
    border-color: #ff0586;
}

.educacion {
    background-color: #ff097813;
    padding: 4rem 0;
    text-align: center;
}

.educacion .wrapper {
    display: flex;
    flex-direction: column;
    align-items: center;
    text-align: center;
}

h2 {
    font-size: 2.5rem;
    margin-bottom: 1rem;
    font-weight: bold;
    text-align: center;
}

section {
    scroll-margin-top: 80px;
}

p {
    font-size: 1rem;
    line-height: 1.5;
    margin-bottom: 1rem;
    text-align: justify;
    margin: 0;
    margin-left: 10%;
    margin-right: 10%;
}

.educacion > .wrapper > p {
    max-width: 700px;
    margin-left: auto;
    margin-right: auto;
    text-align: center;
    margin-bottom: 2rem;
}

.tarjeta {
    width: 280px;
    aspect-ratio: 1 / 1;
    padding: 24px;
    box-sizing: border-box;
    display: flex;
    flex-direction: column;
    
    text-align: center;
    background-color: #fff;
    border: 2px solid #ff0586;
    border-radius: 16px;
    box-shadow: 0 6px 15px rgba(0, 0, 0, 0.15);
    transition: transform 0.3s ease, box-shadow 0.3s ease;
}

.tarjeta-imagen {
    height: 40%;
    min-height: 100px;
    display: flex;
    justify-content: center;
    align-items: center;
}

.tarjeta-imagen img {
    width: 100%;
    height: 100%;
    object-fit: contain;
}

.tarjeta-contenido {
    flex: 1;
    display: flex;
    flex-direction: column;
    justify-content: center;
    text-align: center;
}


.tarjeta:hover {
    transform: translateY(-8px);
    box-shadow: 0 12px 25px rgba(255, 5, 134, 0.3);
}

.tarjetas {
    display: flex;
    justify-content: center;
    gap: 2rem;
    flex-wrap: wrap;
    gap: 18px;
    
}
@media (max-width: 600px) {
    .tarjeta {
        width: 90%;
        max-width: 280px;
    }
}

h3 {
    margin-top: 0.5rem;
    font-weight: bold;
    justify-content: center;
}

.tarjeta p {
    margin: 0.5rem 0;
    text-align: center;

}

.emprendimiento {
    display: grid;
    grid-template-columns: repeat(2, minmax(0, 1fr));
    align-items: center;
    gap: 2rem;
    padding: 4rem 10%;
    border-width: 60px;
    border-color: #ff0586;
}
.emprendimiento-contenido {
    text-align: left;
}
.emprendimiento-contenido p {
    margin-left: 0;
    margin-right: 0;
}

.emprendimiento-foto {
    display: flex;
    justify-content: center;
    align-items: center;
    min-height: 100%;
}

.joyería-foto {
    width: min(70%, 260px);
    height: auto;
    object-fit: contain;
}
@media (max-width: 600px) {
    .emprendimiento {
        grid-template-columns: 1fr;
        padding: 2rem 10%;
    }

    .emprendimiento-contenido {
        text-align: center;
    }
}

.separador-experiencia {
    height: 2px;
    margin: 0 10%;
    background-color: #ff05862b;
}

.wrapper-experiencia {
    display: grid;
    grid-template-columns: repeat(2, minmax(0, 1fr));
    align-items: center;
    gap: 2rem;
    padding: 4rem 10%;
    border-width: 60px;
    border-color: #ff0586;
}

.experiencia-contenido {
    text-align: left;
}

.experiencia-contenido p {
    margin-left: 0;
    margin-right: 0;
}

.experiencia-logo {
    display: flex;
    justify-content: center;
    align-items: center;
    min-height: 100%;
}

.delsol-image {
    width: min(70%, 260px);
    height: auto;
    object-fit: contain;
}

@media (max-width: 600px) {
    .wrapper-experiencia {
        grid-template-columns: 1fr;
        padding: 2rem 10%;
    }

    .experiencia-contenido {
        text-align: center;
    }
}

.inicio-yo {
    display: flex;
    justify-content: center;
    align-items: flex-end;
    margin-bottom: 0%;
}

.yo-image {
    display: block;
    width: 300px;
    height: 300px;
    object-fit: cover;
    margin-bottom: 0

}

.wrapper-inicio {
    display: grid;
    grid-template-columns: repeat(2, minmax(0, 1fr));
    align-items: end;
    gap: 0;
    padding: 0 10%;
}

.inicio-texto {
    text-align: left;
    font-size: 100px;
    font-weight: bold;
}

@media (max-width: 600px) {
    .hero {
        padding: 2rem 0;
    }

    .wrapper-inicio {
        grid-template-columns: 1fr;
        gap: 0;
        padding: 2rem 10%;
    }

    .inicio-yo {
        margin: 0;
    }

    .yo-image {
        width: min(100%, 280px);
        height: auto;
        aspect-ratio: 1 / 1;
    }

    .inicio-texto {
        font-size: clamp(2rem, 10vw, 3rem);
        text-align: center;
    }
}

.habilidades {
    background-color: #ff097813;
    padding: 4rem 0;
    text-align: center;
}
.wrapper-habilidades {
    display: grid;
    grid-template-columns: repeat(2, minmax(0, 1fr));
    align-items: start;
    gap: 2rem;
    padding: 4rem 10%;
    border-width: 60px;
    border-color: #ff0586;
}

.wrapper-habilidadestec ol, .wrapper-habilidadesprof ol{
    text-align: left;
}

.wrapper-habilidadesprof {
    border-left: 3px solid #ff05862b;
    padding-left: 2rem;
}

@media (max-width: 600px) {
    .wrapper-habilidades {
        grid-template-columns: 1fr;
        padding: 2rem 10%;
    }

    .wrapper-habilidadesprof {
        border-left: 0;
        padding-left: 0;
    }
}
</style>