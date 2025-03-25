# Módulo A: Conhecendo o JavaScript  

## Aula 1 - O que o JavaScript é capaz de fazer?  
Nesta aula foram apresentadas algumas funcionalidades do JavaScript e como ele funciona.  

O professor exemplifica os sites como se fossem um site de notícias:  

- **Jornalista (HTML)**: contém o conteúdo que compõe a matéria, textos, imagens, vídeos e links.  
- **Designer (CSS)**: organiza o visual da matéria, alterando cores, fontes, disposição dos parágrafos e imagens.  
- **Programador (JavaScript)**: responsável por todas as interações da matéria, como exibir uma descrição ao passar o mouse sobre uma imagem, ampliar a imagem ao clicar nela e adicionar botões para avançar ou retroceder.  

Também foram mostrados exemplos de sites famosos como Google e YouTube sem o JavaScript, permitindo visualizar o impacto dessa linguagem no funcionamento dos sites atualmente.  

Além disso, foi demonstrado como modificar páginas através da ferramenta **Inspecionar** do navegador, permitindo que os alunos alterem elementos visuais dos sites para aprendizado e experimentação.  

> **Importante:** As alterações feitas no navegador não afetam o site de forma permanente, apenas modificam a versão carregada na sua máquina. Ao atualizar a página, o site retorna à versão original, pois uma nova cópia do código é carregada pelo servidor.  

---

## Aula 2 - Como chegamos até aqui?  

- **1970 - Guerra Fria**: Durante esse período, foi criada a **DARPA**, uma agência de pesquisa tecnológica militar. Havia centros militares onde os dados eram armazenados, mas se um deles fosse destruído, todas as informações eram perdidas. Para minimizar esse risco, foi criada uma rede de comunicação entre os centros militares, permitindo que os computadores compartilhassem informações. Assim nasceu a **Arpanet**, que evoluiu até se tornar a **Internet**.  

- **1993** - Em Genebra, **Tim Berners-Lee** pesquisava formas de tornar o conteúdo mais interativo por meio da ligação entre documentos. Dessa ideia surgiu o **HTML**, o protocolo **HTTP** (que se integrou aos protocolos **TCP/IP**) e a **World Wide Web (WWW)**. Para acessar essas tecnologias, era necessário um navegador, e assim surgiu o **Mosaic**, criado por **Marc Andreessen**.  

- **1994** - Marc Andreessen se juntou ao milionário **James H. Clark**, criador da Silicon Graphics, e juntos fundaram a **Netscape**.  

- **1995** - Brendan Eich, ex-funcionário da Silicon Graphics e agora na Netscape, estava criando uma nova linguagem de programação chamada **Mocha**. Paralelamente, a linguagem **Java** fazia muito sucesso e era considerada "a linguagem do futuro". Como estratégia de marketing, a Netscape decidiu renomear **Mocha** para **JavaScript**.  

  Embora Java e JavaScript tenham nomes parecidos, elas possuem poucas semelhanças. Ambas derivam da linguagem **C**, o que resulta em algumas similaridades, mas a escolha do nome JavaScript foi puramente comercial.  

  Enquanto isso, a Microsoft, ao lançar o **Internet Explorer**, decidiu criar sua própria linguagem, chamada **JScript**.  

- **1997** - Para impedir que a Microsoft continuasse copiando seu código e sua linguagem, a Netscape decidiu padronizar o JavaScript e procurou a empresa **ECMA**, resultando na criação do **ECMAScript**.  

- **2002** - A disputa entre Microsoft e Netscape chegou ao fim. Com a popularização do Internet Explorer, o uso do Mosaic caiu drasticamente, levando a Netscape à falência. No entanto, seus ex-funcionários fundaram a **Mozilla**, que criou o navegador **Firefox**.  

