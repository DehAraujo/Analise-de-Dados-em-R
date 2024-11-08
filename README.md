**Descrição do Projeto**
Este projeto de estatística tem como objetivo analisar se a idade dos clientes está relacionada e influencia as dívidas no cartão de crédito. A análise foi realizada utilizando a linguagem de programação R, com diversas técnicas estatísticas e visualizações gráficas para explorar a distribuição e a correlação entre as variáveis.

**Objetivos do Projeto**
Analisar a Distribuição das Idades: Verificar como as idades dos clientes estão distribuídas.

Analisar a Distribuição das Dívidas: Verificar a distribuição dos valores das dívidas de cartão de crédito entre os clientes.

Calcular a Correlação: Medir a correlação entre a idade e as dívidas no cartão de crédito para entender se há uma relação linear significativa.

Testar a Normalidade: Verificar se as distribuições das idades e das dívidas seguem uma distribuição normal.

Interpretação dos Resultados: Avaliar os resultados para tirar conclusões sobre a influência da idade nas dívidas de cartão de crédito.

**Metodologia**
**Carregamento dos Dados:**

Os dados foram carregados em R e preparados para a análise, incluindo a verificação e tratamento de valores ausentes (NA).

**Análises Estatísticas Descritivas:**

Média, Mediana, Variância e Desvio Padrão: Calculados para entender as características básicas das distribuições das idades e das dívidas.

Histogramas e Gráficos de Densidade: Utilizados para visualizar as distribuições das idades e das dívidas.

Teste de Correlação:

Coeficiente de Correlação de Pearson: Calculado para medir a força e a direção da relação linear entre a idade e as dívidas no cartão de crédito.

Teste de Normalidade:

Teste de Anderson-Darling: Realizado para verificar se as distribuições das idades e das dívidas seguem uma distribuição normal.

**Resultados**
Distribuição das Idades: A maioria dos clientes está na faixa etária entre 25 e 45 anos.

Distribuição das Dívidas: A maioria das dívidas é relativamente baixa, com alguns outliers representando dívidas muito altas.

Correlação: A correlação entre idade e dívidas de cartão de crédito é fraca (0.06674087), sugerindo pouca ou nenhuma relação linear significativa.

Normalidade: Os testes de normalidade (Anderson-Darling) indicaram que nem as idades nem as dívidas seguem uma distribuição normal.

**Conclusão**
Os resultados indicam que a idade dos clientes tem pouca influência sobre as dívidas de cartão de crédito. A maioria das dívidas são pequenas, independentemente da idade dos clientes, com algumas exceções de dívidas altas. A análise sugere que outros fatores, além da idade, provavelmente têm um papel mais significativo no endividamento dos clientes.

**Ferramentas Utilizadas**
Linguagem R: Para a análise e visualização dos dados.

Pacotes R:

dplyr: Para manipulação dos dados.

ggplot2: Para visualização gráfica.

nortest: Para testes de normalidade.
