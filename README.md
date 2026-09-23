### NOME DO PROJETO 
Jogo da velha
### DESCRIÇÃO
Um jogo da velha clássico para o terminal, desenvolvido inteiramente na linguagem C.
### COMO EXECUTAR
Para executar este programa na sua máquina, você deve compilá-lo no terminal usando o comando: `gcc jogodavelha.c -o jogodavelha` Por fim, execute-o com o comando: `jogodavelha.exe` (no Windows) ou `./jogodavelha` (no Linux/Mac).
### COMO JOGAR
1. O programa vai pedir para escolher a sua peça. Digite `X` ou `O` e pressione Enter.
2. Observe o tabuleiro inicial na tela. Escolha uma casa vazia digitando o número correspondente (de 1 a 9).
3. O jogo vai atualizar o tabuleiro com a sua marcação.
4. Repita o processo alternando os jogadores (e escolhendo a sua respectiva peça) até o tabuleiro ficar cheio ou alguém vencer o jogo inserindo três peças iguais na vertical, horizontal ou diagonal.
### CONCEITOS UTILIZADOS
- **Matrizes (Arrays Bidimensionais):** Criação e manipulação de uma grid 3x3 para armazenar e atualizar as jogadas no tabuleiro.
- **Estruturas de Repetição:** Uso de ciclos `for` aninhados para exibir a interface e procurar coordenadas, além de um ciclo `do-while` para gerir o limite de 9 turnos.
- **Tratamento de Caracteres:** Implementação da função `tolower` (da biblioteca `<ctype.h>`) para tornar a escolha das peças flexível, validando a entrada independentemente de estar em maiúscula ou minúscula.
