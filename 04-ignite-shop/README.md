# reactjs-study-repo

# Fundamentos NextJS

### Conceitos

- SPA:
Conceito em que a aplicação é renderizada por parte do cliente e não do servidor em tempo de execução.
- SSR:
Conceito em que a aplicação é renderizada por parte do Servidor e não do cliente em tempo de execução.
- SSG:
Conceito que implementa um CDN (Content Delivery Network) no site para agilizar a entrega de páginas com conteúdos estáticos.
- Robots e indexação:
Conceito de indexação de páginas web para serem melhor introduzidas aos mecanismos de pesquisa como o Google. Em particular, estes robôs tem dificuldades em indexar sites SPA pois o conteúdo só é entregue assim que a página é carregada. Diferente de um SSR em que o conteúdo ja foi carregado antes de ser entregue ao cliente.

## Questionário 1

1. Em uma SPA (Single Page Application), é correto afirmar que:
A aplicação é gerada do lado do cliente, afetando o SEO.

2. Em qual abordagem o HTML é gerado em tempo de execução pelo lado do cliente?
SPA

3. Quando queremos criar uma rota no NextJS que receba um parâmetro slug, qual é o nome correto que deve ser dado para o arquivo?
[slug].tsx

--

# Stiches

- Sintaxe parecida com o styled components porém lida melhor com variações do componente.
- Uma feature interessante é a entrega de conteúdo css integrado ao SSR do Next em que a aplicação carregada pelo servidor, mesmo com o client desativando o JS (camada em que o CSS é escrito) os estilos são carregados no HTML renderizado.

## Questionário 2

1. O que é o StitchesJS e qual a funcionalidade dele, na nossa aplicação?
É uma biblioteca CSS-in-JS, assim como o styled-components, que nos permite estilizar nossa aplicação com uma sintaxe JS e com diversas funcionalidades que melhoram a experiencia de desenvolvimento.

2. Qual a funcionalidade da função `getCssText` do Stitches?

3. Qual das seguintes alternativas cria um elemento header com a cor `green500` declarada no tema em seu background, utilizando o Stitches?
