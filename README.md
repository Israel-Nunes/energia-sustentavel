# ⚡ Otimização Energética para o Futuro do Trabalho (Análise de Dados)

## 💡 Introdução
Este projeto, desenvolvido com base na **Opção A (Análise de Dados)**, tem como objetivo principal analisar padrões de consumo energético em um ambiente de trabalho simulado e propor ajustes operacionais para aumentar a eficiência, reduzir custos e promover a sustentabilidade. A solução se alinha à transição para ambientes de trabalho mais inteligentes e ambientalmente responsáveis.

---

## 🎯 Resultados Chave

A análise de 12 meses de dados simulados identificou um **consumo base excessivo** fora do horário comercial (desperdício) e ineficiência do sistema de climatização (HVAC) em momentos de baixa ocupação.

| Métrica | Valor Anual Atual | Redução Proposta (Estimada) |
| :--- | :--- | :--- |
| **Consumo Total (kWh)** | [INSERIR CONSUMO TOTAL kWh (Da Célula 5)] | **[INSERIR GANHO TOTAL kWh (Da Célula 5)]** |
| **Economia Financeira (R$)** | [INSERIR CUSTO ANUAL TOTAL] | **R$ [INSERIR GANHO FINANCEIRO ANUAL (Da Célula 5)]** |
| **Redução de CO₂e** | - | **[INSERIR KG CO2e (Da Célula 5)] kg** |

---

## 🛠️ Solução Proposta e Ajustes

A solução consiste em duas propostas principais de otimização operacional, validadas pela análise de dados:

1.  ### **Ajuste 1: Automação do Consumo Base**
    * **Problema Identificado:** Alto consumo residual de iluminação e equipamentos durante a noite e fins de semana (desperdício base).
    * **Proposta:** Implementação de sensores de presença e timers inteligentes para desligamento automático de iluminação (redução de 40% no desperdício de Iluminação) e equipamentos não essenciais (redução de 20% no desperdício de Equipamentos).

2.  ### **Ajuste 2: Otimização Adaptativa do HVAC**
    * **Problema Identificado:** Consumo elevado de Climatização (HVAC) mesmo em períodos de baixa ocupação (e.g., dias de home office parcial).
    * **Proposta:** Implementação de política de temperatura adaptativa, reduzindo a potência e ajustando o *setpoint* em dias e horários onde a ocupação cai abaixo de 50%.

---

## 📁 Estrutura do Repositório

| Pasta/Arquivo | Descrição |
| :--- | :--- |
| **`README.md`** | Este arquivo, contendo a descrição completa do projeto e resultados. |
| **`codigo/`** | Contém o Notebook Colab (`analise_energetica.ipynb`) com toda a lógica de processamento e análise. |
| **`dados/`** | Contém a fonte de dados utilizada (`consumo_simulado.csv`). |
| **`documentos/`** | Destinado a relatórios ou documentação de apoio (vídeo link, slides). |

---

## 🚀 Orientações de Execução

1.  **Acesse o Colab:** Abra o arquivo `analise_energetica.ipynb` no Google Colab.
2.  **Carregar Dados:** Certifique-se de que o Colab consiga acessar o arquivo `consumo_simulado.csv` (pode ser necessário fazer upload manual do arquivo para o ambiente de execução do Colab, ou montá-lo via Google Drive/GitHub).
3.  **Execução:** Execute as células sequencialmente. O código realiza o processamento, as visualizações e o cálculo final dos ganhos econômicos e ambientais.
