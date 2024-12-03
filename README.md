# Getting Started

## Requisitos

- Python instalado;
- Internet;
- No caso OS Windows.


### Para clonar o repositório
```
git clone https://github.com/Ianalas/python.git

cd python
```

> *obs.: verifique se a pasta tem o arquivo "manage.py"*
> 


### Para inicializar o ambiente virtual do Python
```
python -m venv venv

.\venv\Scripts\activate  
```

### Realizar as migrações do banco de dados, caso precise
```
python manage.py migrate
```

### Executar o comando para inciar o server
```
python manage.py runserver
```
