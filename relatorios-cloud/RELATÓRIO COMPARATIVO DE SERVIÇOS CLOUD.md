# RELATÓRIO COMPARATIVO DE IMPLEMENTAÇÃO DE SERVIÇOS CLOUD

**Data:** 15 de janeiro de 2025  
**Empresa:** Abstergo Industries  
**Responsável:** Robson Alves Batista

---

## Introdução
Este relatório apresenta uma análise comparativa da implementação de serviços em três grandes provedores de nuvem: **AWS (Amazon Web Services)**, **Microsoft Azure** e **Google Cloud Platform (GCP)**.  
O objetivo é consolidar os resultados obtidos pela Abstergo Industries em termos de **redução de custos**, **eficiência operacional** e **escalabilidade**.

---

## Serviços Selecionados

| Provedor       | Armazenamento                  | Computação Serverless | Banco de Dados Gerenciado |
|----------------|--------------------------------|-----------------------|---------------------------|
| **AWS**        | Amazon S3 + Glacier            | AWS Lambda            | Amazon RDS                |
| **Azure**      | Azure Blob Storage + Archive   | Azure Functions       | Azure SQL Database        |
| **Google Cloud** | Cloud Storage + Coldline      | Cloud Functions       | Cloud SQL                 |

---

## Comparativo de Custos

Valores estimados em **R$ (reais)**, considerando taxa de câmbio de US$ 1 ≈ R$ 5,00.

| Serviço / Recurso         | Infra Local (Antes) | AWS (Depois) | Azure (Depois) | Google Cloud (Depois) |
|----------------------------|---------------------|--------------|----------------|-----------------------|
| Armazenamento de dados     | R$ 25.000/mês       | R$ 7.500/mês | R$ 8.000/mês   | R$ 7.800/mês          |
| Processamento de rotinas   | R$ 15.000/mês       | R$ 4.000/mês | R$ 4.500/mês   | R$ 4.200/mês          |
| Banco de dados             | R$ 22.500/mês       | R$ 10.000/mês| R$ 11.000/mês  | R$ 10.500/mês         |
| **Total**                  | **R$ 62.500/mês**   | **R$ 21.500/mês** | **R$ 23.500/mês** | **R$ 22.500/mês** |

---

##  Gráfico Comparativo de Custo

![Gráfico Comparativo de Custo](https://github.com/robsonosbor/relatorios-implementacao-cloud-aws-azure-gcp/blob/main/graficos/grafico-comparativo-custos-consolidado.png)

---

## Análise Consolidada

- **AWS**: Apresentou a **maior redução percentual de custos (~66%)**, destacando-se pelo uso eficiente do Amazon S3 e Lambda.  
- **Azure**: Obteve uma redução de **~62%**, com destaque para a flexibilidade do Azure SQL Database e integração com o ecossistema Microsoft.  
- **Google Cloud**: Apresentou economia de **~64%**, com forte vantagem em armazenamento de baixo custo (Coldline) e simplicidade de integração com serviços de dados.  

---

## Conclusão

A implementação dos serviços em nuvem trouxe benefícios claros para a Abstergo Industries:  
- **Redução significativa de custos** em todos os provedores.  
- **Escalabilidade e flexibilidade** para lidar com demandas variáveis.  
- **Maior eficiência operacional**, eliminando gastos com infraestrutura física e manutenção.  

Embora todos os provedores tenham demonstrado vantagens, a escolha final pode depender de fatores estratégicos como:  
- Integração com sistemas já existentes (Azure para ambientes Microsoft).  
- Maior variedade de serviços e maturidade (AWS).  
- Custos competitivos e simplicidade de uso (Google Cloud).  

---

## Anexos
- Planilhas comparativas detalhadas.  
- Gráficos de custos antes e depois da implementação.  
- Documentação técnica de integração.

---

**Assinatura do Responsável pelo Projeto:**  

Robson Alves Batista
