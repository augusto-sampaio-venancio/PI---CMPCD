#  Documentação do PI - CMPCD Jaú

Esta documentação descreve o andamento do PI (Projeto Integrador) da faculdade, abordando as etapas realizadas e a evolução do projeto focado no desenvolvimento do sistema para o **CMPCD Jaú**.

## Sumário

<details>
  <summary><strong>Expandir Sumário</strong></summary>

- [1. Introdução](#1-introdução)
  - [Objetivos](#objetivos)
  - [Metodologia](#metodologia)
- [2. Requisitos](#2-requisitos)
  - [Requisitos funcionais](#requisitos-funcionais)
  - [Requisitos não funcionais](#requisitos-não-funcionais)
- [3. Estudo de viabilidade](#3-estudo-de-viabilidade)
- [4. Regras de negócio (Modelo Canvas)](#4-regras-de-negócio-modelo-canvas)
- [5. Design](#5-design)
- [6. Protótipo](#6-protótipo)
- [7. Aplicação](#7-aplicação)

</details>

---

## 1. Introdução

### Contextualização & Justificativa

O **CMPCD Jaú (Conselho Municipal de Pessoas com Deficiência)** é um órgão colegiado de caráter consultivo, deliberativo e fiscalizador, que atua na formulação e fiscalização de políticas públicas voltadas à inclusão. Jaú possui hoje cerca de **7.135 pessoas com deficiência**, e o conselho necessita de uma ferramenta digital que centralize informações e promova a transparência. A motivação deste projeto é criar uma ponte entre os conselheiros, as entidades (AMAE, APAE, CISC) e a Secretaria de Assistência Social, garantindo que os dados demográficos auxiliem na gestão pública eficiente e na valorização dos direitos da pessoa com deficiência.

---

### • Objetivos

##### - Objetivo principal
Desenvolver um site institucional para o **CMPCD Jaú**, integrado à Secretaria de Assistência e Desenvolvimento Social, que possibilite o cadastro e gerenciamento de informações de pessoas com deficiência (PCDs), funcionando como um banco de dados confiável para o planejamento de serviços de inclusão social.

##### - Objetivos específicos
1. Criar um portal informativo com a história do conselho, missão, valores, **organograma** e **galeria de presidentes**.
2. Desenvolver um sistema de cadastro online para PCDs com upload obrigatório de documentos (**RG, Comprovante de Residência e Laudo Médico**).
3. Implementar um **Espaço de Transparência** para divulgação de atas, reuniões, resoluções e contatos dos conselheiros.
4. Facilitar a importação de dados externos provenientes de fichas e planilhas de entidades parceiras (AMAE, APAE, CISC).
5. Garantir acessibilidade digital plena (contraste, fontes ampliadas e suporte a leitores de tela).

---

### • Metodologia

O desenvolvimento é estruturado através das seguintes abordagens:

- **Métodos utilizados:** Metodologia Ágil (Scrum/Kanban) para entregas incrementais.
- **Tecnologias e ferramentas:** HTML5, CSS3 (Bootstrap), JavaScript (ES6+), MySQL para o banco de dados e Figma para design UX/UI.
- **Processos:** Versionamento de código via Git/GitHub e documentação técnica contínua.

---

## 2. Requisitos

### • Requisitos Funcionais

| ID | Requisito | Descrição |
| :--- | :--- | :--- |
| **RF01** | **Institucional e Memória** | Exibir história do conselho, galeria de presidentes, organograma e aba para história dos conselheiros. |
| **RF02** | **Dados Sociais** | Divulgar estatísticas sobre a população PCD de Jaú para conscientização pública. |
| **RF03** | **Canais de Contato** | Formulário de contato, telefones, e-mails e endereços oficiais do conselho. |
| **RF04** | **Espaço para Transparência** | Área dedicada para download de atas, documentos oficiais e resoluções do conselho. |
| **RF05** | **Notícias e Redes Sociais** | Publicação de novidades e integração com feed das redes sociais institucionais. |
| **RF06** | **Cadastro Assistencial** | Formulário com upload de 3 arquivos (RG, Residência e Laudo) direcionado à Assistência Social. |
| **RF07** | **Login de Usuários** | Sistema de autenticação com diferentes níveis de acesso para usuários e administradores. |
| **RF08** | **Painel Administrativo** | Gestão de conteúdos, edição de conselheiros e importação de dados via Excel/Fichas. |

### • Requisitos Não Funcionais

- **Desempenho:** Carregamento Rápido das paginas.
- **Responsividade:** Layout adaptável (Mobile-First) para desktop, tablet e celular.
- **Acessibilidade:** Seguir diretrizes WCAG (contraste, textos alternativos e suporte a leitores de tela).
- **Segurança (LGPD):** Criptografia e acesso restrito aos documentos sensíveis anexados.
- **Interoperabilidade:** Exportação e importação de dados em formatos CSV ou JSON.

---

## 3. Estudo de Viabilidade

- **Viabilidade Técnica:** Uso de tecnologias web padrão e banco de dados relacional (MySQL).
- **Viabilidade Financeira:** Integração com infraestrutura municipal ou hospedagem de baixo custo.
- **Viabilidade Operacional:** Interface simplificada para operação pelos coordenadores da Secretaria de Assistência Social.

---

## 4. 💼 Regras de Negócio (Modelo Canvas)

- **Proposta de Valor:** Centralizar o censo PCD e as ações do conselho em uma plataforma transparente.
- **Segmentos:** Conselheiros do CMPCD, Pessoas PCDs de Jaú e Gestão Pública.
- **Parcerias Chave:** Prefeitura municipal e entidades parceiras (AMAE, APAE, CISC).

---

## 5. Design

### Paleta de Cores
- Azul Primário: #2D9CDB
- Azul Suave: #56CCF2
- Bege Claro: #F9F7F1
- Cinza Suave: #E0E0E0
- Preto Suave: #333333

### Fontes Utilizadas
- **Títulos e Textos:** "Nunito", Arial, Helvetica, sans-serif.

---

## 6. Protótipo

- [Acesse o protótipo no Figma]

---

## 7. Aplicação

A aplicação está em fase de estruturação do banco de dados e front-end.

- **Tecnologias:** HTML5, CSS3, JavaScript e MySQL.
- **Execução local:** 1. Clone o repositório.
  2. Abra o arquivo `index.html` no navegador.
