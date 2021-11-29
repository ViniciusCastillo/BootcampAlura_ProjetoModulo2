# BootcampAlura_ProjetoModulo2
## Análise exploratória da base de cobertura vacinal do SUS
![image](https://user-images.githubusercontent.com/93411539/143798779-5383f897-225b-4483-bcfb-d2feae44b890.png)

### Introdução
Neste projeto realizei uma análise exploratório em cima das bases de cobertura vacinal de crianças até 1 ano do [DataSUS](http://tabnet.datasus.gov.br/cgi/tabcgi.exe?pni/cnv/cpniuf.def). Olhando por tanto por Unidade da Federação quanto por Imunizante.

### Tratamento dos Dados
No [tratamento dos dados](https://github.com/ViniciusCastillo/BootcampAlura_ProjetoModulo2/blob/main/Notebooks/capturaDados.ipynb) eu escolhi o período de 2013 até 2018, pois a base de 2019 está incompleta e os anos anteriores tinham grandes distorções, com imunizantes diferentes, dificultando a análise.

Além disso, retirei alguns imunizantes da análise para reduzir a quantidade de dados a serem analisados, que no período escolhido não aparentavam trazer informações relevantes para mudar as conclusões.

Por fim, criei uma categorização de atingimento da meta em cima das metas do [PNI (pg. 6)](https://portalarquivos2.saude.gov.br/images/pdf/2017/agosto/17/AACOBERTURAS-VACINAIS-NO-BRASIL---2010-2014.pdf), com 3 quebras:
* **Meta Atingida**: Cobertura Vacinal maior ou igual a meta do PNI;
* **Abaixo da Meta**: Cobertura Vacinal até 50% abaixo da meta;
* **Muito Abaixo**: Cobertura Vacinal que não atingiu nem 50% da meta.

### Análise
A [análise](https://github.com/ViniciusCastillo/BootcampAlura_ProjetoModulo2/blob/main/Notebooks/analise.ipynb) foi feita avaliando a frequência de atingimento das classificações acima. Além disso, olhei também a evolução anual do índice de cobertura por imunizante de alguns estados escolhidos com base na avaliação de frequência, buscando pegar um representante de cada tipo de evolução/característica das frequências, fora avaliar o estado de São Paulo também por ser onde moro.

### Conclusões
Consegui perceber que a cobertura de vacinação de maneira geral está em queda dentro do período analisando (2014 - 2018), gerando impactos como um [surto de Sarampo](https://www.bbc.com/portuguese/brasil-55009825), no estado do Pará como epicentro que tem uma das piores coberturas avaliadas, bem como um incremento de outras [doenças](https://portalarquivos2.saude.gov.br/images/pdf/2019/setembro/25/boletim-especial-21ago19-web.pdf) pelo Brasil.

Acredito que temos outras análises a serem feitas, como correlacionar o número de casos das doenças que poderiam ser prevenidas das crianças menores de 5 anos com a redução da cobertura vacinal.

Espero que gostem das análises e até a próxima!

