# Proyecto de Fundamentos de Ciencia de Datos - Grupo 03

Bienvenido a este repositorio. Este proyecto contiene un análisis exploratorio, limpieza y visualización de datos utilizando el conjunto de datos **Horse Colic** (Cólico equino).

El trabajo principal se encuentra desarrollado en un **Jupyter Notebook**, donde se detalla el paso a paso del procesamiento de datos.

  
## Contenido del Repositorio


* **`AmbienteJupyter.ipynb`**: El archivo principal con el código, análisis y gráficos.
* **`horse-colic.data` / `horse-colic.test`**: Los archivos de datos crudos utilizados en el análisis. **Importante:** No mover estos archivos de la carpeta.
* **`requirements.txt`**: Lista de librerías necesarias para ejecutar el proyecto.
* **`Entreg. TPE...docx`**: Informe formal del trabajo práctico.

---

## Guía de Instalación y Ejecución (Paso a Paso)

Sigue estas instrucciones para descargar y ejecutar el proyecto en tu computadora local.

### 1. Prerrequisitos
Antes de empezar, asegúrate de tener instalado **Python** (versión 3.7 o superior).

#### 🪟 Para Windows
* **Opción 1:** [Página oficial de Python](https://www.python.org/downloads/)
* **Opción 2:** [Microsoft Store](https://apps.microsoft.com/detail/9pnrbtzxmb4z)
> **Nota:** Al instalar, asegúrate de marcar la casilla **"Add Python to PATH"**.

#### 🐧 Para Linux (Ubuntu/Debian/Mint)
Abre tu terminal y ejecuta:
```
bash
sudo apt update
sudo apt install python3 python3-pip
```
Git (opcional, si sabes usarlo).

### 2. Descargar el Proyecto
      
Tienes dos opciones para obtener los archivos:

Opción A (Fácil): Haz clic en el botón verde "Code" en la parte superior de esta página y selecciona "Download ZIP". Descomprime el archivo en una carpeta de tu computadora.

Opción B (Opcional con Git): Abre tu terminal y ejecuta:
```
git clone <URL_DE_TU_REPOSITORIO>
cd <NOMBRE_DE_LA_CARPETA_DESCARGADA>
```

### 3. Instalar las Dependencias
Para que el código funcione, necesitas instalar las librerías listadas en requirements.txt.

  
#### 1. Abre la terminal (o Símbolo del sistema en Windows).
  
  
#### 2. Navega hasta la carpeta donde descargaste/descomprimiste los archivos:

    cd ruta/a/tu/carpeta 

  
#### 3. Ejecuta el siguiente comando:
  
    pip install -r requirements.txt

  Nota para Linux: Si el comando anterior falla o dice "command not found", intenta usar pip3 en su lugar

    pip3 install -r requirements.txt
  
#### 4.Abrir el Notebook (Jupyter)
  
##### 1.  Una vez instaladas las dependencias, En la misma terminal, escribe:
  
    jupyter notebook
    
  (Si en Linux no funciona, prueba: python3 -m notebook)
  
    python3 -m notebook
  
##### 2.Se abrirá automáticamente una pestaña en tu navegador.

##### 3.Haz clic en el archivo AmbienteJupyter.ipynb.

### Cómo ejecutar el análisis

Una vez dentro del notebook:

Para correr paso a paso: Selecciona una celda y presiona Shift + Enter.

Para correr todo de una vez: Ve al menú Kernel -> Restart & Run All.
