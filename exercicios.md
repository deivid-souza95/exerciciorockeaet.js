# soma
let numberOne = prompt("Digite o primeiro valor: ")
let numberTwo = prompt("Digite o segundo valor ")

let result = Number(numberOne) + Number(numberTwo)
alert(`O valor da soma é: ${result}`)

# subtração

let numberOne = prompt("Digite o primeiro valor: ")
let numberTwo = prompt("Digite o segundo valor ")

let result = Number(numberOne) - Number(numberTwo)
alert(`O valor da subtração é: ${result}`)

# multiplição

let numberOne = prompt("Digite o primeiro valor: ")
let numberTwo = prompt("Digite o segundo valor ")

let result = Number(numberOne) * Number(numberTwo)
alert(`O valor da multiplição é: ${result}`)

# divisão

let numberOne = prompt("Digite o primeiro valor: ")
let numberTwo = prompt("Digite o segundo valor ")

let result = Number(numberOne) / Number(numberTwo)
alert(`O valor da divisão é: ${result}`)

# resto da divisão

let numberOne = prompt("Digite o primeiro valor: ")
let numberTwo = prompt("Digite o segundo valor ")

let result = Number(numberOne) % Number(numberTwo)
alert(`O valor do resto da divisão é: ${result}`)

# resultado + número impar ou par

let numberOne = prompt("Digite o primeiro valor: ")
let numberTwo = prompt("Digite o segundo valor ")

let result = Number(numberOne) + Number(numberTwo)

if(result % 2 == 0) { 
  
 } if (result % 2 == 1 ){
    }
  
alert(`O valor da é: ${result} 
E o número é ${result % 2 == 0 ? "Par" : "Impar"}`)

# resultado + números iguais (ou diferente)

let numberOne = prompt("Digite o primeiro valor: ")
let numberTwo = prompt("Digite o segundo valor ")

let result = Number(numberOne) + Number(numberTwo)
// alert(`O valor da soma é: ${result}`)

if(numberOne == numberTwo) { 
  alert("O resultado é: " + result + " e os números digitados são iguais") 
} if(numberOne != numberTwo){
  alert("O resultado é: " + result + " e os números digitados são diferentes")
}