# Belajar Django - Transversy Media

untuk install django sebaiknya install dahulu viertual env per project

```bash
pip install pipenv
```

jikalau sudah menginstall maka jalankan virtual env nya , untuk membuat file Pipfile nya di dalam project

```bash
pipenv shell
```

jika sudah lalu install django nya di dalam local project

```bash
pipenv install django
```

## Konsep Project and App

berikut pengertian Project dan App

### Project

project adalah tempat banyaknya app. misal di dalam Project Bisnis kita sebut saja Yudhistira, ada aplikasi untuk API, landing page , serta Admin page

### App

App adalah aplikasi yang menjadi bagian project. seperti API , Landing Page, dll

untuk membuat app dalam project django :

```bash
django-admin startproject pollster
```

### Menjalankan server

untuk menjalankan server pada django, pastikan terminal kalian berada di folder yang memiliki file `manage.py`, lalu jalankan perintah :

```bash
py manage.py runserver 8000
#dimana 8000 adalah port pilihan kita
```

### Migration

jika menjalankan server , biasa suka ada warning untuk menjalankan migration. maksudnya , kita harus menjalankan migration data base terlebih dahulu. cara menjalankan migration :

```bash
py manage.py migrate
```
