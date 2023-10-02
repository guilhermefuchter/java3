# java3

function calcularFatorial(n) {
  if (n <= 1) {
    return 1;
  } else {
    return n * calcularFatorial(n - 1);
  }
}



let diaSemana = 3;

switch (diaSemana) {
  case 1:
    console.log('Segunda-feira');
    break;
  case 2:
    console.log('Terça-feira');
    break;
  default:
    console.log('Outro dia da semana');
}


let numeroComoString = "42";
let numero = parseInt(numeroComoString);


let pessoa = {
  nome: "João",
  idade: 30,
  cidade: "São Paulo"
};


function aplicarFuncao(f, valor) {
  return f(valor);
}

function dobrar(numero) {
  return numero * 2;
}

let resultado = aplicarFuncao(dobrar, 5); 


