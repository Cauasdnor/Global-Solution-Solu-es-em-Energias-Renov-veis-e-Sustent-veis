# 🌱 Global Solution – Soluções em Energias Renováveis e Sustentáveis
### Ciências da Computação – FIAP (2025)

Este repositório contém a solução da equipe para a Global Solution, com foco na análise de consumo energético em um ambiente corporativo híbrido. A proposta consiste em avaliar padrões de uso de energia, identificar desperdícios e propor soluções baseadas em sustentabilidade e eficiência operacional.

---

## 👥 **Integrantes da Equipe**

- **Ana Luiza – RM 563171**  
- **Sofia Franken – RM 562767**  
- **Cauã Santos – RM 564008**

---

## 🎯 **Objetivo do Projeto**

O objetivo deste trabalho é analisar dados de consumo energético ao longo de 30 dias em um ambiente corporativo moderno, identificado desperdícios e propondo melhorias práticas para reduzir custos operacionais e a emissão de CO2.

A solução está alinhada ao conceito de “futuro do trabalho”, que envolve:
- ambientes híbridos,  
- automação inteligente,  
- digitalização,  
- uso eficiente de recursos.  

---

## 📊 **Dataset Utilizado**

O conjunto de dados contém:

- **Total de registros:** 2.190 leituras  
- **Período:** 30 dias  
- **Frequência:** 1 leitura por hora  
- **Áreas monitoradas:**
  - OpenSpace  
  - Salas de Reunião  
  - TI/Servers  
  - Home Office  

Arquivo principal:  
dados_consumo_energia_escritorio.csv

yaml
Copiar código

---

## 🧪 **Metodologia Aplicada**

1. Carregamento e pré-processamento dos dados  
2. Análise geral do consumo total e diário  
3. Identificação de horários de pico e baixa ocupação  
4. Cálculo de desperdício energético  
5. Comparação entre áreas do escritório  
6. Geração de gráficos explicativos  
7. Estimativa de economia energética, financeira e ambiental  

---

## 📉 **Gráficos da Análise**

Os seguintes gráficos foram gerados no notebook:

- `grafico_consumo_diario.png`  
- `grafico_consumo_por_area.png`  
- `grafico_desperdicio_area.png`

(Os arquivos devem estar na pasta `/graficos` do repositório.)

---

## 📈 **Principais Resultados Obtidos**

### 🔹 Consumo total do período:
**1662.88 kWh**

### 🔹 Consumo médio diário:
**4.56 kWh/dia**

### 🔹 Desperdício energético identificado:
**954.28 kWh** (57.39% do total)

### 🔹 Economia estimada com redução de 40%:
- **381.71 kWh economizados**
- **R$ 343.54 de redução na conta**
- **0.0191 toneladas de CO2 evitadas**

Esses dados evidenciam uma grande capacidade de economia caso medidas de automação e uso consciente sejam aplicadas.

---

## ⚙️ **Como Executar o Notebook**

1. Abra o Google Colab  
2. Faça upload dos arquivos:
   - `Global_Solution_Analise.ipynb`
   - `dados_consumo_energia_escritorio.csv`
3. Execute as células na ordem  
4. Os gráficos e indicadores serão gerados automaticamente  

---

## 📂 **Estrutura do Repositório**

/global-solution-energia/
│
├── dados_consumo_energia_escritorio.csv
├── Global_Solution_Analise.ipynb
├── README.md
│
└── /graficos
├── grafico_consumo_diario.png
├── grafico_consumo_por_area.png
└── grafico_desperdicio_area.png

yaml
Copiar código

---

## 🧭 **Conclusão**

A análise mostra que mais da metade do consumo energético ocorre em horários sem atividade.  
Com pequenas ações, como automação, sensores de presença, desligamento programado e ajustes na rotina híbrida, é possível:

✔️ reduzir custos  
✔️ diminuir a emissão de CO2  
✔️ tornar o ambiente corporativo mais sustentável  

Este projeto demonstra como dados + tecnologia = eficiência e impacto ambiental positivo.

---

## ✔️ **Licença**

Projeto acadêmico – FIAP 2025.
