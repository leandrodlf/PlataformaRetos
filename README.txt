PlataformaRetos/
├── manage.py               
├── db.sqlite3               
├── plataforma_retos/       
│   ├── settings.py          
│   ├── urls.py              
│   └── ...
└── retos/                  
    ├── models.py           
    ├── views.py             
    ├── urls.py              
    ├── templates/           
    └── management/commands/ 
----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
Descripción:
Plataforma web educativa desarrollada con Django para resolver retos matemáticos, lógicos y sudokus. Incluye sistema de puntuación, ranking de usuarios y panel de administración.
----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
Requisitos del Sistema
Software necesario:
	Windows 10/11 (probado en Windows 11)
	Python 3.8 o superior
	PowerShell (incluido por defecto en Windows)
	Navegador web (Chrome, Firefox, Edge)
----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
Instalación Paso a Paso

1. Descargar el proyecto
	Coloca la carpeta PlataformaRetos en el Escritorio.

2. Abrir la terminal y navegar al proyecto (o en su defecto ejecutar la terminal en la carpeta correspondiente).
	Windows/Linux: cd ~/Desktop/PlataformaRetos

3. Crear y activar entorno virtual
	# Crear entorno virtual
		Windows: python -m venv venv
		Linux: python3 -m venv venv
	# Activar entorno virtual
		Windows:.\venv\Scripts\Activate.ps1
		Linux: source venv/bin/activate
	Nota (solo Windows): Si aparece un error de ejecución de scripts, ejecuta:
		Set-ExecutionPolicy -ExecutionPolicy RemoteSigned -Scope CurrentUser

4. Instalar dependencias
	Windows/Linux: pip install -r requirements.txt

5. Ejecutar el servidor
	Windows: python manage.py runserver
	Linux: python3 manage.py runserver

6. Acceder a la plataforma
	Abre tu navegador y ve a:
		Plataforma principal: http://127.0.0.1:8000/
		Panel de administración: http://127.0.0.1:8000/admin/

7. Credenciales
	Usuario: inacap
	Password: inacap


