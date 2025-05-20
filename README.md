<!DOCTYPE html>
<html>
<head>
<style>
body {
  background-color: #f0f0f0; 
}

h1 {
  text-align: center; 
  color: #333; 
}

p {
  text-align: justify; 
  font-size: 1.2em; 
}

ul {
  list-style-position: inside; 
  padding-left: 0; 
}

ul li {
  margin-bottom: 0.5em; 
}

img {
  border-radius: 5px; 
  max-width: 100%; 
  height: auto; 
}

table {
  width: 100%; 
  border-collapse: collapse; 
}

th, td {
  border: 1px solid #ddd; 
  padding: 8px;
  text-align: left; 
}

a {
  color: #007bff; 
}

a:hover {
  color: #0056b3; 
}
</style>

</head>
<body>
<h1>Samuel Dias França Silva</h1>
<p>Eu me chamo Samuel Dias França Silva, tenho 18 anos, e sou atleta de judô. Moro no Guará, RA do DF.</p>

 <h2>Lista de hobbies</h2>
 <ul>
  <li>Ir ao Lago Paranoá;</li>
  <li>Dirigir;</li>
  <li>Ouvir músicas.</li>
 </ul>

 <h2>imagem do hobbie</h2>
  <img src="https://s2-oglobo.glbimg.com/ufsqwlapJ3rrYgbIFsk-JdFNCwY=/0x0:6720x4480/888x0/smart/filters:strip_icc()/i.s3.glbimg.com/v1/AUTH_da025474c0c44edd99332dddb09cabe8/internal_photos/bs/2023/U/0/6xiAwUTiqo8yRmLJL6Hw/103283802-pa-brasilia-df-06-06-2023-especial-lago-paranoa-ponte-juscelino-kubitschek-fotogra.jpg" width="250">

 <h2>Tabela com Países que gostaria de vizitar</h2>
  <table border="1">
   <tr>
     <th>País</th>
     <th>Imagem</th>
   </tr>
   <tr>
    <td>Itália</td>
    <td><img src="https://logodownload.org/wp-content/uploads/2023/09/bandeira-italy-flag-4.png" width="250"></td>
   </tr>
   <tr>
    <td>Espanha</td>
    <td><img src="https://upload.wikimedia.org/wikipedia/commons/thumb/9/9a/Flag_of_Spain.svg/800px-Flag_of_Spain.svg.png" width="250"></td>
   </tr>
   <tr>
    <td>Egito</td>
    <td><img src="https://upload.wikimedia.org/wikipedia/commons/thumb/f/fe/Flag_of_Egypt.svg/800px-Flag_of_Egypt.svg.png" width="250""></td>
   </tr>
  </table>
 
  <h2>Link do site</h2>
  <a href="https://pt.wikipedia.org/wiki/Wikip%C3%A9dia:P%C3%A1gina_principal">Ir para Wiki</a>
  
<h2><p>Info.</p></h2>
<button id="botao">Clique para ver uma mensagem!</button>
<div id="mensagem"></div>

<script>

document.getElementById('botao').onclick = function() {
  document.getElementById('mensagem').innerHTML = 'Seja bem-vindo(a), volte sempre!.';
};

</script>


</body>
</html>


