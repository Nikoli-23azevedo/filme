<template>
  <div class="hello">
    <bemvindo>Bem-vindo ao meu Primeiro Projeto Front-End - Desenvolvimento Responsivo</bemvindo>
    <h1>Filmes de terror </h1>
    <h2>Edição 2024</h2>

    <div class="image-container">
      <img src="/assets/filmes.png" alt="Logo Filmes de terror" style="width: 100%; border: 2px solid #42b983;">
    </div>

    <table class="custom-table">
      <thead>
        <tr>
          <th>Filme</th>
          <th>data de lançamento</th>
          <th>História</th>
          <th>Imagem</th>
        </tr>
      </thead>
      <tbody>
        <tr>
          <td>A freira</td>
          <td>6 de setembro de 2018</td>
          <td>Presa em um convento na Romênia, uma freira comete suicídio. Para investigar o caso, o Vaticano envia um padre assombrado e uma noviça prestes a se tornar freira. Arriscando suas vidas, a fé e até suas almas, os dois descobrem um segredo profano e se confrontam com uma força do mal que toma a forma de uma freira demoníaca e transforma o convento em um campo de batalha.Presa em um convento na Romênia, uma freira comete suicídio. Para investigar o caso, o Vaticano envia um padre assombrado e uma noviça prestes a se tornar freira. Arriscando suas vidas, a fé e até suas almas, os dois descobrem um segredo profano e se confrontam com uma força do mal que toma a forma de uma freira demoníaca e transforma o convento em um campo de batalha.</td>
          <td><img src="/assets/afreira.jpg" class="imgTabela" alt="A freira"></td>
        </tr>
        <tr>
          <td>Annabelle</td>
          <td>9 de outubro de 2014</td>
          <td>John e Mia Form são atacados por membros de um culto satânico que usa sua velha boneca como um canal para tornar suas vidas miseráveis. Isso desencadeia uma série de eventos paranormais na residência dos Forms</td>
          <td><img src="/assets/Annabelle.jpg" class="imgTabela" alt="Annabelle"></td>
        </tr>
        <tr>
          <td>Invocação do Mal</td>
          <td>13 de setembro de 2013</td>
          <td>Os investigadores paranormais Ed e Lorraine Warren trabalham para ajudar a família aterrorizada por uma entidade demoníaca em sua fazenda.</td>
          <td><img src="/assets/invocacaodomal.webp" class="imgTabela" alt="Infocação do mal"></td>
        </tr>
        <tr>
          <td>It- A Coisa</td>
          <td> 7 de setembro de 2017 </td>
          <td>Um grupo de crianças se une para investigar o misterioso desaparecimento de vários jovens em sua cidade. Eles descobrem que o culpado é Pennywise, um palhaço cruel que se alimenta de seus medos e cuja violência teve origem há vários séculos.</td>
          <td><img src="/assets/itacoisa.webp" class="imgTabela" alt="It- A Coisa"></td>
        </tr>
        <tr>
          <td>Invocação do Mal 2 </td>
          <td>9 de junho de 2016</td>
          <td>Os famosos demonologistas Lorraine e Ed Warren viajam até o norte de Londres. Lá, eles ajudam uma mãe solteira que cria quatro filhos sozinha em uma casa atormentada por espíritos malignos.</td>
          <td><img src="/assets/mal2.jpg" class="imgTabela" alt="Invocação do Mal 2 "></td>
        </tr>
        <tr>
          <td>Terrifier</td>
          <td>31 de outubro de 2016</td>
          <td>Enquanto cuida de duas crianças no halloween, uma babá encontra uma antiga fita VHS no saco de doces. O filme apresenta três contos de terror, todos ligados entre si por um palhaço assassino. Ao longo da noite, coisas estranhas começam a acontecer na casa e a presença do palhaço parece cada vez mais real.</td>
          <td><img src="/assets/terrefier.jpg" class="imgTabela" alt="Terrifier"></td>
        </tr>
        
        
      
      </tbody>
    </table>

    
    <tr>
<td><img src="/assets/carcaca.jpg" class="imgTabela" alt="Carcaça"></td>

<td><img src="/assets/festival.jpg" class="imgTabela" alt="festival"></td>

<td><img src="/assets/bloqueio.jpg" class="imgTabela" alt="bloqueio"></td>
</tr>
    

    <iframe width="976" height="549" src="https://www.youtube.com/embed/Amy6cl9vi88" title="OS 15 MELHORES FILMES DE TERROR DE 2022 | Omelista" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
  height: 90px;
  width: auto;
}

iframe {
  margin-top: 20px;
}
</style>
