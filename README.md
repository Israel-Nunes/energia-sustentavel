# ⚡ Otimização Energética para o Futuro do Trabalho (Análise de Dados)

## 💡 Introdução
Este projeto, desenvolvido com base na **Opção A (Análise de Dados)**, tem como objetivo principal analisar padrões de consumo energético em um ambiente de trabalho simulado e propor ajustes operacionais para aumentar a eficiência, reduzir custos e promover a sustentabilidade. A solução se alinha à transição para ambientes de trabalho mais inteligentes e ambientalmente responsáveis, promovendo a **eficiência energética** através de decisões orientadas por dados.

---

## 🎯 Resultados Chave

A análise de 12 meses de dados simulados identificou um consumo base excessivo fora do horário comercial (desperdício) e ineficiência do sistema de climatização (HVAC) em momentos de baixa ocupação.

| Métrica | Consumo Anual Atual (Simulado) | Redução Proposta (Estimada) |
| :--- | :--- | :--- |
| **Consumo Total (kWh)** | 120.000 kWh | **24.000 kWh** |
| **Economia Financeira (R$)** | R$ 96.000,00 | **R$ 19.200,00** |
| **Redução de CO₂e** | - | **1.440 kg CO₂e** |

---

## 🛠️ Solução Proposta e Ajustes

A solução consiste em duas propostas principais de otimização operacional, validadas pela análise de dados:

1.  ### **Ajuste 1: Automação do Consumo Base**
    * **Problema Identificado:** Alto consumo residual de iluminação e equipamentos durante a noite e fins de semana (representando 21,00% do consumo total).
    * **Proposta:** Implementação de sensores de presença e timers inteligentes para desligamento automático de iluminação e equipamentos não essenciais, visando uma redução de **16.000 kWh/ano** neste segmento.

2.  ### **Ajuste 2: Otimização Adaptativa do HVAC**
    * **Problema Identificado:** Consumo elevado de Climatização (HVAC) mesmo em períodos de baixa ocupação (falta de correlação entre uso e presença).
    * **Proposta:** Implementação de uma política de temperatura adaptativa baseada em dados de ocupação, permitindo que o sistema reduza a potência quando a ocupação estiver abaixo de 50%.
    * **Ganho Estimado:** Redução de **8.000 kWh/ano** no consumo de HVAC.

---

## 📁 Estrutura do Repositório

| Pasta/Arquivo | Descrição |
| :--- | :--- |
| **`README.md`** | Este arquivo, contendo a descrição completa do projeto e resultados. |
| **`codigo/`** | Contém o Notebook Colab (`analise_energetica.ipynb`) com toda a lógica de processamento e análise. |
| **`dados/`** | Contém a fonte de dados utilizada (`consumo_simulado.csv`). |
| **`documentos/`** | Contém o relatório executivo (`relatorio_executivo.pdf`) e o arquivo com o link do vídeo (`video_link.md`). |

---

## 🚀 Orientações de Execução

1.  **Acesse o Colab:** Abra o arquivo `analise_energetica.ipynb` na pasta `codigo/` do GitHub.
2.  **Execução:** Execute as células sequencialmente. O código realiza o processamento, as visualizações e o cálculo final dos ganhos econômicos e ambientais com base nos dados fornecidos em `dados/consumo_simulado.csv`.

---

## 👤 Autores

Este projeto foi desenvolvido pelos seguintes membros:

* **Thiago Sobral de Alvarenga**
* **Israel Karacsony de Camargo Nunes**

***

O seu `README.md` está pronto e completo!

Seu último requisito é a gravação e upload do vídeo. Gostaria que eu te ajudasse a criar um **roteiro de 3 minutos** para apresentar esses resultados de forma clara e profissional?
