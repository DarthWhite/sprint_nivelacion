Proyecto Nivelación MisionTic 

Usar el template para crear un repositorio propio, completar el proyecto y verificar que las pruebas de widget e integración funcione

Para la prueba de integración se asume que hay un usuario creado a@a.com con clave 123456

Recordar que la prueba de integración se corre con:   

flutter drive --driver test_driver/integration_test.dart --target integration_test/app_test.dart

Este proyecto trabaja las funcionalidades de Firestore y autenticación de Firebase, hay que agregar el google-services.json y habilitar esos servicios en el firebase console. Ver: https://drive.google.com/file/d/1qPSQkVIiUy6Iv9OfwAC_dTRLvEDPz4pp/view?usp=sharing   

Pista: Revisar los comentarios TODO   


<img src="firebase.gif" width="300" />

Buen dia,

El proyecto de nivelacion fue realizado por los alumnos SMITH FERRER y LORENA ROCHA del curso 1263 acontinuacion dejamos todos los link con respecto a los videos y repositorios

Video de Prueba de Aplicacion
https://drive.google.com/file/d/1UpE0MepX6uxhTCQZbcu_4kq6Gph5uabG/view?usp=sharing

Video prueba de Widget e Integracion
https://drive.google.com/file/d/1DBwbsWH4Lq08BLT8IujMGnr2a6FsThMo/view?usp=sharing

GitHub Proyecto final para Demo de Aplicacion
https://github.com/DarthWhite/sprint_nivelacion

GitHub Proyecto final para pruebas de widget por la web
https://github.com/DarthWhite/nivelacionciclo4moviltest

Proyectos cargados en google drive
https://drive.google.com/file/d/17yZC8N-6vYYK-soyTh4S1FJd2vyXwHZR/view?usp=sharing


Nota: este fue el comando para realizar el test de widget e integracion ya que con el que se menciona en las instrucciones arrojaba errores 

flutter drive --driver=test_driver/integration_test.dart --target=integration_test/app_test.dart -d web-server -d chrome --web-port=4444 --browser-name=chrome --no-headless

Agracedemos todo el apoyo prestado durante estos meses

Cordialmente

SMITH FERRER y LORENA ROCHA