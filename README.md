# PyGNSS-SDR

# Getting Started

Este repositorio contiene una herramienta de software desarrollada en python que implementa un bloque de adquisición para señales GPS obtenidas mediante un dispositivo SDR.
Fue desarrollado como Trabajo de graduacion de la carrera Ingenieria Electronica en la Universidad Nacional de Tucuman en el año 2021 bajo la orbita del Laboratorio de Telecomunicaciones de dicha institucion.
En el informe puede encontrar el detalle completo del trabajo realizado.
Seguramente pueden mejorarse muchas cosas, esta es la primera version publica de este trabajo.

Autor: Ing. Lucas Castillo Delacroix  (lucas.castillo.delacroix@gmail.com)
Direccion: Dr. Ing. Mariano Fagre     (mfagre@herrera.unt.edu.ar)  


# Installation

0. instalarlo con pip y verifica la instalación

    pip install virtualenv

    virtualenv --version

1. Cree un entorno virtual.

    virtualenv --python=/usr/bin/python3 my-env         # Create a virtual environment
    
2. Active el entorno virtual.

    source my-env/bin/activate                          # Activate the virtual environment 

3. Instale las dependencias.

    pip install -r requirements.txt                     # Install the dependencies


* Para desactivar el entorno virtual.

    deactivate

* Para eliminar el entorno virtual.

    rm -rf ./my-env 



# Running the PyGNSS-SDR

1. Situarse sobre la carpeta del proyecto y ejecutar ./menu.py
(Si tiene problemas de permiso para ello, debe darle permisos al SO para ejecutarlo de esa manera con el comando: chmod +x menu.py)

Para informacion detallada sobre el uso de la herramienta por favor consulte el anexo A.2 Instrucciones de uso del documento Informe.pdf

## Test File

Del siguiente link (https://mega.nz/folder/xmQSQLgb#m9kiAv4NpG_h22O3mr6Nbw) se pueden descargar dos archivos con grabaciones reales para probar la herramienta:

1. capture1_gnss_sdr.dat
    * Formato GNSS-SDR
    * Frec muestreo: 2e6
    * Satelites presents: 2,12,24,29

2. capture2_rtl_sdr.dat
    * Formato RTL-SDR
    * Frec muestreo: 2e6
    * Satelites presents: 2,12,25,29


# Notes

Si se desea ampliar el conocimiento en el tema, se recomienda visitar la pagina del proyecto GNSS-SDR (https://gnss-sdr.org/) que fue de gran ayuda para mi, especialmente la colaboracion del Dr. Carles Fernández Prades.
