# Playbook: Python_Desk e Pyspark

Compara a eficácia e eficiência entre a biblioteca Dask, que realiza análise escalável em Python e o Apache Spark, utilizando no exemplo Pyspark e comandos SQL para atingir o mesmo resultado. Os estudos são aplicados no arquivo de microdados do Enem2019 que possui aproximadamente 3Gb. 

# Descrição
#### Componentes utilizados:
* **Sistema operacional: windows 11**
* **Python**
* **Pyspark**

# Uso
#### 1. Análises utilizando o Dask:

* A aplicação irá baixar, ler e processar os dados do Enem2019.

* Filtrar os alunos que residem no Estado do Rio de Janeiro.

* Calcular a média de idade e a média da nota em matemática por sexo informando o Município de residência. 

#### 2. Análises utilizando o Spark:

* A aplicação irá ler e processar os dados do Enem2019.

* Calcular a média de idade e a média da nota em matemática por sexo e Estado do Rio de Janeiro e São Paulo. 

* Realizar os mesmos cálculos com comandos SQL.

* Calcular a média de idade, média da nota em matemática, média da nota em CH, desvio padrão da nota em MT, contagem de linhas por grupos de sexo, Estado e Municipio.


