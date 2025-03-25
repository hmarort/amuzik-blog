---
title: Amuzik
layout: post
description: 'Aplicación de reproducción de música con sincronización en tiempo real entre usuarios.'
image: assets/images/amuzik.jpg
nav-menu: true
permalink: /amuzik/
---

<!-- Main -->
<div id="main" class="alt">

<!-- One -->
<section id="one">
    <div class="inner">
        <header class="major">
            <h1>Amuzik</h1>
        </header>
        <p><strong>Tipo:</strong> Aplicación de reproducción de música con sincronización en tiempo real entre usuarios.</p>
        <p><strong>Inspiración:</strong> Spotify + Spicetify</p>
        <p><strong>Objetivo:</strong> Permitir a los usuarios escuchar la misma canción al mismo tiempo desde diferentes lugares.</p>

        <h2>Tecnologías</h2>
        <h3>Frontend</h3>
        <ul>
            <li><strong>Framework:</strong> Ionic 7 con Angular</li>
            <li><strong>Lenguaje:</strong> TypeScript</li>
            <li><strong>UI/UX:</strong> TailwindCSS</li>
        </ul>
        
        <h3>Backend</h3>
        <ul>
            <li><strong>Lenguaje:</strong> PHP</li>
            <li><strong>Framework:</strong> CodeIgniter4 (API REST)</li>
            <li><strong>Base de Datos:</strong> PostgreSQL</li>
            <li><strong>Autenticación:</strong> JWT (JSON Web Token)</li>
        </ul>
        
        <h3>APIs Externas</h3>
        <ul>
            <li><strong>YouTube API:</strong> Reproducción de música</li>
            <li><strong>WebSockets (PHP Ratchet o Node.js):</strong> Sincronización en tiempo real</li>
        </ul>

        <h2>Planificación del Proyecto</h2>
        <h3>1. Planificación Inicial</h3>
        <table>
            <tr><th>Fase</th><th>Fecha de Inicio</th><th>Fecha de Fin</th></tr>
            <tr><td>Definición de Funcionalidades</td><td>18/03/2025</td><td>20/03/2025</td></tr>
            <tr><td>Análisis del Proyecto</td><td>21/03/2025</td><td>09/04/2025</td></tr>
            <tr><td>Definición del Entorno</td><td>21/03/2025</td><td>25/03/2025</td></tr>
            <tr><td>Definición de Herramientas</td><td>26/03/2025</td><td>01/04/2025</td></tr>
            <tr><td>Definición del Modelo de Datos (E/R)</td><td>02/04/2025</td><td>09/04/2025</td></tr>
        </table>

        <h3>2. Diseño y Arquitectura</h3>
        <table>
            <tr><th>Fase</th><th>Fecha de Inicio</th><th>Fecha de Fin</th></tr>
            <tr><td>Diseño de Datos</td><td>10/04/2025</td><td>10/04/2025</td></tr>
            <tr><td>Diseño de Clases</td><td>11/04/2025</td><td>15/04/2025</td></tr>
            <tr><td>Diseño de la UI (Colores y Temas)</td><td>16/04/2025</td><td>16/04/2025</td></tr>
            <tr><td>Definición de la Estructura de la Aplicación</td><td>17/04/2025</td><td>18/04/2025</td></tr>
        </table>

        <h3>3. Implementación</h3>
        <table>
            <tr><th>Fase</th><th>Fecha de Inicio</th><th>Fecha de Fin</th></tr>
            <tr><td>Desarrollo de la Interfaz Gráfica</td><td>18/04/2025</td><td>11/06/2025</td></tr>
            <tr><td>Desarrollo del Backend</td><td>18/04/2025</td><td>11/06/2025</td></tr>
        </table>

        <h3>4. Pruebas y Ajustes Finales</h3>
        <table>
            <tr><th>Fase</th><th>Fecha de Inicio</th><th>Fecha de Fin</th></tr>
            <tr><td>Pruebas Unitarias y de Integración</td><td>12/06/2025</td><td>20/06/2025</td></tr>
            <tr><td>Creación del Manual de Usuario</td><td>23/06/2025</td><td>24/06/2025</td></tr>
            <tr><td>Implantación y Cierre</td><td>25/06/2025</td><td>25/06/2025</td></tr>
        </table>

        <h2>Módulos Principales</h2>
        <h3>Módulo de Usuarios</h3>
        <ul>
            <li>Registro e inicio de sesión con autenticación segura.</li>
            <li>Creación, edición y eliminación de cuentas.</li>
            <li>Lista de amigos (agregar, aceptar, rechazar solicitudes).</li>
            <li>Perfiles de usuario con configuración personalizada.</li>
        </ul>

        <h3>Módulo de Reproducción de Música</h3>
        <ul>
            <li>Reproducción de canciones desde la API de YouTube.</li>
            <li>Control de reproducción (pausar, avanzar, retroceder).</li>
            <li>Sincronización con otros usuarios en tiempo real.</li>
        </ul>

        <h3>Módulo de Sincronización y Conexión</h3>
        <ul>
            <li>Creación de salas privadas para escuchar juntos.</li>
            <li>Uso de WebSockets para sincronización en tiempo real.</li>
            <li>Opción de invitar amigos a una sesión en curso.</li>
        </ul>

        <h3>Módulo de Personalización</h3>
        <ul>
            <li>Cambio de temas (claro, oscuro, colores personalizados).</li>
            <li>Modificación del tamaño de elementos (fuentes, botones).</li>
        </ul>
    </div>
</section>

</div>