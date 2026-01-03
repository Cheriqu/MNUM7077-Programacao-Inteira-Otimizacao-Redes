# Programação Inteira e Otimização em Redes (MNUM7077) - PPGMNE UFPR

Este repositório reúne os projetos desenvolvidos para a disciplina de Programação Inteira. O foco é o estudo de métodos avançados para resolver problemas de otimização onde as variáveis de decisão são discretas, aplicando tanto algoritmos clássicos quanto modelagem de casos reais.



## 🏆 Projeto Aplicado: Logística da Copa do Mundo 2026

O destaque deste portfólio é a modelagem matemática para otimizar a logística das seleções na Copa do Mundo de 2026 (EUA, México e Canadá). O problema envolve a alocação de **Base Camps** e o roteamento das seleções para minimizar distâncias de viagem.

* **Dados Reais:** Utilização de bases de dados contendo cidades-sede, distâncias, centros de treinamento (Base Camps) e grupos simulados.
* **Restrições:** O modelo considera a capacidade dos centros, a necessidade de deslocamento para os jogos e a viabilidade logística.
* **Complexidade:** Resolução de um problema NP-Difícil com limite de tempo computacional (3600s) para encontrar a melhor solução viável.

## 🧠 Algoritmos e Métodos (Python & R)

Além da modelagem, o repositório contém a implementação de algoritmos fundamentais da otimização inteira:

### 1. Métodos Exatos
* **Branch and Bound:** Implementação do algoritmo de ramificação e limite para varrer a árvore de soluções e encontrar o ótimo global.

### 2. Heurísticas e Metaheurísticas
* **Local Branching:** Implementação de uma estratégia de busca local para melhorar soluções em problemas de Programação Inteira Mista (MIP) difíceis, explorando vizinhanças da solução corrente.

## 🚀 Tecnologias

* **Linguagens:**
    * **R:** Utilizado para o projeto da Copa 2026 (Manipulação de dados e chamada de solvers).
    * **Python:** Utilizado para a implementação didática dos algoritmos (Branch & Bound, Local Branching).
* **Bibliotecas:** `Pandas`, `NumPy` e interfaces para solvers de otimização.

## 📂 Estrutura de Arquivos

* `Copa2026_vPH.Rmd` / `.pdf`: Código e relatório do projeto de logística da Copa.
* `PPGMNE_PI_Lista_Branch_Bound.ipynb`: Notebook com a lógica do Branch and Bound.
* `PPGMNE_PI_Lista_Local_Branching.ipynb`: Notebook com a aplicação de Local Branching.
* `Base de dados...csv`: Conjunto de dados utilizados na simulação.

---
**Autor:** Luiz Henrique Barretta Francisco
*Graduado em Estatística / Mestrando em Métodos Numéricos em Engenharia - UFPR*
