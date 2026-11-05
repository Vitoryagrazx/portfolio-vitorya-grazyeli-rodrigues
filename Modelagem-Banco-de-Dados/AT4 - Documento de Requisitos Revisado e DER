
# 🗃️ AT4 - Documento de Requisitos Revisado e DER

## 📝 Descrição do Projeto

Esta atividade foi desenvolvida na disciplina de **Modelagem de Banco de Dados**, do curso de **Análise e Desenvolvimento de Sistemas (ADS)** da Universidade Cidade de São Paulo (UNICID), no 2º semestre de 2026.

O projeto consiste na revisão técnica do Documento de Especificação de Requisitos e Regras de Negócio do **Sistema de Gerenciamento para Salão de Beleza**, destinado à empresa Fátima Aparecida de Lima Cabeleireira.

A atividade dá continuidade às etapas anteriores, aprofundando a definição de requisitos, regras operacionais, restrições de integridade e relacionamentos entre as entidades de dados.

### 🏢 Informações do Projeto

- **Empresa:** Fátima Aparecida de Lima Cabeleireira
- **Projeto:** Sistema de Gerenciamento para Salão de Beleza
- **Equipe:** Grupo 2
- **Disciplina:** Modelagem de Banco de Dados
- **SGBD previsto:** MySQL 8.0
- **Documento:** Versão 2.0 - Revisão Técnica Final
- **Ano:** 2026

---

## 🎯 Objetivo da Atividade

Revisar e aprimorar a documentação de requisitos desenvolvida anteriormente, estabelecendo uma base mais detalhada para a modelagem conceitual, lógica e física do banco de dados.

A proposta busca garantir que as informações do sistema sejam organizadas de maneira consistente, evitando redundâncias e permitindo relacionamentos adequados entre as entidades.

---

## 📋 Revisão dos Requisitos

### 1. Requisitos Funcionais (RF)

O documento apresenta **16 requisitos funcionais**, especificando as operações previstas para o sistema.

Entre as principais funcionalidades estão:

- Cadastro de clientes e fichas capilares.
- Gerenciamento de profissionais e perfis de acesso.
- Cadastro de serviços e associação de insumos.
- Controle de agendamentos e prevenção de conflitos.
- Registro e histórico de atendimentos.
- Gerenciamento de pagamentos e fechamento de caixa.
- Controle financeiro e relatórios analíticos.
- Aplicação de integridade referencial.
- Histórico de preços dos serviços.
- Registro de despesas operacionais.

### 2. Requisitos Não Funcionais (RNF)

Foram especificados **8 requisitos não funcionais**, relacionados aos critérios de qualidade e funcionamento esperado:

- Segurança e controle de acesso.
- Privacidade e proteção de dados conforme a LGPD.
- Integridade transacional.
- Desempenho e tempo de resposta.
- Usabilidade e acessibilidade.
- Disponibilidade, backup e recuperação.
- Auditoria de operações críticas.
- Controle de concorrência e isolamento transacional.

### 3. Regras de Negócio (RN)

Foram documentadas **13 regras de negócio**, com mecanismos previstos para implementação no banco de dados.

Entre elas:

- Impedir agendamentos conflitantes.
- Garantir horários válidos.
- Exigir duração positiva dos serviços.
- Vincular agendamentos a clientes cadastradas.
- Preservar o histórico de cancelamentos.
- Impedir estoque negativo.
- Registrar a baixa e o estorno de insumos.
- Validar pagamentos.
- Preservar preços históricos.
- Categorizar despesas.
- Consolidar informações financeiras.
- Controlar perfis de acesso.
- Impedir operações com entidades inativas.

### 4. Políticas e Restrições (PR)

O documento apresenta **6 políticas e restrições**, relacionadas à segurança, proteção de dados e consistência das informações.

Foram abordados:

- LGPD e tratamento de dados pessoais.
- Controle de acesso por perfis.
- Integridade relacional.
- Preservação de históricos.
- Backup e continuidade do negócio.
- Validação e consistência de dados.

---

## 🗄 Modelagem do Banco de Dados

### Entidades Identificadas

A revisão da modelagem apresenta **15 entidades**, organizadas para representar as informações operacionais e financeiras do salão.

