
# 📚 AT2 - Levantamento de Requisitos e Regras de Negócio

## 📝 Descrição do Projeto

Esta atividade foi desenvolvida na disciplina de **Modelagem de Banco de Dados**, do curso de **Análise e Desenvolvimento de Sistemas (ADS)** da Universidade Cidade de São Paulo (UNICID), no 2º semestre de 2026.

O projeto consiste na especificação dos requisitos e regras de negócio de um **Sistema de Gerenciamento para Salão de Beleza**, destinado à empresa Fátima Aparecida de Lima Cabeleireira.

A proposta busca organizar e centralizar informações relacionadas ao funcionamento do salão, contribuindo para melhorar o controle dos agendamentos, atendimentos, estoque, pagamentos e despesas.

### 🏢 Informações do Projeto

- **Empresa:** Fátima Aparecida de Lima Cabeleireira
- **Projeto:** Sistema de Gerenciamento para Salão de Beleza
- **Equipe:** Grupo 2
- **Disciplina:** Modelagem de Banco de Dados
- **SGBD previsto:** MySQL
- **Ano:** 2026

### 🎯 Objetivo da Atividade

Identificar e documentar os requisitos necessários para o desenvolvimento de um sistema de gerenciamento que atenda às necessidades operacionais do salão.

A atividade dá continuidade ao levantamento realizado na AT1, transformando os problemas identificados em requisitos, regras de negócio e diretrizes para a futura modelagem do banco de dados.

---

## 📋 Levantamento de Requisitos

### 1. Requisitos Funcionais (RF)

Foram especificados 16 requisitos funcionais, relacionados às operações que o sistema deverá realizar.

Entre as funcionalidades previstas estão:

- Cadastro e gerenciamento de clientes e fichas capilares.
- Cadastro de serviços e insumos.
- Gerenciamento de agendamentos.
- Prevenção de conflitos de horários.
- Registro de atendimentos realizados.
- Consulta ao histórico de serviços das clientes.
- Registro de pagamentos e fechamento de caixa.
- Controle de despesas operacionais.
- Geração de relatórios financeiros.
- Controle de acesso e integridade dos registros.

### 2. Requisitos Não Funcionais (RNF)

Foram definidos seis requisitos não funcionais, relacionados à qualidade e ao funcionamento esperado do sistema:

- **Segurança:** Controle de acesso às informações.
- **Privacidade:** Proteção dos dados pessoais conforme a LGPD.
- **Integridade:** Consistência dos dados e relacionamentos.
- **Desempenho:** Agilidade nas consultas e operações.
- **Usabilidade:** Interface simples e organizada.
- **Disponibilidade e recuperação:** Procedimentos de backup e restauração.

### 3. Regras de Negócio (RN)

O documento apresenta 12 regras de negócio que orientam o funcionamento do sistema.

Entre as principais regras estão:

- Impedir agendamentos conflitantes.
- Garantir horários válidos.
- Registrar a duração estimada dos serviços.
- Associar agendamentos às clientes cadastradas.
- Preservar o histórico de agendamentos cancelados.
- Impedir quantidades negativas no estoque.
- Registrar o consumo de produtos.
- Validar os valores dos pagamentos.
- Preservar o histórico dos preços cobrados.
- Registrar despesas operacionais.
- Permitir consultas financeiras por período.
- Garantir a integridade dos relacionamentos.

### 4. Políticas e Restrições (PR)

Foram mapeadas seis políticas e restrições relacionadas à proteção e à consistência das informações:

- Proteção de dados pessoais conforme a LGPD.
- Controle de acesso às funcionalidades.
- Integridade dos registros do banco de dados.
- Preservação dos históricos.
- Backup e recuperação das informações.
- Validação dos dados cadastrados.

---

## 🗄 Entidades de Dados Identificadas

A partir dos requisitos, foram propostas entidades preliminares para a futura modelagem do banco de dados:

- **Cliente:** Informações cadastrais e de contato.
- **Ficha Capilar:** Histórico e características dos cabelos.
- **Serviço:** Procedimentos oferecidos pelo salão.
- **Agendamento:** Datas, horários e serviços marcados.
- **Atendimento:** Registro dos serviços realizados.
- **Pagamento:** Valores e formas de pagamento.
- **Produto/Insumo:** Materiais utilizados e controle de estoque.
- **Despesa:** Gastos operacionais do salão.

Essas entidades serão utilizadas como referência para a elaboração do Diagrama Entidade-Relacionamento (DER) e do modelo lógico relacional, após as revisões necessárias.

---

## 🚀 Tecnologias Utilizadas

- **SGBD previsto:** MySQL.
- **Documentação:** Especificação de requisitos e regras de negócio.
- **Técnicas:** Levantamento de requisitos, análise de processos e identificação de entidades.
- **Modelagem:** Conceitos de banco de dados relacional, chaves primárias, chaves estrangeiras e integridade referencial.

Nesta etapa, o foco foi a documentação e a definição dos requisitos, sem implementação do sistema.

---

## 📊 Resultados e Aprendizados

A atividade permitiu aprofundar a compreensão das necessidades de uma empresa real e estruturar uma proposta de sistema de gerenciamento.

### Principais Resultados

- Elaboração do documento de especificação de requisitos.
- Identificação de 16 requisitos funcionais.
- Definição de 6 requisitos não funcionais.
- Especificação de 12 regras de negócio.
- Mapeamento de 6 políticas e restrições.
- Identificação de entidades preliminares.
- Elaboração inicial da matriz de rastreabilidade.

### Aprendizados

Durante a atividade, foram trabalhados conceitos importantes para o desenvolvimento de sistemas:

- Diferença entre requisitos funcionais e não funcionais.
- Importância das regras de negócio.
- Organização de dados para sistemas relacionais.
- Definição de restrições de integridade.
- Importância da segurança e da proteção de dados.
- Relação entre requisitos e modelagem de banco de dados.

A atividade demonstrou como uma documentação bem estruturada pode orientar as próximas etapas de desenvolvimento de um sistema.

---

## 🧠 Declaração de Uso Ético da IA

Este README foi estruturado com o apoio do **ChatGPT (OpenAI)**, utilizando como referência o documento acadêmico elaborado para a atividade.

A ferramenta auxiliou na organização, síntese e apresentação das informações para o portfólio do GitHub.

Esta declaração refere-se à elaboração do README, não substituindo o registro das ferramentas efetivamente utilizadas na produção do documento original pela equipe.

---

## 💻 Deploy do Projeto

Não se aplica nesta etapa, pois a atividade consiste no levantamento e na especificação de requisitos, sem desenvolvimento de uma aplicação para publicação.

---

## 📂 Documentação

A documentação completa da atividade contém a especificação dos requisitos funcionais e não funcionais, regras de negócio, políticas, entidades preliminares e matriz de rastreabilidade.

**Documento:** Especificação de Requisitos e Regras de Negócio - Sistema de Gerenciamento para Salão de Beleza.

---

[⬅ Voltar ao Portfólio Principal](../../README.md)
