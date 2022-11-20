# O que a análise dos tributos diretos e das transferências monetárias no topo da distribuição nos informa sobre desigualdades de raça e gênero no Brasil?

Neste repositório, você encontrará os arquivos referentes à Nota de Política Econômica Nº27, intitulada "O que a análise dos tributos diretos e das transferências monetárias no topo da distribuição nos informa sobre desigualdades de raça e gênero no Brasil?". A nota pode ser lida aqui.

Este repositório está estruturado da seguinte forma:

```
POFRacaGenero
│   README.md   
│   POF.csv
└───Dados
│   │   ALUGUEL_ESTIMADO.rds
│   │   CADERNETA_COLETIVA.rds
│   │   DESPESA_COLETIVA.rds
│   │   DESPESA_INDIVIDUAL.rds
│   |   DESPESA_INDIVIDUAL.rds
│   |   INVENTARIO.rds
│   |   OUTROS_RENDIMENTOS.rds
│   |   RENDIMENTO_TRABALHO.rds
│   |   SERVICO_NAO_MONETARIO_POF2.rds
│   |   SERVICO_NAO_MONETARIO_POF4.rds
│   |   Tradutor_Rendimento.xlsx
│   
└───Scripts - Python
|   │   POF - MADE.ipynb
|   │   ProcessamentoEAnalise.ipynb
|   │   Pipfile
|   │   Pipfile.lock
└───Scripts - R
|   │   POF - Made Final.Rmd
|   │   renv.lock
```
Há um arquivo "POF.csv" 
Na pasta `Dados` temos uma série de arquivos RDS contendo os microdados brutos da POF 2017-2018 e o Tradutor de Rendimentos.
Na pasta `Scripts - Python` temos os dois Jupyter Notebooks:
<ul>
  <li> POF - MADE: Notebook que transforma os microdados em uma base única. </li>
  <li> ProcessamentoEAnalise: Notebook que processa a base final e gera os gráficos e estatísticas descritivas utilizadas na NPE 27. </li>
</ul>
Além deles, também temos os arquivos referentes ao ambiente virtual utilizado para desenvolver os scripts, assim, facilitando a manutenção de dependências. Caso queira saber mais sobre o uso do Pipfile para manutenção de dependências, leia este <a href="https://medium.com/@patrickporto/introdu%C3%A7%C3%A3o-ao-pipenv-49aa9685dfe4">artigo</a>. 

Na pasta `Scripts - R` temos um RMarkdown que transforma os microdados em uma base única. Além disso, também temos os o arquivo refernte ao REnviroment, que possui um papel semelhante ao do Pipfile supracitado. Um bom guia para o uso do REnv está <a href="https://sites.google.com/nyu.edu/nyu-hpc/hpc-systems/greene/software/r-packages-with-renv?pli=1"> neste link</a>.
