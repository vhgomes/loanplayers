## 📌 Visão Geral
Este projeto consiste em uma API cujo objetivo é mapear e analisar jogadores emprestados entre os clubes do Brasileirão Série A. (API PARA CONSULTA! https://www.api-football.com/)
A ideia surgiu a partir da necessidade de acompanhar jogadores formados na base do **Palmeiras** que estão atualmente emprestados a outros clubes, permitindo entender **onde estão jogando**, **se continuam emprestados** e **como estão performando**.
Embora o foco inicial seja em um único clube, a API é pensada para evoluir e abranger **todos os times da Série A**, oferecendo uma visão centralizada sobre empréstimos no futebol brasileiro.

## 🎯 Objetivo do Projeto
- Centralizar informações sobre jogadores emprestados
- Facilitar a análise de atletas da base que estão ganhando rodagem em outros clubes
- Criar uma base sólida para futuras análises esportivas e comparações de desempenho

## 🚀 Funcionalidades Iniciais

Na primeira fase, o projeto será focado em **um único time**:
- 📋 Listar todos os jogadores atualmente vinculados ao clube
- 🔄 Identificar se o jogador está emprestado ou atuando pelo próprio time
- 📊 Consultar estatísticas individuais do jogador enquanto está emprestado
## 🔮 Possíveis Evoluções

- Suporte a todos os clubes do Brasileirão Série A
- Comparação de desempenho entre jogadores emprestados e jogadores do elenco principal
- Histórico de empréstimos por jogador
- Dashboards e visualizações de dados

## 🔍 Processo de Consulta dos Dados

A coleta de informações será realizada utilizando a **API-Football**, que fornece dados atualizados sobre clubes, jogadores, transferências e estatísticas do futebol mundial.
Neste primeiro momento, o escopo do projeto estará limitado ao **Palmeiras**, utilizando diretamente o **ID do clube** para realizar as consultas necessárias.

### 🔄 Fluxo de Consulta
O processo seguirá os seguintes passos:
1. 🏟️ **Selecionar o time**
    - Consulta direta ao Palmeiras a partir do seu identificador na API.
2. 👥 **Listar jogadores vinculados ao clube**
    - Obter todos os jogadores atualmente associados ao time.
3. 🆔 **Identificar o jogador**
    - Extrair o ID individual de cada jogador retornado.
4. 🔁 **Consultar histórico de transferências**
    - Verificar se o jogador possui registros de empréstimo ou transferência.
5. 🏷️ **Analisar o tipo de transferência**
    - Identificar se a movimentação é do tipo _empréstimo_.
6. ⚽ **Determinar o clube de destino**
    - Exibir para qual time o jogador foi emprestado.

Esse fluxo permite mapear com precisão **quais jogadores estão emprestados**, **para quais clubes** e cria a base para futuras análises de desempenho.