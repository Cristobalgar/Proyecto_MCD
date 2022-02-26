# Proyecto_MCD
Proyecto sobre Análisis Covid-19

El propósito de este repositorio *demostrar el manejo y comprensión* de lo aprendido en el  curso de **Herramientas de Productividad en Ciencia De Datos** para los propedéuticos de la Maestría en Ciencia De Datos de la Universidad de Sonora, la actividad es sobre la Descarga y análisis de los datos COVID-19 en el estado de Zacatecas.

Los datos que serán mostrados en este análisis fueron rescatados de la base de datos de la Secretaría de Salud.

La metodología que se va llevar a cabo es un a muy simple, por medio del *Dockerfile* se usó bajo un contenedor de ubuntu que también incluye un *script de Shell* donde continúe.

Se descargaron los archivos o datos de la página de la pSecretaría de Salud sobre Datos Abiertos Dirección General Epidemióloga.

Se limpiaron los datos primero buscando los que son de Zacatecas donde en estos datos son el número 32 de la entidad, siguiente a eso se va a cortar los datos que no se ocupan donde solo nos vamos a quedar con la edad, el sexo, es indigena y habla lenguage indigenada.

Esto lo hicimos con los siguiente códigos: 



