# Otimizando Custos no Azure
Neste repositório, estarei documentando o passo a passo da execução do laboratório "Otimizando Custos no Azure", fornecido pela Microsoft Learn, e a minha experiência de aprendizado com o laboratório.

## Objetivo do laborátorio
Agora é a sua hora de brilhar e construir um perfil de destaque na DIO! Explore todos os conceitos abordados até aqui e escreva um resumo do que você aprendeu durante o desenvolvimento do lab. Para concluir este desafio, você deverá entregar o link de um repositório no GitHub contendo um arquivo README com o seu resumo. 

*******
### Índice  
  - [Definindo Cargas de Trabalho](#definindo-cargas-de-trabalho)
  - [Ajustando Suposições](#ajustando-suposições)
  - [Visualizando Relatórios](#visualizando-relatórios)
  - [Conclusão](#conclusão)

*******

## Definindo Cargas de Trabalho

1- Começamos acessando o [Portal Azure](https://portal.azure.com), na aba "Calculadora do TCO (Custo Total de Propriedade)".

 Aqui podemos estimar a economia de custos gerada pela migração de cargas de trabalho para o Azure.

![ ](https://imgur.com/02z35Ci.png)

2 - Insira os detalhes das suas cargas de trabalho locais. Essas informações serão usadas para entender seu TCO atual e os serviços recomendados no Azure.

    Servidores: Insira os detalhes de sua infraestrutura de servidor local. Depois de adicionar uma carga de trabalho, selecione o tipo de carga de trabalho e insira os detalhes restantes.

    Bancos de dados: Insira os detalhes da sua infraestrutura de banco de dados local. Depois de adicionar um banco de dados, insira os detalhes da sua infraestrutura de banco de dados local na seção "Origem". Na seção "Destino", selecione o serviço do Azure que você gostaria de usar.

    Armazenamento: Insira os detalhes de sua infraestrutura de armazenamento local. Depois de adicionar o armazenamento, selecione o tipo de armazenamento e insira os detalhes restantes.

    Rede: Insira a quantidade de largura de banda de rede que você consome atualmente em seu ambiente local.


## Ajustando Suposições

3 - As suposições a seguir no modelo de TCO (custo total de propriedade) são as médias do setor credenciadas pela Nucleus Research. Para obter um relatório de TCO mais preciso, atualize e personalize esses valores para refletir sua situação, que pode variar de acordo com o setor e o local.

![ ](https://imgur.com/nplBzUd.png)

## Visualizando Relatórios

4 - Com as configurações feitas, é possível visualizar a projeção de custos baseada em período de tempo, região e programa de licenciamento.

![ ](https://imgur.com/pxDbSmB.png)

## Conclusão
Esse laboratório serviu para mostrar na prática o modelo de custo da Azure e seus serviços.

### Referências
* ######