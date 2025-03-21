# Desafio da Lista de Convidados VIP

## Introdução
O desafio proposto consiste na criação de um sistema para gerenciar a lista de convidados de uma festa de aniversário exclusiva. Mais do que uma simples implementação técnica de uma estrutura de dados, esse desafio exige raciocínio lógico e aplicação prática dos conceitos de organização e seleção de participantes. A solução deve equilibrar eficiência, organização e personalização, considerando os requisitos específicos do problema.

## Objetivo
O problema central envolve a otimização da seleção e alocação de 100 convidados, escolhidos entre 1000 potenciais participantes. Essa seleção é baseada em critérios específicos, como:
- **Proximidade com o aniversariante** (medida pelo "score de amizade");
- **Preferências individuais** (bebidas e cardápio);
- **Organização estratégica das mesas** (considerando categorias, idades e scores);
- **Disponibilidade para transporte VIP**.

## Dados da Resolução
Para resolver o problema consideramos as seguintes etapas:

### 1. Identificação dos Participantes
Os 1000 convidados potenciais são analisados de acordo com os seguintes critérios:
- **Score de amizade**: mede o grau de proximidade com o aniversariante;
- **Faixa etária**: garante um equilíbrio na distribuição de idades;
- **Preferências pessoais**: assegura que as preferências de bebidas e cardápio sejam atendidas;
- **Localização**: define a logística de transporte para convidados VIP.

### 2. Seleção dos Convidados VIP
A escolha dos 100 convidados é feita priorizando:
- **Os 100 maiores scores de amizade**;
- **Distribuição justa entre diferentes faixas etárias e categorias**;
- **Atendimento às preferências alimentares e de bebida**;
- **Viabilidade de transporte, quando necessário**.

### 3. Organização das Mesas
A disposição dos convidados é feita considerando:
- **Capacidade das mesas** (4 pessoas por mesa);
- **Agrupamento por afinidade e score de amizade**;
- **Faixas etárias semelhantes** (evitando grandes disparidades);
- **Distribuição equilibrada entre categorias e interesses**.

### 4. Planejamento do Transporte VIP
Para os convidados elegíveis ao transporte em limousine, consideramos:
- **Distância entre a residência e o local da festa**;
- **Priorização dos convidados com maior score de amizade**;
- **Otimização das rotas para melhor aproveitamento do transporte**.

## Considerações Finais
A solução ideal deve equilibrar eficiência, personalização e logística, garantindo que:
- Os convidados mais próximos do aniversariante sejam priorizados;
- A experiência da festa seja harmoniosa e personalizada;
- A logística de acomodação e transporte seja otimizada.

