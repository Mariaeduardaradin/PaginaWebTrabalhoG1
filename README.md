# Trabalho G1 - Front-End

**Nome:** MARIA EDUARDA RADIN

**RA:** 1139405

## Sobre o trabalho

Este projeto é o trabalho da G1 na disciplina de Front-End.

A proposta do trabalho é escolher uma página de um site que já existe como referência e desenvolver uma nova página usando HTML e CSS, buscando reproduzir a organização e as características visuais.

Para este trabalho, escolhi utilizar a página inicial do Duolingo como referência.

A escolha do Duolingo aconteceu principalmente porque é um site que eu já conhecia e que também é bastante utilizado por alguns dos meus amigos. Eles usam a plataforma tanto para praticar línguas que já sabem quanto para aprender idiomas novos.

Outro motivo foi por causa da organização da página. Ela tem diferença visual entre a versão para computador e a versão para celular. Isso me ajuda a trabalhar a responsividade no projeto e também posso tentar reproduzir as diferenças usando o que foi aprendido em aula.

**Página de referência:** https://pt.duolingo.com/

## Início do desenvolvimento

Depois de escolher a página que vai ser usada como referência, comecei criando a estrutura inicial do projeto.

A primeira versão do projeto foi simples, com o `index.html` e o `style.css` separados. Também criei uma pasta para deixar as imagens que iriam ser utilizadas na página.

O primeiro arquivo que comecei a montar foi o index.html. Nesse momento, a ideia era primeiro criar a estrutura da página e depois começar a trabalhar na aparência dela com CSS.

Fiz o primeiro commit para registrar o início do projeto antes de começar a adicionar as outras partes da página.

## Montando a primeira parte da página

Depois da estrutura inicial, escolhi qual parte da página do Duolingo iria reproduzir primeiro. Não tentei fazer ela inteira de uma vez, pois ela possui bastante conteúdo.

Nessa primeira parte coloquei:

- o logotipo;
- o botão de idioma do site;
- a imagem principal;
- o título;
- o botão "COMECE AGORA";
- o botão "JÁ TENHO UMA CONTA";
- a barra com os idiomas.

No HTML, procurei organizar essas partes da seguinte forma: O cabeçalho ficou dentro de header, a navegação dentro de nav e o conteúdo principal dentro de main, separado em section.

Também coloquei o alt nas imagens.

Aqui não estava tentando deixar tudo exatamente igual, primeiro queria conseguir montar a estrutura e fazer a página aparecer corretamente no navegador.

Para reproduzir a aparência da página precisei separar as imagens. A primeira imagem é o logotipo usado no cabeçalho e a segunda é a imagem principal que aparece na área de destaque da página.

## Começando o CSS

Depois de montar a estrutura HTML, comecei o style.css. Uma das primeiras coisas que fiz foi criar algumas variáveis para cores.

Algumas cores seriam usadas em mais de um lugar, então se for preciso mudar alguma delas, posso alterar o valor da variável em vez de procurar a cor em cada parte do arquivo.

Também fiz uma configuração inicial para retirar as margens e os espaçamentos padrão dos elementos.

## Ajustando a aparência inicial

Depois de organizar o CSS, comparei o resultado que aparecia no navegador com a página do Duolingo que estou usando de referência.

Tinham algumas partes bem diferentes, principalmente o tamanho da imagem principal, do título e o espaço entre os elementos. Fui fazendo alterações para tentar aproximar o resultado da página original.

Tive alguns problemas durante essa parte por causa de uns erros na escrita do CSS. Então a mudança que eu esperava acontecer depois da alteração no código não funcionava. Depois conferi o código e consegui encontrar o erro e corrigir.

## Trabalhando com a versão para celular

Na página original, não são só os elementos que ficam menores quando a tela diminui, a organização muda também. No celular, por exemplo, a imagem fica em cima do conteúdo e os botões um abaixo do outro.

Por isso, fiz pensando primeiro na tela menor e depois fazendo alterações para telas maiores usando uma media query.

Também tive dificuldades em acertar o tamanho dos elementos. A imagem estava ocupando muito espaço e os botões juntamente com o título precisaram de alterações para que ocupassem melhor o espaço.

## Trabalhando com a versão para telas maiores

Depois de deixar a tela menor com um visual aceitável, passei a trabalhar na versão para computador.

Usei o media query para mudar a organização conforme a tela vai ficando maior. 

Nessa versão, a imagem e o conteúdo ficam lado a lado. Também mudei o tamanho da imagem e do título, e a largura dos botões e da área do texto. Alguns valores precisaram ser ajustados comparando o resultado com a referência. 

A primeira versão ainda não ficou parecida com a referência. As diferenças que notei foram a distribuição dos elementos, o conteúdo e a barra de idiomas que ainda ficam em posições diferentes da página original.

## Comparando com a página original

Como eu estava tendo uma certa dificuldade para acertar os valores dos elementos, pesquisei no ChatGPT se existia alguma forma de descobrir o tamanho dos elementos, cores, fontes e espaçamentos.

Assim, ele recomendou utilizar a ferramenta de inspeção do navegador para tentar achar algumas dessas informações na página original. Já que eu não sabia como usar a ferramenta, pedi para o ChatGPT me explicar passo a passo do que precisava fazer, quais propriedades procurar e como interpretar os valores para que o resultado fosse o mais parecido com a página de referência.

Uma das partes que investiguei dessa forma foi a barra de idiomas da versão para computador. Consegui encontrar alguns valores relacionados.

Tentei alterar para esses novos valores, mas o resultado ainda não foi tão eficaz, novas mudanças vão precisar ser feitas.

## Continuando os ajustes

Utilizando a ferramenta de inspeção e comparando as duas páginas, fui fazendo novos ajustes no CSS.

Alguns elementos precisaram ser alterados várias vezes para ficarem o mais próximos da referência possível. O tamanho das imagens, a largura das áreas de conteúdo, os espaçamentos e o jeito como os textos quebravam de uma linha para outra eram o foco das mudanças que precisavam ser feitas.

Ao longo dos testes com os valores encontrados na inspeção da página original, percebi que não poderia usar e os mesmos valores, pois a estrutura do meu projeto é diferente da estrutura do Duolingo. Então usei as informações como uma referência e fui adaptando para o meu CSS.

Durante esse processo fui testando as alterações tanto na versão de telas menores quanto na de telas maiores, pois algumas mudanças que funcionavam em uma não ficavam boas na outra.

## Adicionando outra parte da página

Depois de terminar os principais ajustes da primeira parte, comecei a reproduzir mais uma seção da página original.

Escolhi a seção "grátis. divertido. eficaz." que possui um título, um pequeno texto explicativo, um link e uma imagem.

Criei uma nova section no HTML e separei o texto e a imagem em divs. A imagem também recebeu um texto alternativo através do atributo alt.

Organizei essa seção para celular, onde o texto é centralizado e a imagem fica abaixo do conteúdo. Logo após, fiz os ajustes para a versão de computador dentro da media query, onde o texto e a imagem ficam lado a lado.

Uma das dificuldades dessa parte foi acertar a largura da área de texto porque, dependendo do valor utilizado, as frases quebravam em lugares diferentes da página original. Por isso, fui alterando a largura e comparando as duas páginas até chegar em uma quebra de texto mais parecida com a referência.

Também ajustei o espaço entre o texto e a imagem e o tamanho da ilustração separadamente para cada versão.