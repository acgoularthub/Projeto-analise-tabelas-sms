# Pojeto de aprendizado Python

    O objetivo do projeto é apresentar um código que leia tabelas de dados Excel e analise seus conteúdos fazendo uma comparação
    entre os dados em busca de vendas maiores que 50 mil. No caso em que esses dados sejam encontrado, será enviado um SMS para o 
    número de telefone cadastrado. 

# O que é preciso:

* O projeto usa o twilio para enviar SMS, logo será necessário ter uma conta no Twilio para utilizar o serviço.
  
Inicie o ambiente virtual do projeto com o comando:

```python
$ python3 -m venv venv
$ source venv/bin/activate
```

Instale os requisitos do projeto com o comando:

```python
$ pip install -r requirements.txt
```

Execute o código, fazendo as devidas alterações (numero de telefone, hash do twilio, etc) e depois execute o comando:

```python
$ python main.py
```

Você pode adicionar ou alterar as tabelas dentro da pasta dados, lembrando de manter o padrão corrente ou alterar o código para que suporte suas tabelas.