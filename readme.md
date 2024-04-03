# Ejercicios y instrucciones #
#### Estos ejercicios son para que  los realizen y entiendan para que sirve cada una de las extensiones con lo cual no son dificiles si no mas bien explicativos ####

#  Pasos previos #
- Ahora vamos a hacer unos pasos previos, lo primero desactivar el antivirus a tiempo real de windows ya que nos va a estorbar luego.

- Lo que vamos a hacer a continuación es añadir la ruta del directorio de scripts de Python al PATH, para ello abrimos el explorador de archivos, damos click derecho sobre "Este equipo", "Propiedades", "Configuración avanzada del sistema", ahora deberiamos estar en una pestaña que pone "Propiedades del sistema", una vez aquí le damos a "Variables de entorno", selecionamos nuestra variable "path", le damos a editar, nueva y pegamos la ruta de acceso: "C:\Users\tunombre_usuario\AppData\Local\Packages\PythonSoftwareFoundation.Python.3.11_qbz5n2kfra8p0\LocalCache\local-packages\Python311\Scripts\pytest
", la podeis buscar por vuestra cuenta pero os la pongo, teneis que cambiar el nombre de usuario por el vuestro propio.

- Ya para acabar hay que añadir otra ruta de acceso más "C:\Users\tunombre_usuario\AppData\Local\Programs\Python\Python311\Scripts
", en una estamos accediendo por la carpeta "Programs" y con la otra por "Packages".
# 1 Pytes-html #
- Lo primero que teneis que hacer abrir el date.py junto con el test_date que ya os lo doy yo, una vez hecho esto vamos a instalar pytes-html escribiendo el siguiente comando en la terminal "pip install pytest-html".

- Una vez que lo tenemos instalado crearemos nuestro archivo html, este se llamará "reporte.html".


- Y por último escribiremos "pytest --html=reporte.html
" en nuestra terminal, esto nos debe generar un informe de las pruebas en el html que podemos ver en el explorador de nuestro equipo.



# 2  Pytes-xdist #
- Lo que tenemos que hacer en este es poner en la terminal "pip install pytest-xdist
" para descargarlo, esta extensión de pytest te permite ejecutar pruebas en paralelo y distribuir las pruebas en múltiples procesos o máquinas. Esto sirve para  acelerar significativamente la ejecución, especialmente en máquinas con múltiples núcleos de CPU.

- Y para activarlo "pytest -n 4", 
# 3  Pytes-random-order #
- Como de costumbre lo primero que vamos a hacer es instalaro poniendo "pip install pytest-random-order
" en nuestra terminal.
- Y ahora para realizar las pruebas de forma aleatoria ponemos "pytest --random-order
" en la terminal, esta extensión permite ejecutar las pruebas en un orden aleatorio en lugar del orden en el que están definidas en los archivos de prueba. Esto ayuda a identificar dependencias no deseadas entre las pruebas y garantizar que las pruebas sean independientes entre sí.

## BUENA SUERTE ##