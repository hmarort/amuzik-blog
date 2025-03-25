---
title: Tecnologías
layout: page
description: El stack tecnológico detrás de Amuzik
image: assets/images/tech.jpg
nav-menu: true
permalink: /tecnologias/
---

<!-- Main -->
<div id="main" class="alt">

<!-- One -->
<section id="one">
    <div class="inner">
        <header class="major">
            <h1>{{ page.title }}</h1>
        </header>
        {% if page.image %}<span class="image main"><img src="{{ site.baseurl }}/{{ page.image }}" alt="" /></span>{% endif %}
        
        <h2>Descripción General</h2>
        <p>Amuzik utiliza un conjunto de tecnologías modernas y eficientes para crear una experiencia de usuario de primera clase.</p>

        <h2>Detalles del Stack</h2>
        
        <h3>Frontend</h3>
        <ul>
            <li><strong>Framework Principal</strong>: Ionic 7 con Angular<ul>
                <li>Desarrollo multiplataforma</li>
                <li>Rendimiento y escalabilidad</li>
            </ul></li>
            <li><strong>Lenguaje</strong>: TypeScript<ul>
                <li>Tipado estático</li>
                <li>Mejora la mantenibilidad del código</li>
            </ul></li>
            <li><strong>Diseño UI/UX</strong>: TailwindCSS<ul>
                <li>Diseño responsive</li>
                <li>Personalización rápida y sencilla</li>
            </ul></li>
        </ul>

        <h3>Backend</h3>
        <ul>
            <li><strong>Lenguaje</strong>: PHP<ul>
                <li>Amplia compatibilidad</li>
                <li>Rendimiento optimizado</li>
            </ul></li>
            <li><strong>Framework</strong>: CodeIgniter4 (API REST)<ul>
                <li>Desarrollo ágil</li>
                <li>Seguridad integrada</li>
            </ul></li>
            <li><strong>Base de Datos</strong>: PostgreSQL<ul>
                <li>Alta concurrencia</li>
                <li>Soporte geoespacial</li>
            </ul></li>
            <li><strong>Autenticación</strong>: JWT (JSON Web Token)<ul>
                <li>Seguridad de sesiones</li>
                <li>Stateless authentication</li>
            </ul></li>
        </ul>

        <h3>APIs y Tecnologías Externas</h3>
        <ul>
            <li><strong>Audius API</strong>: <ul>
                <li>Reproducción de música</li>
                <li>Catálogo musical diverso</li>
            </ul></li>
            <li><strong>WebSockets</strong>: <ul>
                <li>Sincronización en tiempo real</li>
                <li>Comunicación bidireccional</li>
            </ul></li>
        </ul>

        <ul class="actions">
            <li><a href="/planificacion/" class="button next">Ver Planificación del Proyecto</a></li>
        </ul>
    </div>
</section>

</div>