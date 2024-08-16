<template>
  <div class="hello">
    <bemvindo>Bem-vindo ao meu Primeiro Projeto Front-End - Desenvolvimento Responsivo</bemvindo>
    <h1>S DE PÁSCOA CACAU SHOW</h1>
    <h2>Edição 2024</h2>

    <div class="image-container">
      <img src="@/assets/cacaulogo.png" alt="Logo Cacau Show" style="width: 100%; border: 2px solid #42b983;">
    </div>

    <table class="custom-table">
      <thead>
        <tr>
          <th>nome</th>
          <th>data de lançamento</th>
          <th>História</th>
          <th>Imagem</th>
        </tr>
      </thead>
      <tbody>
        <tr>
          <td>A freira</td>
          <td>6 de setembro de 2018</td>
          <td>Um padre e uma noviça chegam à Romênia para investigar a morte de uma jovem freira. No entanto, as coisas tomam um rumo feio depois que eles encontram uma força sobrenatural.</td>
          <td><img src="@/assets/afreira.jpg" class="imgTabela" alt="A freira "></td>
        </tr>
        <tr>
          <td>Annabelle</td>
          <td>9 de outubro de 2014</td>
          <td>John e Mia Form são atacados por membros de um culto satânico que usa sua velha boneca como um canal para tornar suas vidas miseráveis. Isso desencadeia uma série de eventos paranormais na residência dos Forms</td>
          <td><img src="@/assets/annabele.jpg" class="imgTabela" alt="Annabelle "></td>
        </tr>
        <tr>
          <td>Castanha do Pará</td>
          <td>170g</td>
          <td>R$39,90</td>
          <td><img src="@/assets/invocacaodomal.webp" class="imgTabela" alt="Castanha do Pará "></td>
        </tr>
        <tr>
          <td>Ninho</td>
          <td>300g</td>
          <td>R$55,90</td>
          <td><img src="@/assets/itacoisa.webp" class="imgTabela" alt="Ninho "></td>
        </tr>
        <tr>
          <td>Trufado</td>
          <td>220g</td>
          <td>R$45,90</td>
          <td><img src="@/assets/mal2.png" class="imgTabela" alt="Trufado "></td>
        </tr>
        <tr>
          <td>Trufado</td>
          <td>220g</td>
          <td>R$45,90</td>
          <td><img src="@/assets/panico.jpg" class="imgTabela" alt="Trufado "></td>
        </tr>
        <tr>
          <td>Caramelo Salgado</td>
          <td>180g</td>
          <td>R$37,90</td>
          <td><img src="@/assets/caramelo.png" class="imgTabela" alt="Caramelo Salgado "></td>
        </tr>
      </tbody>
    </table>

    <iframe src="https://www.youtube.com/embed/QZWg_n1YAts?si=E5LwDNgLX3yOTMDO" width="100%" height="400px" frameborder="0" allowfullscreen></iframe>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>

<style scoped>
.bemvindo {
  color: #42b983;
  font-size: 24px;
  margin-bottom: 10px;
}

h1 {
  font-size: 36px;
}

h2 {
  font-size: 24px;
}

.image-container {
  text-align: center;
  margin-bottom: 20px;
}

.custom-table {
  width: 100%;
  border-collapse: collapse;
  margin-top: 20px;
  box-shadow: 0 4px 8px rgba(0,0,0,0.1);
}

.custom-table th, .custom-table td {
  border: 1px solid #ddd;
  padding: 10px;
  text-align: center;
}

.custom-table th {
  background-color: #f2f2f2;
}

.imgTabela {
  height: 80px;
  width: auto;
}

iframe {
  margin-top: 20px;
}
</style>
