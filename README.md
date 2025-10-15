# 🎲 Jogo Par ou Ímpar (Python - Terminal)

![Feito com Python](https://img.shields.io/badge/feito%20com-Python-FFC0CB?logo=python&logoColor=white)
![Status](https://img.shields.io/badge/status-concluído-FFC0CB)
![Licença](https://img.shields.io/badge/licença-Livre-FFC0CB)
![Autoria](https://img.shields.io/badge/feito%20por-Lavínia%20Butinholi%20Basílio-FFC0CB)

[Repositório do projeto](https://github.com/seuusuario/jogo-par-ou-impar)

---

## 📖 Descrição
Este projeto implementa o clássico **Jogo Par ou Ímpar**, onde o usuário joga contra a máquina.  
O jogo permite múltiplas rodadas, contabiliza pontos de cada jogador e encerra automaticamente quando alguém atinge a maioria das vitórias.  
Ideal para estudo de **loops, condições, entradas de usuário** e **randomização** em Python.

---

## ⚙️ Funcionalidades
- 🔹 Jogador vs Máquina  
- 🎯 Contagem de pontos e vitórias  
- 🔄 Permite múltiplas rodadas  
- 💻 Interface simples via terminal  
- 🚨 Validação de entradas do usuário  

---

## 🧠 Estrutura do Código
| Variável/Função | Descrição |
|-----------------|------------|
| `repeticao` | Número de rodadas que o jogador deseja jogar |
| `jogador` | Contador de pontos do jogador |
| `maquina` | Contador de pontos da máquina |
| `ganhou` | Indica se o jogo já terminou |
| `impopar` | Escolha do jogador: Ímpar (1) ou Par (2) |
| `pc` | Número aleatório escolhido pela máquina |
| `player` | Número escolhido pelo jogador |
| `soma` | Soma dos números da máquina e do jogador para determinar vencedor |

---

## 👩‍💻 Autor

**Lavínia Butinholi Basílio**  

Desenvolvedora apaixonada por tecnologia e aprendizado, responsável por este projeto de estudo em **loops, condições e randomização em Python**.  
O jogo foi criado como um recurso educativo para **entender lógica de jogos e contagem de pontos** de forma prática e divertida.

---

## 🪶 Licença

Este projeto é de **uso livre** para fins **educacionais e de aprendizado**.  

Sinta-se à vontade para estudar, modificar e aprimorar, explorando conceitos de **programação em Python**. 💡



## 🎮 Como Jogar

1. Execute o programa.  
2. Escolha **quantas rodadas deseja jogar**.  
3. Em cada rodada:
   - Escolha **Ímpar (1)** ou **Par (2)**.  
   - Escolha um **número inteiro** que deseja jogar.  
   - A máquina escolherá outro número aleatório.  
   - O programa soma os dois números e determina o vencedor da rodada.  
4. O jogo contabiliza pontos automaticamente.  
5. O jogo termina quando alguém atinge a maioria das vitórias ou todas as rodadas acabam.  
6. Ao final, o programa exibe a **pontuação final** e declara o vencedor ou empate.


## 🚀 Como Executar

### 1️⃣ Pré-requisitos
- Ter o **Python 3** instalado no sistema

### 2️⃣ Clonar o repositório
```bash
git clone https://github.com/seuusuario/jogo-par-ou-impar.git
cd jogo-par-ou-impar

python par_ou_impar.py
