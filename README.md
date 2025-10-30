📄 Instrucciones de Integración: Proyecto Concesionario
URL del Repositorio: https://github.com/AndresPytho/Proyecto-Concecionario-.git
Fase 1: Clonar el Proyecto
Utiliza la terminal de Git (Git Bash) para descargar la copia local:
1.	Ubicación: Abre la terminal y sitúate en la carpeta donde guardas tus proyectos (ej: cd ~/Documents/NetBeansProjects).
2.	Comando de Clonación: Ejecuta la siguiente línea:
Bash
git clone https://github.com/AndresPytho/Proyecto-Concecionario-.git
3.	Acceso: Cuando el sistema te pida credenciales, usa tu Username y tu Token de Acceso Personal de GitHub para autenticar.
Fase 2: Configurar en NetBeans
Una vez que la carpeta se haya descargado, ábrela en el IDE:
•	Abre NetBeans y ve a File (Archivo) > Open Project... (Abrir Proyecto...).
•	Selecciona la carpeta Proyecto-Concecionario- recién creada y haz clic en Abrir.
Fase 3: Flujo de Trabajo (Regla de Oro)
Para evitar conflictos de código, siempre sigue estos pasos:
1.	Al iniciar: Descarga cualquier cambio reciente del equipo:
Bash
git pull origin main
2.	Al finalizar: Guarda tu trabajo y compártelo:
o	git commit -am "Mensaje describiendo los cambios"
o	git push origin main

