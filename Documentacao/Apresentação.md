
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
Ex: <Nav>,<main>, <footer>, <address>, etc.

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

*
##	marcação correta de texto com destaque (uso de elementos em, strong, mark, …) com alteração da formatação padrão através de CSS;
 
* 

##	imagens – utilização de elemento img e figure (c/ figcaption) e inserção por CSS;

*

##	ligações (hyperlinks internos e externos);

*

##	formulário.
 
 *
 
#	Nos documentos CSS deverá existir pelo menos um exemplo de:
##	cada um dos tipo de seletores simples (tipo, id, classe, pseudo-classe e atributo);

*

##	seletor de pseudo-elementos e seletor combinador;

*

##	propriedades do texto e da fonte;	

*

##	formatação do fundo de página com utilização de imagem de fundo e cor de fundo;

*

##	formatação de estilo para uma lista;

*

##	manipulação dos 4 elementos de formatação da caixa de elementos HTML;

*

##	utilização de propriedades de flutuação, de posicionamento e combinadas – flutuação e posicionamento;

*

##	esconder um elemento;

*

##	formatação de uma tabela;

*

##	substituição de um elemento por uma imagem;

*
##	responsividade para duas dimensões de ecrã (media queries).
 
 *

#	Integração do conteúdo do documento XML nos conteúdos HTML:
##	A totalidade, ou parte, do conteúdo do documento XML deve ser integrado de forma dinâmica numa das páginas HTML utilizando javascript. A integração do conteúdo deve ocorrer através da transformação dos dados no documento XML para HTML. Por exemplo para uma Tabela.

*

##	A definição de estilos deverá ser feita mediante a utilização de CSS externo e nunca inline;

*

##	No final, todos os ficheiros HTML e CSS deverão ser válidos quando testados pelo validador da W3C;

*

##	Deve existir a apresentação de pelo menos uma ajuda (tooltip) para o utilizador.

*

#	Valoriza-se a integração (devidamente fundamentada durante a apresentação) de elementos adicionais aos estudados durante as aulas, como por exemplo:
#	utilização de eventos JavaScript para manipular elementos HTML
##	Alteração do conteúdo de elementos.
##	Alteração da apresentação (estilo) de elementos.
##	Esconder/apresentar elementos.
##	uso dos elementos HTML: video, audio. canvas, ...
#	Relatório










---

< [Previous](Produto.md) | [^ Main](../README.md) | Next >
:--- | :---: | ---: 