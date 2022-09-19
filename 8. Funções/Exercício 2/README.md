- **Exercícios de escrita de código**
    1. Escreva as funções explicadas abaixo:
        
        a) A função não deve receber nenhum parâmetro e deve imprimir uma mensagem falando algumas informações sobre você, como: 
        
        ```
        "Eu sou Caio, tenho 23 anos, moro em São Paulo e sou estudante."
        ```
        
        Troque o nome, idade, cidade e se é estudante ou não por informações sobre você. Lembrando que a função não possui entradas, apenas imprime essa mensagem.
        
        b)  Agora escreva uma função que receba 4 parâmetros que correspondem às informações de uma pessoa: o nome (`string`), a idade (`number`), a cidade (`string`) e uma profissão (`string`). Ela deve retornar uma `string` que unifique todas as informações da pessoa em uma só mensagem com o template:
        
        ```
        Eu sou [NOME], tenho [IDADE] anos, moro em [ENDEREÇO] e sou [PROFISSÃO].
        ```
        
        - Exemplo
            
            Para a entrada:  `"Laís"`, `23`, `"São Paulo"` e `"instrutora"`, deve retornar:
            
            `"Eu sou Laís, tenho 23 anos, moro em Rua Guarapari 190 e sou instrutora."`
            
        - 💡  Dica
            
            <aside>
            ⭐ Na hora de criar a frase, você pode utilizar as template strings que vimos em aulas anteriores! As variáveis da frase, nesse caso, serão os próprios parâmetros recebidos na função
            
            </aside>
            
        
    2. Escreva as funções explicadas abaixo:
        
        a) Escreva uma função que receba 2 números como parâmetros, e, dentro da função, faça a soma das duas entradas e retorne o resultado. Invoque a função e imprima no console o resultado.
        
        b) Faça uma função que recebe 2 números e retorne um booleano que informa se o primeiro número é **maior ou igual** ao segundo.
        
        c) Escreva uma função que receba um número e devolva um booleano indicando se ele é par ou não
        
        d) Faça uma função que recebe uma mensagem (`string`) como parâmetro e imprima o tamanho dessa mensagem, juntamente com uma versão dela em letras maiúsculas.
        
    3. Crie uma função para cada uma das operações básicas (soma, subtração, multiplicação e divisão). Em seguida, peça para o usuário inserir dois números e **chame** essas 4 funções com esses valores inputados pelo usuário sendo o argumento. Por fim, mostre no console o resultado das operações:
        
        ```
        Números inseridos: 30 e 3
        Soma: 33
        Diferença: 27
        Multiplicação: 90
        Divisão: 10
        ```
        
        - 💡  Dica
            
            <aside>
            ⭐ Lembre-se de converter a entrada do usuário para número antes de fazer os cálculos :)
            
            </aside>