<!-- PROJECT LOGO -->
<br />
<p align="center">
  <a>
    <img src="https://upload.wikimedia.org/wikipedia/commons/4/43/Cognizant_logo_2022.svg" alt="Logo">
  </a>

<h3 align="center">Performance Testing</h3>
<h4 align="center">Sesión 1 - Introducción a Performance Testing & JMeter</h4>

## Integrantes

* Roberto Bertrand Lizárraga
* Iván Montiel Cardona
* Mungarro Echeverría Héctor
* Salmerón González Victor

## Desarollo
En esta sesión se harán variaciones a los datos que se envían en las peticiones con respecto a cantidad de usuarios vs tiempo de petición, tanto en la misma transacción como en una nueva.

Asegúrate de comprender:

* Cómo se estructura un test plan.
* Dónde se indican las variables de prueba (hilos y tiempos).
  
### Requerimientos

Con lo trabajado en el work, ya hemos hecho la grabación y ejecución de un escenario de prueba, en este paso vamos a interactuar con los datos enviados para las peticiones de prueba con las siguientes indicaciones:

* Ejecutar con 20 hilos (usuarios) la transacción con intervalos de 2 segundos la petición. Luego de la ejecución de la prueba de carga con 20 usuarios simultáneos revisamos el árbol de resultados donde vemos la cantidad de pasos exitosos vs. fallidos que resultaron, si no hay fallidos el sistema está soportando satisfactoriamente la cantidad de usuarios.
* Ejecutar con 30 hilos (usuarios) la transacción con intervalos de 1 segundos la petición. Luego de la ejecución de la prueba de carga con 30 usuarios simultáneos revisamos el árbol de resultados donde vemos la cantidad de pasos exitosos vs. fallidos que resultaron, si no hay fallidos el sistema está soportando satisfactoriamente la cantidad de usuarios, de lo contrario vamos revisando cuantos pasos fallidos resultaron y vamos comparando qué cantidad soporta el sistema.
* Ejecutar con 100 hilos (usuarios) la transacción con intervalos de 2 segundos la petición. Luego de la ejecución de la prueba de carga con 100 usuarios simultáneos revisamos el árbol de resultados donde vemos la cantidad de pasos exitosos vs. fallidos que resultaron, si no hay fallidos el sistema está soportando satisfactoriamente la cantidad de usuarios, de lo contrario vamos revisando cuantos pasos fallidos resultaron y vamos comparando qué cantidad soporta el sistema. Ahora, si en alguno de los 2 pasos anteriores hubo muchos pasos fallidos este va a ser muy probable que ocurra con mayor cantidad.

### Resultados

Video: [video](https://drive.google.com/uc?export=download&id=1f7FjZ5d0Llartl--lVLX1ZYcdT5Nr0oa)

Archivo de configuración: [jmx file](j)

## Licencia
Distribuido bajo la licencia GNU. Consulte `LICENCE` para obtener más información.

##### Equipo 2