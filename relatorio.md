<h1>Relatório da Atividade Avaliativa de SO - João Heli</h1>

<h2>1. Introdução</h2>
A atividade avaliativa consiste em criar um servidor em Django utilizando uma imagem do Fedora, subsequentemente, executamos os comandos e as alterações necessárias para subir um servidor local, com o propósito de aprender sobre o processo de containeirização no Docker e outras nuances de como o backend (Django) funciona

<br><br>

<h2>2. Relato das Atividades</h2>
<ul>

<li>1. Criei um fork da atividade no repositório indicado pelo professor no VScode</li>
<div align="center">
  <img src="images\1.png" width="300px">
</div>  


<li>2. Segui o passo a passo da atividade, desde o processo de criação do Dockerfile e a execução dos comandos referentes ao seu funcionamento</li>
<div align="center">
  <img src="images\2.png" width="500">
</div>  

<li>3. Rodando o ambiente do Fedora interativamente com a imagem criada</li>
<div align="center">
  <img src="images\3.png" width="500">
</div> 


<li>4. Segui uma série de instruções dentro do container referentes a como configurar um servidor Django:
</li>

<ul>
<li>Criei uma aplicação Django;
</li>
<li>Modifiquei alguns parâmetros como adicionar minha aplicação nos settings e permitir todas as conexões;
</li>

<li>Criei um superusuário que me permite acessar o painel de administrador do Django;
</li>

<li>Criei uma view simples;
</li>

<li>Criei e configurei as URLs do projeto para estabalecer as rotas;
</li>
</ul>

<li>5. Após configurar e estabelecer as configurações necessárias, executei o comando para subir o meu servidor de desenvolvimento, hosteado localmente na máquina, com a página inicial e de administrador funcionando como esperado:</li>

<div align="center">
  <img src="images\4.png" width="700">
</div> 

<div align="center">
  <img src="images\5.png" width="700">
</div> 

<li>6. Observamos no terminal que o servidor está processando as requisições normalmente</li>

<div align="center">
  <img src="images\6.png" width="700">
</div> 

</ul>

<br><br>

<h2>3. Considerações Finais</h2>
A atividade foi bastante proveitosa e enriquecedora, pois possibilitou visualizarmos na prática como implementar uma aplicação conteinerizada de um servidor Django, o processo em si foi relativamente simples e não houveram muitas dúvidas em relação a sua execução. As dificuldades foram mais em relação a utilização de alguns comandos do Linux/Powershell, mas que foram contornadas com consulta na internet.