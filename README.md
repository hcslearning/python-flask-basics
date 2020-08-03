# python-flask-basics

```bash
cd myproject

# Crear Ambiente Virtual
# -------------------------
# crea un ambiente virtual para aislar las dependencias 
# del proyecto vs las instaladas en el sistema
python3 -m venv venv
# activa el ambiente virtual
. venv/bin/activate

# Instalar Flask 1.1
# ------------------------
pip3 install Flask
# o también puede usar el archivo con las versiones
# específicas usadas
pip install -r requirements.txt

# Correr el proyecto
# ---------------------
export FLASK_APP=hello.py
# correr el proyecto
# por defecto quedara en http://localhost:5000
flask run

```
