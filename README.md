# 🎯 Calculadora de Cavados de Projétil

![Status](https://img.shields.io/badge/Status-Conclu%C3%ADdo-brightgreen)
![Tech](https://img.shields.io/badge/Tech-HTML%20%7C%20CSS%20%7C%20JS-blue)

Aplicação web desenvolvida para auxiliar no cálculo técnico de cavados em projéteis balísticos, focada em precisão e facilidade de uso em campo.

## 🔗 Acesso ao Sistema
> **[Clique aqui para acessar a Calculadora Online](https://thiagofarias2013-dot.github.io/calc-cav/)**

## 📋 Sobre o Projeto
Este software foi desenvolvido no contexto de **Análise e Desenvolvimento de Sistemas** para solucionar um problema prático de balística forense: determinar o número total de cavados ($N_c$) de um projétil baseando-se em fragmentos ou medidas unitárias.

A aplicação elimina a necessidade de contagem manual ou cálculos repetitivos, garantindo precisão através da inserção de parâmetros métricos fundamentais e entregando tanto o resultado matemático exato quanto o arredondamento lógico (inteiro).

## 📐 Modelo Matemático
O algoritmo baseia-se na relação geométrica entre a circunferência total do projétil e a largura da unidade de ciclo (cavado + ressalto).

A fórmula implementada é:

$$N_c = \frac{\pi \times d}{cav + res}$$

Onde:
* **$d$**: Diâmetro total do projétil.
* **$cav$**: Medida de um único cavado (input unitário).
* **$res$**: Medida de um único ressalto (input unitário).
* **$\pi$**: Constante (aprox. 3,14).

## 🚀 Tecnologias Utilizadas
O projeto foi construído utilizando tecnologias web modernas, garantindo compatibilidade Cross-Browser e Responsividade (Mobile-First):

* **HTML5:** Estruturação semântica e acessibilidade.
* **CSS3:** Estilização responsiva, Clean Design e UX (User Experience).
* **JavaScript (ES6+):** Lógica de cálculo, manipulação do DOM e tratamento de exceções.

## 🛠️ Funcionalidades
- [x] Cálculo automático baseado em inputs decimais.
- [x] Tratamento de erros (prevenção de divisão por zero).
- [x] Suporte a vírgula (padrão PT-BR) e ponto como separadores decimais.
- [x] Interface com Tooltips explicativos para o usuário final.

---
Desenvolvido por um estudante de Análise e Desenvolvimento de Sistemas.
