# Innovando en ciberseguridad con Data Analytics & IA

Shenia Kuchumova: <ekuchumova@gradiant.org>

Iago Abad: <iabad@gradiant.org>

## Workshop Foro Tecnológixo 2024

El taller estará dividido en dos partes: anonimización y detección de anomalías.

## Entorno de ejecución cloud: Google Colab

La forma más cómoda de seguir el taller, nos olvidamos de preparar el entorno. Solo tendremos que iniciar sesión con nuestra cuenta de Google en Google Colab, buscar el repo del taller y abrir cada libreta:

*[Google Colab](https://colab.research.google.com/)* > abrimos libreta con *GitHub* > buscamos *Gradiant/forotecnoloxico-2024-cybersecurity-data* > abrimos las libretas

O todavía más fácil:

<https://colab.research.google.com/github/Gradiant/forotecnoloxico-2024-cybersecurity-data/blob/master/data_anonymization.ipynb>

<https://colab.research.google.com/github/Gradiant/forotecnoloxico-2024-cybersecurity-data/blob/master/AnomalyDetection.ipynb>

## Entorno de ejecución local

Con un entorno local podemos ejecutar el código en nuestro ordenador sin necesidad de conexión a internet, pero tendremos que crearlo, configurarlo y descargar el repo previamente.

### Clonar el repositorio

La opción más común es instalar Git en vuestro ordenador y ejecutar `git clone git@github.com:Gradiant/forotecnoloxico-2024-cybersecurity-data.git`

Otra opción es descargarlo directamente desde la página del repo de GitHub (*Código* > *Descargar ZIP*) y descomprimirlo.

### Creación del entorno

Creamos un entorno de Python para no tener ningún problema de versiones durante el taller.

#### Con conda / miniconda

Nosotros recomendamos usar conda.
Tenéis la guía de instalación aquí: <https://docs.conda.io/projects/miniconda/en/latest/miniconda-install.html>

```shell
conda create --name foro2024 python=3.9.15
conda activate foro2024
pip install -r requirements.txt
```

#### Con venv

```shell
mkdir envs 
python3.9 -m venv envs/foro2024
source envs/foro2024/bin/activate
pip install -r requirements.txt
```

### Ejecución

Durante el taller vamos a trabajar con libretas de jupyter.
Podemos ejecutarlas levantando jupyter lab, lo cual nos abrirá una pestaña nueva en el navegador desde donde podemos ejecutar nuestras libretas:

```shell
jupyter lab
```

...o abriendo directamente los archivos .ipynb en nuestro editor de código favorito como VsCode o PyCharm. Jupyter y VsCode no siempre se llevan bien, así que recomendamos usar el navegador.
