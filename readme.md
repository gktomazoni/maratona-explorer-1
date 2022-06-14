// 1. Variaveis

let estaChovendo = true
conts meuNome = gabriel

// 2. Tipos de dados
    String
        - " "
        - ' '

    Number
        - 12 - Integrar (+, -)
        - 3.2 - Float (+, -)
 
    Boolean
        - True or false

    Undefined 
        - Indefinido

// 3. Operadores
    - Atribuicao (ex: =)
    - atribu valores 
        -  aritimeticos (ex: * / + -)
        - calculos matematicos simples
    
    - concatenacao de string
        - console.log("23" + 4 + "abc") -> os valores serao adicionados um atras do outro devido a string, nao serao somados

    - comparacao de valores
        - const maiorQue = 1 > 2  // false
        - const igualA = 1 == 1 // true

// 4. Condicional (if/else)
    - const idade = 17
    - const maiorDeDezoito = idade >= 18
    - if (mairoDeDezoito) {
        alert("pode tirar a carteira de motorista")
    }
    else {
        alert("nao pode tirar")
    }
  
// 5. Estrutura de dados 
    - Array - Vetor - Lista
    - Array -----            0     1    2  3
    - const temperaturas = (23.3, 32.2, 1, 5)

    - const pessoa {
        nome: "gabriel",
        idade: 38,
        filhos: ["K", "E", "J", "L", "G"]
    }
    console.log(pessoa.idade)

// 6. Funcao
    6.1 Criacao
        function nomeDaFuncao() {
            console.log('codigo dentro da funcao') 
        }
    6.2 Execucao
        nomeDaFuncao()
    
    - Parametros da funcao
        function soma(a, b) {
            console.log(a + b)
        }
        soma(34, 45)
        soma(90, 54)
    
    - Retorno
        function soma(a, b) {
            return a + b
        }
        const multiplica = soma(2, 2) * 4
        console.log(multiplica)

        console.log(soma(2, 2))

    - Extensoes da linguagem (Ex: math, date, etc...)
    
        - math.random()
        - math.floor(1.2)
        - math.ceil(1.2)
        - math.PI
    
    - DOM - Document Object Model

        - window
        - window.alert ("alerta")
        - document
        - document.write ("texto")
        - manipular elementos
        - document.documentElement.style.background = "black"