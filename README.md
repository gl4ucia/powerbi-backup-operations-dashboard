
---
## Indicadores (KPIs)

Os KPIs criados no projeto:

- **Total de Jobs Processados**
- **Taxa de Sucesso (%)**
- **Total de Falhas**
- **SLA Estourado (%)**
- **Volume Total de Dados Processados (GB)**

---

## Visualizações Desenvolvidas

### **1. Tendência de Falhas por Dia**
- Linha contínua mostrando variações no volume de falhas ao longo do período.
- Ajuda a identificar picos inesperados de falha.

### **2. Status dos Jobs por Ambiente**
- Gráfico de colunas empilhadas com Sucesso x Falha.
- Facilita comparações entre Produção, Homologação e Desenvolvimento.

### **3. Falhas por Cliente**
- Gráfico de barras organizado por clientes, mostrando onde há maior incidência de falhas.

---

## Dicionário de Dados

| Coluna             | Descrição                                            |
|--------------------|--------------------------------------------------------|
| JobID              | Identificador único do job                             |
| DataHoraInicio     | Data e hora de execução do backup                      |
| Cliente            | Unidade / empresa do cliente                           |
| Ambiente           | Produção / Homologação / Desenvolvimento              |
| Ferramenta         | Veeam ou NetBackup                                     |
| TipoJob            | Completo / Incremental / Diferencial                  |
| Regiao             | On-premise, AWS ou Azure                               |
| DuracaoMin         | Tempo de execução em minutos                           |
| TamanhoGB          | Volume de dados processados (GB)                       |
| Status             | Sucesso ou Falha                                       |
| CategoriaFalha     | Tipo de falha (rede, credencial, storage, etc.)        |
| SLA_Minutos        | Tempo máximo aceitável                                 |
| SLA_Estourado      | Sim / Não                                              |

---

## Tecnologias Utilizadas

- **Power BI Desktop**
- **Power Query (ETL)**
- **DAX (criação de medidas e indicadores)**
- **Python (geração do dataset simulado)**
- **Governança de Dados**
- **Storytelling com Dados**

---

## Insights Obtidos (exemplos)

- O ambiente de **Produção concentra o maior volume tanto de jobs quanto de falhas**.
- A tendência de falhas apresenta **picos em datas específicas**, indicando possíveis janelas de manutenção ou instabilidade.
- Alguns clientes apresentam **falhas recorrentes**, sugerindo necessidade de análise mais profunda.

---

## Como Executar o Projeto

1. Baixe o arquivo `.pbix` na pasta `/pbix`
2. Instale o Power BI Desktop  
3. Abra o arquivo  
4. Verifique se o arquivo CSV está na pasta correta (`/data`)  
5. Caso necessário, atualize o caminho da fonte de dados

---

## Skills Demonstradas

- Power BI  
- Modelagem de Dados  
- DAX  
- ETL com Power Query  
- Visual Design e Data Storytelling  
- Métricas de desempenho  
- Análise de dados operacionais
  
---

## Sobre Mim

Sou profissional de TI com experiência em infraestrutura, backup corporativo, cloud e governança de dados, atualmente em transição para **Análise de Dados e BI**.  
Este projeto representa minha evolução prática na área, aplicando dados reais do meu contexto profissional para gerar insights estratégicos.

---

