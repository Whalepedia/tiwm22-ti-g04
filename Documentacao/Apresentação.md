#	Relatório

* O relatório pode ser encontrado [Aqui](../README.md).

# Apresentação

* A apresentação pode ser encontrada [Aqui](../Documentacao/Apresenta%C3%A7aotr.md)




# Demonstração do cumprimento dos requisitos mínimos solicidados pelo Docente:

##	Área temática: “Animais”: 

* O tema escolhido para o site são "baleias", o que condiz com o tema. 


##	4 páginas HTML estáticas;

* O site contém, atualmente, 5 (cinco) páginas estáticas. 

Segue abaixo, a listagem de todas as páginas estáticas do projeto:

- [Página inicial (index)](https://tiwm22-ti-g04.netlify.app/index.html): [Código HTML](../src/index.html), [Código CSS](../src/styles/index.css).

- [Página Espécies](https://tiwm22-ti-g04.netlify.app/pages/especies.html): [Código HTML](../src/pages/especies.html), [Código CSS](../src/styles/escecies.css).

- [Página Alimentação](https://tiwm22-ti-g04.netlify.app/pages/alimentacao.html): [Código HTML](../src/pages/alimentacao.html), [Código CSS](../src/styles/alimentacao.css).

- [Página Reprodução](https://tiwm22-ti-g04.netlify.app/pages/reproducao.html): [Código HTML](../src/pages/reproducao.html), [Código CSS](../src/styles/common.css).

- [Página Curiosidades](https://tiwm22-ti-g04.netlify.app/pages/curiosidades.html): [Código HTML](../src/pages/curiosidades.html), [Código CSS](../src/styles/common.css).


##	1 documento XML e respetivo schema para validação

* O projeto também conta com 1 documento [XML](../src/data/dataset.xml) e seu respetivo schema para validação ([XSD](../src/data/dataset.xsd)), o qual está integrado de forma orgânica parcialmente ao HTML, como consta na página [alimentação](https://tiwm22-ti-g04.netlify.app/pages/alimentacao.html), slide 1. Tal integração foi feita utilizando a linguagem de programação Javascript e o CSS. Neste caso específico, optou-se por acrescentar a integração do XML a página de alimentação, slide 1, para guardar as informações da tabela apresentada. 


#	Os documentos HTML deverão apresentar uma correta marcação semântica do conteúdo:	
##	uso correto dos elementos section, article, nav, aside, address, header, footer, figure, main, div, ...

* Verificação constante em: 
Ex: 

        <Nav>,<main>, <footer>, <address>, etc.

- [Página inicial (index) Código HTML](../src/index.html).

- [Página Espécies Código HTML](../src/pages/especies.html).

- [Página Alimentação Código HTML](../src/pages/alimentacao.html).

- [Página Reprodução Código HTML](../src/pages/reproducao.html).

- [Página Curiosidades Código HTML](../src/pages/curiosidades.html).
- 
#	Nos documentos HTML deverá existir pelo menos um exemplo de:
##	tabela – com utilização de elementos/atributos thead, tbody, tfoot e rowspan e colspan;

* Uma table com todos os requisitos elencados, foi utilizada no código HTML da página [Alimentação](../src/pages/alimentacao.html), linhas 47 a 74.

            <table>
              <thead>
                  <tr>
                    <th colspan="4">Alimentação</th>
                  </tr>
                  <tr>
                    <td>Nome</td>
                    <td>Alimento</td>
                    <td>Quantidade</td>
                    <td>Local</td>
                  </tr>
              </thead>
              <tbody id="corpoTable">
               
              </tbody>
              <tfoot>
                <tr>
                  <td rowspan="2" colspan="2">fonte: </td>
                  <td><a href="https://www.natgeo.pt/animais/2021/11/as-baleias-comem-tres-vezes-mais-do-que-se-pensava">Natgeo.pt</a></td>
                  <td>tirou-se <strong>Quantidade</strong></td>
                </tr>
                <tr>
                  
                  <td><a href="https://www.quecomem.com/o-que-as-baleias-jubarte-comem/">Quecomem.com</a></td>
                  <td>tirou-se <strong>o restante</strong></td>
                </tr>
              </tfoot>
            </table>

##	listas (ordenada, não ordenada, definições) com pelo menos uma lista aninhada;

* As listas foram implementadas na página de [curiosidades](../src/pages/curiosidades.html). 
* Além das citadas abaixo, existem outros exemplos de lista na página curiosidades.

* Lista ordenada, não ordenada e aninhada:

        <ul>
            <li>A beluga também é conhecida como baleia-branca ou beluca.</li>
            <li>As belugas não têm barbatana dorsal, daí o nome “golfinho sem barbatana”, porém, não são golfinhos!</li>
            <li>Há registros de belugas machos imitando a voz humana durante a transição da fase juvenil para a fase
              adulta:
              <ol>
                <li>
                  <p>Estudos citam que: uma baleia chamada de Noc confundiu o mergulhador de um grupo,
                    que ouviu várias vezes a palavra fora em inglês. Em seguida descobriu que o aviso vinha de Noc.
                  </p>
                </li>

                <li>
                  <p>Dizem que as Belugas imitam as voz humana espontaneamente, como se o objetivo fosse bater mesmo um
                    papo
                    com seus cuidadores nos aquários. </p>
                </li>
              </ol>
            </li>

            <li>Ao contrário dos outros cetáceos que mostram algum grau de fusão cervical, com exceção dos baleias,
              alguns gulfinhos do rio e os narvais, as sete vértebras cervicais não estão unidas entre si, o que lhe dá
              flexibilidade ao girar a cabeça para os lados, sem a necessidade de girar o corpo.</li>

        </ul>

* Lista de definições: 

          <dl>
            <dt>A Orca, mais conhecida como baleia assassina é uma baleia?</dt>
            <dd> Não! A orca, na verdade, é um golfinho!</dd> 
          </dl>

##	marcação correta de texto com destaque (uso de elementos em, strong, mark, …) com alteração da formatação padrão através de CSS;
 
* As marcações de texto foram implementadas em algumas das páginas, como por exemplo [index](../src/index.html). 
            
          <footer>
          <address>Autores: Amanda Reiko de Oliveira Sato - 43490 <br>
                            Ana Clara Gonçalves Mota - 43451 <br>
                            Maximiliano Marques Lopes - 42644
          </address>
          <p>Copyright ©2022 All rights reserved | <strong>Whalepédia</strong> 🐋 </p>
        </footer>

##	imagens – utilização de elemento img e figure (c/ figcaption) e inserção por CSS;

* Utilizado para demonstração de um GIF na página [Curiosidades](../src/pages/curiosidades.html).
  
           <figure>
            <img src="../images/orca.gif" alt="Gif de Orcas nadando" />
            <figcaption>Orca e filhote nadando em círculos!</figcaption>
          </figure>

##	ligações (hyperlinks internos e externos);

* Utilizamos para encaminhar o usuário para a aba de espécies usando um botão na guia [index](../src/index.html).
            
              <a href="pages/especies.html" id="BotaoBaleiaAzul">
                 SAIBA MAIS SOBRE ELA!
               </a>
            
            <div class="slide">
            <a
            href="pages/especies.html#jubarte"  id="JubartePng"><img src="images/WhalePng.png" alt="Jubarte"></a>
          </div>
          <div class="slide">
            <a
            href="pages/especies.html#baleiaAzul" id="AzulPng"><img src="images/Blue-Whale.png" alt="BALEIA-AZUL"  ></a>
          </div>
          <div class="slide">
            <a
            href="pages/especies.html#beluga"  id="BelugaPng"><img src="images/Beluga.png" alt="Beluga"></a>
          </div>
        

##	formulário.
 
 * Criamos um formulário onde o usuário pode enviar (de maneira falsa) um registro de imagem e texto ambos requeridos para o envio ser realizado pelo input tipo submit.


            <form>
                    <h1>Compartilhe conosco algum registro que você fez!</h1>
                    <textarea name="description" placeholder="Descreva seu registro!" cols="20" required></textarea>
                    <label for="file">Anexe seu arquivo </label>
                    <input type="file" accept="image/*,video/*" name="file" id="file" required>
                    <input type="submit" value="Submit" id="btnsubmit" onclick="Validar()">
             </form>
 
#	Nos documentos CSS deverá existir pelo menos um exemplo de:
##	cada um dos tipo de seletores simples (tipo, id, classe, pseudo-classe e atributo);

* Seguem trechos dos códigos CSS da página principal [Index CSS](../src/styles/index.css).
	
* Tipo:
    
            nav {
                display: inline-flex;
                width: 100%;
            }

* Id:

            #BotaoBaleiaAzul {
                background-color: rgba(255, 255, 255, 0.701);
                position: absolute;
                border-radius: 10px;
                padding: 5px 10px;
                font-size: 15pt;
                margin-left: 0;
                margin-top: 60vh !important;
                text-decoration: none;
                font-weight: 800;
                letter-spacing: -1px;
                color: #0d4691;
             }

* Classe: 
  
            .links {
                font-weight: 800;
                color: #002960;
                text-decoration: none;
                font-size: 1.8rem;
                text-shadow: rgba(255, 255, 255, 0.671) 1px 1px 1px;
                display: inline-flex;
                flex-direction: row;
                justify-content: center;
            }

* Atributo e Pseudo-classe:
  
            .manual-btn:hover {
                background-color: #05d5fe;
            }
            form input[required]:hover{
            background-color: rgb(22, 127, 255);
            }
            
            
            
##	seletor de pseudo-elementos e seletor combinador;

* Utilizado para efetivar um estilo em um irmão de h1 no elemento de ID CardArea na página [Index CSS](../src/styles/index.css).
	
            #CardArea h1 + p {
              font-size: 26pt;
              font-weight: bolder;
              text-align: justify;
              text-shadow: rgba(255, 255, 255, 0.671) 1px 1px 1px;
            }

##	propriedades do texto e da fonte;	

* Utilizado para efetivar um estilo em um irmão de h1 no elemento de ID CardArea na página [Index CSS](../src/styles/index.css).
  
            #CardArea h1 + p {
              font-size: 26pt;
              font-weight: bolder;
              text-align: justify;
              text-shadow: rgba(255, 255, 255, 0.671) 1px 1px 1px;
            }


##	formatação do fundo de página com utilização de imagem de fundo e cor de fundo;

* Sua utlização foi na página principal em [Index CSS](../src/styles/index.css):
  
            body {
              background-image: url("../images/background-ocean.png");
              background-attachment: fixed;
              background-color: #71a6ea;
              margin: 0;
              padding: 0 2px;
              font-family: "Handlee", cursive;
              font-family: "Urbanist", sans-serif;
              color: #002960;
              overflow-x: hidden;
              overflow-y: scroll;
              width: 100%;
              height: 100%;
            }

##	formatação de estilo para uma lista;

*  utilização para a tag Nav na página principal [Index CSS](../src/styles/index.css):
	
            nav ul {
              display: inline-flex;
              flex-direction: row;
              flex-wrap: wrap;
              justify-content: center;
              float: left;
              list-style: none;
              align-items: center;
              padding-left: 0px;

              -webkit-animation-name: bob-float, bloob;
              animation-name: bob-float, bloob;
              -webkit-animation-duration: 0.3s, 1.5s;
              animation-duration: 0.2s, 3s;
              -webkit-animation-delay: 0s, 0.3s;
              animation-delay: 0s, 0.3s;
              -webkit-animation-timing-function: ease-out, ease-in-out;
              animation-timing-function: ease-out, ease-in-out;
              -webkit-animation-iteration-count: 1, infinite;
              animation-iteration-count: 1, infinite;
              -webkit-animation-fill-mode: forwards;
              animation-fill-mode: forwards;
              -webkit-animation-direction: normal, alternate;
              animation-direction: normal, alternate;
            }

            nav li {
              margin-right: 2vw;
            }

##	manipulação dos 4 elementos de formatação da caixa de elementos HTML;

* A utilização desses estilos podem ser encontrados sem dificuldades ao longo de todos os arquivos de estilo mas segue um exemplo de código retirado da página principal [Index CSS](../src/styles/index.css):
	
            #BotaoBaleiaAzul {
              background-color: rgba(255, 255, 255, 0.701);
              position: absolute;
              border-radius: 10px;
              padding: 5px 10px;
              font-size: 15pt;
              margin-left: 0;
              margin-top: 6vh;
              text-decoration: none;
              font-weight: 800;
              letter-spacing: -1px;
              color: #0d4691;
            }

##	utilização de propriedades de flutuação, de posicionamento e combinadas – flutuação e posicionamento;

* Utilizamos essa propriedade na Nav na página princial [Index CSS](../src/styles/index.css):
	
            nav ul {
              display: inline-flex;
              flex-direction: row;
              flex-wrap: wrap;
              justify-content: center;
              float: left;
              list-style: none;
              align-items: center;
              padding-left: 0px;

              -webkit-animation-name: bob-float, bloob;
              animation-name: bob-float, bloob;
              -webkit-animation-duration: 0.3s, 1.5s;
              animation-duration: 0.2s, 3s;
              -webkit-animation-delay: 0s, 0.3s;
              animation-delay: 0s, 0.3s;
              -webkit-animation-timing-function: ease-out, ease-in-out;
              animation-timing-function: ease-out, ease-in-out;
              -webkit-animation-iteration-count: 1, infinite;
              animation-iteration-count: 1, infinite;
              -webkit-animation-fill-mode: forwards;
              animation-fill-mode: forwards;
              -webkit-animation-direction: normal, alternate;
              animation-direction: normal, alternate;
            }

##	esconder um elemento;

*  Utilizado para dar um aviso estilo alert porém criando com HTML, javascript e CSS na página [principal](../src/styles/index.html).
### Javascript:

	function desabilitarElemento(){
    var avisoCard = document.getElementById("avisoWhatsapp")

    avisoCard.classList.add("desabilitado")
	}

### HTML:	
	 <span id="avisoWhatsapp">
        <h1>Aviso!</h1>
        <p>Estamos com nossa conta do Instagram em manutenção!<br/>
          Pedimos desculpas pelo inconveniente.
        </p>
        <button onclick="desabilitarElemento()">OK</button>
      </span>
### CSS:	
	.desabilitado{
	  display: none;
	}

##	formatação de uma tabela;

* Utilizado para inserir alguns estilos na tabela na página [Alimentação](../src/pages/alimentacao.css).
	
            table, td, th {
                border: 1px solid white;
              }

              table {
                border-collapse: collapse;
                width: 100%;
              }

              td {
                text-align: center;
              }

##	substituição de um elemento por uma imagem;

*           Segue elemento trocado por imagem na página [Curiosidades](../src/pages/curiosidades.css):

* HTML:

            <h1 id="topo">
              <span>Como as baleias respiram se vivem no mar?</span>
            </h1>
            
* CSS:
              
            h1#topo {
	          	width: 500px;
		          height: 290px;
		          background-image: url(../images/respiração_baleias.png);
	            }
            
##	responsividade para duas dimensões de ecrã (media queries).
            
* A utlização das medias queries são em todas as páginas, que suportam um média gama de dispositivos, afim de não colar muito código neste arquivo apenas inserimos qual padrões utilizamos, mas pode-se conferir em todos os arquivos [Aqui](../src/styles/).
            
            @media only screen and (min-width: 768px) and (max-width: 1290px)
            @media only screen and (min-width: 1290px)
            @media screen and (max-width: 768px)

#	Integração do conteúdo do documento XML nos conteúdos HTML:
##	A totalidade, ou parte, do conteúdo do documento XML deve ser integrado de forma dinâmica numa das páginas HTML utilizando javascript. A integração do conteúdo deve ocorrer através da transformação dos dados no documento XML para HTML. Por exemplo para uma Tabela.

* Conforme dado no exemplo, utilizamos os dados em uma tabela na página com auxílio de Javascript.
           
###        Javascript:
            
            let url = "../data/dataset.xml"

            $.ajax(url)
                .done(function(xml){
                    $(xml).find("baleia").each(function(){
                        console.log("Entrei")
                        $("#corpoTable").append(`
                        <tr>
                            <td>${ $(this).find("nome").text()}</td>
                            <td>${ $(this).find("alimento").text()}</td>
                            <td>${ $(this).find("quantidade").text()}</td>
                            <td>${ $(this).find("local").text()}</td>
                        </tr>
                        `);
                    });

                })
                .fail(function(){
                    alert("Falha na obtenção dos dados XMl.")
                })
            
###            HTML:

            <table>
              <thead>
                  <tr>
                    <th colspan="4">Alimentação</th>
                  </tr>
                  <tr>
                    <td>Nome</td>
                    <td>Alimento</td>
                    <td>Quantidade</td>
                    <td>Local</td>
                  </tr>
              </thead>
              <tbody id="corpoTable">
               
              </tbody>
              <tfoot>
                <tr>
                  <td rowspan="2" colspan="2">fonte: </td>
                  <td><a href="https://www.natgeo.pt/animais/2021/11/as-baleias-comem-tres-vezes-mais-do-que-se-pensava">Natgeo.pt</a></td>
                  <td>tirou-se <strong>Quantidade</strong></td>
                </tr>
                <tr>
                  <td><a href="https://www.quecomem.com/o-que-as-baleias-jubarte-comem/">Quecomem.com</a></td>
                  <td>tirou-se <strong>o restante</strong></td>
                </tr>
              </tfoot>
            </table>
            
###            XML:

            <?xml version="1.0" encoding="UTF-8"?>
            <baleias 
            xmlns="https://www.w3schools.com"
            xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance"
            xsi:schemaLocation="https://www.w3schools.com dataset.xsd">
                <baleia>
                    <nome>Baleia-Azul</nome>
                    <alimento>Crustáceos, Moluscos, Zooplancton e Krill.</alimento>
                    <quantidade>4 toneladas por dia</quantidade>
                    <local>Hemisfério Sul</local>
                </baleia>
                <baleia>
                    <nome>Baleia Beluga</nome>
                    <alimento>Lulas, Camarões, Caranguejo e Salmão.</alimento>
                    <quantidade>18,2 a 27,2kg por dia</quantidade>
                    <local>Hemisfério Sul</local>
                </baleia>
                <baleia>
                    <nome>Baleia Jubarte</nome>
                    <alimento>Sardinhas, Anchovas, Krill	2 toneladas por dia.</alimento>
                    <quantidade>2 toneladas por dia</quantidade>
                    <local>Hemisfério Norte Polar</local>
                </baleia>
            </baleias>

##	A definição de estilos deverá ser feita mediante a utilização de CSS externo e nunca inline;

* Não foram utilizados estilos inline.

##	No final, todos os ficheiros HTML e CSS deverão ser válidos quando testados pelo validador da W3C;

* Todos os arquivos e suas validações podem ser encontrados no arquivo [Produto](../Documentacao/Produto.md).

##	Deve existir a apresentação de pelo menos uma ajuda (tooltip) para o utilizador.

* Utilizamos de uma tooltip hover em um dos títulos de card na página [Reprodução](../src/pages/reprodução.html).
* Segue trecho do código CSS:
            
            #titleRepro:hover::after{
                content: "Veja tudo sobre a reprodução no card ao lado!";
                position: absolute;
                margin-top: -15%;
                margin-left: 3%;
                padding: 1vw;
                border-radius: 20px;
                text-shadow: none;
                color: white;
                background-color: #00265891;
                font-size: 18pt;
            }

