# Sistema de Gestão das Olimpíadas (SGO)

## Descrição do Sistema

O Sistema de Gestão das Olimpíadas (SGO) é uma plataforma desenvolvida para coordenar os diversos aspectos dos Jogos Olímpicos. O sistema abrange o gerenciamento de competições, as inscrições de atletas, a alocação de locais para as provas e o controle de resultados, além de gerar relatórios de medalhas.

Este projeto foi desenvolvido para a disciplina de Projeto de Software do curso de Engenharia de Software da PUC Minas.

### Regras de Negócio

O sistema opera com base nas seguintes regras:

  * **Cadastro de Competições:** Permite o registro de competições, incluindo modalidade, data, horário, local e a lista de atletas inscritos.
  * **Inscrição de Atletas:** Atletas de diferentes nacionalidades podem se inscrever nas competições. Um atleta pode competir em múltiplos eventos, mas só pode representar um único país por modalidade.
  * **Alocação de Locais:** Os locais das competições são alocados buscando evitar conflitos de horário. Um mesmo local não pode sediar mais de uma competição simultaneamente.
  * **Controle de Resultados:** Após cada competição, os resultados são registrados para determinar os três primeiros colocados (ouro, prata e bronze).
  * **Relatórios de Medalhas:** O sistema é capaz de gerar relatórios que exibem o desempenho dos países com base no número de medalhas conquistadas.

## Histórias de Usuário

**US01: Cadastrar Competição**

  * **Eu, como** Administrador,
  * **Quero** poder cadastrar novas competições no sistema, informando a modalidade, data, horário e local,
  * **Para** organizar os eventos das Olimpíadas.

**US02: Inscrever Atleta em Competição**

  * **Eu, como** Atleta,
  * **Quero** poder me inscrever em uma ou mais competições disponíveis,
  * **Para** participar dos jogos.

**US03: Alocar Local para Competição**

  * **Eu, como** Administrador,
  * **Quero** alocar um local disponível para uma competição,
  * **Para** garantir que não haja conflitos de horário e local.

**US04: Registrar Resultados da Competição**

  * **Eu, como** Administrador,
  * **Quero** registrar os resultados de uma competição finalizada, indicando o primeiro, segundo e terceiro lugar,
  * **Para** manter o quadro de medalhas atualizado.

**US05: Atualizar Quadro de Medalhas**

  * **Eu, como** Administrador,
  * **Quero** que o quadro de medalhas seja atualizado automaticamente após o registro de um resultado,
  * **Para** refletir o desempenho dos países em tempo real.

**US06: Gerar Relatório de Medalhas**

  * **Eu, como** um Sistema de Relatórios,
  * **Quero** gerar relatórios de medalhas que mostrem o desempenho de cada país,
  * **Para** fornecer uma visão geral das conquistas.

## Diagramas UML

A seguir são apresentados os diagramas UML que modelam o sistema, conforme solicitado no projeto.

### Diagrama de Caso de Uso

O diagrama de caso de uso modela as principais funcionalidades do sistema e a interação entre os atores.

\<img width="500px" height="500px" src="../Trabalho-SGO/imagens/diagrama-de-cado-de-uso.jpg"/\>

### Diagrama de Classes

Este diagrama reflete a estrutura do sistema, incluindo as principais classes e seus relacionamentos.

\<img width="500px" height="500px" src="../Trabalho-SGO/imagens/diagrama-de-classes.jpg"/\>

### Diagrama de Pacotes

O diagrama de pacotes organiza as classes do sistema em pacotes para separar as diferentes responsabilidades.

\<img width="500px" height="500px" src="../Trabalho-SGO/imagens/diagrama-de-pacotes.jpg"/\>

### Diagrama de Componentes

Modela os componentes principais do sistema e como eles interagem entre si.

\<img width="500px" height="500px" src="../Trabalho-SGO/imagens/diagrama-de-componentes.jpg"/\>

### Diagrama de Implantação

Ilustra a arquitetura física do sistema, mostrando como os componentes serão distribuídos na infraestrutura de TI.

\<img width="500px" height="500px" src="../Trabalho-SGO/imagens/diagrama-de-implantacao.jpg"/\>