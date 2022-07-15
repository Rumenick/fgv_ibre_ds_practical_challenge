![](https://portalibre.fgv.br/sites/default/themes/custom/portalibre/logo.png)

## Parabéns por ter chegado até aqui...

Agradecemos o tempo disposto para participar do processo.

Neste repositório temos o material fornecido para realizar o teste prático para vaga de Cientista de Dados (Pleno/Sênior) do FGV IBRE, bem como são apresentadas abaixo alguns instruções para realizar o desafio.

## Desafio

### Qual é o desafio?

Prever a inflação oficial do Brasil mês a mês até o final do ano de 2022.

### Quais dados posso usar?

Na pasta `data` temos um arquivo \*.xls denominado `indices`, nele você encontrará as séries históricas dos seguintes índices:

-   IPCA (Número Índices) - Índice Nacional de Preços ao Consumidor Amplo do IBGE;

-   Índice Geral de Preços do Mercado - IGP-M do FGV IBRE;

-   IPC-BR-M-Índice Mensal - (POF 2017/2018). Vigência a partir de 01/2020: Índice de Preços ao Consumidor (IPC) do FGV IBRE; 

- IPA-EP-M (Número Índice): Índices de Preços ao Consumidor Amplo do FGV IBRE;e

-   INCC-M - Índice Nacional de Custo da Construção (INCC) do FGV IBRE.

Notas:

1.  todos os valores no arquivo de dados representam números índices, se desejar obter a variação percentual (inflação) de um determinado mês use a seguinte fórmula:

$$
\text{variação (\\%)}_{\text{ mês}} = \frac{\text{n. índice no mês} - \text{n. índice no mês anterior}}{\text{n. índice no mês anterior}} \times 100.
$$

Exemplo: a inflação oficial no mês de junho de 2022 foi 0,67%, isto é,

$$
\text{variação (\\%)}_{\text{ Jun/22}} = \frac{\text{6455,85} - \text{6412,88}}{\text{6412,88}} \times 100 = \text{0,67\\%};
$$

1.  Use os dados do período de Jan/1995 a Jun/2022.

### Onde posso encontrar mais contexto sobre os dados?

Os canais oficiais do FGV IBRE (site, youtube, linkedin) e do IBGE são excelentes fontes, fique a fonte para explorar.

### O que esperamos como resultado do teste?

O objetivo no teste prático não é que você encontre o melhor modelo, mas entender qual é o racional utilizado para resolver um potencial problema do seu dia a dia de trabalho como Cientista de Dados no FGV IBRE. Sendo assim, dentro do **prazo de 7 dias**, esperamos que você:

-   Explore o contexto dos dados;
-   Realize uma análise exploratória dos dados;
-   Teste modelos econométricos, estatísticos e/ou de Aprendizado de Máquina;
-   Elaborar um breve apresentação contendo seu entendimento do contexto dos dados e o racional desde a análise exploratória dos dados até a escolha do modelo.

**Observação:** Além do teste prático, será enviado via e-mail um teste técnico, que busca explorar sua capacidade de esboçar uma solução e planejar as etapas para resolver um problema de extração de dados da Web e um problema de análise envolvendo big data.

### Como devo entregar o teste?

-   na pasta `docs` salve sua apresentação em formato \*.pdf;

-   na pasta `src` salve todos os scripts/notebooks (ex.: .r, .rmd, .py, .ipynb) utilizados;

-   responda ao e-mail anexando:

    \(i\) a apresentação;

    \(ii\) o arquivo .\*pdf com respostas do teste técnico; e

    \(iii\) a pasta fgv_ibre_ds_practical_challenge zipada contendo todos os arquivos gerados.
