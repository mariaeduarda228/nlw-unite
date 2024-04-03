fronteditor.dev/nlw-unite
# HTML
*Marcador de texto*
  - Elemento/Tag (h1, href...)
  - Atributos
  - Identação (espaços antes de cada linha de código)
  - width (largura)
  - Quebra de linha (br)
  - style (estilo)
  - div
  - input
  - button (botão)
  - onsubmit(executa uma funçõ em especifico)
  - required (obrigatorio)

# CSS
/* folha de estilo em cascata */
  - background-color(cor de fundo)
  - separa por -
  - ; ao final
  ``` css
  ```
  - especificação (sempre que quiser aplicar o mesmo tamanho de fonte precisa especificar)
  - cascata(declaração após declaração vindo de maneira gradativa)
  - padding(se colocar dois o primeiro será em cima e o segundo em baixo)
  - :root
  - class(seletor de classe começa com um. e divide com um-)
  - gap (espaços)

# JavaScript
*linguagem de programação*
// (comentário)
  - Variaveis (caixinhas que guardam informações)
  - função
'''js
// variaveis
const mensagem = 'oi, tudo bem?'
// tipos de dados
  // number
  //strings
// funcao
alert(mensagem)
arrow (=>)
arrowfuncion ({})
retur (substitui o valor da função)
// objeto JavaScript
// array []
  - let 
// objeto javascript
const participante = {
  nome: "Mayk Brito",
  email: "mayk@gmail.com",
  dataInscricao: new Date(2024, 2, 22, 19, 20),
  dataCheckIn: new Date(2024, 2, 25, 22, 08)
}

// array
let participantes = [
  {
    nome: "Mayk Brito",
    email: "mayk@gmail.com",
    dataInscricao: new Date(2024, 2, 22, 19, 20),
    dataCheckIn: new Date(2024, 2, 25, 22, 08)
  },
]

  - lista (0, 1, 2, 3...)
  - for(para)

// estrutura de repetição - loop
for(let participante of participantes) {
  // faça alguma coisa aqui 
  // enquanto tiver participantes nessa lista
}
```
  - códigos de terceiros
  // condicional
  - if(se)

// condicional 
if( participante.dataCheckIn == null) { 
  dataCheckIn = ` 
    <button 
      data-email="${participante.email}" 
      onclick="fazerCheckIn(event)" 
    > 
      Confirmar check-in 
    </button> 
  `
}
  - true ou false (boolean)