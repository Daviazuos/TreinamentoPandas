# Tutorial de instalação do Jupyter Notebook

## Pré requisito: 
Python 3+

## Instruções
1. Clonar o repositório http://srv01stm136.dominio.zanc.com.br/Python/treinamento-pandas.git;
2. Criar e ativar um virtualenv para instalar o Jupyter Notebook;
    ```
    python -m venv venv
    venv\Scripts\activate
    ```
3. Executar os comandos abaixo:
    ```
    pip install jupyterlab
    pip install pandas
    ```
4. Após a conclusão da instalação, executar o comando no terminal:
    ```
    jupyter notebook
    ```