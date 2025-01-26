# Pokerito

Pokerito é um jogo simples inspirado no Poker, onde você joga contra o computador. O objetivo é obter mais correspondências de cartas do que o oponente.

## Regras do Jogo

1. O jogador e o computador recebem uma carta aleatória.
2. O dealer sorteia cinco cartas (o "river").
3. O jogador e o computador comparam suas cartas com as do river.
4. Quem tiver mais correspondências vence!
5. Se houver empate, todos ganham!

## Tecnologias Utilizadas

- Java
- Scanner para entrada do usuário
- Random para sorteio de cartas

## Como Executar o Jogo

1. Certifique-se de ter o [JDK](https://www.oracle.com/java/technologies/javase-downloads.html) instalado.
2. Compile o código-fonte:
   ```sh
   javac Pokerito.java
   ```
3. Execute o jogo:
   ```sh
   java Pokerito
   ```

## Exemplo de Saída

```
Let's play Pokerito. Type anything when you're ready.
It's like Poker, but a lot simpler.

• There are two players, you and the computer.
• The dealer will give each player one card.
• Then, the dealer will draw five cards (the river)
• The player with the most river matches wins!
• If the matches are equal, everyone's a winner!

• Ready? Type anything if you are.

Here's your card:
  _____
 |A _  |
 | ( ) |
 |(_'_)|
 |  |  |
 |____V|

Here's the computer's card:
  _____
 |7    |
 | o o |
 |o o o|
 | o o |
 |____7|

Now, the dealer will draw five cards. Press enter to continue.

Card 1:
  _____
 |10  o|
 |o o o|
 |o o o|
 |o o o|
 |___10|

...

The computer wins!
```

## Melhorias Futuras

- Adicionar naipes para as cartas
- Implementar uma interface gráfica
- Criar um modo multiplayer

## Autor
Desenvolvido por [Seu Nome].

