# EV Challenge 2026 — Arquitetura Sustentável para Eletropostos

## Integrantes
- Bryan Lugli — RM:571350
- Beckman Lugli — RM:573442 
- Guiherme Xavier — RM:573053

---

# Objetivo do Projeto

Este projeto tem como objetivo propor uma solução computacional eficiente para sistemas de eletropostos, utilizando conceitos de Arquitetura de Computadores, Sistemas Embarcados e Programação em Assembly.

A proposta busca reduzir o consumo energético causado pelo processamento computacional dos eletropostos, tornando o sistema mais sustentável e eficiente.

---

# Problema Identificado

Atualmente, muitos eletropostos utilizam softwares desenvolvidos em linguagens de alto nível executados em hardwares genéricos.

Esse modelo pode gerar diversos problemas, como:

- Maior consumo energético
- Uso excessivo de CPU
- Processamento desnecessário
- Maior quantidade de ciclos de clock
- Necessidade de hardware mais potente
- Menor eficiência energética

Mesmo pequenas operações, como autenticação de usuário ou leitura de sensores, podem consumir recursos computacionais acima do necessário.

---

# Justificativa

A mobilidade elétrica depende diretamente da eficiência energética.

Embora os eletropostos sejam projetados para fornecer energia limpa aos veículos elétricos, o próprio sistema computacional interno pode gerar desperdício energético significativo.

Por isso, otimizar o software e a arquitetura utilizada contribui diretamente para:

- Sustentabilidade
- Economia de energia
- Melhor aproveitamento de energias renováveis
- Redução de custos operacionais

---

# Proposta de Solução

Nossa proposta consiste no desenvolvimento de um módulo computacional otimizado em Assembly utilizando arquitetura RISC-V.

O sistema será responsável por operações críticas do eletroposto, como:

- Autenticação de usuários
- Controle de carregamento
- Leitura de sensores
- Monitoramento energético
- Controle de corrente elétrica

A utilização de Assembly permite maior controle sobre o hardware, reduzindo o número de instruções executadas e diminuindo o consumo energético.

---

# Arquitetura Utilizada

## RISC-V

Escolhemos a arquitetura RISC-V devido às suas características de eficiência energética e simplicidade.

### Características do RISC-V
- Menor conjunto de instruções
- Execução mais rápida
- Menor consumo energético
- Melhor desempenho em sistemas embarcados
- Hardware mais simples

---

# Comparação: RISC vs CISC

| Característica | RISC | CISC |
|---|---|---|
| Quantidade de instruções | Pequena | Grande |
| Complexidade | Baixa | Alta |
| Consumo energético | Menor | Maior |
| Eficiência | Alta | Média |
| Hardware | Mais simples | Mais complexo |
| Ideal para embarcados | Sim | Nem sempre |

## Conclusão da Comparação

A arquitetura RISC apresenta maior eficiência energética, sendo mais adequada para aplicações sustentáveis e sistemas embarcados de baixo consumo.

---

# Comparação: Linguagem de Alto Nível vs Assembly

| Aspecto | Alto Nível | Assembly |
|---|---|---|
| Facilidade de programação | Alta | Média |
| Controle do hardware | Baixo | Total |
| Quantidade de instruções | Maior | Menor |
| Consumo energético | Maior | Menor |
| Eficiência computacional | Média | Alta |

---

# Pipeline

O conceito de pipeline permite que o processador execute múltiplas etapas simultaneamente, aumentando o desempenho computacional.

## Benefícios
- Maior velocidade
- Melhor aproveitamento da CPU
- Menor desperdício computacional
- Maior eficiência energética

---

# Clock e Ciclos de CPU

O clock determina a velocidade de execução das instruções do processador.

Quanto maior a quantidade de ciclos utilizados por um programa:
- maior será o consumo energético
- maior será o aquecimento
- menor será a eficiência

A programação em Assembly reduz a quantidade de ciclos necessários para execução das tarefas.

---

# Sistemas Embarcados

O projeto foi pensado para funcionar em sistemas embarcados e microcontroladores de baixo consumo.

## Vantagens
- Menor gasto energético
- Hardware compacto
- Maior eficiência
- Menor custo operacional

---

# Exemplo de Código em Alto Nível (C)

```c
int soma(int a, int b){
   return a + b;
}
```

---

# Exemplo em Assembly

```assembly
LI R1, 1
LI R2, 2
ADD R3, R1, R2
```

---

# Comparação entre os códigos

O código em Assembly:
- executa menos instruções
- possui menor abstração
- reduz o uso da CPU
- consome menos energia

Já linguagens de alto nível geram instruções adicionais durante a compilação.

---

# Sustentabilidade

A sustentabilidade é o principal foco deste projeto.

A redução do consumo computacional impacta diretamente:
- na economia de energia
- na eficiência dos eletropostos
- no melhor aproveitamento de energia renovável

Além disso:
- reduz a necessidade de hardware potente
- diminui geração de calor
- melhora a vida útil do sistema

---

# Impactos Esperados

## Técnicos
- Redução do consumo computacional
- Menor utilização de CPU
- Maior eficiência energética
- Melhor desempenho embarcado

## Sustentáveis
- Menor desperdício de energia
- Melhor uso de energias renováveis
- Redução do impacto ambiental

---

# Tecnologias Utilizadas

- Assembly
- RISC-V
- Sistemas Embarcados
- Arquitetura de Computadores
- Pipeline
- Controle de clock
- Eficiência energética

---

# Conclusão

Este projeto demonstra como conceitos de Arquitetura de Computadores e Programação em Assembly podem contribuir diretamente para a sustentabilidade na mobilidade elétrica.

A utilização de arquiteturas eficientes e software otimizado reduz o desperdício computacional e melhora o desempenho energético dos eletropostos.

Assim, a tecnologia pode ser utilizada não apenas para desempenho, mas também para promover soluções sustentáveis e energeticamente eficientes.
