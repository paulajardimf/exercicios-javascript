- **Exercícios de interpretação de código**
    
    Tente responder os exercícios dessa seção sem executar o código. Se ficar muito difícil, pode rodar no seu computador **para analisar e pensar sobre o resultado.** 
    
    1.  Indique todas as mensagens impressas no console, **SEM EXECUTAR o programa**.
        
        ```jsx
        let string
        console.log('a. ', string)
        
        string = null
        console.log('b. ', string)
        
        string = "paralelepípedo"
        console.log('c. ', string.length)
        
        let i = 0
        console.log('d. ', string[i])
        
        const valor = string[i+6]
        console.log('e. ', valor)
        
        i = 13
        console.log('f. ', string[i])
        
        i = 14
        console.log('g. ', string[i])
        ```
        
    2. Leia o código abaixo com atenção 
        
        ```jsx
        const frase = prompt("Digite uma frase")
        
        console.log(frase.toUpperCase().replaceAll("A", "I"), frase.length)
        ```
        
        Qual será o valor impresso no console se a entrada do usuário for: `"Subi num ônibus em Marrocos"`?