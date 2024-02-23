# Como construir um classificador de aprendizado de máquina em Python com Scikit-learn

- Implementação de um algoritmo simples de aprendizado de máquina em python usando a biblioteca scikit-learn.
- O banco de dados está contido na própria biblioteca. O banco de dados contém informações sobre tumores de câncer de mama.
- O algoritmo utilizado aqui foi um classificador binário Naive-Bayes (NB) que prevê se um tumor é maligno ou não.

## Ambiente de desenvolvimento

1. Faça o clone do repositório do projeto

   $ git clone endereco_do_repositorio_no_github
   
3. Navegue até o diretório do projeto

   $ cd nome_diretorio

4. Verificar a versão do python (Esse notebook foi feito na versão 3.10)
   
   $ python3 --version
   
5. Criar o ambiente virtual dentro do diretório
  
   $ python -m venv pyenv

6. Ative o ambiente virtual

  $ source pyenv/bin/activate # no windows, use 'pyenv/Scripts/activate'

6. Instale o jupyter notebook

  $ pip install jupyterlab

7. Inicie o jupyterlab 

Voilá, tá pronto pra conferir o notebook. 

## Conclusões 

- Neste tutorial, aprendi a construir um classificador de aprendizado de máquina em python.
- Aprendi também a carregar os dados, organizá-los, treinar os dados, e fazer a classificação:
    - 0 : tumor maligno
    - 1 : tumor benigno
    - O classificador NB apresentou 94,15% de precisão, isso significa que 94,15% das vezes o classificador é capaz de fazer a previsão correta, indicando se o tumor é maligno ou benigno.

## Referência

- Machine Learning Projects compiled by Brian Boucheron e Lisa Tagliaferri