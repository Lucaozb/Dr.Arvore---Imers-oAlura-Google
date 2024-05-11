# Dr.Árvore - Imersão Alura+Google
# Problemática: As mudanças climáticas estão, batendo a nossa porta, e cada vez mais 
# será demandado profissionais que se preocupam, cuidam e trabalham com florestas e ambientes naturais
# e para que esses profissionais possam tomar as melhores decisões, é necessário conhecer e conhecer bem as florestas.
# inventários florestais em áreas nativas são agora mais que nunca de extrema importância! E para inventariar precisamos identificar as espécies presentes
# Objetivo: Este Projeto tem o intuito de dar _start_ em uma ferramenta não so de consulta mais especializada na identificação das espécies
# Para isso obtemos no site da EMBRAPA FLORESTAS, os 5 volumes de Espécies Florestais Brasileiras, que conta com um  total de 340 espécies descritas!
# Desenvolvimento: Então usando as ferramentas do _studioia_ da Google e usando técnicas de engenharia de prompt, extraímos os dados do documento, quais espécies estão descritas?
# em quais paginas a descrição começa e aonde ela termina? qual é o volume que ela foi descrita.
# Em seguida usando Python, e suas extraordinárias bibliotecas extraímos os conteúdos para cada espécie e criamos um Banco de Dados contendo as 340 espécies e todo o conteúdo que se # tem de cada espécie.
# Usamos a API da Google para resumir o conteúdo de cada espécie! Mantendo o significado, semântica, e salvando as informações mais importantes para que possamos usar como      
# identificadores!
# Após o resumo usamos a técnica de Embeddeings fornecidos pelo pelos modelos da Google. Com o intuito de trabalhar esses dados da melhor forma e obter a partir de entradas de características do operador a espécie mais provável. 
# Criando assim uma IA especializada nos dados publicados dos Livros Espécies Florestais Brasileiras
# Além de ajudar na identificação, o resultada mostra que podemos além de identificar consultar sobre as espécies cadastradas
# As limitações são clara, existem muito mais de 340 espécies florestais no nosso ecossistema, porém esse é um primeiro passo!
# Avaliamos também que a evolução do modelo pode ser feita, através da adição dos dados, e usando a multimodalidade dos modelos da Google.
# Para usarmos também fotos/ imagens para auxiliar na identificação.
# A partir deste ponto iremos avançar na criação do Dr.Árvore para que cada vez mais ele se especialize na identificação das espécies florestais!
