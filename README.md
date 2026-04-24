<style>
  /* Fondo oscuro y tipografía moderna */
  body {
    background-color: #0d1117; /* GitHub Dark Blue-Gray */
    color: #c9d1d9;
    font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Helvetica, Arial, sans-serif, "Apple Color Emoji", "Segoe UI Emoji";
    line-height: 1.6;
    margin: 0;
    padding: 0;
  }

  /* Contenedor principal para centrar el contenido */
  .container {
    max-width: 900px;
    margin: 0 auto;
    padding: 40px 20px;
  }

  /* Sección de Cabecera (Hero) */
  .hero {
    text-align: center;
    padding: 60px 0;
    border-bottom: 1px solid #30363d;
  }

  .hero h1 {
    font-size: 3rem;
    color: #58a6ff; /* GitHub Blue */
    margin-bottom: 10px;
  }

  .hero p {
    font-size: 1.25rem;
    color: #8b949e;
  }

  /* Estilo para los títulos de sección */
  h2 {
    color: #58a6ff;
    border-bottom: 2px solid #30363d;
    padding-bottom: 10px;
    margin-top: 40px;
  }

  /* Tarjetas de Habilidades (Skills Grid) */
  .skills-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
    gap: 20px;
    margin-top: 20px;
  }

  .skill-card {
    background-color: #161b22;
    border: 1px solid #30363d;
    border-radius: 8px;
    padding: 20px;
    text-align: center;
    transition: transform 0.2s, box-shadow 0.2s;
  }

  .skill-card:hover {
    transform: translateY(-5px);
    box-shadow: 0 5px 15px rgba(88, 166, 255, 0.2);
    border-color: #58a6ff;
  }

  .skill-card img {
    height: 50px;
    margin-bottom: 15px;
  }

  /* Tarjetas de Proyectos */
  .project-card {
    background-color: #161b22;
    border: 1px solid #30363d;
    border-radius: 8px;
    padding: 25px;
    margin-bottom: 20px;
  }

  .project-card h3 {
    margin-top: 0;
    color: #f0f6fc;
  }

  .project-card p {
    color: #8b949e;
  }

  .tag {
    display: inline-block;
    background-color: rgba(88, 166, 255, 0.1);
    color: #58a6ff;
    padding: 5px 10px;
    border-radius: 20px;
    font-size: 0.8rem;
    margin-right: 5px;
    margin-top: 10px;
  }

  /* Botón de Acción Principal */
  .cta-button {
    display: inline-block;
    background-color: #238636; /* GitHub Green */
    color: white;
    padding: 12px 24px;
    text-decoration: none;
    border-radius: 6px;
    font-weight: bold;
    margin-top: 20px;
    transition: background-color 0.2s;
  }

  .cta-button:hover {
    background-color: #2ea043;
  }

</style>

<div class="container">

  <header class="hero">
    <h1>Erick Aloy</h1>
    <p>Ingeniero en Sistemas en Formación | Universidad Técnica de Ambato (FISEI)</p>
    <a href="https://github.com/ErickAloy871" class="cta-button">Ver Perfil Completo de GitHub</a>
  </header>

  <section id="skills">
    <h2>🛠️ Tecnologías Principales</h2>
    <div class="skills-grid">
      
      <div class="skill-card">
        <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/java/java-original.svg" alt="Java" />
        <h3>Java</h3>
        <p>Desarrollo Backend y aplicaciones de escritorio (Swing/Ant).</p>
      </div>

      <div class="skill-card">
        <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/csharp/csharp-original.svg" alt="C#" />
        <h3>C# / .NET</h3>
        <p>Desarrollo en ecosistema Microsoft y lógica de negocios.</p>
      </div>

      <div class="skill-card">
        <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/angularjs/angularjs-plain.svg" alt="Angular" />
        <h3>Angular / TS</h3>
        <p>Creación de interfaces de usuario modernas y escalables (SPA).</p>
      </div>

      <div class="skill-card">
        <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/oracle/oracle-original.svg" alt="Oracle" />
        <h3>Oracle / SQL</h3>
        <p>Diseño avanzado de bases de datos relacionales y gestión de datos.</p>
      </div>

    </div>
  </section>

  <section id="projects">
    <h2>💻 Proyectos Destacados</h2>
    
    <div class="project-card">
      <h3>🎬 Plataforma para Cine</h3>
      <p>Desarrollo de una interfaz web moderna para la gestión y visualización de cartelera de cine.</p>
      <span class="tag">Angular</span>
      <span class="tag">TypeScript</span>
      <span class="tag">UI/UX</span>
    </div>

    <div class="project-card">
      <h3>🚛 Sistema de Logística de Transporte</h3>
      <p>Diseño e implementación de una base de datos relacional para el control de cooperativas y socios de transporte.</p>
      <span class="tag">Oracle Database</span>
      <span class="tag">SQL</span>
      <span class="tag">Data Modeling</span>
    </div>

  </section>

  <footer style="text-align: center; margin-top: 60px; padding-top: 20px; border-top: 1px solid #30363d; color: #8b949e;">
    <p>&copy; 2026 Erick Aloy. Desarrollado y alojado en GitHub Pages.</p>
  </footer>

</div>
