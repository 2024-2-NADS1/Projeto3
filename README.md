# FECAP - Fundação Escola de Comércio Álvares Penteado

<p align="center">
<a href= "https://www.fecap.br/"><img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRhZPrRa89Kma0ZZogxm0pi-tCn_TLKeHGVxywp-LXAFGR3B1DPouAJYHgKZGV0XTEf4AE&usqp=CAU" alt="FECAP - Fundação Escola de Comércio Álvares Penteado" border="0"></a>
</p>

# Nome do Projeto

<p><strong>EN: </strong>BODY FEEDBACK BRACELET [BFB]</p>
<p><strong>PT-BR: </strong> PULSEIRA DE ANÁLISE CORPORAL [PAC]</p>

## Nome do Grupo

<P>D4Vz</P>

## Integrantes

<a href="https://github.com/DevGustar">Gustavo Roberto</a> |
<a href="https://github.com/NogGab">Gabriel Nogueira</a> |
<a href="https://github.com/ErikRaimundo">Erik Raimundo</a> |
<a href="https://github.com/eijikanai">Henrique Kanai</a>

## Orientadores

<a href="https://www.linkedin.com/in/victorbarq/?originalSubdomain=br">Dr. Victor Rosetti de Queiroz</a> |
<a href="https://www.linkedin.com/in/lucymari/?originalSubdomain=br">Dra. Lucy Mari Tabuti</a> |
<a href="https://www.linkedin.com/in/eduardo-savino-gomes-77833a10/">Dr. Eduardo Savino Gomes</a> |
<a href="https://www.linkedin.com/in/remuniz/">Dra. Renata Muniz do Nascimento</a> |
<a href="https://www.linkedin.com/in/ronaldo-araujo-pinto-3542811a/">Me. Ronaldo Araujo Pinto</a>

## Descrição

<p>Este projeto consiste em uma <strong>pulseira inteligente</strong> que monitora o bem-estar de pessoas com ansiedade, ajudando-as em momentos de desconforto. Nossa pulseira conta com sensores que medem umidade e temperatura do ambiente, batimentos cardíacos, oxigênio no sangue (SpO₂) e temperatura corporal, monitorando essas variáveis em tempo real. Com essas informações, a pulseira identifica possíveis sinais de estresse ou ansiedade e, através de um site, sugere métodos de autocuidado personalizados para o usuário.</p>

<p align="center">
<img src="https://i.ibb.co/dJCPYRQ/aluno-desenvolvendo-projeto.jpg" alt="Aluno desenvolvendo projeto" border="0">
</p>

## 🛠 Estrutura de pastas

- Raiz<br>

<br>
|-->documentos<br>

<br>
  &emsp;|--> Algoritmos e Lógica de Programação<br>
    &emsp;&emsp;|--> Entrega 1<br>
    &emsp;&emsp;|--> Entrega 2<br>
    &emsp;&emsp;|--> Entrega 3<br>
    &emsp;&emsp;|--> Entrega 4<br>

<br>
  &emsp;|--> Banco de Dados<br>
    &emsp;&emsp;| ModeloConceitual.brM3<br>
    &emsp;&emsp;| ModeloLógico.brM3<br>
    &emsp;&emsp;| ModelosBD.pdf<br>

<br>
  &emsp;|--> Metodos Quantitativos<br>
    &emsp;&emsp;|--> Entrega 1<br>
      &emsp;&emsp;&emsp;| MetodosQuantitativos01.pdf<br>
    &emsp;&emsp;|--> Entrega 2<br>
      &emsp;&emsp;&emsp;| MetodosQuantitativos02.pdf<br>
    &emsp;&emsp;|--> Entrega 3<br>
      &emsp;&emsp;&emsp;| MetodosQuantitativos03.pdf<br>
    &emsp;&emsp;|--> Entrega 4<br>
      &emsp;&emsp;&emsp;| MetodosQuantitativos04.pdf<br>

  <br>
  &emsp;|--> Redes de Computadores<br>
    &emsp;&emsp;|--> Entrega 1<br>
      &emsp;&emsp;&emsp;| RedesDeComputadores01.pdf<br>
    &emsp;&emsp;|--> Entrega 2<br>
      &emsp;&emsp;&emsp;| RedesDeComputadores02.pdf<br>
    &emsp;&emsp;|--> Entrega 3<br>
      &emsp;&emsp;&emsp;| RedesDeComputadores03.pdf<br>
    &emsp;&emsp;|--> Entrega 4<br>
      &emsp;&emsp;&emsp;| RedesDeComputadores04.pdf<br>

  <br>
  &emsp;|--> Sistemas Embarcados e Internet das Coisas<br>
    &emsp;&emsp;|--> Entrega 1<br>
    &emsp;&emsp;|--> Entrega 2<br>
    &emsp;&emsp;|--> Entrega 3<br>
    &emsp;&emsp;|--> Entrega 4<br>

