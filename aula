//declarando variaveis

let s = ""; //string
let i = 0; //number
let f= 0.0; //number
let b = true; //boolean
let l= [1,2,3,4]; //array
let o= {a: 1, b: 2,c:3 }; //object

//if else
    let num= 9; 
if (num > 10) {
    console.log("O numero e maior que 10");
} else if (num === 10) {

    console.log("O numero e igual que 10");
}else {
    console.log("O numero e menor que 10");
}


//atividade calcular idade
let anoNascimento = 2005;
let anoAtual = 2024;
let idade = anoAtual - anoNascimento;
console.log("Voce tem", idade, "anos."); //equivale ao ESCREVA

//ou
let anonascimento = 2005;
console.log (`O personagem tem ${2024- 2005} anos.`); 


//sistema de notas escolar
let nota=67;
if (nota >= 90) {
    console.log("Aprovado com louvor");
}
else if (nota >= 70) {
    console.log("Aprovado");
}
else if (nota >= 50) {
    console.log("Recuperacao");
}
else {
    console.log("Reprovado");
}   

//outra forma 
 let Nota=68 
if ((Nota >= 90) && (Nota <= 100)) {
    console.log("Excelente");
}
else if ((Nota <90) && (Nota >=70)) {
    console.log("Bom trabalho");
}
else if ((Nota <70) && (Nota >=50)) {
    console.log("Pode melhorar");
}
else if ((Nota >= 0) && (Nota < 50)) {
    console.log("Precisa estudar mais");
}

//questão IMC
let peso = 40;
let altura = 1.58;
let imc = peso / (altura * altura);
if (imc < 18.5) {
    console.log("Abaixo do peso");
}
else if (imc >= 18.5 && imc < 24.9) {
    console.log("Peso normal"); //para LET que é um valor específico, usamos else if e não só else
}
else if (imc >= 25 && imc < 29.9) {
    console.log("Sobrepeso");
} 
else if (imc >= 30) {
    console.log("Obesidade");
}

//comando for
for (let i = 0; i < 5; i++) {
    console.log("Contagem:", i);
}
//estrutura de repetição for com FOR
for (let i = 1; i <= 100; i=i+9) {
   console.log (i);
}
let lista = ["joão", "maria", "pedro", "ana","luana","carlos"]; //lembrando que a lista começa do 0
for (let i = 0; i <= lista.length, i = i+1) {
    console.log(`$(i) - ${lista[i-1]}`); 
} 
for (let i in lista) {
    console.log(`$Number(i)`)
}

//buscador no array: escolher um nome da lista e dizer em que posição ele está
let nomeProcurado = "maria";
let posicao = lista.indexOf(nomeProcurado);
if (posicao !== -1) {
    console.log(`O nome ${nomeProcurado} está na posição ${posicao} da lista.`);
}
else {
    console.log(`O nome ${nomeProcurado} não foi encontrado na lista.`);
}

//outra forma soq mior
for (let i in lista) {
    if(lista[i] === 'joão') {
        console.log(`O nome ${lista[i]} está na posição ${i} da lista.`);
    }

}
//tambem temos while e switch case, function
let palavra = "meu nome é fulano"; 
function Linguadop (palavra) {
    for (elem of palavra) {
        switch (letra) {
            case "a": palavracom += "apa"; break; /*caso de letra a vai receber "apa" e 
            quebra**/
            case "e": palavracom += "epe"; break;
            case "i": palavracom += "ipi"; break;
            case "o": palavracom += "opo"; break;
            case "o": palavracom += "upo"; break;
            default: palavracom += letra; break; /*se não for nenhuma das letras, vai re-
            ceber o elemento, tipo analisa as vogais e vai mudando de acordo**/
        }
           
    }
}
console.log(Linguadop(palavra));
