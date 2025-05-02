Manual: Cómo subir tu trabajo a GitHub usando ramas
Este manual te guiará paso a paso para subir tu trabajo a GitHub utilizando ramas. Las ramas son una herramienta fundamental en Git que te permite trabajar en nuevas funcionalidades o correcciones sin afectar directamente el código principal de tu proyecto.

1. Configuración inicial de Git
Antes de empezar a usar Git, debes identificarte ante el sistema. Esto permite que cada cambio registrado quede asociado a un nombre y correo electrónico. Esta configuración se realiza una sola vez en tu computadora.

Debes indicar tu nombre real o nombre de usuario, y una dirección de correo electrónico válida (preferiblemente la misma que usas en GitHub).

2. Crear un repositorio Git en tu proyecto local
Un repositorio es el espacio donde Git guarda el historial de tu proyecto. Para comenzar a trabajar con Git, debes convertir tu carpeta de proyecto en un repositorio. Esto permite que Git comience a rastrear los archivos, detectar cambios y guardar versiones del trabajo.

Una vez creado, se genera una carpeta oculta que Git utilizará para registrar toda la información interna.

3. Agregar archivos al repositorio y hacer el primer registro
Después de que tu carpeta está lista como repositorio, debes indicar qué archivos deseas que Git empiece a rastrear. Generalmente, se agregan todos los archivos relevantes del proyecto. Una vez seleccionados, se realiza un "commit", que es como tomar una fotografía del estado actual del proyecto, con una breve descripción.

Este primer commit es el punto de partida del historial de tu proyecto.

4. Crear una rama para trabajar
Las ramas en Git sirven para desarrollar nuevas ideas, funcionalidades o correcciones de errores sin interferir con el trabajo principal que suele estar en una rama llamada "main" o "master".

Cuando creas una nueva rama, estás haciendo una copia del estado actual del proyecto. A partir de ahí, puedes trabajar de forma independiente. Esto te da libertad para experimentar sin miedo a dañar el código original.

Puedes tener tantas ramas como necesites, cada una con un propósito específico: desarrollo, pruebas, nuevas ideas, etc.

5. Asociar tu proyecto local a un repositorio remoto en GitHub
Git funciona localmente, pero para compartir tu trabajo o colaborar con otras personas, debes conectar tu proyecto local a un repositorio en GitHub. GitHub es una plataforma en línea que permite alojar tus repositorios, colaborar con otros desarrolladores y tener respaldo de tus archivos.

Para hacer esto, necesitas copiar la dirección del repositorio que creaste en GitHub (puede estar en formato HTTPS o SSH). Luego le indicas a Git que ese repositorio remoto será el destino donde se subirán los cambios.

A partir de ese momento, tu proyecto local estará vinculado con GitHub.

6. Subir tu rama con los cambios al repositorio en GitHub
Después de trabajar en tu rama y realizar varios commits (cada uno representando un cambio o mejora), puedes subir todo ese historial al repositorio remoto. Esto permite que tus avances estén guardados en la nube y también disponibles para otras personas que trabajen contigo.

Además, si en algún momento pierdes tu computadora o tus archivos locales, tendrás una copia de respaldo segura en GitHub.

Al subir por primera vez una rama nueva, también la creas en GitHub.

7. Continuar trabajando desde tu rama
Una vez que tu rama está subida, puedes seguir trabajando en ella. Cada vez que realices un cambio importante, lo registras en un nuevo commit, y luego vuelves a subir la rama con los cambios actualizados.

Esto mantiene tu rama sincronizada entre tu equipo local y el repositorio remoto.

Trabajar desde una rama te permite desarrollar sin afectar el código principal, revisar tus propios avances y facilitar futuras integraciones.

8. Crear un Pull Request para integrar tu trabajo
Cuando tu trabajo en la rama esté completo y probado, el siguiente paso es unirlo con la rama principal del proyecto. Esto se hace a través de una solicitud de incorporación, conocida como Pull Request en GitHub.

Un pull request permite que otros revisen tu código antes de aceptarlo. Puedes usarlo tú mismo para revisar tus cambios, o compartirlo con compañeros para recibir retroalimentación.

Dentro del pull request puedes ver todos los archivos modificados, los comentarios de cada commit y una comparación con la rama original. Una vez aprobado, se puede fusionar (merge) y tu trabajo pasará a formar parte del proyecto principal.

