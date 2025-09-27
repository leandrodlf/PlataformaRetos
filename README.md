# PlataformaRetos

PlataformaRetos/
├── manage.py # Script de gestión de Django
├── db.sqlite3 # Base de datos (se crea automáticamente)
├── venv/ # Entorno virtual (no subir a Git)
├── plataforma_retos/ # Configuración del proyecto
│ ├── settings.py # Configuración principal
│ ├── urls.py # URLs del proyecto
│ └── ...
└── retos/ # Aplicación principal
├── models.py # Modelos de datos
├── views.py # Lógica de la aplicación
├── urls.py # URLs de la aplicación
├── templates/ # Plantillas HTML
└── management/commands/ # Comandos personalizados

markdown
Copiar código

## Descripción

Plataforma web educativa desarrollada con Django para resolver retos matemáticos, lógicos y sudokus. Incluye sistema de puntuación, ranking de usuarios y panel de administración.

## Requisitos del Sistema

- Windows 10/11 (probado en Windows 11)  
- Python 3.8 o superior  
- PowerShell (incluido por defecto en Windows)  
- Navegador web (Chrome, Firefox, Edge)  

## Instalación Paso a Paso

1. **Descargar el proyecto**  
   Coloca la carpeta `PlataformaRetos` en el Escritorio.

2. **Abrir PowerShell o terminal y navegar al proyecto**  
   ```bash
   cd ~/Desktop/PlataformaRetos
Crear y activar entorno virtual

Crear entorno virtual:

bash
Copiar código
# Windows
python -m venv venv

# Linux
python3 -m venv venv
Activar entorno virtual:

bash
Copiar código
# Windows
.\venv\Scripts\Activate.ps1

# Linux
source venv/bin/activate
Nota (solo Windows): Si aparece un error de ejecución de scripts, ejecuta:

powershell
Copiar código
Set-ExecutionPolicy -ExecutionPolicy RemoteSigned -Scope CurrentUser
Instalar dependencias

bash
Copiar código
pip install -r requirements.txt
Ejecutar el servidor

bash
Copiar código
# Windows
python manage.py runserver

# Linux
python3 manage.py runserver
Acceder a la plataforma
Abre tu navegador y ve a:

Plataforma principal: http://127.0.0.1:8000/

Panel de administración: http://127.0.0.1:8000/admin/
