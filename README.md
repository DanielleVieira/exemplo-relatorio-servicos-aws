# RELATÓRIO DE IMPLEMENTAÇÃO DE SERVIÇOS AWS

**Data:** 09 de março de 2026  
**Empresa:** Abstergo Industries  
**Responsável:** Danielle Vieira  

---

## Introdução
Este relatório apresenta o processo de implementação de ferramentas de computação em nuvem na empresa **Abstergo Industries**, realizado por **Danielle Vieira**. O objetivo do projeto foi identificar e implementar **três serviços da Amazon Web Services (AWS)** com a finalidade de **reduzir custos operacionais imediatos**, melhorar a eficiência da infraestrutura tecnológica e permitir maior escalabilidade das operações da empresa.

Atualmente, a empresa não utiliza soluções em nuvem, mantendo sua infraestrutura local (on-premises), o que gera custos elevados com manutenção de servidores físicos, energia elétrica, equipe técnica e atualizações de hardware. A adoção de serviços da AWS permitirá a migração gradual desses sistemas para a nuvem, reduzindo custos e aumentando a flexibilidade operacional.

---

## Descrição do Projeto
O projeto de implementação de ferramentas foi dividido em **3 etapas**, cada uma com objetivos específicos voltados à **redução de custos operacionais e melhoria da gestão de dados e aplicações**.

---

### Etapa 1
- **Nome da ferramenta:** Amazon EC2 (Elastic Compute Cloud)  
- **Foco da ferramenta:** Hospedagem de servidores e aplicações em nuvem substituindo servidores físicos.  
- **Descrição de caso de uso:**  

A empresa atualmente mantém servidores físicos próprios para hospedar sistemas internos, banco de dados e aplicações utilizadas para gestão de vendas e distribuição de medicamentos. Esses servidores exigem investimento constante em hardware, manutenção, energia elétrica e refrigeração.

Com a implementação do **Amazon EC2**, esses servidores podem ser migrados para máquinas virtuais na nuvem. Dessa forma, a empresa paga apenas pelos recursos computacionais utilizados.

**Principais ganhos:**
- Eliminação da necessidade de compra e manutenção de servidores físicos.
- Redução de gastos com energia e infraestrutura de data center.
- Possibilidade de aumentar ou reduzir recursos conforme a demanda (escalabilidade).
- Alta disponibilidade e confiabilidade da infraestrutura.

---

### Etapa 2
- **Nome da ferramenta:** Amazon S3 (Simple Storage Service)  
- **Foco da ferramenta:** Armazenamento seguro e escalável de arquivos e dados empresariais.  
- **Descrição de caso de uso:**  

A empresa precisa armazenar diversos tipos de arquivos, como documentos fiscais, relatórios de vendas, contratos com farmácias e registros de distribuição de medicamentos. Atualmente, esses arquivos são armazenados em servidores locais, o que gera custos de armazenamento e riscos relacionados a perda de dados.

Com o **Amazon S3**, todos esses arquivos podem ser armazenados na nuvem com alta durabilidade e segurança. Além disso, o serviço possui diferentes classes de armazenamento que permitem reduzir custos para arquivos que são acessados com menor frequência.

**Principais ganhos:**
- Redução de custos com armazenamento físico e manutenção de servidores.
- Alta durabilidade dos dados.
- Pagamento apenas pelo espaço utilizado.
- Possibilidade de arquivamento de dados antigos com custo muito baixo.

---

### Etapa 3
- **Nome da ferramenta:** AWS Lambda  
- **Foco da ferramenta:** Execução de processos automatizados sem necessidade de manter servidores ativos.  
- **Descrição de caso de uso:**  

A empresa realiza diversas tarefas automatizadas, como geração de relatórios de vendas, processamento de pedidos e integração de sistemas entre parceiros farmacêuticos. Em um modelo tradicional, essas tarefas exigem servidores funcionando continuamente, mesmo quando não estão sendo utilizados.

Com **AWS Lambda**, essas tarefas podem ser executadas apenas quando necessário, através de funções serverless. Isso elimina a necessidade de manter servidores dedicados para esses processos.

**Principais ganhos:**
- Redução de custos com servidores ociosos.
- Pagamento apenas pelo tempo de execução das funções.
- Maior eficiência na automação de processos internos.
- Escalabilidade automática para lidar com picos de demanda.

---

## Conclusão
A implementação das ferramentas **Amazon EC2, Amazon S3 e AWS Lambda** na empresa **Abstergo Industries** tem como objetivo principal **reduzir custos operacionais relacionados à infraestrutura de TI**, ao mesmo tempo em que melhora a eficiência, segurança e escalabilidade dos sistemas.

Com a adoção dessas soluções em nuvem, espera-se:
- diminuição dos custos com servidores físicos e armazenamento local;
- maior flexibilidade para expansão da infraestrutura;
- aumento da confiabilidade e segurança dos dados;
- melhoria na automação de processos internos.

Recomenda-se a continuidade da utilização das ferramentas implementadas e a avaliação futura de outros serviços da AWS que possam contribuir para a otimização dos processos tecnológicos da empresa.

---

**Assinatura do Responsável pelo Projeto:**  

Danielle Vieira
