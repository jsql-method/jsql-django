# jsql-django

Oprogramowanie opracowane przez firmę JSQL Sp. z o.o. w ramach prowadzonego projektu:

Opracowanie nowej metody procesu tworzenia oprogramowania poprzez optymalizację architektury warstwowej typu klient-serwer
Spółka JSQL sp. z.o.o. bierze udział w programie realizując projekt pt.:

“Opracowanie nowej metody procesu tworzenia oprogramowania poprzez optymalizację architektury warstwowej typu klient-serwer”

współfinansowanym przez Unię Europejską ze środków Regionalnego Programu Operacyjnego Województwa Zachodnipomorskiego 2014-2020

Oś priorytetowa 1 Gospodarka, Innowacje, Nowoczesne Technologie.
Działanie: 1.1. Projekty badawczo-rozwojowe przedsiębiorstw
Typ projektu 2

Projekty badawczo-rozwojowe przedsiębiorstw wraz z przygotowaniem do wdrożenia w działalności gospodarczej
Wartość Projektu: 1 380 501,67 PLN
Wkład Funduszy Europejskich: 1 090 679,25 PLN

Zakres i cel Projektu:
Przedmiotem Projektu jest opracowanie nowej metody procesu tworzenia oprogamowania poprzez optymalizację architektury warstwowej typu klient-serwer, dzięki której uzyskane zostaną znaczące ułatwienia oraz optymalizacje na wszystkich płaszczyznach tworzenia oraz utrzymywania oprogramownia, m.in. zmniejszony koszt zasobów ludzkich, zmniejszony koszt utrzymywania projektu, zmniejszona ilość kodu źródłoweog projektu, możliwości przesunięcia zasobów na inne projekty.

Proces badawczy składa się z 4 etapów/Zadań badawczych:
1. Opracowanie modelu teoretycznego nowej metody tworzenia oprogramowania JSQL
2. Eksperymenty badawcze – badania nad nową metodą tworzenia oprogramowania JSQL
3. Budowa i demonstracja prototypu nowej metody tworzenia oprogramowania JSQL
4. 
#### A JSQL Django plugin for executing hashed queries

# Getting Started
#### Install JSQL Django plugin
```shell
pip install jsql-django
```
#### Include JSQL Django plugin views to your `urls.py` file
##### Import views
```python
from jsql.view import SelectView, InsertView, UpdateView, DeleteView
```
##### Describe urls
```python 
    url('select', SelectView.as_view()),
    url('insert', InsertView.as_view()),
    url('update', UpdateView.as_view()),
    url('delete', DeleteView.as_view()),
```

#### Include ApiKey and MemberKey in your `settings.py` file
```python
API_KEY = 'your_api_key'
MEMBER_KEY = 'your_member_key'
```
