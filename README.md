# ♟️ Algoritmo Minimax em Python

![Python](https://img.shields.io/badge/Python_3-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Game Theory](https://img.shields.io/badge/IA-Teoria_dos_Jogos-6A1B9A?style=for-the-badge)

Implementação em Python do algoritmo **Minimax** com ponderação por profundidade aplicado ao Jogo da Velha (*Tic-Tac-Toe*), garantindo tomada de decisão ótima em jogos de soma zero com informação perfeita.

---

## 🧠 Como Funciona

O algoritmo explora recursivamente a árvore de estados do jogo alternando entre dois agentes:
- **Maximizador (`O` - IA):** Busca maximizar a pontuação final (`+10 - profundidade`), escolhendo vitórias mais rápidas.
- **Minimizador (`X` - Jogador):** Assume que o oponente jogará de forma ótima para minimizar a pontuação da IA (`-10 + profundidade`).

$$\text{utilidade}(s, d) = \begin{cases} 10 - d & \text{se } O \text{ vence} \\ -10 + d & \text{se } X \text{ vence} \\ 0 & \text{em caso de empate} \end{cases}$$

---

## 🚀 Como Executar

```bash
git clone https://github.com/zlluska/Minimax.git
cd Minimax
python minimax.py
```

---

## 🔗 Veja Também

- Repositório complementar com **Backtracking & Busca em Labirinto**: [`jogo-da-velha-minimax`](https://github.com/zlluska/jogo-da-velha-minimax)

## 👤 Autor

**Lucas Fraga** — [GitHub (@zlluska)](https://github.com/zlluska)
