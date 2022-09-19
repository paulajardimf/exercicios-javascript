- **Exercícios de escrita de código**
    1. Faça um programa que pergunta ao usuário qual a idade dele e imprima no console se ele/ela pode dirigir (apenas maiores de idade).
        
        a) Faça um `prompt` para receber a idade do usuário e guarde em uma variável.
        
        b) Garanta que essa variável é do tipo `Number`, você deve usar o cast para number para isso.
        
        c) Agora veja se essa idade do usuário corresponde à idade mínima que permite dirigir. Se sim, imprima no console `"Você pode dirigir"`, caso contrário, imprima `"Você não pode dirigir."`
        
    2. Agora faça um programa que verifica que turno do dia um aluno estuda. Peça para digitar **M** (matutino) ou **V** (Vespertino) ou **N** (Noturno). Imprima no console a mensagem "Bom Dia!", "Boa Tarde!" ou "Boa Noite!". Utilize o bloco `if/else`
        - 💡 Dica
            
            <aside>
            ⭐ Se o usuário digitar "V" no prompt, você deverá imprimir no console a mensagem `"Boa Tarde!"`
            Nesse caso, temos 3 resultados diferentes (Bom dia/Tarde/Noite)
            
            </aside>
            
            Se o usuário digitar "V", a saída deve ser:
            
            ```
            "Boa Tarde!"
            ```
            
        
    3. Repita o exercício anterior, mas utilizando a estrutura de `switch case` agora.
        - 💡 Dica
            
            <aside>
            ⭐ Lembre-se que o switch case é como se fosse um if, mas ele verifica APENAS IGUALDADES ESTRITAS (`===`)
            
            </aside>
            
        
    4. Considere a situação: você vai ao cinema com um amigo ou amiga, porém ele/ela só assistirá a um filme com você se ele for do gênero fantasia **e** se o ingresso está abaixo de 15 reais. Faça um código que pergunta ao usuário qual o gênero de filme que vão assistir e outra pergunta sobre o preço do ingresso, então verifique se seu amigo ou amiga vai topar assistir o filme. Caso positivo, imprima no console a mensagem: `"Bom filme!"`, caso contrário, imprima `"Escolha outro filme :("`