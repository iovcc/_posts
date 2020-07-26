---
layout: single
title: "Porque Ofuscar Código?"
categories:
  - ofuscar
tags: [ofuscar, estilo, aperfeiçoamento, qualidade, desempenho]
excerpt: "Ofuscar código vai muito além de esconder como você fez no código, vamos entender isso."
toc: true
author_profile: true
authors: [CarlosDelfino]
---

Ofuscar código pode ser feito de diversas formas:

* Através de softwares especializados;
* Através de descuido, uma escrita desleixada e sem compromisso com a leitura;
* Através de otimização intencional do programador, por prazer ou segurança;
* Estressar o compilador tornando a compilação lenta;

Vamos pensar um pouco nisso, cada motivo acima será discutido abaixo:

## Mas o que é ofuscação?

**ofuscar**
```
   verbo
   1. transitivo direto
      impedir a vista de; ocultar, encobrir, obscurecer.
      "densas nuvens ofuscavam o sol"
   2 transitivo direto e pronominal
      tornar(-se) turvo, confuso.
      "a ganância ofuscou-lhe a razão"
```

Acima a definição do termo **Ofuscar** no dicionário do google baseado no dicionário Oxford.

Como podemos ofuscar é o ato de ocultar algo, de torna-lo oculto, difícil de ver, ou no caso de entender.

## Ofuscando por Software

Ofuscar por software hoje em dia é muito comum, quase toda linguagem tem um mecanismo para ofuscação de código, principalmente aquelas que são fácilmente revertidas do bytecode como Java, PHP, Python, JavaScript entre outras. Já linguagens como C e C++, HDLs como Verilog, VHDL e Chisel, não há muito o porque faze-lo, primeiro o código será compilado de tal forma que mesmo uma ferramenta de descompilação que consiga converter o código de maquina em linguagém de alto nível ou redes de fios e dispositivos lógicos em sua representação textual, não se conseguirá um resultado muito legível a própria otimização realizada naturalmente pelo compilador ou sintetizador irá ofuscar boa parte do código.

A ofuscação por software quase é feita para proteção da propriedade intelectual. O Código pode vir a ter algorítimos que venham a valer milhões, então a ofuscação protege este código de ser vasado quando transportado para outros ambientes onde serão compilados ou usados, mas como dito é mais usado em linguagens transpiladas ou interpretadas, já que seu código é fácilmente acessível, mesmo que o servidor onde é armazenado tenha máxima segurança, assim as linguagens PHP, JavaScript, Python, Perl e Java são as que tem ferramentas mais desenvolvidas para ofuscação.

Mas ainda assim a ofuscação pode trazer muito benefícios em contextos variádos não importe a linguagem, vamos continuar pensando nisso.

## O Descuido do programador

A Pior ofuscação que podemos ter, é o descuido do programador, quando este usa nomes de variáveis e funções que não tem relação com o que irá conter e pior ainda nem mesmo com o contexto do código escrito. Quando o programador tem total descuido com a formatação do código, com o uso de blocos lógicos de decisão inadequados e muitas vezes abusa do uso de forma incorreta, o abuso do uso da instrução "goto" quando esta existe, e códigos sem métricas que abusam dos parâmetros em funções mal planejadas.

O ofuscação de código por descuido é um acidente que deve ser evitado com estudo, prática, critica de pares e outros colegas mais qualificados, além do uso de ferramentas de analise das métricas do código.

A Prática de analise de métricas em códigos foi amplamente difundida com a linguagem Java, e posteriormente adotada largamente no mercado de engenharia de software com a adoção da Integração Continua, assim o código sendo enviado ao repositório é automáticamente analisando sendo reprovado se não atender algumas exigências apresentadas pela equipe de liderança técnica da empresa.

## A Otimização por prazer e desenvolvimento próprio

A otimização de código pelo prazer de faze-la pode trazer ofuscação no bom sentido, muitas vezes usamos estruturas de código que tornam a primeira leitura difícil, exigindo do par que analisa o código gerado por outros programadores maior dedicação ao entendimento do que foi feito. O que pode caracterizar uma ofuscação do código, de forma algumas vezes errônea pois quem assim define otimizações é porque não se inteira dos algoritmos ampliando seu vocabulário de padrões de código.

A também a ofuscação intencional por prazer, onde o codificador estuda estruturas eficientes ou mesmo que desafiam o compilador a gerar resultados diferenciados, assim trazendo um código a primeira vista absurdo, algo como o que vemos com jogos de palavras na poesia, porém com uma interpretação mais cuidadosa percebemos muitas vantagens.

Mas quais vantagens poderiam trazer uma ofuscação por puro prazer de faze-la, se temos ferramentas que o fazem tá rápidamente? 

Bem, a prática de racionar sobre um código legível e transforma-lo em algo encriptado a certo nível, é um exercício mental, isso amadurece o programador, traz um novo horizonte a sua mente desenvolvimento sua capacidade interpretátiva de códigos, amplia seu conhecimento de dialetos usados pelo compilador, convidando o programador  a conhecer melhor se compilador preferido ou imposto pela empresa que trabalha. 

A ofuscação por prazer, pode ser também uma tática da empresa em motivar o programador a se colocar a par do código existente, fazendo desafios internos entre os pares para identificar positivamente ou negativamente a qualidade do código escrito pelos colegas.

E claro a ofuscação pode ser uma brincadeira, uma ironia com seus colegas, desafiando o entendimento deles, uma forma inteligente de fazer uma pegadinha codificada.

Então concluímos que toda otimização acaba se tornando a primeira vista uma ofuscação para o programador que tem menos experiência e tem mãos um código otimizado.

## A Ofuscação por segurança

Algumas vezes, tão raras quanto pelo motivo do prazer em complicar, temos a necessidade de proteger nosso código, um pensamento, um algoritmo que queremos proteger seja porque motivo for. Assim, escrevemos códigos observando algumas diretivas da empresa ou com base em sugestões de consultores.

A ofuscação por segurança, feita manualmente por programadores mais experientes, pode ser feita para evitar que programados recém contratados venham a interpretar algoritmos de relevância na empresa.

Isso até funciona, quando apenas um programador trabalha no código, mas pode vir a ser um agrande atraso de vida na empresa.

## Ofuscação para Para testes

A ofuscação do código pode também ser feita com o objetivo de testes do código, teste das ferramentas envolvidas na compilação, na grámatica da linguagem. Programadores que escrevem seus próprios compiladores ou que escrevem novos dialetos de linguagem, podem abusar intencionalmente nas formas de escrita ampliando assim o dialeto que orbita a forma clássica de escrita de código naquela linguagem.

Isso é interessante, pois desenvolver a ferramenta otimizando os resultados que ela pode oferecer, e o conhecimento do programador sobre al.

## Porque um concurso de ofuscação

Para incentivar os programadores a gerar melhor código e amadurecer a comunidade através da interpretações entendimento dos códigos gerados, para brincar, criticar positivamente códigos, concursos podem vir a ser propostos, seja internamente em empresas como também externamente no meio acadêmico ou intraempresarial.

Em concursos de ofuscação se desenvolve as habilidades citadas acima.

Um cursos é um espaço onde pode-se classificar códigos de forma jocosa, irônica, estilo, e técnicas ligadas ao compilador, etc. Sendo um forum para o debate dentro destas qualificações de forma inteligente e produtiva.

O que acha da ideia? O que tem feito quanto a ofuscação de seus códigos?