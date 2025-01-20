
<template>
  <div class="contenedor">
    <!-- Sección de información -->
    <div class="info-container">
      <div class="imagen-container">
        <img
          src="https://upload.wikimedia.org/wikipedia/en/4/47/FC_Barcelona_%28crest%29.svg"
          alt="Liga Deportiva"
        />
        <h3>Acuerdo Ministerial</h3>
        <p>N.º 625 del 19/09/2000</p>
      </div>
      <!-- Línea divisoria -->
      <div class="linea-separadora"></div>
      <div class="texto-container">
        <p>
          Como cada semana, en Fondo Segunda tenemos que nombrar al que es nuestro MVP. En este caso, de la Jornada 22 de La Liga Hyperemotion. No ha sido sencillo escoger esta vez, nunca esto lo es habitual. Tenemos a cuatro candidatos y sólo nos podemos quedar con uno.
        </p>
        <p>
          Varios han sido los detalles que nos han hecho quedarnos con él. Se llama Gelabert, y es un mediocampista de Club de Cielo con una gran visión del juego.
        </p>
      </div>
    </div>

    <!-- Sección del mapa -->
    <div class="map-container">
      <iframe
        src="https://upload.wikimedia.org/wikipedia/en/4/47/FC_Barcelona_%28crest%29.svg"
        width="100%"
        height="300"
        style="border:0;"
        allowfullscreen=""
        loading="lazy"
        referrerpolicy="no-referrer-when-downgrade"
      ></iframe>
    </div>
  </div>
</template>

<script>
export default {
  name: "CampeonatoPage",
};
</script>

<style scoped>
/* Contenedor principal */
.contenedor {
  background-color: #232629;
  color: white;
  padding: 20px;
  font-family: Arial, sans-serif;
}

/* Información principal */
.info-container {
  display: flex;
  gap: 20px;
  align-items: center;
  margin-bottom: 20px;
}

.imagen-container {
  flex: 1;
  text-align: center;
}

.imagen-container img {
  max-width: 100%;
  height: auto;
  border-radius: 10px;
}

.imagen-container h3 {
  margin: 10px 0 5px;
  font-size: 1.2rem;
}

.imagen-container p {
  font-size: 1rem;
  color: #d9d9d9;
}

/* Línea divisoria */
.linea-separadora {
  width: 2px;
  background-color: white;
  height: 100%;
  border-radius: 1px;
}

.texto-container {
  flex: 2;
  text-align: justify;
}

.texto-container p {
  margin-bottom: 10px;
  font-size: 1rem;
  line-height: 1.5;
}

/* Sección del mapa */
.map-container {
  margin-top: 20px;
  border: 2px solid #444;
  border-radius: 10px;
  overflow: hidden;
}
</style>
