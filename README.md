# 🎮 Horde Survivor

Protótipo de jogo 2D desenvolvido com **PixiJS**, em que o jogador controla um personagem e precisa sobreviver a ondas crescentes de inimigos.

![status](https://img.shields.io/badge/status-prot%C3%B3tipo-9b5cff) ![engine](https://img.shields.io/badge/engine-PixiJS-5ad1ff)

## Sobre o projeto

Este projeto nasceu de um interesse antigo por desenvolvimento de jogos, iniciado em um protótipo acadêmico feito na Unreal Engine (controle de personagem em terceira pessoa com ondas de inimigos). Aqui, a mesma ideia central — sobreviver a hordas progressivas — foi recriada do zero para a web, usando **PixiJS** puro, sem frameworks de jogo prontos.

O foco do projeto foi entender e implementar, na prática, os fundamentos de um jogo 2D:

- Game loop e atualização de estado a cada frame
- Input de teclado (movimento) e mouse (mira e disparo)
- Spawn dinâmico de inimigos por onda, com dificuldade crescente
- Detecção de colisão entre jogador, inimigos e projéteis
- HUD reativo (vida, onda, pontuação)

## Como jogar

- **Movimento:** `W A S D` ou setas direcionais
- **Mirar:** mova o mouse (ou o dedo, em telas touch)
- **Atirar:** clique ou toque na tela
- **Objetivo:** sobreviva ao maior número de ondas possível. A cada onda, inimigos ficam mais rápidos e mais numerosos.

## Tecnologias

| Tecnologia | Uso |
|---|---|
| **PixiJS** | Renderização 2D via WebGL/Canvas |
| **JavaScript** | Lógica de jogo, física simples e IA de perseguição |
| **HTML/CSS** | Estrutura, HUD e responsividade |

## Mecânicas implementadas

- Inimigos com IA simples de perseguição (seguem a posição do jogador a cada frame)
- Sistema de ondas com aumento progressivo de velocidade e quantidade de inimigos
- Colisão jogador ↔ inimigo (dano) e projétil ↔ inimigo (derrota)
- Tela de game over com estatísticas da partida (onda alcançada e pontuação)

## Rodando localmente

Por ser um projeto em arquivo único, não há dependências de build:

```bash
# clone o repositório
git clone <url-do-repositorio>
cd horde-survivor

# abra o arquivo diretamente no navegador
open index.html   # ou dê duplo clique no arquivo
```

## Autor

**Daniel Pereira Carli**
[LinkedIn](https://www.linkedin.com/in/daniel-pereira-carli-9b00a9270/) · [GitHub](https://github.com/DanielCarli88)
