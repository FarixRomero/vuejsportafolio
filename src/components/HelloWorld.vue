<template>
  <header>
    <div class="nav">
      <div class="logo">
        <svg
          width="40"
          height="40"
          viewBox="0 0 39 39"
          fill="none"
          xmlns="http://www.w3.org/2000/svg"
        >
          <rect
            x="19.1066"
            y="0.707107"
            width="26.545"
            height="26.0208"
            transform="rotate(45 19.1066 0.707107)"
            stroke="#64FFDA"
          />
          <path
            d="M18.1211 14.4688V23H16.9902V14.4688H18.1211ZM21.6953 18.3066V19.2324H17.875V18.3066H21.6953ZM22.2754 14.4688V15.3945H17.875V14.4688H22.2754Z"
            fill="#64FFDA"
          />
        </svg>
      </div>
      <div class="listnav">
        <ol class="navlinks">
          <li>Sobre mi</li>
          <li>Mi experiencia</li>
          <li>Proyectos</li>
          <li>Contactame</li>
        </ol>
        <div>
          <a href="" class="cv_button"> Descargar CV </a>
        </div>
      </div>
    </div>
  </header>
  <section class="seccion1">
    <div>
      <h5>Hola, mi nombre es</h5>
      <h2>Farix Romero.</h2>
      <h4>Desarrollo aplicativos para la web</h4>
      <p>
        Programador Back-end en php/Laravel. Estudiante de Ingeniería
        informática en la Pontífice Universidad Católica del Perú, perteneciente
        al décimo superior.
      </p>
    </div>
    <div>
      <a class="boton_cv">Descarga mi CV</a>
    </div>
  </section>
  <section class="seccion2">
    <h2>Sobre mi</h2>
    <div class="grid2">
      <div>
        <p>
          Hola!! Mi nombre es Farix Romero y me gusta crear contenido que viva
          en el internet. Me interesa la creación web desde 2017 cuando empece
          mis propios proyectos usando HTML y CSS.
        </p>
        <p>
          He tenido el privilegio de trabajar por más de un año con
          <a
            href="https://us.mullenlowe.com/"
            rel="noopener noreferrer"
            target="_blank"
            >una agencia de emprendimientos EQUIPU.</a
          >
        </p>
        <p>
          Además durante mi carrera universitaria he hecho proyectos freelance
          en diversas categorias.
        </p>
        <p>Aquí mencionaré las tecnologías que uso en mis proyectos.</p>
        <ul class="grid1">
          <li>JavaScript</li>
          <li>HTML y CSS</li>
          <li>PHP</li>
          <li>Laravel</li>
          <li>MySQL</li>
          <li>AWS</li>
          <li>VueJS</li>
          <li>WordPress</li>
        </ul>
      </div>
      <div
        style="display: flex; justify-content: center; align-items: flex-start"
      >
        <div class="wrapper">
          <img
            src="farix.jpg"
            style="width: 100%; mix-blend-mode: multiply"
            alt=""
          />
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: "HelloWorld",
  props: {
    msg: String,
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
.seccion1 {
    height: 100vh;
    display: flex;
    flex-direction: column;
    justify-content: center;
    /* align-items: center; */
    align-items: flex-start;
    width: 85%;
    margin: auto;
    max-width: 1000px;
  }
  .seccion2 {
    display: flex;
    height: 100vh;

    flex-direction: column;
    justify-content: center;
    /* align-items: center; */
    align-items: flex-start;
    width: 85%;
    margin: auto;
    max-width: 1000px;
  }

</style>