- **2008** - O Google entrou na disputa lançando o **Google Chrome**, que rapidamente se tornou o navegador mais utilizado. O Chrome trouxe consigo um poderoso motor para rodar JavaScript, chamado **V8**, que é **open source**.  

  Com o código aberto do **V8**, um grupo de desenvolvedores o adaptou para rodar fora do navegador.  

- **2010** - Surge o **Node.js**, permitindo a execução de JavaScript fora dos navegadores, inclusive em servidores.  

---

## Aula 3 – Dando os primeiros passos  

O professor inicia a aula com algumas perguntas:  

### **Q01 - Você sabe qual empresa criou o JavaScript?**  
O **JavaScript** foi criado pela **Netscape**. Inicialmente, seu nome era **Mocha**, e ele estava sendo desenvolvido por **Brendan Eich** em **1995**.  

### **Q02 - Java e JavaScript possuem alguma relação?**  
A única relação entre elas é que ambas derivam da linguagem **C**, o que resulta em algumas semelhanças na estrutura, como o uso do `if`. O nome **JavaScript** foi escolhido por uma estratégia de marketing da **Netscape**, já que **Java** estava muito popular na época e era considerada "a linguagem do futuro".  

### **Q03 - O que ECMAScript tem a ver com JavaScript?**  
O **ECMAScript** é a versão padronizada do JavaScript pela empresa **ECMA**. Essa padronização se tornou necessária quando a **Microsoft**, ao lançar o **Internet Explorer**, criou a linguagem **JScript**, que era praticamente uma cópia do JavaScript com algumas modificações.  

---

## Orientações para um estudo eficiente  

Para obter o melhor aprendizado, foi recomendada a seguinte abordagem:  

- Assistir às aulas;  
- Anotar pontos importantes e de interesse;  
- Participar de fóruns;  
- Estudar em grupo e tentar ensinar outras pessoas sobre o que foi aprendido;  
- Ler livros sobre o conteúdo.  

### **Livros recomendados:**  
- *JavaScript: O Guia Definitivo* – **David Flanagan**  
- *JavaScript: Guia do Programador* – **Mauricio Samy Silva**  
- Guias de referência da **[Mozilla](https://developer.mozilla.org/en-US/docs/Web/JavaScript)** e **[ECMA](https://ecma-international.org/publications-and-standards/standards/ecma-262/)**  
  > *Obs.: Esses guias são mais técnicos, longos e complexos.*

---

## Aula 4 – Criando o seu primeiro script  

O professor inicia a aula com algumas perguntas:  

### **Q01 - Quais livros/documentos foram recomendados?**  
Os livros recomendados foram:  

- **JavaScript: O Guia Definitivo**, de *David Flanagan*  
- **JavaScript: Guia do Programador**, de *Mauricio Samy Silva*  
- Guias de referência do **Mozilla** e do **ECMA**  

### **Q02 - Para aprender JavaScript, é necessário saber inglês?**  
O inglês é muito importante, pois grande parte dos artigos, manuais e guias estão nesse idioma. Embora seja possível aprender sem saber inglês, em algum momento a falta do idioma pode se tornar uma barreira para a evolução.  

### **Q03 - Quais dicas foram dadas para quem quer estudar?**  
As dicas foram:  

- Assistir às aulas;  
- Anotar pontos importantes e de interesse;  
- Participar de fóruns;  
- Estudar em grupo e tentar ensinar outras pessoas sobre o que foi aprendido;  
- Ler livros sobre o conteúdo.  

---

Foi feita uma introdução básica sobre **HTML** e **CSS** para aqueles que não têm conhecimento prévio. Foram abordadas informações sobre as tags `<head>` e `<body>`, além da explicação sobre onde inserir os blocos `<style>` e `<script>` para, então, começar a usar JavaScript.  

Foram apresentados três comandos básicos em **JavaScript**:  

```html
<script>
    window.alert('Minha primeira mensagem');
    window.confirm('Está gostando de JavaScript?');
    window.prompt('Qual é o seu nome?');
</script> 



