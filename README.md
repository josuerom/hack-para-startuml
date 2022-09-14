![Image text](https://img.freepik.com/premium-photo/hacker-without-face-hood-dark_295303-1506.jpg?w=2000)
# Hack Avanzado para tener StartUML Totalmente Gratis - Aquí te enseño como.

Buen día! cordial saludo estimada/o. El presente documento contiene información muy valiosa para tener el programa **StartUML** totalmente gratis sin tener que gastar ni un sólo peso colombiano en su licencia de **$99** dólares USD. Cabe mencionar, que acá no se hace uso de *cracks, activadores o programas de terceros,* se hace uso del propio código fuente del programa, además, no tiendo a compartir esta información con nadie (nada más que yo quiera intercambiar conocimentos).

Para empezar, quiero explicar brevemente **qué es StartUML.**

En pocas palabras, es una herramienta que permite la construcción de muchos tipos de diagramas como de (Casos de uso, Entidad relación, Secuencias, Actividades, UML, Flujo, etc), para el ámbito de sistemas o carreras afines; lo desarrolló ***UML de MKLab*.** Este software tenía licencia bajo una versión modificada de GNU GPL hasta el año 2014, cuando se lanzó la versión 2.0.0 le agregaron una licencia propietaria de $ pago. Posteriormente, hoy en día es una de las herramientas más utilizada por los profesionales, programadores, diseñadores y estudiantes de todo tipo.

Ahora bien, le he hallado su vulnerabilidad ya que gran parte de el está escrito en JavaScript. Quiero presentarle las herramientas que debe descargar inmediatamente.

1. Nodejs —→ [Descarga | Node.js (nodejs.org)](https://nodejs.org/es/download/current/)
2. Editor de código —→ (Sublime Text, VS Code, Atom o Notepad++), *OJO: por ningun motivo se te ocurra utilizar el Bloc de Notas.*

Una vez tengas esas herramientas instaladas, podrás continuar con los pasos siguientes:

1. Abra el *Símbolo del Sistema,* ejecutela como administrador.

Copie y pegue los siguientes comandos (uno por uno):

1. cd C:\Program Files\StarUML\resources
2. npm install -g asar
3. asar extract app.asar app

Luego de eso, abra su *Explorador de Archivos,* y diríjase a la siguiente ruta —→ **C:\Program Files\StarUML\resources\app\src\engine** cuando esté allí verá 14 archivos con extensión .js (JavaScript). Deberás editar dos de ellos, el primero es el que tiene el nombre **license-manager** (muy lógico ¿No?).

Abrelo con el editor que gustes, aunque recomiendo VS Code. Posteriormente, debes comentar la línea número **139.** Para comentarla sólo debes agregar estos dos carácteres **//** al inicio de la línea que indiqué anteriomente, y de paso debes sólo modificar el segundo argumento de la línea superior número **138.** Donde dice **true** debes poner **false**. Después, guarda el cambio con **Ctrl + S.** Cuando lo intentes te saldrá un mensaje que te exige que debes ejecutar el editor como administrador ya que ese archivo necesita privilegios de super usuario.

A continuación, abra el archivo con el nombre **update-manager.** En el se deben de comentar las líneas número **36, 37, 38, 46, 47, 48, 51, 52, 53 y la 72.** Guarde los cambios del archivo y cierre el editor.

Por último, abra el *Explorador de Archivo,*  posiciónese en la siguiente ruta —→ **C:\Program Files\StarUML\resources** cuando esté allí verá varios archivos pero fíjese en el que se llama **app.asar** (ojo no la carpeta) el cual debe renombrar a **appJR3.asar**

Abra nuevamente el *Símbolo del Sistema**,*** corralo como administrador, y ejecute los únicos dos comandos siguientes (uno por uno):

1. cd C:\Program Files\StarUML\resources
2. asar pack app app.asar

**!LISTO YA LO TIENES¡** *Ahora puedes abrir el programa y verificar si aún tienes la versión* **UNREGISTERED** por defecto.

**Autor: Josué JR3**

**Contacto: josueromram@outlook.es**

**Fecha de publicación: Lunes 12 de Septiembre de 2022**

©️ Está rotundamente prohibido compartir este documento sin mi previa autorización.
