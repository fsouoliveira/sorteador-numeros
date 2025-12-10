🎲 Projeto — Sorteador de Números Aleatórios

Este projeto é uma aplicação simples em HTML, CSS e JavaScript, desenvolvida para realizar o sorteio de números aleatórios dentro de um intervalo definido pelo usuário. Ele permite escolher a quantidade de números a serem sorteados e garante que todos os números sejam únicos.


---

🚀 Funcionalidades

Inserir:

Quantidade de números desejados

Intervalo inicial (De)

Intervalo final (Até)


Sorteio de números sem repetição

Validações:

"De" deve ser menor que "Até"

Quantidade não pode ser maior que o tamanho do intervalo


Exibição dos números sorteados na tela

Botão de reiniciar, limpando todos os campos



---

🧠 Lógica Principal

O sorteio utiliza:

Math.floor(Math.random() * (max - min + 1)) + min;

Para garantir números dentro do intervalo informado.
O array sorteados evita repetições.


---

📦 Estrutura do Projeto

📁 projeto-sorteador
 ├── index.html
 ├── style.css
 └── app.js


---

⚙️ Como usar

1. Informe a quantidade de números.


2. Defina os valores De e Até.


3. Clique em Sortear.


4. Veja o resultado diretamente na tela.


5. Utilize o botão Reiniciar para limpar tudo e realizar novos testes.




---

🧩 Código JavaScript (script.js)

> Responsável pela lógica de sorteio e validações.



sortear(): realiza o sorteio e exibe o resultado.

obterNumeroAleatorio(): gera números aleatórios dentro do intervalo.

alterarStatusBotao(): ativa/desativa o botão de reinício.

reiniciar(): limpa campos e resultado.
