# Tarefa-SENAI-UC8-Atividade-Online2-
Tarefa realizado para o curso de Desenvolvedor Android para Mobile SENAI

// condicionando o cadastramento de participantes até 100
//-----------------//

let listaDeParticipantes = ["Helena", "Chico", "Mário", "José", "João"];
let    quantidadeDeParticipantes =  listaDeParticipantes.length;
if (quantidadeDeParticipantes < 100) {
    listaDeParticipantes.push("José");
console.log(listaDeParticipantes);
}

else {
    console.log("Cadastro não permitido, máximo de 100 participantes");
}


// condicionando o cadastramento até 18 anos 

const idade = 10;
if (idade >= 18)
    console.log("cadastro realizado com sucesso!"); 
    
else {
    console.log("Cadastro não permitido, idade inferior a 18 anos!");
}


///Listando os eventos e palestantres

let listaDePalestrantes = ["Palestrante: Helena  Evento: Introdução a JavaScripit", "Palestrante: João  Evento: FrontEnd", "Palestrante: Mário  Evento: Novas tecnologias"];
let quantidadeDePalestrantes =  listaDePalestrantes.length;
let inicio = 0;

do {
    console.log(listaDePalestrantes[inicio]);
    inicio++;
} while (inicio < quantidadeDePalestrantes);
