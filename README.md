# ⚡ EV Challenge 2026 — Arquitetura Sustentável para Eletropostos

## 👥 Integrantes
- Bryan Lugli — RM:571350
- Beckman Lugli — RM:573442
- Guilherme Xavier — RM:573053

---

# 🎯 Objetivo do Projeto

O objetivo deste projeto é desenvolver uma proposta de solução computacional eficiente para eletropostos, utilizando conceitos de Arquitetura de Computadores e programação em Assembly.

A ideia principal é reduzir o consumo energético causado pelo processamento computacional dos sistemas internos dos eletropostos, tornando o funcionamento mais eficiente e sustentável.

---

# ❗ Problema

Atualmente, muitos eletropostos utilizam softwares desenvolvidos em linguagens de alto nível executados em hardwares genéricos. Isso pode gerar maior consumo energético e uso excessivo do processador, principalmente em tarefas simples como autenticação de usuários, leitura de sensores e controle de carregamento.

Além disso, o excesso de processamento aumenta a quantidade de ciclos de CPU utilizados, reduzindo a eficiência energética do sistema.

---

# 📌 Justificativa

Mesmo sendo utilizados em um contexto sustentável, os eletropostos também precisam possuir sistemas computacionais eficientes.

A otimização do software e da arquitetura utilizada pode reduzir desperdícios computacionais, melhorar o aproveitamento da energia e diminuir custos operacionais.

---

# 💡 Proposta de Solução

Nossa proposta consiste no desenvolvimento de um módulo otimizado em Assembly utilizando arquitetura RISC-V.

O sistema será responsável por funções importantes do eletroposto, como:
- autenticação de usuários
- leitura de sensores
- controle de carregamento
- monitoramento energético

A utilização de Assembly permite maior controle sobre o hardware, reduzindo a quantidade de instruções executadas e diminuindo o consumo energético.

---

# 🖥️ Arquitetura Utilizada

Foi escolhida a arquitetura RISC-V por possuir um conjunto de instruções mais simples e eficiente.

Diferente de arquiteturas mais complexas, o modelo RISC trabalha com menos instruções, permitindo execução mais rápida e menor gasto energético, sendo muito utilizado em sistemas embarcados.

---

# ⚙️ Conceitos Aplicados

## 🔄 Pipeline

O pipeline permite que o processador execute diferentes etapas simultaneamente, aumentando o desempenho e reduzindo desperdícios computacionais.

## ⏱️ Clock e ciclos de CPU

Quanto maior a quantidade de ciclos utilizados por um programa, maior será o consumo de energia.

Com Assembly, é possível reduzir instruções desnecessárias e melhorar a eficiência do processamento.

## 🔋 Sistemas embarcados

O projeto foi pensado para rodar em sistemas embarcados e microcontroladores de baixo consumo energético.

---

# 🔍 Comparação entre Alto Nível e Assembly

Linguagens de alto nível são mais fáceis de programar, porém geram mais instruções durante a compilação.

Já o Assembly possui acesso mais direto ao hardware, permitindo maior otimização e menor uso do processador.

---

# 💻 Exemplo de Código em C

```c
int soma(int a, int b){
   return a + b;
}
```

---

# 🧠 Exemplo em Assembly

```assembly
LI R1, 1
LI R2, 2
ADD R3, R1, R2
```

---

# 🌱 Sustentabilidade

A proposta busca reduzir o consumo computacional dos eletropostos, diminuindo o gasto energético e melhorando a eficiência no uso de energias renováveis.

Além disso, a redução do processamento também diminui aquecimento do hardware e aumenta a vida útil dos equipamentos.

---

# 📈 Impactos Esperados

- menor consumo energético
- maior eficiência computacional
- redução do uso de CPU
- melhor desempenho em sistemas embarcados
- menor desperdício de energia

---

# 🛠️ Tecnologias Utilizadas

- Assembly
- RISC-V
- Sistemas embarcados
- Pipeline
- Arquitetura de computadores

---

# ✅ Conclusão

Este projeto demonstra como conceitos de Arquitetura de Computadores podem contribuir para soluções mais sustentáveis na mobilidade elétrica.

A utilização de Assembly e arquiteturas eficientes permite reduzir desperdícios computacionais e melhorar o desempenho energético dos eletropostos.
