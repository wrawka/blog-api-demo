# YATUBE API
API �������� ������� "YATUBE" @ ������.���������

---
![](https://img.shields.io/badge/OpenAPI-3.0.2-red)
![](https://img.shields.io/badge/python-3.7-blue)
![](https://img.shields.io/badge/django-2.2.6-brightgreen)

- [YATUBE API](#yatube-api)
    - [��� ���](#���-���)
    - [����� ���](#�����-���)
    - [��� ���� ������������:](#���-����-������������)
    - [������������ �� API � ������� ��������](#������������-��-api-�-�������-��������)
    - [�������������](#�������������)

### ��� ���

������������� restful-API ��� ��������� ������

### ����� ���

��������� ������������ �� �������� ����� ���� ���:
- ������� � ������������� DRF
- �������������� �� JWT-������� �� ������ Djoser / DRF-simplejwt
- ������������� ������� � API �� ��������� permissions

### ��� ���� ������������:

����������� ����������� � ������� � ���� � ��������� ������:

```
git clone https://github.com/wrawka/api_final_yatube
```

```
cd api_final_yatube
```

������� � ������������ ����������� ���������:

```
python3 -m venv .venv
```

```
source .venv/Scripts/activate
```

```
python3 -m pip install --upgrade pip
```

���������� ����������� �� ����� requirements.txt:

```
pip install -r requirements.txt
```

��������� ��������:

```
python3 manage.py migrate
```

��������� ������:

```
python3 manage.py runserver
```


### ������������ �� API � ������� ��������

����� ������� ���������� �������
������������ �� API � ������� �������� ����� �������� �� ������:
**[http://127.0.0.1:8000/redoc/](http://127.0.0.1:8000/redoc/)**

### �������������

- ������� �������� ����� 
- ���������� ���������� Stack Overflow
- ���� ����