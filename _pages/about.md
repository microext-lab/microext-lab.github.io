---
permalink: /
title: "Grupo de Investigación en Ecología Microbiana de Ambientes Extremos"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<style>
.slider-container {
  width: 100%;
  height: 350px;
  overflow: hidden;
  position: relative;
  border-radius: 8px;
  margin-bottom: 30px;
}

.slider-track {
  display: flex;
  width: calc(200%); /* duplicado para loop perfecto */
  animation: slide 30s linear infinite;
}

.slider-track img {
  width: 10%;   /* 10 imágenes → cada una ocupa 10% */
  height: 350px;
  object-fit: cover;
}

@keyframes slide {
  0%   { transform: translateX(0); }
  100% { transform: translateX(-50%); } /* corre 10 imágenes y engancha el duplicado */
}
</style>



<div class="slider-container">
  <div class="slider-track">
    <img src="/images/banner1.jpg">
    <img src="/images/banner4.JPG">
    <img src="/images/banner3.JPG">
    <img src="/images/banner2.JPG">
    <img src="/images/banner5.JPG">
    <img src="/images/banner8.jpg">
    <img src="/images/banner7.jpg">
    <img src="/images/banner6.jpg">
    <img src="/images/banner9.JPG">
    <img src="/images/banner10.jpg">

    <img src="/images/banner1.jpg">
    <img src="/images/banner4.JPG">
    <img src="/images/banner3.JPG">
    <img src="/images/banner2.JPG">
    <img src="/images/banner5.JPG">
    <img src="/images/banner8.jpg">
    <img src="/images/banner7.jpg">
    <img src="/images/banner6.jpg">
    <img src="/images/banner9.JPG">
    <img src="/images/banner10.jpg">
    
  </div>
</div>


Nuestro grupo estudia la ecología microbiana del suelo, integrando herramientas moleculares, experimentación y análisis bioinformáticos para comprender el rol de las comunidades microbianas en ecosistemas naturales y perturbados, especialmente aquellos afectados por incendios. También abordamos el estudio de biocostras, ambientes extremos y procesos biogeoquímicos en sistemas acuáticos y terrestres.

---

## **Líneas de investigación**

<div style="display: flex; flex-wrap: wrap; gap: 20px; margin-top: 30px;">

  <!-- TARJETA 1 — POST-INCENDIOS (NARANJA) -->
<a href="/linea-postincendios/" style="text-decoration: none;"
    flex: 1 1 30%;
    padding: 20px;
    text-decoration: none;
    background: #FFE4C4; /* naranjita suave */
    border-radius: 12px;
    color: black;
    box-shadow: 0 2px 6px rgba(0,0,0,0.15);
    transition: transform 0.2s ease;
  ">
    <h3 style="margin-top: 0;">Ecología microbiana post-incendios</h3>
    <p style="margin-bottom: 0;">Microbiomas edáficos, pirófilos, severidad y resiliencia.</p>
  </a>

  <!-- TARJETA 2 — ANTÁRTIDA (AZUL) -->
  <a href="/linea-antartida" style="
    flex: 1 1 30%;
    padding: 20px;
    text-decoration: none;
    background: #D6ECFF; /* celestito */
    border-radius: 12px;
    color: black;
    box-shadow: 0 2px 6px rgba(0,0,0,0.15);
    transition: transform 0.2s ease;
  ">
    <h3 style="margin-top: 0;">Ecología microbiana en lagunas de Antártida</h3>
    <p style="margin-bottom: 0;">Matas microbianas, clima extremo y diversidad polares.</p>
  </a>

  <!-- TARJETA 3 — HÍPERSALINOS (VERDE) -->
  <a href="/linea-hipersalinos" style="
    flex: 1 1 30%;
    padding: 20px;
    text-decoration: none;
    background: #DFF5DF; /* verde pastel */
    border-radius: 12px;
    color: black;
    box-shadow: 0 2px 6px rgba(0,0,0,0.15);
    transition: transform 0.2s ease;
  ">
    <h3 style="margin-top: 0;">Geomicrobiología en ambientes hipersalinos</h3>
    <p style="margin-bottom: 0;">Biocostras, cianobacterias y procesos geobiológicos.</p>
  </a>

</div>
---
<h2><strong>Líneas de investigación</strong></h2>

<style>
.lineas-grid {
  display: flex;
  gap: 20px;
  flex-wrap: wrap;
  margin-bottom: 40px;
}

.linea-card {
  flex: 1 1 250px;
  padding: 20px;
  border-radius: 12px;
  color: black;
  text-decoration: none;
  box-shadow: 0 4px 8px rgba(0,0,0,0.1);
  transition: transform 0.2s ease;
}

.linea-card:hover {
  transform: scale(1.03);
}

