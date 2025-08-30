# APLICACIÓN BINGO
Clonar repositorio: "git clone git@github.com:HugoAndres23/Parking.git" ó descargar ZIP

# PASO 1:
Abrir la terminal en la carpeta del proyecto y crear ambiente de python usando el siguiente comando: "python -m venv env"
Activar entorno virtual de Python con el siguiente comando: "env\Scripts\activate" ó "env\Scripts\activate.bat"

# PASO 2:
Instalar en el ambiente virtual las dependencias, en la misma terminal ejecutar el siguiente comando: "pip install -r backend/requirements.txt"

# PASO 3:
Lanzar el servidor de Uvicorn, en la misma terminal ejecutar: "cd backend" y luego "uvicorn main:app --reload"

# PASO 4:
Abrir el navegador e ingresar a: 127.0.0.1:8000 ó localhost:8000