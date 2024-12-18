# Projeto Jogo de Xadrez

Este projeto é um jogo de xadrez baseado em console, escrito em Java. O jogo permite que dois jogadores joguem uma partida de xadrez padrão, fornecendo funcionalidades para validação de movimentos, detecção de xeque/xeque-mate, promoção de peças e captura de peças.

<p align="center"> <img src="https://github.com/user-attachments/assets/2401c459-481f-4bd9-b49f-e139be3c187a" alt="image" width="15%" style="margin-right: 10px;"/>     <img src="https://github.com/user-attachments/assets/bab03651-fd09-4e55-a124-ef22bd7b3987" alt="{C85CE5BD-0CD3-4B6A-BFD1-59A3D6357A0B}" width="15%" style="margin-right: 10px;"/>     <img src="https://github.com/user-attachments/assets/ee2306a3-5912-4505-bdf1-000f8b5c467c" alt="{05CF1898-822A-4B31-AB04-B08D549BE60D}" width="15%" style="margin-right: 10px;"/> </p>

## Sumário

- [Introdução](#introdução)
- [Como Jogar](#como-jogar)
- [Estrutura do Projeto](#estrutura-do-projeto)
- [Program.java](#programjava)
- [Personalização](#personalização)

## Introdução

Para obter uma cópia local e executar o projeto, siga estas etapas simples.

### Pré-requisitos

- Java Development Kit (JDK) 8 ou superior
- Uma IDE como IntelliJ IDEA ou Eclipse

### Instalação

1. Clone o repositório:
    ```sh
    git clone https://github.com/seu-usuario/jogo-de-xadrez.git
    ```
2. Abra o projeto na sua IDE preferida.

3. Compile e execute a classe `application.Program` para iniciar o jogo.

## Como Jogar

- O jogo é jogado no console.
- Os jogadores são solicitados a inserir seus movimentos na notação padrão de xadrez (por exemplo, `e2` para `e4`).
- O tabuleiro é exibido no console após cada movimento, mostrando as posições de todas as peças.
- O jogo lida com movimentos especiais, como roque, en passant e promoção.
- O jogo termina em xeque-mate, empate ou stalemate conforme as regras padrão do xadrez.

## Estrutura do Projeto

O projeto está organizado em vários pacotes:

- `application`: Contém o programa principal e a classe utilitária de UI.
- `boardgame`: Contém classes relacionadas ao tabuleiro e lógica geral do jogo.
- `chess`: Contém classes específicas da lógica e regras do jogo de xadrez.

## `Program.java`

Esta é a classe principal que inicia o jogo, lida com a entrada do usuário e gerencia o loop do jogo.

## Personalização

Para personalizar ou estender o jogo, você pode:
- Modificar classes de peças existentes ou criar novas no pacote `chess`.
- Ajustar a classe `UI` para diferentes saídas de console ou interações com o usuário.
- Adicionar novas regras ou modificar as existentes na classe `ChessMatch`.