/* Colores personalizados */
.postfuego { background-color: #ffcc9c; }     /* naranjita */
.hipersalinos { background-color: #d6f5d6; }  /* verde suave */
.antartida { background-color: #d9ecff; }     /* azul clarito */
</style>

<div class="lineas-grid">

  <a class="linea-card postfuego" href="/linea-postincendios">
    <h3>🔥 Ecología microbiana post-incendios</h3>
    <p>Estudio de comunidades edáficas afectadas por fuego.</p>
  </a>

  <a class="linea-card hipersalinos" href="/linea-hipersalinos">
    <h3>🧂 Geomicrobiología de ambientes hipersalinos</h3>
    <p>Procesos microbianos en lagunas y sistemas salinos.</p>
  </a>

  <a class="linea-card antartida" href="/linea-antartida">
    <h3>❄️ Ecología microbiana de lagunas de Antártida</h3>
    <p>Comunidades de matas microbianas en ecosistemas polares.</p>
  </a>

</div>


---
<style>
.cards-container {
  display: flex;
  gap: 20px;
  flex-wrap: wrap;
  margin: 30px 0;
}

.card {
  flex: 1;
  min-width: 260px;
  background-color: #f3f5ff; /* COLOR DEL FONDO → podés cambiarlo */
  padding: 25px;
  border-radius: 12px;
  text-align: center;
  box-shadow: 0 4px 10px rgba(0,0,0,0.1);
  transition: 0.3s;
  font-size: 18px;
}

.card:hover {
  transform: translateY(-5px);
  box-shadow: 0 8px 15px rgba(0,0,0,0.15);
  cursor: pointer;
}

.card a {
  color: #003366;
  font-weight: bold;
  text-decoration: none;
}
</style>

<div class="cards-container">

  <div class="card">
    <a href="{{ site.baseurl }}/lineas/ecologia-fuego.html">
      Ecología microbiana post-incendios
    </a>
  </div>

  <div class="card">
    <a href="{{ site.baseurl }}/lineas/geomicrobiologia-hipersalinos.html">
      Geomicrobiología en ambientes hipersalinos
    </a>
  </div>

  <div class="card">
    <a href="{{ site.baseurl }}/lineas/lagunas-antartida.html">
      Microbiología de lagunas de Antártida
    </a>
  </div>

</div>




## **Coordinadora de grupo: Dra. Cecilia E. Mlewski**

<div style="display: flex; align-items: flex-start; gap: 20px; margin-top: 10px;">

  <img src="{{ site.baseurl }}/images/Ceci-Mlewski.jpg" width="200" style="border-radius: 12px;" alt="Foto de Cecilia">

  <div>
  <em>Bióloga. Investigadora.</em> Mi línea de trabajo aborda el estudio de las comunidades de microorganismos en ambientes extremos desde una perspectiva ecológica, genética y funcional, utilizando técnicas de secuenciación masiva de segunda generación, clonado/Sanger, marcación por hibridación in situ fluorescente y microscopía.

  Dentro de los ambientes extremos encontramos lagos de la Antártida, más precisamente del archipiélago James Ross, donde estudiamos la diversidad microbiológica de matas microbianas asociadas a estos lagos, su dinámica y la importancia de ciertos grupos como posibles proxies relacionados al cambio climático. 

  La Laguna Negra y Terma Los Hornos, en la Puna Catamarqueña, representan otro de nuestros focos de estudio geomicrobiológico, donde buscamos comprender la relación microorganismo–mineral y la señal que esta interacción deja en el registro geológico, con implicancias astrobiológicas.  

  Con cepas de cianobacterias aisladas de la Puna avanzamos en el estudio de la resistencia y la remoción de arsénico. 

  Finalmente, comenzamos a estudiar el efecto del fuego en las comunidades edáficas del Bosque Serrano, su dinámica y la detección de posibles microorganismos pirófilos.
  </div>

</div>

---

## **Investigadora: Dra. Edith Filippini**

<div style="display: flex; align-items: flex-start; gap: 20px; margin-top: 10px;">

  <img src="{{ site.baseurl }}/images/edith.jpg" width="200" style="border-radius: 12px;" alt="Foto de Edith">

  <div>
  <em>Bióloga. Docente e investigadora.</em> Trabajo en ecología de líquenes estudiando cómo se estructuran las comunidades según los diferentes usos del suelo. Actualmente me focalizo en las biocostras del Chaco Seco, investigando su composición, patrones de distribución y la relación con los rasgos funcionales de la vegetación.  

  Soy una de las coordinadoras del proyecto “El Bosque Nativo Vuelve”.
  </div>

</div>

---

## **Investigadora: Dra. Gabriela García**

<div style="display: flex; align-items: flex-start; gap: 20px; margin-top: 10px;">

  <img src="{{ site.baseurl }}/images/gabi.jpeg" width="200" style="border-radius: 12px;" alt="Foto de Gabi">

  <div>
  <em>Geóloga. Docente e investigadora.</em> Mi campo de investigación es el estudio de las fuentes y transformaciones de elementos en el medio exógeno a distintas escalas espaciales y temporales. Estos estudios permiten comprender los procesos que controlan el transporte y la remoción de elementos en medios acuosos y la formación de depósitos.  

  Utilizo técnicas avanzadas de caracterización de geomateriales (XRD, SEM/EDX, EMP, ICP-MS), además de herramientas de luz sincrotrón (XAFS, XRF) y análisis isotópicos. Los procesos observados en el campo son complementados con experimentos de laboratorio y modelado geoquímico.
  </div>

</div>

---

## **Investigadora: Dra. Romina C. Torres**

<div style="display: flex; align-items: flex-start; gap: 20px; margin-top: 10px;">

  <img src="{{ site.baseurl }}/images/romi.jpg" width="200" style="border-radius: 12px;" alt="Foto de Romi">

  <div>
  <em>Bióloga. Docente e investigadora.</em> Me interesa particularmente el estudio de los procesos de regeneración de especies leñosas y la respuesta de la flora a distintos disturbios. También participo en proyectos de extensión y educación ambiental.
  </div>

</div>

