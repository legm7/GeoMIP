# Método 2

> Base de la estrategia 2.

---

## Instalación

Guía de Configuración del Entorno con VSCode

### ⚙️ Instalación - Configuración

#### 📋 **Requisitos Mínimos**
- ![PowerShell](https://img.shields.io/badge/-PowerShell-blue?style=flat-square) Terminal PowerShell/Bash.
- ![VSCode](https://img.shields.io/badge/-VSCode-007ACC?logo=visualstudiocode&style=flat-square) Visual Studio Code instalado.
- ![Python](https://img.shields.io/badge/-Python%203.9.13-3776AB?logo=python&style=flat-square) Versión python 3.9.13 (o similar).

---

#### 🚀 **Configuración**

1. **🔥 Crear Entorno Virtual**  
   - Abre VSCode y presiona `Ctrl + Shift + P`.
   - Busca y selecciona:  
     `Python: Create Environment` → `Venv` → `Python 3.9.13 64-bit` y si es el de la `(Microsoft Store)` mejor. En este paso, es usualmente recomendable el hacer instalación del Virtual Environment mediante el archivo de requerimientos, no obstante , puedes usar UV. También es importante aclarar lo siguiente, habra que de desactivar cada uno de los antivirus, uno por uno en su análisis de tiempo real, permitiendo así la generación de los ficheros necesarios para el virtual-environment.
   - ![Wait](https://img.shields.io/badge/-ESPERA_5_segundos-important) Hasta que aparezca la carpeta `.venv`

2. **🔄 Reinicio**
   - Cierra y vuelve a abrir VSCode (obligado ✨).
   - Verifica que en la terminal veas `(.venv)` al principio  
     *(Si no: Ejecuta `.\.venv\Scripts\activate` manualmente, pon `activate.bat` si estás en Bash)*


> **💣 (Opcional) Instalación de librerías con UV**
>   En la terminal PowerShell (.venv activado): 
>   Primero instalamos `uv` con 
>   ```powershell
>   pip install uv
>   ```
>   Procedemos a instalar las librerías con
>   ```powershell
>   python -m uv pip install -e .
>   ```

> **Este comando:**
> Instala dependencias de pyproject.toml
> Configura el proyecto en modo desarrollo (-e)
> Genera proyecto_2025a.egg-info con metadatos

> 1. ✅ Verificación Exitosa
   ✔️ Sin errores en terminal
   ✔️ Carpeta proyecto_2025a.egg-info creada
   ✔️ Posibilidad de importar dependencias desde Python

> 🔥 Notas Críticas
   - Procura usar la PowerShell como terminal predeterminada (o Bash).
   - Activar entorno virtual antes de cualquier operación.
   - Si usaste UV la carpeta `proyecto_2025a.egg-info` es esencial.

---

*Para proceder con una introducción o guía de uso del aplicativo, dirígete a `.docs\application.md`, donde encontrarás cómo realizar análisis en este FrameWork.*
