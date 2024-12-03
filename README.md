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

### Instalar o django
```
pip install django
```

### Realizar as migrações do banco de dados, caso precise
```
python manage.py migrate
```

### Executar o comando para inciar o server
```
python manage.py runserver
```


### Por fim no browser terá que aparecer isto:
URL: <http://127.0.0.1:8000/>
![image](https://github.com/user-attachments/assets/3f496f31-2599-475e-941a-ff6829276bfe)
