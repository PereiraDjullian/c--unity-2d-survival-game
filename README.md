# 🎮 Dino Survival Game (Unity)

## 📌 Sobre o Projeto
Este projeto foi desenvolvido como parte da atividade **Desafio Individual Unity 2 e 3**, com o objetivo de criar e evoluir um jogo de sobrevivência simples utilizando a Unity e C#.

O jogo consiste em um personagem que precisa sobreviver o máximo possível desviando de obstáculos (cactos) que surgem ao longo do tempo, com dificuldade progressiva.

---

## 🎯 Experiência do Jogo
A proposta do jogo é gerar uma sensação de **desafio e progressão**, onde o jogador tenta sobreviver o máximo possível enquanto a velocidade e frequência dos inimigos aumentam.

---

## 🕹️ Mecânicas do Jogo

- Movimento lateral (esquerda/direita)
- Pulo simples e pulo duplo
- Sistema de colisão:
  - Colisão lateral com inimigo → morte
  - Pular em cima do inimigo → destrói o inimigo
- Sistema de pontuação (score)
- Progressão de dificuldade ao longo do tempo
- Sistema de respawn de inimigos (cactos)
- Sistema de áudio (pulo, morte, etc.)

---

## 🧠 Sistema de Recompensa

- O jogador ganha pontos ao sobreviver
- Pontos extras ao derrotar inimigos
- A dificuldade aumenta com o tempo, incentivando melhora de performance

---

## 📈 Progressão de Dificuldade

O jogo aumenta automaticamente a dificuldade:
- Os inimigos passam a aparecer com mais frequência
- O desafio cresce conforme o tempo de sobrevivência

---

## 🎮 Interface (UI)

- Menu inicial
- Sistema de pause (ESC)
- Tela de Game Over
- Contador de pontuação (score)

---

## 🔊 Feedback

- Animações:
  - Correr
  - Pular
  - Morrer
- Efeitos sonoros:
  - Pulo
  - Morte

---

## ⚙️ Tecnologias Utilizadas

- Unity (2D)
- C#
- TextMeshPro (UI)
- Sistema de Física 2D (Rigidbody2D, Colliders)

---

## 🚧 Desafios Enfrentados

Durante o desenvolvimento, alguns desafios foram:

- Ajuste de colisões entre player e inimigos
- Implementação do sistema de pulo duplo
- Criação do sistema de spawn com progressão
- Organização da lógica de animações e estados

Esses problemas foram resolvidos com testes constantes e ajustes nos scripts.

---

## 📚 Aprendizados

- Manipulação de física em jogos 2D
- Uso de scripts em C# dentro da Unity
- Controle de cenas (SceneManager)
- Sistema de UI com TextMeshPro
- Organização de lógica de gameplay

---

## ▶️ Como Jogar

- **A / D ou Setas** → mover personagem
- **Espaço** → pular (duplo pulo disponível)
- **ESC** → pause

Objetivo: sobreviver o máximo possível e fazer a maior pontuação.

---

## 🌐 Build WebGL

> ⚠️ Ainda não implementado

O projeto poderá futuramente ser exportado para WebGL para execução no navegador.

---

## 📂 Estrutura do Projeto

- Scripts principais:
  - `Player.cs`
  - `Cactus.cs`
  - `CactusSpawner.cs`
  - `GroundMovement.cs`
  - `AudioManager.cs`
  - `PauseManager.cs`
  - `GameManager.cs`

---



