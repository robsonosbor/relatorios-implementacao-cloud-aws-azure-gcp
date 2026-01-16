# RELATÓRIO DE IMPLEMENTAÇÃO DE SERVIÇOS AWS

**Data:** 15 de janeiro de 2025  
**Empresa:** Abstergo Industries  
**Responsável:** Robson Alves Batista



## Introdução
Este relatório apresenta o processo de implementação de ferramentas na empresa farmacêutica fictícia **Abstergo Industries**, realizado por Robson Alves Batista.  
O objetivo principal do projeto é elencar **3 serviços AWS** que proporcionem **diminuição imediata de custos**, sem comprometer a segurança, escalabilidade e eficiência dos processos internos da organização.



## Descrição do Projeto

O projeto foi dividido em **3 etapas**, cada uma focada em um serviço específico da AWS, com objetivos claros de otimização de custos e melhoria operacional.

### Etapa 1: Amazon S3 (Simple Storage Service)
- **Foco da ferramenta:** Armazenamento escalável e de baixo custo.  
- **Descrição de caso de uso:**  
  A empresa substituiu servidores locais de arquivos por buckets no Amazon S3, utilizando políticas de ciclo de vida para mover dados antigos para classes de armazenamento mais baratas, como **S3 Glacier**.  
  Isso reduziu custos com infraestrutura física e manutenção, além de garantir maior durabilidade e disponibilidade dos dados.



### Etapa 2: AWS Lambda
- **Foco da ferramenta:** Computação serverless com cobrança sob demanda.  
- **Descrição de caso de uso:**  
  Processos internos que antes rodavam em servidores dedicados foram migrados para funções Lambda, como rotinas de integração de dados laboratoriais e automação de relatórios.  
  Com isso, a empresa passou a pagar apenas pelo tempo de execução, eliminando custos de servidores ociosos e reduzindo despesas operacionais.



### Etapa 3: Amazon RDS (Relational Database Service)
- **Foco da ferramenta:** Banco de dados gerenciado e otimizado.  
- **Descrição de caso de uso:**  
  A migração de bancos de dados locais para o Amazon RDS permitiu reduzir custos com licenciamento, manutenção e administração de servidores.  
  Além disso, o uso de instâncias otimizadas e escalabilidade automática garantiu melhor performance e menor gasto em recursos não utilizados.



## Comparativo de Custos

A tabela abaixo apresenta uma estimativa comparativa de custos **antes e depois da implementação** dos serviços AWS.  
**Taxa de câmbio utilizada:** US$ 1 ≈ R$ 5,00 (valores aproximados para fins de simulação).

| Serviço / Recurso         | Situação Anterior (Infra Local) | Situação Atual (AWS) | Economia Estimada |
|----------------------------|---------------------------------|----------------------|-------------------|
| Armazenamento de dados     | R$ 25.000/mês (servidores físicos + manutenção) | R$ 7.500/mês (Amazon S3 + Glacier) | ~70% |
| Processamento de rotinas   | R$ 15.000/mês (servidores dedicados) | R$ 4.000/mês (AWS Lambda sob demanda) | ~73% |
| Banco de dados             | R$ 22.500/mês (licenciamento + hardware + manutenção) | R$ 10.000/mês (Amazon RDS gerenciado) | ~55% |
| **Total**                  | **R$ 62.500/mês** | **R$ 21.500/mês** | **~66% de redução** |



##  Gráfico Comparativo de Custo

![Gráfico Comparativo de Custo](https://github.com/robsonosbor/relatorios-implementacao-cloud-aws-azure-gcp/blob/main/graficos/grafico-comparativo-custos-aws.png)



## Conclusão
A implementação dos serviços **Amazon S3, AWS Lambda e Amazon RDS** trouxe benefícios imediatos para a Abstergo Industries, incluindo:  
- Redução significativa de custos com infraestrutura.  
- Maior eficiência operacional e escalabilidade.  
- Diminuição de riscos relacionados à manutenção de sistemas locais.  

Recomenda-se a continuidade da utilização desses serviços e a avaliação de novas soluções AWS que possam ampliar ainda mais a eficiência e a produtividade da empresa.



## Anexos
- Manuais de configuração dos serviços.  
- Planilhas comparativas de custos antes e depois da implementação.  
- Documentação técnica de integração.



**Assinatura do Responsável pelo Projeto:**  

Robson Alves Batista

