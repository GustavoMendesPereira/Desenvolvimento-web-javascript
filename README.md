// console.log("Hello world")

// let idade = Number(prompt("Qual a sua idade: "));

// if(idade >= 18){
//     console.log("Voce tem " + idade + " Anos. Você é maior de idade");
// }else{
//     console.log("Voce tem " + idade + " anos. Você é menor de idade.");
// }

// let nota1 = Number(prompt("Qual a primeira nota: "));
// let nota2 = Number(prompt("Qual a segunda nota: "));
// let nota3 = Number(prompt("Qual a terceira nota: "));

// let media = (nota1 + nota2 + nota3) / 3;

// if(media >= 9){
//     console.log("Excelente! Você foi aprovado, sua média é " + media);
// }else if(media >= 6){
//     console.log("Parabens! Voce foi aprovado, sua média é " + media);
// }else{
//     console.log("Que pena! Você foi reprovado, sua média é " + media);
// }

// let usuario = prompt("Digite o nome do usuario");
// let senha = Number(prompt("Digite sua senha: "));

// if(usuario === "admin" && senha === 123){
//     console.log("Acesso garantido");
// }else{
//     console.log("Usuario e/ou senha incorreto(s)");
// }

// let dia = Number(prompt("Digite um numero entre 1 a 7 do dia da semana:"));
// switch(dia){
//     case 1:
//         console.log("Domingo")
//         break;
//         case 2:
//         console.log("Segunda")
//         break;
//         case 3:
//         console.log("Terça")
//         break;
//         case 4:
//         console.log("Quarta")
//         break;
//         case 5:
//         console.log("Quinta")
//         break;
//         case 6:
//         console.log("Sexta")
//         break;
//         case 7:
//         console.log("Sabado")
//         break;
// }

// for (let i = 1; i <= 5; i++){
//     console.log(i)
// }

// let numero = Number(prompt("Digite um numero para exibir a tabuada:"));

// for(let i = 1; i <= 10; i++){
//     console.log(numero + "X" + i + "=" + (numero * i));
// }

// let contador = 1;

// while(contador <= 5){
//     console.log(contador);
//     contador++
// }

// let numero = 10;

// do {
//     console.log(numero);
//     numero++;
// }while(numero <=5);

AULA 2 
let alunos = ["Maria", "João", "Daniel", "Luana", "Marcos"];

// console.log(alunos);

// console.log(alunos[3]); // traz um aluno especifico dentro do array

// alunos.push("Gabriel"); //Adiciona o item no array
// console.log(alunos);

// alunos.pop(); //retira o ultimo
// console.log(alunos);

// alunos.shift(); //remove o primeiro
// console.log(alunos);

// alunos.unshift("Gabriela");
// console.log(alunos);

// alunos.splice(1,2); //remover de acordo com a posição
// console.log(alunos);

// let posicao = alunos.indexOf("Luana"); //encontrar posição dentro do array
// console.log(posicao);

for(let i = 0; i < alunos.length; i++);{
    console.log(alunos[i]);
}
for(let aluno of alunos){
    console.log(aluno);
}
