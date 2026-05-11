https://app.cyberhuntlab.com.br

## **Projeto: Smart Bankroll Manager (Balança Inteligente)**
### **1. Visão Geral**
Este projeto nasceu da necessidade de transformar uma banca inicial pequena (R$ 73,00) em um patrimônio de equilíbrio através da matemática aplicada e disciplina operacional. A aplicação não é apenas uma calculadora de juros compostos, mas um sistema de gestão de risco dinâmico que prioriza a sobrevivência do capital em mercados voláteis.
### **2. Arquitetura e Lógica de Desenvolvimento**
O projeto foi estruturado com foco em **Clean Code** e **Interatividade**, utilizando:
 * **Motor de Cálculo Exponencial**: Implementação da fórmula de juros compostos para projetar metas diárias de 5% a 15%.
 * **Algoritmo de Balança Inteligente**: O diferencial técnico do projeto. Desenvolvi uma função que permite ao usuário sincronizar seu saldo real a qualquer momento. Se houver uma perda, o sistema recalcula automaticamente toda a trajetória futura, ajustando as metas em dinheiro para manter a porcentagem de risco constante.
 * **Gestão Anti-Quebra (Sem Martingale)**: A lógica do software proíbe cálculos de recuperação agressiva (dobrar apostas), focando em entradas fixas e limites de *Stop Loss* de 10% do capital atual.
### **3. Implementação Técnica**
 * **Frontend Reativo**: Utilizei HTML5 e CSS3 com uma estética "Dark Mode & Neon", otimizada para visualização em dispositivos móveis e tablets.
 * **Visualização de Dados**: Integração com a biblioteca **Chart.js** para gerar gráficos de linha em tempo real, permitindo que o usuário visualize a curva de crescimento e ajuste as expectativas visualmente.
 * **DOM Manipulation**: JavaScript puro (Vanilla JS) para garantir que a tabela de 30 dias e o gráfico se atualizem instantaneamente ao alterar os parâmetros de entrada.
### **4. Metodologia "Pé no Chão"**
O software foi desenhado para educar o usuário. Conforme a banca cresce e atinge marcos como R$ 3.500,00, a lógica interna sugere a redução das metas percentuais (de 8% para 2-3%), transicionando de uma fase de alavancagem para uma fase de consistência patrimonial.