<br>
|-->imagens<br>

<br>
  &emsp;| aluno_desenvolvendo_projeto.jpg<br>
  &emsp;| informações_sensores.jpg<br>

<br>
|-->src<br>

<br>
  &emsp;|-->Backend<br>
  &emsp;|-->Frontend<br>

<br>
| readme.md<br>

## 🛠 Hardwares e Instalação

<p><strong>Componentes necessários</strong></p>
<ul>
  <li>Computador, monitor, mouse, teclado e seus respectivos cabos de alimentação/conexão</li>
  <li>Sistema operacional (windows, linux etc)</li>
  <li>1x ESP32</li>
  <li>1x breadboard (1x)</li>
  <li>13x Jumpers MxF</li>
  <li>6x Jumpers MxM</li>
  <li>1x DHT22</li>
  <li>1x MAX30102</li>
  <li>1x MLX90614</li>
</ul>

<p><strong>Passo a passo para a execução deste projeto</strong></p>
<ul>
  <li>Baixe o <a href="https://www.arduino.cc/en/software">Arduino IDE</a> no site oficial.</li>
  <li>Baixe as bibliotecas utilizadas, sendo:
    <a href="https://www.arduino.cc/en/software">ESP32</a> no site oficial do arduino.
    <a href="https://www.arduino.cc/en/software">DHT22</a> no site oficial do arduino.
    <a href="https://www.arduino.cc/en/software">MAX30102</a> no site oficial do arduino.
    <a href="https://www.arduino.cc/en/software">MLX90614</a> no site oficial do arduino.
  </li>
  </ul>
  <p>Após a instalação de tudo, conectar o protótipo a rede Wi-Fi e então o IP que aparecer na tela, é correspondente ao IP do ESP32. Então basta copiar e colar este mesmo IP no Browser e você
  irá ter acesso à página que terá as informações das devidas detecções dos sensores presentes no projeto.</p>

  ## 🗃 Histórico de Lançamento
  <ul>
    <li><strong>0.1.0</strong> - 22/10/2024: Compra de materiais.</li>
     <li><strong>0.2.0</strong> - 29/10/2024: Estudos sobre exercícios propostos contra estresse/ansiedade.</li>
     <li><strong>0.3.0</strong> - 02/11/2024: Desenvolvimento dos códigos dos sensores, do circuito e página HTML para demonstração das detecçõoes dos sensores.</li>
     <li><strong>0.4.0</strong> - 07/11/2024: Organização do GitHub e pastas.</li>
     <li><strong>0.5.0</strong> - 14/11/2024: Integração às bibliotecas necessárias.</li>
     <li><strong>0.6.0</strong> - 17/11/2024: Conclusão do projeto.</li>
  </ul>


## 📋 Licença/License


## 🎓 Referências

Aqui estão as referências usadas no projeto.

1. <https://www.unimedcampinas.com.br/blog/saude-emocional/6-exercicios-para-acalmar-a-mente>
2. <https://www.tuasaude.com/frequencia-cardiaca/#google_vignette>
3. <https://www.unimed.coop.br/viver-bem/saude-em-pauta/relacao-entre-calor-e-estresse>
4. <https://www.cnnbrasil.com.br/saude/calor-extremo-entenda-como-as-altas-temperaturas-afetam-o-corpo-e-a-saude/>
