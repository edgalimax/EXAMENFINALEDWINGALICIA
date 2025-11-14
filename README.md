# EXAMEN FINAL - Django Tienda Simple
Paginas: Inicio, Categorías (listar/crear/editar), Productos (listar/crear/editar), Créditos y Admin opcional.
Instalación rápida (Windows):
```
cd examenfinal
python -m venv venv
venv\Scripts\activate
pip install -r requirements.txt
python manage.py migrate
python manage.py runserver
```
Despliegue Railway: usar Procfile; agregar SECRET_KEY, DEBUG=False, ALLOWED_HOSTS=* y (opcional) Postgres (DATABASE_URL).


### Notas
- Para Windows local: usa `requirements.txt` (SQLite).
- Para desplegar en Railway: usa `requirements_deploy.txt`.
