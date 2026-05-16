# Task List Django Project

Proyecto Django sencillo para administrar tareas con vista de lista y detalle.

## Qué incluye

- Aplicación `tasks` con modelo `Task`
- Lista de tareas y detalle de tarea
- Plantillas en `templates/`
- Archivos estáticos en `static/css/style.css`
- Base de datos SQLite (`db.sqlite3`)

## Requisitos

- Python 3.x
- virtualenv o entorno virtual de Python
- Dependencias en `requirements.txt`

## Instalación

1. Crear y activar el entorno virtual:

   ```powershell
   python -m venv .venv
   .venv\Scripts\Activate.ps1
   ```

2. Instalar dependencias:

   ```powershell
   pip install -r requirements.txt
   ```

3. Aplicar migraciones:

   ```powershell
   python manage.py migrate
   ```

4. Iniciar el servidor de desarrollo:

   ```powershell
   python manage.py runserver
   ```

5. Abrir en el navegador:

   ```text
   http://127.0.0.1:8000/
   ```

## Rutas principales

- `/` — Lista de tareas
- `/tareas/<id>/` — Detalle de una tarea

## Notas

- El proyecto usa SQLite como base de datos.
- El ajuste `DEBUG` está activado en `base_project/settings.py`, por lo que este proyecto es adecuado para desarrollo.
