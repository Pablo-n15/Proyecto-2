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
<b>Scenario 1:</b> Usuario crea una cuenta con opcion "Mobile email" desde el startup exitosamente.
</summary>
<br>
 <em> <b>WHEN</b> Usuario selecciona un país. <br>
  <b>And</b> Selecciona o ingresa un email de cuenta no registrada con la opción "mobile email" para continuar manualmente.<br>
  <b>And</b> Autentica el email atraves de un envio de codigo al emaul usado. <br>
  <b>And</b> Crea una contraseña de usuario. <br>
  <b>And</b> Selecciona una localidad (por geolocalización o agrega manualmente). <br>
  <b>THEN</b> Usuario entra al Homepage de la App como usuario registrado. <br>
  <b>And</b> Tiene acceso a todas las opciones de la App como usuario registrado. <br>
  <b>And</b> En el tab "MI CUENTA" se habilita el proceso de "Completar mi cuenta" (si se omitieron los pasos de completar cuenta).
</details></em>

<details>
<summary>
<b>Scenario 2:</b> Usuario crea una cuenta con opcion "Google" desde el startup exitosamente.
</summary>
<br> <em>
    <b>WHEN</b> Usario selecciona un país. <br>
    <b>And</b> Selecciona un email de cuenta NO REGISTRADA con la opción "Google" para continuar automático. <br>
    And Selecciona una localidad (por geolocalización o agrega manualmente).<br>
    <b>THEN</b> Usuario entra al Homepage de la App como usuario registrado. <br>
    <b>And</b> Tiene acceso a todas las opciones de la App como usuario registrado. <br>
    <b>And</b> En el tab "MI CUENTA" se habilita el proceso de "Completar mi cuenta" (si se omitieron los pasos de completar cuenta).
</details> </em>

<details>
<summary>
<b>Scenario 3:</b> Usuario crea una cuenta con opcion "Facebook" desde el startup exitosamente.
</summary>
<br> <em>
<b>WHEN</b> Usuario selecciona un país. <br>
<b>And</b> Selecciona un email de cuenta NO REGISTRADA con la opción "Facebook" para continuar automático.<br>
<b>And</b> Acepta los permisos de la Web/App de Facebook.<br>
<b>And</b> Selecciona una localidad (por geolocalización o agrega manualmente).<br>
<b></b> Usuario entra al Homepage de la App como usuario registrado.<br>
<b></b> Tiene acceso a todas las opciones de la App como usuario registrado.<br>
<b></b> En el tab "MI CUENTA" se habilita el proceso de "Completar mi cuenta" (si se omitieron los pasos de completar cuenta).
</details> </em>

<details>
<summary>
<b>Scenario 4:</b> Usuario omite la creacion de cuenta desde el startup de la APP.
</summary>
<br> <em>
<b>WHEN</b> Usuario selecciona un país. <br>
<b>And</b> Selecciona o ingresa un email de cuenta NO REGISTRADA con la opción "mobile email" para continuar manualmente. <br>
<b>And</b> Hace click sobre la fecla superior izquierda para vovler atras (En la pantalla de seleccionar Email). <br>
<b>And</b> Usuario regresa y salta automaticamente a la pantalla de selección de localidad. <br>
<b>THEN</b> Usuario entra al Homepage de la App como usuario NO REGISTRADO.<br>
<b>And</b> NO tiene acceso a todas las opciones de la App por no tener cuenta activa. <br>
<b>And</b> En el Tab "MI CUENTA" el perfil aparece sin estado activo: con la opcion de iniciar sesion o registrarse.
</details> </em>


