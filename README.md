# Hola, Mundo! 🚀

<p align="center">
  <img src="https://img.shields.io/badge/Django-6.1.1-092E20?style=for-the-badge&logo=django" alt="Django 6.1.1" />
  <img src="https://img.shields.io/badge/Python-3.12-3776AB?style=for-the-badge&logo=python" alt="Python 3.12" />
  <img src="https://img.shields.io/badge/SQLite-Database-003B57?style=for-the-badge&logo=sqlite" alt="SQLite" />
</p>

Una pequeña aplicación web desarrollada con Django para mostrar una página de inicio con el clásico mensaje: <strong>Hola, Mundo!</strong>.

---

## ✨ Descripción

Este proyecto es una base simple y limpia para comenzar con Django. Incluye una vista principal, una plantilla HTML y la estructura básica del proyecto para facilitar el desarrollo de nuevas funcionalidades.

---

## 🧩 Características

- Configuración inicial de Django
- Vista principal con plantilla personalizada
- Estructura organizada por apps
- Base de datos SQLite por defecto
- Listo para expandirse con más páginas, formularios o modelos

---

## 🏗️ Estructura del proyecto

```text
hola-mundo/
├── db.sqlite3
├── manage.py
├── requirements.txt
├── README.md
├── django_base/
│   ├── __init__.py
│   ├── asgi.py
│   ├── settings.py
│   ├── urls.py
│   └── wsgi.py
├── pages/
│   ├── __init__.py
│   ├── admin.py
│   ├── apps.py
│   ├── models.py
│   ├── tests.py
│   ├── urls.py
│   ├── views.py
│   └── migrations/
│       └── __init__.py
└── templates/
    └── home.html
```

---

## 🚀 Instalación

1. Clona el repositorio:

```bash
git clone <url-del-repositorio>
cd hola-mundo
```

2. Crea y activa un entorno virtual:

```bash
python -m venv venv
```

En Windows:

```bash
venv\Scripts\activate
```

En macOS/Linux:

```bash
source venv/bin/activate
```

3. Instala las dependencias:

```bash
pip install -r requirements.txt
```

4. Ejecuta las migraciones:

```bash
python manage.py migrate
```

5. Inicia el servidor:

```bash
python manage.py runserver
```

Luego abre tu navegador en:

```text
http://127.0.0.1:8000/
```

---

## 📄 Página principal

La vista inicial renderiza el archivo:

```text
templates/home.html
```

Y muestra el contenido:

```html
<h1>Hola, Mundo!</h1>
```

---

## 🛠️ Tecnologías utilizadas

- Python
- Django
- SQLite
- HTML5

---

## 👤 Autor

Proyecto creado para practicar y aprender el funcionamiento básico de Django.

---

## 📌 Siguientes pasos

Puedes continuar con:

- Crear más páginas
- Agregar modelos y formularios
- Conectar la aplicación a una base de datos más robusta
- Desplegarla en Render, Railway, PythonAnywhere o Heroku

Si quieres, también puedo ayudarte a convertir este proyecto en una aplicación más moderna con navegación, estilo visual y componentes reutilizables. 
