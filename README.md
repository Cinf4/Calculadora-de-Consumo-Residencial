# ⚡ Simulador de Auditoria Energética Residencial

![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![Status](https://img.shields.io/badge/Status-Concluído-brightgreen?style=for-the-badge)
![License](https://img.shields.io/badge/License-MIT-yellow?style=for-the-badge)

O **Simulador de Auditoria Energética** é uma ferramenta desenvolvida em Python para auxiliar cidadãos brasileiros na gestão do consumo elétrico doméstico. O sistema permite calcular o impacto financeiro real de cada aparelho, integrando as variações das **Bandeiras Tarifárias da ANEEL**.

## 🎯 Objetivo
Proporcionar transparência e educação financeira, permitindo que o usuário identifique os "vilões" da conta de luz e simule economias baseadas em mudanças de hábito.

## 🚀 Funcionalidades
- **Cálculo Multi-Aparelhos:** Adicione quantos dispositivos quiser em uma única simulação.
- **Sistema de Bandeiras:** Ajuste dinâmico de custo (Verde, Amarela, Vermelha P1 e P2).
- **Robustez (Anti-Erro):** Tratamento de exceções para garantir que o programa não feche caso o usuário digite letras em campos numéricos.
- **Insight de Economia:** Projeção automática de economia ao reduzir 10% do consumo.

## 🧮 Fórmula Utilizada
O cálculo do consumo mensal segue a norma técnica:

$$ConsumoMensal(kWh) = \frac{Potência(W) \times Horas/Dia \times 30 dias}{1000}$$

O custo total é obtido multiplicando o consumo pelo valor do kWh ajustado pela bandeira tarifária selecionada.

## 🛠️ Tecnologias e Ferramentas
* **Linguagem:** Python 3.x 🐍
* **Lógica:** Estruturas de repetição (`while`), Condicionais (`if/elif`) e Tratamento de Erros (`try/except`).
* **Versionamento:** Git & GitHub.

## 💻 Como Executar
1. Certifique-se de ter o [Python](https://www.python.org/) instalado.
2. Clone este repositório:
   ```bash
   git clone [https://github.com/seu-usuario/nome-do-repositorio.git](https://github.com/seu-usuario/nome-do-repositorio.git)
