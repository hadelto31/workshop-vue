

<template>
  <b-card mt-5>
    <b-container>
      <b-row>
        <b-col class="text-center" col lg="1">
          <b-img
            src= "https://peaku.io/img/logo-blue.png"
            img-alt="Card image"
            img-left
            class="mb-3"
            style="width: 65%; height: 65%; fluid "
          />
        </b-col>
        <b-col>
          <b-card-text>
            <div>
              
                <h6 >{{ vacante }}</h6>
                <p >{{ habilidades }}</p>
              
            </div>

            <p>{{ empresa }}</p>
            <p>{{ ubicacion }}</p>
            <p>{{ sueldo }}</p>
            <p>{{ vacantes }}</p>
            <p>{{ dias }}</p>
          </b-card-text>
        </b-col>
      </b-row>
    </b-container>
  </b-card>
</template>




<script>
export default {
  props: {
    rutaimg: String,
    vacante: String,
    habilidades: String,
    empresa: String,
    ubicacion: String,
    sueldo: String,
    vacantes: Number,
    dias: String,
  },
};
</script>

<style scoped>
h6, p {
  display: inline-block;
  margin: 0;
  margin-right: 20px;
}
</style>

