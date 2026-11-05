
# 🎤 AT3 - Apresentação Coletiva Pitch

## 📝 Descrição do Projeto

Esta atividade foi desenvolvida na disciplina de **Modelagem de Banco de Dados**, do curso de **Análise e Desenvolvimento de Sistemas (ADS)** da Universidade Cidade de São Paulo (UNICID), no 2º semestre de 2026.

A atividade consistiu na elaboração de um **Pitch Coletivo**, com o objetivo de apresentar e defender a proposta de um Sistema de Gerenciamento para Salão de Beleza.

A apresentação abordou os principais requisitos do sistema, as regras de negócio, as políticas de segurança e a estrutura conceitual do banco de dados.

### 🏢 Informações do Projeto

- **Empresa:** Fátima Aparecida de Lima Cabeleireira
- **Projeto:** Sistema de Gerenciamento para Salão de Beleza
- **Equipe:** Grupo 2
- **SGBD previsto:** MySQL
- **Formato:** Apresentação coletiva (Pitch)
- **Duração prevista:** 4 minutos
- **Ano:** 2026

---

## 🎯 Objetivo da Apresentação

Apresentar de maneira clara e objetiva a solução tecnológica proposta para os problemas operacionais identificados no salão de beleza.

O Pitch teve como foco demonstrar como um banco de dados relacional poderá contribuir para organizar as informações da empresa, melhorar os processos internos e garantir maior integridade e segurança aos registros.

---

## 📋 Conteúdos Apresentados

### 1. Escopo do Sistema

Foram apresentados os principais módulos previstos para o sistema:

- Cadastro de clientes e fichas capilares.
- Gerenciamento de serviços.
- Organização da agenda de atendimentos.
- Prevenção de conflitos de horários.
- Controle de produtos e estoque.
- Registro de pagamentos e despesas.

Também foram discutidas funcionalidades fora do escopo inicial, como integração automática com WhatsApp, folha de pagamento, contabilidade completa e emissão de documentos fiscais eletrônicos.

### 2. Requisitos Funcionais (RF)

A apresentação destacou funcionalidades essenciais para o funcionamento do sistema:

- **RF04:** Gerenciamento de agendamentos.
- **RF06:** Prevenção de conflitos de horários.
- **RF08:** Registro dos atendimentos realizados.
- **RF10:** Gestão de pagamentos.
- **RF13:** Gestão de perfis de acesso, como possibilidade sujeita à revisão.

O objetivo é permitir uma administração mais organizada e centralizada das operações do salão.

### 3. Requisitos Não Funcionais (RNF)

Foram apresentados critérios de qualidade e desempenho esperados para o sistema:

- **Desempenho:** Operações comuns concluídas em até 3 segundos em pelo menos 95% dos testes.
- **Usabilidade:** Pelo menos 90% das tarefas propostas concluídas sem ajuda.
- **Integridade:** Rejeição de operações que violem as restrições definidas.
- **Segurança:** Acesso restrito a usuários autorizados.
- **Privacidade:** Proteção dos dados conforme a LGPD.
- **Recuperação:** Previsão de procedimentos de backup e restauração.

Esses critérios representam requisitos propostos, e não resultados de testes de uma aplicação implementada.

### 4. Regras de Negócio (RN)

Foram destacadas regras fundamentais para manter a consistência das operações:

- **RN01:** Impedir agendamentos ativos conflitantes para o mesmo profissional.
- **RN06:** Impedir que a quantidade disponível de produtos fique negativa.
- **RN09:** Preservar o valor cobrado em atendimentos anteriores, mesmo após alterações de preços.

A apresentação também abordou mecanismos de banco de dados previstos para apoiar essas regras, como validações, restrições CHECK e gatilhos (TRIGGER).

### 5. Políticas e Restrições (PR)

Foram discutidos aspectos relacionados à conformidade e à proteção das informações:

- Proteção de dados pessoais conforme a LGPD.
- Controle de acesso às informações.
- Preservação de históricos.
- Procedimentos de backup e recuperação.
- Integridade referencial.
- Validação de dados registrados.

### 6. Entidades de Dados

A apresentação abordou entidades previstas para a modelagem conceitual:

- Cliente
- Ficha Capilar
- Serviço
- Produto/Insumo
- Agendamento
- Atendimento
- Pagamento
- Despesa

Também foram discutidas as relações entre essas entidades e a importância da organização dos dados.

### 7. Integridade e Modelagem

Foram apresentados conceitos essenciais para a futura estruturação do banco de dados:

- Chaves primárias (PK).
- Chaves estrangeiras (FK).
- Integridade referencial.
- Restrições de domínio.
- Preservação de históricos.
- Normalização até a Terceira Forma Normal (3FN).

---

## 🚀 Tecnologias Utilizadas

- **Banco de dados previsto:** MySQL.
- **Ferramenta de apresentação:** Google Slides.
- **Conceitos aplicados:** Engenharia de Requisitos, Modelagem de Banco de Dados e Integridade Referencial.
- **Formato de entrega:** Apresentação coletiva.

Nesta etapa, o foco foi a comunicação e a defesa técnica da solução proposta, sem implementação de um sistema funcional.

---

## 📊 Resultados e Aprendizados

### Principais Resultados

- Organização dos requisitos em uma apresentação coletiva.
- Delimitação do escopo inicial do sistema.
- Apresentação dos principais requisitos funcionais e não funcionais.
- Discussão das regras de negócio e políticas de segurança.
- Identificação das entidades fundamentais para a modelagem.
- Exposição das diretrizes de integridade e normalização.

### Aprendizados

A atividade contribuiu para o desenvolvimento de habilidades técnicas e socioemocionais, especialmente:

- Comunicação de conceitos técnicos.
- Trabalho em equipe.
- Organização de informações.
- Pensamento crítico.
- Argumentação e apresentação de soluções.
- Compreensão da importância da integridade dos dados.

O Pitch demonstrou a importância de apresentar não apenas as funcionalidades de um sistema, mas também suas regras, limitações e critérios de qualidade.

---

## 🧠 Declaração de Uso Ético da IA

Este README foi elaborado com o apoio do **ChatGPT (OpenAI)**, a partir dos materiais da apresentação coletiva.

A ferramenta foi utilizada para auxiliar na organização, síntese e documentação do conteúdo acadêmico para o portfólio do GitHub.

Esta declaração refere-se à elaboração do README e não substitui a declaração das ferramentas efetivamente utilizadas na produção dos slides pela equipe.

---

## 💻 Deploy do Projeto

Não se aplica nesta etapa, pois a atividade consistiu na apresentação coletiva de uma proposta de sistema, sem desenvolvimento de uma aplicação para publicação.

---

## 📂 Documentação

**Material:** Apresentação Coletiva Pitch - Grupo 2.

A apresentação reúne os principais requisitos, regras de negócio, políticas, entidades de dados e aspectos de integridade previstos para o sistema de gerenciamento do salão de beleza.

---

[⬅ Voltar ao Portfólio Principal](../../README.md)
