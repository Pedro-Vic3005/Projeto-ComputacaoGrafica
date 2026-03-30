# 🐍 Cobra 2D

Um jogo clássico da cobrinha desenvolvido com **HTML5 + Canvas + JavaScript puro**, com sistema de pontuação, aumento de dificuldade progressivo e movimentação baseada em grid.

---

## 🎮 Demonstração

O jogo funciona diretamente no navegador.

### 📷 Exemplos do jogo

- Estado em andamento:
- Estado inicial:

![Tela inicial](assets/jogo2.png)

---

## 🚀 Funcionalidades

- ✅ Movimentação da cobra em grid
- ✅ Sistema de pontuação (Score)
- ✅ Sistema de recorde (High Score)
- ✅ Crescimento da cobra ao coletar maçãs 🍎
- ✅ Aumento de dificuldade progressivo (velocidade)
- ✅ Colisão com:
  - Parede ❌
  - Próprio corpo ❌
- ✅ Reinício automático ao perder
- ✅ Animações:
  - Língua da cobra 🐍
  - Maçãs pulsando 🍎

---

## 🧠 Lógica do Jogo

### 📌 Objetivo

Controlar a cobra para coletar as maçãs espalhadas pelo mapa, acumulando pontos e aumentando seu tamanho sem colidir.

---

### 📌 Regras principais

- A cobra se move continuamente em uma direção
- O jogador controla usando as setas do teclado:
  - ⬆️ Cima
  - ⬇️ Baixo
  - ⬅️ Esquerda
  - ➡️ Direita

---

### 📌 Sistema de crescimento

- Cada maçã coletada:
  - +1 ponto
  - Aumenta o tamanho da cobra
  - Aumenta a velocidade do jogo

---

### 📌 Condições de derrota

O jogo reinicia automaticamente quando:

- ❌ A cobra bate na parede
- ❌ A cobra colide com o próprio corpo

---

### 📌 Sistema de pontuação

- Score atual é exibido durante o jogo
- High Score é salvo durante a sessão

---

## ⚙️ Tecnologias utilizadas

- HTML5
- CSS3
- JavaScript (Vanilla)
- Canvas API

---

## 🧩 Arquitetura do Código

### 🎯 Principais componentes

#### 🔹 Renderização
- `desenharGrid()`
- `desenhaCobra()`
- `desenharRastro()`
- `desenharMacas()`

#### 🔹 Lógica do jogo
- `atualizarMovimento()`
- `gerarPosicaoAleatoria()`
- `reiniciarJogo()`

#### 🔹 Loop principal
- `animar()`

#### 🔹 Controle do jogador
- Evento `keydown`

---

## ▶️ Como executar

1. Baixe ou clone o projeto:
```bash
git clone <seu-repositorio>
