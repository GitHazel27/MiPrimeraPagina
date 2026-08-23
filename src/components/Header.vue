<template>
    <header>
        <nav>
           <ul>
            <li><a href="#inicio">Inicio</a></li>
            <li><a href="#sobre-mi">Sobre mí</a></li>
            <li><a href="#educacion">Educación</a></li>
            <li><a href="#experiencia">Experiencia</a></li>
            <li><a href="#habilidades">Habilidades</a></li>
            <li><a href="#contacto">Contacto</a></li>
           </ul> 
        </nav>
    </header>
</template>

<script lang="ts" setup>
</script>

<style scoped>

header{
    font-family: sans-serif;
    font-weight: bold;
    position: sticky;
    top: 0;
    z-index: 1000;
    background-color: #fff;
    box-shadow: 0 4px 15px rgba(0, 0, 0, 0.2);
}
header {
    position: fixed;
    top: 0;
    left: 0;
    width: 100%;
    z-index: 1000;
}

main {
    padding-top: 80px;
}
nav{
    max-width: 100%;
    width: 100%;
    background-color: #ffffff;
    border-radius: 10px;
    width: 100%;
    height: 60px;
    display: block;
    padding: 10px 14px;
    /*box-shadow: 0 8px 25px rgb(4, 4, 4);*/
}

nav ul {
    display: flex;
    justify-content: flex-end;
    align-items: center;
    gap: 2rem;
    margin: 0;
    padding: 0 2rem;
    list-style: none;
}

nav a {
    color: rgb(0, 0, 0);
    font-weight: bold;
    font-size: 1.2rem;
}

html {
    scroll-behavior: smooth;
}

.nav-link {
    color: #000;
    text-decoration: none;
    transition: color 0.3s ease;
}

nav a:hover {
    color: #ff0586;
    background-color: #ffffff;
    border: 3px solid #ff0586;
    border-radius: 30px;
    padding: 5px 10px;
    transform: translateY(-10px);
    box-shadow:0 15px 25px rgba(15, 15, 15, 0.124);
    box-sizing: border-box;
    transition:transform 0..3s ease ;
}
</style>