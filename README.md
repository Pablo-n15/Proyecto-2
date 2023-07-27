# Descripción

Este proyecto trata sobre el sistema de creacion de cuenta de la aplicacion mobile OLX.
El objetivo de este proyecto es mostrar mis habilidades en el analisis, diseño y ejecución de pruebas manuales.

La historia de usuario fue tomada del proyecto open source UPEX en el cual tuve participacion.

Cada una de las pruebas que se veran aqui fueron diseñadas por mi.

* [Criterios de aceptación]()
* [Casos de prueba]()
  

## Historia de usuario
  
![](https://github.com/Pablo-n15/Proyecto-2/blob/main/USER%20STORY.jpg)


## Criterios de Aceptación

<details>
<summary>
<b>Scenario 1:</b> Usuario crea una cuenta con opcion "Mobile email" desde el startp exitosamente.
</summary>
<br>
  <h4><b>WHEN</b> Usuario selecciona un país.</h4>
  <h5><b>And</b> Selecciona o ingresa un email de cuenta no registrada con la opción "mobile email" para continuar manualmente.</h5>
  <b>And</b> Autentica el email atraves de un envio de codigo al emaul usado.
  <b>And</b> Crea una contraseña de usuario.
  <b>And</b> Selecciona una localidad (por geolocalización o agrega manualmente).
  <b>THEN</b> Usuario entra al Homepage de la App como usuario registrado.
  <b>And</b> Tiene acceso a todas las opciones de la App como usuario registrado.
  <b>And</b> En el tab "MI CUENTA" se habilita el proceso de "Completar mi cuenta" (si se omitieron los pasos de completar cuenta).
</details>
