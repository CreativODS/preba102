---
title: "Inicio home"
date: "2025-12-02"
---

<!-- Importamos componentes si los necesitas -->
import ".home.css"

<!-- Hero full-width con imagen de fondo -->
<div className="hero">
  <div className="hero-overlay">
    <h1 className="hero-title-dela">Tu Título en Dela Gothic One</h1>
    <p className="hero-subtitle-inter">Subtítulo o tagline en Inter</p>
  </div>
</div>

<!-- Sección de columnas: texto + imagen -->
<section className="columns two-columns">
  <div className="col-text">
    <p className="inter">we are collaborative supporting</p>
    <h2 className="dela">bridge builders</h2>
    <p className="inter">a nivel interestelar</p>
  </div>
  <div className="col-image">
    <img src="/images/econdmainphoto.png" alt="Descripción foto" />
  </div>
</section>

<!-- Espacio vacío / separador -->
<div className="spacer large"></div>

<!-- Texto centrado con color especial y mezcla de tipografías -->
<section className="center-text">
  <p className="inter">HERE IS THE DEAL, WE CAN ONLY ACHIEVE IT,</p>
  <h2 className="dela highlight">THOGETHER(#F90068)</h2>
</section>

<!-- Sección con dos columnas: celda izquierda y dos celdas a la derecha -->
<section className="columns custom-grid">
  <div className="grid-left">
    <h3 className="dela">Título celda izquierda — Dela Gothic One</h3>
    <p className="inter">Cuerpo en Inter</p>
  </div>
  <div className="grid-right">
    <div className="cell">
      <h3 className="dela">Título celda derecha 1</h3>
      <p className="inter">Texto celda derecha 1</p>
    </div>
    <div className="cell">
      <h3 className="dela">Título celda derecha 2</h3>
      <p className="inter">Texto celda derecha 2</p>
    </div>
  </div>
</section>

<!-- Otro espacio vacío / separador -->
<div className="spacer medium"></div>

<!-- Columna doble: texto + foto otra vez -->
<section className="columns two-columns">
  <div className="col-text">
    <p className="inter">Subtítulo en Inter</p>
    <h2 className="dela">Título en Dela Gothic One</h2>
    <p className="inter">Cuerpo de texto en Inter</p>
  </div>
  <div className="col-image">
    <img src="/images/econdmainphoto.png" alt="Descripción foto" />
  </div>
</section>
