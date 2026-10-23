# ♟️ Desafio de Xadrez em C

![Linguagem C](https://shields.io)
![Ambiente](https://shields.io)
![Status](https://shields.io)

## 📝 Descrição do Projeto
Este projeto consiste no desenvolvimento de um simulador de movimentação de peças de **Xadrez**, construído em **Linguagem C** para execução direta no terminal. O principal objetivo do desafio foi aplicar estruturas de repetição e funções avançadas para determinar e validar os limites de movimentação de diferentes peças dentro do tabuleiro.

O desenvolvimento foi dividido de forma incremental em três níveis de complexidade (Novato, Aventureiro e Mestre).

---

## 🎮 Níveis de Desenvolvimento e Funcionalidades

### 🥉 1. Nível Novato (Fundamentos de Loops)
* **Estruturas de Repetição Básicas:** Implementação de loops simples para controlar a quantidade exata de casas percorridas pelas peças principais.
* **Movimentação Controlada:**
  * **Bispo:** Movimentação de 5 casas na diagonal superior direita.
  * **Torre:** Movimentação de 5 casas para a direita.
  * **Rainha:** Movimentação de 8 casas para a esquerda.
* **Saída Formatada:** Exibição clara e padronizada das direções no console usando as nomenclaturas obrigatórias (ex: `Cima`, `Direita`, etc.).

### 🥈 2. Nível Aventureiro (Loops Aninhados)
* **Movimentação Complexa (Cavalo):** Lógica desenvolvida para simular o movimento característico em "L" do Cavalo (movimentar para baixo e para a esquerda).
* **Múltiplas Estruturas:** Uso obrigatório de pelo menos duas estruturas de repetição distintas na mesma lógica, combinando estruturas como `for`, `while` ou `do-while`.
* **Loops Aninhados:** Controle do padrão de movimento em "L" através do aninhamento de loops para validar as coordenadas internas passo a passo.

### 🥇 3. Nível Mestre (Recursividade e Controle Avançado)
* **Funções Recursivas:** Substituição dos loops simples por algoritmos de recursividade para gerenciar as movimentações do Bispo, Torre e Rainha.
* **Mecânicas Avançadas do Cavalo:** Movimentação do Cavalo otimizada para realizar 1 vez o movimento em "L" (para cima e à direita) utilizando variáveis múltiplas e/ou condições de parada.
* **Estruturas de Desvio:** Aplicação prática dos comandos de controle de fluxo `continue` e `break`.
* **Mapeamento do Bispo:** Implementação obrigatória de funções recursivas combinadas com loops aninhados para renderizar e mover o Bispo diagonalmente.

---

## 🛠️ Requisitos Técnicos Consolidados

### Requisitos Funcionais
* **Entrada Manual e Constantes:** Definição manual dos valores de movimentação no escopo usando variáveis controladas e constantes para evitar repetição de código.
* **Nomenclatura Padronizada:** Respeito estrito às saídas textuais obrigatórias do sistema: `printf("Cima\n");`, `printf("Baixo\n");`, `printf("Esquerda\n");` e `printf("Direita\n");`.

### Requisitos Não-Funcionais
* **Performance:** Cálculos e impressões em tela executados sem atrasos perceptíveis no console.
* **Manutenibilidade e Documentação:** Código escrito com nomes de variáveis altamente legíveis e documentado com comentários detalhados explicando a lógica de cada função.

---

## 🚀 Como Executar o Projeto

Certifique-se de possuir um compilador C (como o `gcc`) devidamente configurado em sua máquina local.

1. Clone este repositório:
```bash
git clone https://github.com
```

2. Acesse a pasta do projeto:
```bash
cd desafio-xadrez-AlexSG1709-main
```

3. Compile o código-fonte:
```bash
gcc xadrez.c -o xadrez
```

4. Execute o simulador no terminal:
```bash
./xadrez
```

---
*Projeto desenvolvido como atividade acadêmica para a plataforma MateCheck.*
