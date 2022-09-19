- **Exercícios de escrita de código**
    1. Resolva os passos a seguir: 
        
        a) Crie um objeto. Ele deve conter duas propriedades: nome (string) e apelidos (um array que sempre terá exatamente **três apelidos**). Depois, escreva uma função que recebe como entrada um objeto e imprime uma mensagem no modelo abaixo**:** 
        
        ```jsx
        // Exemplo de entrada
        const pessoa = {
           nome: "Amanda", 
           apelidos: ["Amandinha", "Mandinha", "Mandi"]
        }
        
        // Exemplo de saída
        "Eu sou Amanda, mas pode me chamar de: Amandinha, Mandinha ou Mandi"
        ```
        
        - 💡  Dica
            
            <aside>
            ⭐ Não se esqueça de chamar a função passando o objeto que você criou como argumento, senão seu código não será executado!
            
            </aside>
            
        
        b) Agora, usando **o operador spread**, crie um novo objeto mantendo o valor da propriedade nome, mas com uma nova lista de três apelidos. Depois, chame a função feita no item anterior passando como argumento o novo objeto
        
        - 💡  Dica
            
            <aside>
            ⭐ Não lembra da sintaxe de espalhamento ou spread? Não tem problema!
            
            Pode pesquisar a vontade! Nesse [link](https://blog.fellyph.com.br/javascript/spread-operator/) tem vários exemplos - e não se esqueçam que o Google é melhor amigo da pessoa desenvolvedora 💘
            
            </aside>
            
        
    2. Resolva os passos a seguir: 
        
        a) Crie dois objetos diferentes com as seguintes propriedades: nome, idade e profissão. 
        
        b) Escreva uma função que receba esses objetos e retorne um array com as seguintes informações:
        
        1. O valor de `nome`
        2. O numero de caracteres do valor `nome`
        3. O valor de `idade`
        4. O valor de `profissão`
        5. O numero de caracteres do valor `profissão`
        - Exemplo
            
            ```jsx
            const pessoa = {
            	nome: "Bruno", 
              idade: 23, 
            	profissao: "Instrutor"
            }
            
            minhaFuncao(pessoa)
            
            // Retorno: ["Bruno", 5, 23, "Instrutor", 9]
            ```
            
        
    3. Resolva os passos a seguir: 
        
        a) Crie uma variável de escopo global que guarde um `array` vazio chamada `carrinho`
        
        b) Crie três novos objetos que representem frutas de um sacolão. Eles devem ter as seguintes propriedades: nome (`string`) e disponibilidade (`boolean` - devem começar como `true`)
        
        c) Crie uma função que **receba** um objeto fruta por **parâmetro** e coloque-a dentro do array de `carrinho`. Invoque essa função passando os três objetos criados. 
        
        - 💡  Dica
            
            <aside>
            💡 Aqui você deve usar o método **push()**
            
            </aside>
            
        
        d) Imprima a variável `carrinho` e garanta que ela agora seja um **array preenchido com três objetos.** 
        
        - 💡  Dica
            
            Deve aparecer algo assim no console do seu navegador:
            
            ![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/d281f8fc-0f7c-48fb-8bc3-7d58a22c3757/Captura_de_Tela_2021-05-05_s_15.47.27.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/d281f8fc-0f7c-48fb-8bc3-7d58a22c3757/Captura_de_Tela_2021-05-05_s_15.47.27.png)
            
            Se voce clicar nessa setinha, o array é expandido e deve parecer com isso:
            
            ![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/99cd6642-12d3-46c6-96dc-43a6569d001d/arr.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/99cd6642-12d3-46c6-96dc-43a6569d001d/arr.png)