#	Valoriza-se a integração (devidamente fundamentada durante a apresentação) de elementos adicionais aos estudados durante as aulas, como por exemplo:
#	utilização de eventos JavaScript para manipular elementos HTML

* Utilizamos de um botão para subir ao topo da página que some e aparece dependendo da posição na página :
            
            let mybutton = document.getElementById("myBtn");

            window.onscroll = function() {scrollFunction()};

            function scrollFunction() {
              if (document.body.scrollTop > 20 || document.documentElement.scrollTop > 20) {
                mybutton.style.display = "block";
              } else {
                mybutton.style.display = "none";
              }
            }


            function topFunction() {
              document.body.scrollTop = 0;
              document.documentElement.scrollTop = 0; 
            }
            
##	Alteração do conteúdo de elementos.
            
* Não utilizamos desse atributo.
            
##	Alteração da apresentação (estilo) de elementos.

* Acreditamos que a alteração que aqui se discorre, é respectiva a alguma restrição ou regra via CSS, então, sim, utilizamos dentro de todos os Media queries.
            
##	Esconder/apresentar elementos.

* Utilizamos via Javascript em conjunto com CSS, segue trecho:
	
            let mybutton = document.getElementById("myBtn");

            window.onscroll = function() {scrollFunction()};

            function scrollFunction() {
              if (document.body.scrollTop > 20 || document.documentElement.scrollTop > 20) {
                mybutton.style.display = "block";
              } else {
                mybutton.style.display = "none";
              }
            }


            function topFunction() {
              document.body.scrollTop = 0;
              document.documentElement.scrollTop = 0; 
            }
            
##	uso dos elementos HTML: video, audio. canvas, ...

* Utilizamos um Iframe como elemento HTML na página :
	
                  <iframe width="420" height="315" src="https://www.youtube.com/embed/tmq7Ccd8QuM">
                  </iframe>




---

< [Previous](Produto.md) | [^ Main](../README.md) | Next >
:--- | :---: | ---: 
