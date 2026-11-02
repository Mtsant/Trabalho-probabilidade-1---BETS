# Máquina Estatística: Trabalho I de Probabilidade e Estatística I

IFES, Campus Serra. Bacharelado em Sistemas de Informação. 2026/2.
Professor: Fidelis Zanetti de Castro.

## Integrantes

* José Augusto
* Matheus Santos
* Rodolfo Müller

## Aviso

Simulador acadêmico - somente créditos fictícios.

## Arquivos do pacote

|Arquivo|Conteúdo|
|-|-|
|tigrIFES.xlsm|Simulador em VBA (macros) com os cinco experimentos, tabelas e gráficos|
|relatorio.pdf|Relatório do grupo|
|README.md|Este arquivo|

## Ambiente

* Linguagem: VBA (Visual Basic for Applications) e funções do Microsoft Excel 2010 ou mais moderno.
* Gerador pseudoaleatório: função 'Rnd' do VBA, iniciada com 'Rnd -1' seguido de 'Randomize <semente>', uma única vez no início de cada execução.

## Como executar

1. Abra o arquivo '.xlsm' no **computador** (o Excel do celular e o Excel Online descartam as macros) e clique em "Habilitar conteúdo/macros".
2. Abra a aba de cada experimento.
3. Por aba:

   * Caça Níquel: Aba com uma máquina caça níquel simples, rosto feliz, cereja, estrela coração e tigre correspondem aos prêmios de 5, 10, 15, 25 e 50 respectivamente. O tigre possui uma animação especial. A única célula editável é I18:J19, que corresponde a quantidade de créditos. Ao jogar, perca um crédito, ao ganhar, receba o prêmio de acordo com a imagem.
   * Experimento 1: Experimento na aba "Experimento 1", células editáveis pintadas de verde claro. Edite a semente, o número de rodadas e clique no botão "EXECUTAR N RODADAS" caso queira gerar valores com outras sementes e quantidades de rodadas. Tabela e gráficos são dinâmicos e se alteram.
   * Experimento 2: Experimento dividido em 4 abas, Exp2Seed2026, Exp2Seed10, Exp2Seed123456 e Experimento2. As 3 primeiras abas possuem as tabelas de cada semente com o valor de cada rolo, o lucro até aquela rodada e o lucro médio. Enquanto a aba Experimento2 possui uma tabela com 4 colunas: o número da rodada e o lucro médio  de cada tabela, além disso, também há um gráfico com o lucro médio de cada semente em função da rodada e uma tabela do lucro médio de cada semente nas rodadas 100, 1000 e 10000. É possível alterar somente a semente de cada uma das três tabelas.
   * Experimento 3: Experimento na aba "Experimento3", células editáveis em verde claro: semente, saldo inicial, número de participantes, número de rodadas, e quantidade de participantes no gráfico. Caso queira testar diferentes valores, altere um dos números em verde claro e clique no botão "SIMULAR X PARTICIPANTES E Y RODADAS", a tabela ciano à esquerda e gráfico irão se alterar. A tabela à direita possui a quantidade de créditos de cada jogador por rodada e na última linha a última rodada do jogador, caso ele tenha zerado seus créditos, será essa rodada, cada jogador é uma coluna e cada linha uma rodada. Os valores dessa tabela que conflitarem com novos são sobrescritos, porém, os valores antigos que estiverem fora dos limites declarados nas variáveis não serão nem apagados nem considerados no cálculo da tabela e gráfico.
   * Experimentos 4 e 5: usam os mesmos 10.000 resultados do Experimento 1 (aba "Experimento1"). É preciso apenas clicar no botão nas respectivas abas ("Experimento4" e "Experimento5") para aplicar o processo do experimento à tabela do experimento 1.
4. Os resultados e as fórmulas de resumo são atualizados na própria aba.

## Onde estão os resultados

* Experimento 1: aba "Experimento1", à esquerda, há uma tabela com 5 colunas, 3 para o resultado de cada rolo, uma que indica se houve algum prêmio naquela rodada ou não e outra indicando o lucro daquela rodada. Embaixo das células editáveis semente e rodadas, há uma tabela com as medidas requisitadas na especificação. Mais embaixo há outra tabela com a frequência de cada tripla e o lucro dela. Sob essas tabelas, estão os gráficos com a frequência de cada tripla.
* Experimento 2: Abas "Exp2Seed2026", "Exp2Seed10", "Exp2Seed123456" para os resultados das sementes individuais e aba "Experimento2" para um resumo do todo. Cada uma das abas individuais das sementes possuem a tabela de resultados e a tabela das rodadas 100, 1000 e 10000 para cada semente. Na aba "Experimento2", há uma tabela com o lucro médio de cada semente por rodada, uma tabela com o lucro médio das sementes nas rodadas 100, 1000 e 10000, e um gráfico que mostra a evolução do lucro médio das sementes por rodada.
* Experimento 3: aba Experimento3, à esquerda, a tabela ciano possui as medidas pedidas na especificação, embaixo dela está o gráfico da evolução do saldo dos participantes por rodada. Há uma outra tabela à direita com o saldo de todos os participantes (colunas) por rodada (linhas). 
* Experimento 4: aba Experimento4, duas tabelas com as medidas requisitadas dos pares consecutivos e um gráfico. O gráfico do relatório foi feito em python e está ligeiramente diferente daquele na planilha, no entanto, as informações são idênticas.
* Experimento 5: aba Experimento5, uma tabela comparando as medidas pedidas na especificação entre o resultado do prêmio normal e do prêmio com um aumento de 10%. Embaixo há outra tabela com a quantidade e lucro de cada tripla. Assim como no experimento 4, os gráficos desse experimento foram feitos em python e são um pouco diferentes mas possuem os mesmo valores.



## Uso de IA

A IA foi utilizada para tirar dúvidas tanto na elaboração do relatório quanto para o desenvolvimento do código, com destaque para os experimentos 4 e 5 que foram originalmente feitos em python e, então, traduzidos para VBA do Excel. A IA também foi utilizada para revisão da entrega final e resultados gerados pelo simulador, além de procurar inconsistências nas tabelas.

