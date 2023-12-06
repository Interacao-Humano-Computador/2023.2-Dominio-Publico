# Guia de Estilo

## Introdução

Um guia de estilo é um documento que define as diretrizes de design de um produto ou serviço. Ele registra todas as decisões de design tomadas, de forma a garantir que o produto final seja consistente e coerente. O guia de estilo é uma ferramenta de comunicação essencial para a equipe de design, pois permite que todos os membros da equipe estejam alinhados com as expectativas do produto. O guia de estilo também é importante para a equipe de desenvolvimento, pois fornece um conjunto de regras e padrões que devem ser seguidos.<a id="anchor_3" href="#l1">³</a>

##### Objetivo do guia de estilo

Esse guia de estilos visa manter a consistência e a clareza no design do projeto, garantindo que as decisões de design sejam documentadas, compartilhadas e implementadas de forma eficaz.

##### Organização e conteúdo do guia de estilo

A organização do guia de estilo seguirá de forma proposta por Marcus<a id="anchor_1" href="#l1">¹</a>  e Mayhew<a id="anchor_2" href="#l1">²</a>  e encontrada em Barbosa<a id="anchor_3" href="#l1">³</a>. Sendo ela:

1. Introdução
2. Resultados de análise
3. Elementos de interface
4. Elementos de interação
5. Elementos de ação
6. Vocabulário e padrões

##### Público-alvo do guia de estilo

Este guia de estilo foi elaborado pelo e para os estudantes da disciplina de Interação Humano Computador da Universidade de Brasília. Porém pode ser utilizado por quaisquer outras equipe de design e desenvolvimento do site Domínio Público que possam ter interesse pelo artefato. 

##### Como utilizar o guia 

Este guia deve ser utilizado como uma referência para tomar decisões de design durante todo o ciclo de vida do projeto de Interação Humano Computador, incluindo a fase de produção e a fase de manutenção. Além disso, também deve ser utilizado na implementação de fases intermediárias, como a prototipação. As decisões aqui tomadas são importante para garantir que as necessidades dos usuários sejam atendidas, levando a uma interação eficaz e a melhores experiências na utilização do sistema.

##### Como manter o guia

É fundamental que a equipe mantenha o compromisso de atualizar o guia sempre que novas decisões sejam tomadas ou quando houver mudanças que contrariem o que foi previamente descrito. Isso garantirá que o guia esteja em constante conformidade com as diretrizes e padrões estabelecidos e resultará em maior clareza e uniformidade nos produtos desenvolvidos. Tal prática contribuirá para uma experiência de usuário mais satisfatória, pois todos os elementos do sistema estarão alinhados a um mesmo padrão, minimizando possíveis problemas de usabilidade.


## Resultados de análise

##### Descrição do ambiente de trabalho do usuário

O Domíminio Público é comumente acessado através de computadores (notebooks ou desktops). Por isso é necessário que, ao projetar a interface, sejam considerandas as especificidades dos dispositivos, como tamanho de tela, resolução, etc, de forma a garantir uma experiência de usuário satisfatória e eficiente para aqueles que acessem a plataforma por meio destes dispositivos. Isso engloba a adaptação do design para diferentes tipo e tamanhos de telas (responsividade), a definição apropriada de elementos visuais e a implementação de funcionalidades de fácil uso, aprendizado e acesso. Os elementos da interface podem ser encontrados na figura 1. Para melhorar a responsividade do site, é necessário adequar as telas às diferentes resoluções de dispositivos. Como se trata de um site antigo, ele provavelmente não foi desenvolvido pensando em dispositivos móveis nem em monitores mais recentes, o que pode resultar em uma visualização descentralizada em telas diferentes. Para resolver esse problema, pode-se implementar um padrão de tela mais atual.

## Elementos de interface

<font size="2"><p style="text-align: center">Figura 1: Elementos da inteface </p></font>

<center>
<iframe style="border: 1px solid rgba(0, 0, 0, 1);" width="800" height="450" src="https://www.figma.com/embed?embed_host=share&url=https%3A%2F%2Fwww.figma.com%2Ffile%2FSl8uPWGWzVHmIsux7X2Fqz%2FDom%C3%ADnio-P%C3%BAblico%3Ftype%3Ddesign%26node-id%3D0%3A1%26mode%3Ddesign%26t%3DHV0FeSo8yHHQpgUY-1" allowfullscreen></iframe>
</center>

