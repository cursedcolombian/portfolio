<script setup>
import {ref} from 'vue'
</script>

<template>
    <div className="flex-inline">
            <div className="label bottom-line">
                <div class="inline">
                    <img src="assets/user.svg" alt="user image" width="32px">
                    <h2>¿Quién soy?</h2>
                </div>
                <p>Mi nombre es Santiago y soy un diseñador multimedia especializado en diseño de interfaces y maquetación web.</p>
                <br>
                <p>Mi objetivo es hacer tu marca mas reconocible en el medio que se observe, ya sea en la web o en tu pieza grafica de eleccion.</p>
                <br>
                <div class="inline">
                    <img src="assets/code.svg" alt="code image" width="32px">
                    <h2>Mis conocimientos</h2>
                </div>
                <p>Tengo conocimientos en la suite de Adobe, Figma y en maquetación web con HTML, CSS, JS, PHP.
                </p>
                <br>
                <div class="inline wrap" style="gap:1rem;">
                    <img width="48px" src="assets/adobecc.svg" alt="CODE LOGO">
                    <img width="48px" src="assets/figma.svg" alt="CODE LOGO">
                    <img width="48px" src="assets/HTML5.svg" alt="CODE LOGO">
                    <img width="48px" src="assets/CSS3.svg" alt="CODE LOGO">
                    <img width="48px" src="assets/js.png" alt="CODE LOGO">
                </div>
                <br>
                <p>
                    Actualmente, estoy fortaleciendo mis habilidades en React, Vue y algunos lenguajes de back-end para gestion de base de datos como MySQL y Firebase.
                </p>
                <br>
                <div class="inline wrap" style="gap:1rem;">
                    <img width="48px" src="assets/PHP.svg" alt="CODE LOGO">
                    <img width="48px" src="assets/react.svg" alt="CODE LOGO">
                    <img width="48px" src="assets/vue.svg" alt="CODE LOGO">
                    <img width="88px" src="assets/mysql.png" alt="CODE LOGO">
                    <img width="48px" src="assets/firebase.svg" alt="CODE LOGO">
                </div>
                <br>
            </div>
            <div className="label bottom-line">
                <div class="inline">
                <img src="assets/exp.svg" width="32px" alt=""><h2 id="exp">Experiencia</h2>
                </div>
                <h3>- Como diseñador de interfaces y piezas graficas -</h3>
                <p>
                    Desarrollo de piezas gráficas, interfaces de usuario y creación de contenido 
                    variado enfocado para uso interno dedicado a marcas como Coca-Cola México, 
                    Bancolombia, Teleperformance, Avianca y Arcos Dorados Argentina.

                </p>
                <br>
                <a href="#" >
                    <img src="assets/figma.svg" width="32px" alt="figma">
                    Mis proyectos en Figma
                </a>
                <br>
                <h3>- Como diseñador // maquetador y desarrollador web -</h3>
                <p>Desarrollo Pagina web e Eccomerce:
                </p>
                <br>
                <a href="https://mayfersantabarbara.com.co/index.php" target="_blank">
                    <img src="assets/mayfer.svg" width="32px" alt="mayfer ico">
                    Compañia Mayfer SB
                </a>
                <br>
                <p>
                    Desarrollo de pagina web y catalogo estatico:
                </p>
                <br>
                <a href="https://pyctecnologia.com.co/" target="_blank">
                    <img src="assets/pyc.png" width="32px" alt="pyc ico">
                    PYC | Tecnologia y Suministros
                </a>
            </div>
        </div>
</template>