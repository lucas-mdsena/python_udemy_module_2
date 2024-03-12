# **Manipulação de dados com Pandas**
Este repositório contém os materiais utilizados nas aulas do módulo 2, no curso da Udemy.
***


# **Dataframes, dados estruturados, semiestruturados e não estruturados**

## **O que é um Dataframe?**
Dataframe é uma estrutura de dados tabelar, ou seja, organiza os dados de uma forma estruturada por linhas e colunas – tendo linhas como observações ou ocorrências e colunas como características (features).
![image](https://github.com/lucas-mdsena/python_udemy/assets/93884007/f8792ce1-7528-4f15-952a-4d2455659d26)

## **Dados estruturados​**
A definição utilizada anteriormente ao Dataframes, aplica-se aqui também. Podemos adicionar que, quando temos características em colunas e observações em linhas, os dados estão no formato wide ou tidy. Se invertido, chamamos de formato long (pouco usual).​
Exemplos de dados estruturados são os arquivos .xlsx (excel) e bancos de dados SQL.

## **Dados semiestruturados​**
Os dados semiestruturados são chamados assim, pois não estão formatados como uma tabela, mas possuem uma estrutura de organização que permite identificar o tipo de cada informação – etiquetas/tags ou nós, a depender do tipo.
![image](https://github.com/lucas-mdsena/python_udemy/assets/93884007/ebfa0d4b-1922-400e-ac95-5375c0ffc613)
Fonte: https://upload.wikimedia.org/wikipedia/commons/5/56/JSON_vs._XML.png

## **Dados não estruturados​**
Não estruturados não possuem a estrutura de identificação que os outros dois têm. Não há como antecipar o tipo (número inteiro, data, caractere). Dados não estruturados podem ser arquivos de texto, .csv, texto de e-mails, imagens, músicas.
![image](https://github.com/lucas-mdsena/python_udemy/assets/93884007/d93ca6ed-9f3d-4db8-baae-23c9554e4aca)
Fonte: https://upload.wikimedia.org/wikipedia/commons/1/17/Cordillera_de_los_Andes.jpg


# **O que é o Pandas?​**
[Pandas](https://pandas.pydata.org/) é uma biblioteca open source desenvolvida para Python, que oferece um conjunto de **ferramentas para manipulação e análise de dados**.
<br>
- Aceita diversos tipos de arquivos como fonte de dados, como csv, xls, json, xml, html, arquivos de texto.
- Possui uma sintaxe de alto nível e bastante intuitiva.
- É compatível com outras bibliotecas populares, como NumPy, Matplotlib, Statsmodels, SciPy, Scikit-Learn.​
<br>
O nome Pandas deriva de panel data, termo comum em bases de dados na econometria.


# **Instalando o Pandas**
Para utilizarmos uma biblioteca, ele deve estar instalada na máquina que executa e interpreta os comandos da linguagem Python.​
<br>
Vamos apresentar três formas de se instalar a biblioteca Pandas (ou qualquer outra biblioteca para Python), para que o usuário escolha conforme sua preferência.​

## **Instalando no Windows**
Abra o terminal ou o prompt de comando e digite o comando:​

```
pip install pandas

```
```
pip install pandas==1.4.4

```

## **Instalando via notebook Jupyter​**

```
!pip install pandas

```
```
!pip install pandas==1.4.4

```

## **Google Colab​**
Nas máquinas disponibilizadas via Google Colab, o Pandas já vem instaladas, bastando apenas carregá-lo. Para instalar outra biblioteca, basta usar o comando de instalação padrão via notebooks Jupyter.