<font size="2"><p style="text-align: center">Fonte: [Victor Hugo](https://github.com/ViictorHugoo) e [Maria Alice](https://github.com/Maliz30)</p></font>

## Elementos de interação

##### Estilos de interação

Os usuários podem interagir com o site de diversas formas, como por meio de pesquisa de mídia, download de mídia, acesso à ajuda, acesso à aba para colaboradores, acesso a estatísticas, avaliação de mídia e esclarecimento de dúvidas. Todas essas ações são realizadas por meio de botões, hiperlinks e campos de preenchimento (*inputs*). Há diversas melhorias que poderão ser feitas em todos esses aspectos, cada um com sua funcionalidade sendo explorada ao máximo para deixar o site mais amplo e bem desenvolvido.

##### Seleção de um estilo

O estilo do domínio público possui uma interface carregada de informações desnecessárias e orientada aos objetivos de achar mídia e download. Por isso, suas páginas não se diferem muito umas das outras, possuindo botões e caminhos semelhantes. Para melhorar esse aspecto, poderia ser feito um reagrupamento das informações desnecessárias para que ficassem mais bem colocadas no site, fazendo-o parecer menos poluído. Na questão das páginas serem parecidas, poderiam ser feitas diversas mudanças para deixá-las mais interessantes para o usuário se diferindo uma das outras de acordo com a funcionalidade.

##### Aceleradores/Teclas de Atalho
Não há teclas de atalho no site do Domínio Público.

## Elementos de ação

##### Preenchimento de campos
Os campos de preenchimento disponíveis requerem que o usuário insira manualmente as informações de acordo com seus objetivos, porém não fornecem qualquer modelo ou exemplo sobre como preenchê-los corretamente. Estes campos podem incluir barras de pesquisa, caixas de auxílio para preenchimento, caixas de e-mail para envio de mensagens, entre outros elementos que demandam inserção de texto.

##### Seleção
O site oferece vários elementos de seleção, como tipo de mídia, categoria e idioma. Esses elementos permitem que os usuários encontrem conteúdo específico ou restrinjam os resultados da pesquisa.

Tipo de mídia: O site oferece uma variedade de tipos de mídia, incluindo imagens, vídeos, áudio e texto. Os usuários podem selecionar o tipo de mídia que desejam visualizar.

Categoria: O site organiza o conteúdo em categorias, de acordo com o tipo de mídia escolhido. Os usuários podem selecionar a categoria que desejam explorar.

Idioma: O site possui obras em vários idiomas, incluindo português, inglês, espanhol e francês. Os usuários podem selecionar o idioma que desejam explorar.

##### Ativação
Há botões, ícones, imagens e _hyperlink_ como elementos clicáveis.

## Vocabulário e Padrões

##### Terminologia
O site utiliza um vocabulário simples, que buscam o entendimento do público geral da sociedade brasileira. 

##### Tipos de tela
As telas seguem um padrão de título e posição dos elementos, porém há excesso de informações e detalhes, prejudicando a experiência do usuário.

##### Sequências de diálogos
A sequência de diálogos segue um padrão onde todos os botões são iguais e com o mesmo formato independentemente da função.

## Referências Bibliográficas

> <a id="l1" href="#anchor_1">1.</a> MARCUS, A. Graphic design for electronic documents and user interfaces. Association for Computing Machinery, New York, NY, USA, 1991.
> 
> <a id="l2" href="#anchor_2">2.</a> MAYHEW, D. J. The Usability Engineering Lifecycle: A Practitioner’s Handbook for User Interface Design. Morgan Kaufmann, 1st edition edition, 1999.
> 
> <a id="l3" href="#anchor_3">3.</a> BARBOSA, S. D. J.; SILVA, B. S. Interação Humano-Computador. Rio de Janeiro: Elsevier, 2011.



## Histórico de versões

| Versão | Data     | Descrição                     | Autor(es)                                       | Revisor(es)                               |
| ------ | -------- | ----------------------------- | ----------------------------------------------- | ----------------------------------------- |
| 1.0    | 21/10/23 | Introdução do Guia de Estilos | [Luciano Ricardo](https://github.com/l-ricardo) | [Maria Alice](https://github.com/Maliz30) |
| 1.1    | 21/10/23 | Resultados e Elementos iniciados | [Victor Hugo](https://github.com/ViictorHugoo) | [Maria Alice](https://github.com/Maliz30) |
| 1.2 | 23/10/2023 | Elementos de interface e elementos de ação | [Maria Alice](https://github.com/Maliz30) e [Victor Hugo](https://github.com/ViictorHugoo) | [Luciano Ricardo](https://github.com/l-ricardo) |
| 1.3    | 06/12/23 | Correção do Artefato | [Pedro Henrique](https://github.com/pedro-hsf) | [Ana Catarina](https://github.com/an4catarina) |

