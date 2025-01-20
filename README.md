let Titulo = document.querySelector('h1')
Titulo.innerHTML = ('Hora do Desafio!')

function BotãoConsole(){
    console.log('O botão foi clicado')
}
function BotãoAlert(){
    alert('Eu amo Jf')
}
function BotãoPrompt(){
    let Cidade = prompt('Me fale o nome de uma cidade brasileira')
    alert(`Estive em ${Cidade}, lembre de você.`)
}
function BotãoSoma(){
    let numUM = parseInt(prompt('Digite um numero inteiro'))
    let numDois = parseInt(prompt('Digte o segundo numero inteiro'))
    alert(numUM + numDois)
}
