![Image text](https://img.freepik.com/premium-photo/hacker-without-face-hood-dark_295303-1506.jpg?w=2000)
# Hack Avanzado para tener StartUML Totalmente Gratis - Aquí te enseño como.

Hola! cordial saludo estimada/o. El presente documento contiene una información muy valiosa para tener el programa **StartUML** totalmente gratis sin tener que gastar ni un sólo peso colombiano en su licencia de **$99** dólares USD. Cabe mencionar, que acá no se hace uso de *cracks o activadores,* se hace uso del código fuente del propio programa, además, no tiendo a compartir está información con nadie (nada más que yo quiera intercambiar conocimentos).

Para empezar, quiero explicar brevemente **¿Qué es StarUML?**

Es una herramienta que permite la construcción de muchos tipos de diagramas para el ámbito de Sistemas o afines; lo desarrolló ***UML de MKLab*.** Este software tenía licencia bajo una versión modificada de GNU GPL hasta el año 2014, cuando se lanzó la versión 2.0.0 le agregaron una licencia propietaria de $ pago. Posteriormente, hoy en día es una de las herramientas más utilizada por los profesionales, programadores, diseñadores y estudiantes de todo tipo.

Ahora bien, presento las herramientas que debes descargar inmediatamente.

1. Nodejs —→ [Descarga | Node.js (nodejs.org)](https://nodejs.org/es/download/current/)
2. Editor de código —→ (Sublime Text, VS Code, Atom o Notepad++), *OJO: por ningun motivo se te ocurra utilizar el Bloc de Notas.*

Una vez tengas esas herramientas instaladas en tu computador, podrás continuar con los siguientes pasos:

1. Abra el Símbolo del Sistema, ejecutela como administrador.

Copie y pegue los siguientes comandos (uno por uno):

1. cd C:\Program Files\StarUML\resources
2. npm install -g asar
3. asar extract app.asar app

Luego de eso, abra su *Explorador de Archivos,* y diríjase a la siguiente ruta —→ **C:\Program Files\StarUML\resources\app\src\engine** cuando esté allí verá 14 archivos con extension .js (JavaScript). Deberás editar dos de ellos, el primero es el que tiene el nombre **license-manager** (muy lógico !No¡).

Abrelo con el editor que gustes, aunque recomiento que uses VS Code. Posteriormente, debes comentar la línea número **139.** Para comentarla sólo debes agregar estos dos carácteres **//** al inicio de la línea que indiqué anteriomente, y de paso debes sólo modificar el segundo argumento de la línea superior número **138.** Donde dice **true** debes poner **false**. Después, guarda el cambio con **Ctrl + S.** Cuando lo intentes te saldrá un mensaje, el que te exige que debes ejecutar el editor como administrador ya que ese archivo necesita privilegios de super usuario.

A continuación, abra el otro archivo que tiene el nombre **update-manager.** En el se deben de comentar las líneas número **36, 37, 38, 46, 47, 48, 51, 52, 53 y la 72.** Guarde los cambios del archivo y cierre el editor.

Por último, posiciónese en la siguiente ruta —→ **C:\Program Files\StarUML\resources** cuando esté allí verá un archivo con el nombre **app.asar** (ojo no la carpeta) el cual debe renombrar a **appJR3.asar**

Abra nuevamente el *Símbolo del Sistema**,*** corrala como administrador, y ejecute los únicos dos comandos siguientes (uno por uno):

1. cd C:\Program Files\StarUML\resources
2. asar pack app app.asar

**!LISTO YA LO TIENES¡** *Ahora puedes abrir el programa y verificar si aún tienes la versión por defecto* **UNREGISTERED**.

**Autor: Josué JR3**

**Correo: josueromram@outlook.es**

**Fecha de publicación: Martes 30 de Agosto de 2022**

**Sitio oficial:** https://blush-cirrus-df9.notion.site/Hack-Avanzado-para-tener-StartUML-Totalmente-Gratis-Aqu-te-ense-o-como-b41b775fec214fcd8d675db933cabd15

©️ Está rotundamente prohibido compartir este documento sin mi previa autorización.
