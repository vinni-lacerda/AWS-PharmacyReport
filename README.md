# RELATÓRIO DE IMPLEMENTAÇÃO DE SERVIÇOS AWS

**Data:** 15/03/2026  
**Empresa:** Abstergo Industries  
**Responsável:** Vinicius Lacerda  

---

# Introdução

Este relatório apresenta o processo de implementação de serviços de computação em nuvem na empresa **Abstergo Industries**, realizado por **Vinicius Lacerda**. O objetivo do projeto foi selecionar e implementar três serviços da AWS com o propósito de **reduzir custos operacionais em redes de farmácias**, especialmente em áreas como armazenamento de dados, infraestrutura de servidores e gerenciamento de sistemas.

A adoção de soluções em nuvem permite maior escalabilidade, segurança e redução de custos com infraestrutura física, além de facilitar a gestão de sistemas utilizados em farmácias, como controle de estoque, registro de vendas e armazenamento de documentos digitais.

---

# Descrição do Projeto

O projeto de implementação foi dividido em **três etapas**, cada uma utilizando um serviço específico da AWS com foco na otimização de custos e melhoria da eficiência operacional das farmácias.

---

# Etapa 1

**Nome da ferramenta:** Amazon S3  

**Foco da ferramenta:**  
Armazenamento escalável de arquivos e documentos com baixo custo.

**Descrição do caso de uso:**

Farmácias geram uma grande quantidade de documentos digitais, como:

- notas fiscais eletrônicas  
- relatórios de vendas  
- backups de sistemas de gestão  
- registros de movimentação de estoque  

O **Amazon S3** foi implementado como solução de armazenamento para esses arquivos, substituindo servidores locais e discos físicos utilizados anteriormente.

Utilizando classes de armazenamento como **S3 Intelligent-Tiering**, arquivos pouco acessados são automaticamente movidos para camadas de menor custo, reduzindo significativamente os gastos com armazenamento.

---

# Etapa 2

**Nome da ferramenta:** Amazon EC2  

**Foco da ferramenta:**  
Hospedagem de sistemas de gestão utilizados pelas farmácias.

**Descrição do caso de uso:**

O **Amazon EC2** foi implementado para hospedar sistemas utilizados pelas farmácias, como:

- sistemas de controle de estoque  
- sistemas de vendas (PDV)  
- sistemas administrativos  

A utilização de instâncias EC2 permite executar servidores virtuais sob demanda, eliminando a necessidade de manter servidores físicos em cada unidade da farmácia.

Essa abordagem reduz custos com:

- aquisição de hardware  
- manutenção de servidores  
- consumo de energia  
- suporte técnico local  

---

# Etapa 3

**Nome da ferramenta:** Amazon RDS  

**Foco da ferramenta:**  
Gerenciamento automatizado de banco de dados.

**Descrição do caso de uso:**

O **Amazon RDS** foi implementado para gerenciar os bancos de dados utilizados pelos sistemas das farmácias, armazenando informações como:

- cadastro de medicamentos  
- histórico de vendas  
- controle de estoque  
- dados de clientes  

Com o uso do Amazon RDS, a empresa elimina a necessidade de administrar servidores de banco de dados manualmente, pois o serviço oferece recursos automáticos como:

- backups automáticos  
- atualização de software  
- alta disponibilidade  
- monitoramento de desempenho  

Essa solução reduz custos com administração de infraestrutura e melhora a confiabilidade dos dados.

---

# Conclusão

A implementação dos serviços **Amazon S3, Amazon EC2 e Amazon RDS** na empresa **Abstergo Industries** contribui diretamente para a **redução de custos operacionais em farmácias**, além de melhorar a escalabilidade e a segurança dos sistemas utilizados.

Entre os principais benefícios obtidos estão:

- redução de custos com infraestrutura física  
- maior disponibilidade dos sistemas  
- armazenamento seguro e escalável de dados  
- automação do gerenciamento de banco de dados  

A adoção dessas tecnologias permite que a empresa modernize sua infraestrutura de TI e foque em melhorar seus serviços e processos internos. Recomenda-se a continuidade da utilização dos serviços da AWS e a avaliação de novas soluções em nuvem para otimizar ainda mais os processos da empresa.


**Assinatura do Responsável pelo Projeto**

Vinicius Lacerda