| Entidade | Finalidade |
| :--- | :--- |
| `cliente` | Armazena dados cadastrais das clientes. |
| `ficha_capilar` | Registra informações e avaliações capilares. |
| `detalhe_ficha_quimica` | Organiza o histórico de procedimentos químicos. |
| `servico` | Armazena os serviços oferecidos. |
| `historico_preco_servico` | Registra alterações nos preços dos serviços. |
| `produto` | Controla produtos e insumos. |
| `servico_insumo` | Relaciona serviços aos produtos utilizados. |
| `agendamento` | Registra horários e reservas. |
| `atendimento` | Registra os serviços realizados. |
| `pagamento` | Armazena as transações de pagamento. |
| `categoria_despesa` | Classifica as despesas operacionais. |
| `despesa` | Registra os gastos do estabelecimento. |
| `perfil_acesso` | Define os perfis de acesso. |
| `usuario` | Armazena os operadores do sistema. |
| `log_auditoria` | Registra alterações em operações críticas. |

### 🔗 Relacionamentos Entre Entidades

A modelagem contempla diferentes tipos de relacionamentos:

- **1:N:** Uma cliente pode possuir vários agendamentos.
- **1:N:** Um serviço pode estar associado a vários agendamentos.
- **1:1:** Um agendamento pode estar associado a um atendimento.
- **1:N:** Um atendimento pode possuir vários pagamentos.
- **N:N:** Serviços e produtos são relacionados pela tabela `servico_insumo`.
- **1:N:** Uma categoria de despesa pode estar associada a várias despesas.

### 📐 Normalização

A documentação descreve a aplicação das seguintes formas normais:

- **1FN:** Organização dos atributos em valores atômicos.
- **2FN:** Eliminação de dependências parciais.
- **3FN:** Eliminação de dependências transitivas.

A normalização busca reduzir redundâncias e garantir maior consistência das informações armazenadas.

### 🔐 Restrições de Integridade

Foram especificados mecanismos de proteção e consistência dos dados:

- Chaves primárias (PRIMARY KEY).
- Chaves estrangeiras (FOREIGN KEY).
- Restrições CHECK.
- Restrições UNIQUE e NOT NULL.
- Controle de valores válidos.
- Preservação dos históricos.
- Regras de relacionamento entre as tabelas.

---

## 🚀 Tecnologias Utilizadas

- **SGBD definido:** MySQL 8.0.
- **Motor de armazenamento previsto:** InnoDB.
- **Codificação prevista:** utf8mb4.
- **Modelagem:** Banco de dados relacional.
- **Conceitos:** DER, normalização, integridade referencial e regras de negócio.
- **Linguagem prevista para implementação:** SQL.

Nesta etapa, o foco foi a revisão técnica e a especificação da estrutura de dados, preparando a documentação para as próximas atividades.

---

## 📊 Resultados e Aprendizados

### Principais Resultados

- Revisão da especificação de requisitos do sistema.
- Detalhamento de 16 requisitos funcionais.
- Definição de 8 requisitos não funcionais.
- Documentação de 13 regras de negócio.
- Mapeamento de 6 políticas e restrições.
- Especificação de 15 entidades de dados.
- Descrição dos relacionamentos entre entidades.
- Formalização das restrições de integridade.
- Organização da matriz de rastreabilidade.

### Aprendizados

A atividade permitiu aprofundar os conhecimentos relacionados à engenharia de requisitos e à estruturação de bancos de dados relacionais.

Entre os principais conceitos trabalhados estão:

- Importância da revisão técnica de requisitos.
- Identificação de entidades e atributos.
- Definição de cardinalidades.
- Aplicação das formas normais.
- Utilização de chaves primárias e estrangeiras.
- Preservação da integridade e segurança dos dados.
- Relação entre requisitos de negócio e estruturas do banco de dados.

---

## 🧠 Declaração de Uso Ético da IA

Este README foi elaborado com o apoio do **ChatGPT (OpenAI)**, a partir do documento acadêmico de especificação de requisitos e regras de negócio.

A ferramenta auxiliou na organização, síntese e apresentação do conteúdo para o portfólio acadêmico no GitHub.

Esta declaração refere-se à elaboração do README e não substitui a declaração das ferramentas utilizadas na produção do documento original pela equipe.

---

## 💻 Deploy do Projeto

Não se aplica nesta etapa, pois a atividade consiste na revisão dos requisitos e na especificação da modelagem de banco de dados, sem publicação de uma aplicação funcional.

---

## 📂 Documentação

**Documento:** Especificação de Requisitos e Regras de Negócio - Sistema de Gerenciamento para Salão de Beleza.

**Versão:** 2.0 - Revisão Técnica Final.

O documento apresenta as entidades, atributos, relacionamentos, regras e restrições que servirão de referência para a implementação do banco de dados.

O diagrama gráfico do DER deverá ser disponibilizado separadamente, caso faça parte dos arquivos finais do projeto.

---

[⬅ Voltar ao Portfólio Principal](../../README.md)
