
##Paso:1 Redirigete a la carpeta del proyecto con CD
 
##Paso 2: Cree el ambiente virtual
python -m venv myenv

###Paso 3: Activar el entorno virtual
myenv\Scripts\activate

#Observacion: si esta en MacOS debe utilizar el siguiente comando para el paso 3
source myenv/bin/activate

## Paso 4: Instalar las librerias del archivo requirements.txt
pip install -r requirements.txt

## Paso 5 Luego descargar el csv mas reciente de la siguiente url:
https://datosabiertos.mineduc.cl/titulados-en-educacion-superior

## Paso 6: Ejecutar la aplicacion 
python get_excel_resumen_es.py 
