# Evaluación de los IDEs

## Instalación de entornos de desarrollo propietarios y libres

### Diferencias proceso instalación IDE propietario vs libre

Para realizar a cabo este proyecto he decidido instalarme los siguientes IDEs:

- Propietario: IntelliJ IDEA (Jetbrains)

Este es el IDE de pago por excelencia para Java y Kotlin el cual nos ofrece gran cantidad de funcionalidades que veremos más adelante. 

Se puede descargar a través del siguiente enlace: 

[Enlace Descarga IntelliJ IDEA](https://www.jetbrains.com/idea/)

- Libre: Visual Studio Code (Microsoft)

Antes de empezar, cabe destacar que aunque sea un editor de texto en sí mismo, a través de la implementación de plugins y herramientras propias de un IDE como compiladores, intérpretes o debuggueadores realmente es considerado por muchos como un IDE debido a la versatilidad que éste nos aporta.

Se puede descargar a través del siguiente enlace:

[Enlace Descarga VSC](https://code.visualstudio.com/)

Para evidenciar las diferencias, he documentado los pasos principales con capturas de pantalla para ambos entornos:

#### **Visual Studio Code**

Antes de empezar la instalación tenemos que aceptar el acuerdo de condiciones y políticas de privacidad, por lo tanto es recomendable leérselo con el fin de saber que estamos aceptando al utilizar este IDE. Aunque os adelanto que e acuerdo de licencia es sencillo puesto que únicamente requiere aceptar la licencia MIT, con enlaces al proyecto Open Source de Microsoft.

![Imagen 1 VSC](./assets/images/VSC-1.png)

Asimismo, la instalación es ligera, rápida y con requisitos mínimos (434 MB). Se instala fácilmente en la carpeta del usuario (`AppData\Local\Programs\Microsoft VS Code`) siempre que no deseemos cambiarla.

![Imagen 2 VSC](./assets/images/VSC-2.png)

También nos permite seleccionar tareas adicionales como crear accesos directos y registrar el editor en el PATH, muy útil para desarrolladores.

![Imagen 3 VSC](./assets/images/VSC-3.png)

Una vez instalado, en el primer arranque ya podemos apreciar como la interfaz inicial es minimalista y accesible, mostrando directamente las funciones básicas.

![Imagen 4 VSC](./assets/images/VSC-4.png)

#### **IntelliJ IDEA**
En este caso el proceso de instalación es más guiado, con recomendaciones iniciales para asegurar una instalación profesional (por ejemplo, cerrar otras aplicaciones).

![Imagen 1 IntelliJ IDEA](./assets/images/INTELLIJIDEA-1.png
)
De la misma forma nos pide seleccionar carpeta de instalación en `Program Files`, y requiere mucho más espacio (4.7 GB), lo que indica herramientas integradas y mayor robustez.

![Imagen 2 IntelliJ IDEA](./assets/images/INTELLIJIDEA-2.png)

Asimismo, permite configurar asociaciones específicas para archivos de programación (.java, .gradle...), orientado a proyectos avanzados.

![Imagen 3 IntelliJ IDEA](./assets/images/INTELLIJIDEA-3.png)
Finalmente, la pantalla final es más formal, con opción de iniciar automáticamente el IDE y una bienvenida guiada. Incluso ofrece tutorial onboarding para nuevos usuarios.

![Imagen 4 IntelliJ IDEA](./assets/images/INTELLIJIDEA-4.png)

Una vez iniciado, la pantalla inicial se ve aún más profesional que la de Visual Studio Code, como se muestra a continuación:

![Imagen 5 IntelliJ IDEA](./assets/images/INTELLIJIDEA-5.png)

**Conclusión comparativa**

- **VS Code**, como entorno libre, destaca por la agilidad y sencillez del proceso, accesible para cualquier usuario, sin trabas ni requerimientos avanzados.
- **IntelliJ IDEA**, entorno propietario, sobresale por el enfoque profesional, la customización y la robustez del proceso, aunque requiere más recursos y pasos.


### ¿Qué ventajas identificaste en cada uno de los entornos durante la instalación?

### **Visual Studio Code**

- **Agilidad del proceso**: Instalación muy rápida y ligera, que requiere pocos recursos y espacio en disco. En menos de un minuto está listo para usar, lo que facilita el acceso incluso en equipos con hardware limitado.
- **Simplicidad y claridad**: Todo el proceso es intuitivo y directo, sin pasos innecesarios ni requisitos de registro, pago o verificación por licencia.
- **Personalización inicial**: Permite desde el primer momento elegir opciones como la creación de accesos directos, asociación de archivos y registro en el PATH, lo que resulta muy útil para desarrolladores que buscan comodidad y versatilidad en el uso diario.
- **Accesibilidad**: No necesita datos personales ni información privada para poder instalarlo puesto que el usuario es totalmente independiente, lo que lo convierte en una solución flexible y segura.
- **Interfaz minimalista y abierta**: En el primer arranque, la interfaz es clara y moderna, lista para empezar a trabajar o personalizarla con plugins/extensiones según las necesidades del usuario.

### **IntelliJ IDEA**

- **Instalación guiada y profesional**: Desde el inicio, el asistente de instalación ofrece recomendaciones y opciones pensadas para desarrolladores avanzados (como cerrar aplicaciones activas para evitar conflictos). Ya tan solo por esos mínimos detalles el proceso se percibe más profesional y detallado.
- **Opciones avanzadas de configuración**: Permite elegir asociaciones de tipos de archivo (.java, .gradle...) y añadir utilidades al menú contextual, lo que facilita el trabajo con proyectos de gran escala y diferentes tecnologías.
- **Robustez y potencia**: El requerimiento de espacio (4.7 GB) anticipa la cantidad de herramientas profesionales ya incluidas, lo que ahorra tiempo en configuraciones posteriores.
- **Experiencia integral para el usuario**: La pantalla final incluye directamente la opción de iniciar el IDE y realizar un tour guiado, favoreciendo el aprendizaje para nuevos usuarios.
- **Preparación para desarrollo profesional**: Está pensado para grandes proyectos de ingeniería de software, lo que se nota en la profundidad de sus opciones y el entorno de trabajo altamente especializado.

## Gestión de módulos y extensiones en el entorno de desarrollo

### Visual Studio Code

En Visual Studio Code he decidido instalarme el plugin de Pylint.
La instalación del plugin **Pylint** ha aportado una mejora radical a mi flujo de trabajo con Python puesto que me ayuda a detectar errores y problemas de estilo en tiempo real, lo que me permite anticipar y corregir fallos antes de ejecutar el código, resultando fundamental para garantizar la calidad, legibilidad y coherencia del proyecto desde el primer momento.

Además, gracias a la gestión intuitiva de extensiones, puedo añadir funcionalidades específicas según las necesidades del proyecto. Por ejemplo, combinando Pylint con otras extensiones como **Prettier** para formatear el código automáticamente, consiguiendo que el desarrollo en Visual Studio Code sea mucho más eficiente y profesional.

*Ejemplo formateo Prettier*

![Ejemplo Prettier](./assets/images/projectB.gif)

En definitiva, **Visual Studio Code destaca por la facilidad y rapidez para instalar cualquier plugin**, permitiendo personalizar el entorno según las necesidades concretas de cada proyecto y perfil de desarrollador.

El proceso de instalación en Visual Studio Code es muy sencillo, puesto que si accedemos al apartado de Extensiones (Plugins) desde la barra lateral nos redirigirá automáticamente al apartado en donde podemos descargarnos las extensiones deseadas, como se muestra a continuación:

![Barra Lateral Extensiones](./assets/images/VSC-barralateral.png) 

Una vez en el apartado de extensiones procedemos a buscar la extensión según nuestros intereses, en este caso he optado por Pylint como se mencióno anterormente.

![Pylint VSC](./assets/images/pylint.png)

*Ejemplo de funcionamiento*

![Ejemplo Pylint](./assets/images/ejemplo_pylint.png)

Como podemos observar, esta extensión nos muestra advertencias y mensajes informativos que aunque no sean errores que corten el flujo del programa es de vital importancia solucionarlos para mayor profesionalidad.

### IntelliJ IDEA
### IntelliJ IDEA

En IntelliJ IDEA he decidido que la mejor extensión que me podía instalar es la que da soporte a Kotlin puesto que más adelante en el curso trabajaremos con este excelente lenguaje de programación sucedáneo del lenguaje orientado a objetos por excelencia Java.

En este caso, para proceder a la instalación de extensiones desde el propio IDE también es muy sencillo puesto que desde la pantalla de inicio en la barra lateral podemos observar una opción que nos redirige directamente al apartado de la instalación de los plugins o extensiones, como se observa a continuación:

![Barra Lateral Plugins](./assets/images/IntelliJ%20IDEA_barralateral.png)

Una vez dentro, buscamos la extensión de nuestra preferencia, en este caso Kotlin, la cual nos aporta un soporte avanzado para el lenguaje, facilitándonos el desarrollo de software.

La instalación del **plugin de Kotlin** transforma IntelliJ IDEA en un entorno robusto y preparado para el desarrollo con este lenguaje. El soporte avanzado incluye autocompletado inteligente, refactorización guiada, integración con sistemas de dependencias y testeo simplificado. Esto facilita el desarrollo de aplicaciones modernas, acortando los tiempos de búsqueda, configuración y resolución de problemas durante la programación.

*Ejemplo integración de Git en IntelliJ IDEA*

![GitToolBox](./assets/images/git-create-repo-dialog.png)

IntelliJ IDEA sobresale, además, por la profundidad y calidad de sus plugins. Por ejemplo, al añadir **GitToolBox** consigo información de control de versiones directamente integrada en el editor, acelerando las tareas de colaboración y gestión de código fuente.

**Comparación final**
Instalar y utilizar extensiones es sencillo en ambos IDE, pero Visual Studio Code sobresale por la flexibilidad y rapidez para ampliar funcionalidades, mientras que IntelliJ IDEA destaca por la profundidad y calidad de los módulos que incorpora, ideal para proyectos avanzados y exigentes.

## Personalización y automatización del entorno 

### Visual Studio Code

Para empezar, con el objetivo de reducir mi fatiga visual durante sesiones largas de trabajo me instalé la extensión One Dark Pro haciéndome más agradable la experiencia y mejorando mi concentración.

*Antes*

![One Dark Pro Antes](./assets/images/antesdarkpro.png)

*Después*

![One Dark Pro Después](./assets/images/onedarkpro.png) 

Seguidamente, he ajustado algunos atajos de teclado desde el propio Visual Studio Code con el fin de facilitar y agilizar el trabajo. 

1. Abrir Terminal `(Ctrl + T)`
   ![Atajo Teclado Terminal](./assets/images/terminaltoggle.png)
   ![Ejemplo Terminal](./assets/images/ejemploterminal.png)
2. Duplicar línea `(Shift + ↓)` 
    ![Atajo Teclado Copiar Línea Hacia Abajo](./assets/images/copylinedown.png)
    ![Ejemplo Duplicar Línea](./assets/images/ejemploduplicarlinea.png)
3. Ver previsualización de un archivo Markdown con la extensión de *Markdown Preview Enhancer* (`Ctrl + Shift + V`)
    ![Previsualización Markdown](./assets/images/markdownpreview.png)
    *Imagen de ejemplo*
    ![Ejemplo Markdown](./assets/images/ejemplomarkdown.png)
4. Eliminar Línea (`Ctrl + K`)
   ![Atajo Teclado Eliminar Línea](./assets/images/eliminarlinea.png)
5. Edición Múltiple (`Ctrl + D`)
    ![Atajo Teclado Selección Múltiple](./assets/images/seleccionmultiple.png)
    ![Ejemplo Selección Múltiple](./assets/images/ejemploseleccionmultiple.png)
6. Buscar en un archivo (`Ctrl + F`)
    ![Atajo Teclado Buscar en Archivos](./assets/images/buscarenarchivos.png)
    ![Ejemplo Búsqueda](./assets/images/ejemplobusqueda.png)

Gracias a la personalización avanzada del entorno, especialmente con la configuración de atajos de teclado para acciones críticas (como abrir terminal, duplicar línea, edición múltiple y previsualización Markdown), mi productividad ha mejorado notablemente. Puedo trabajar sin distracciones, minimizando el uso del ratón y automatizando tareas frecuentes. Al adaptar Visual Studio Code a mis necesidades reales de flujo de trabajo, reduzco errores, ahorro tiempo en tareas repetitivas y dedico mi energía a la lógica y creatividad en el desarrollo.

Respecto a la parte de automatización de tareas he configurado con la extensión **Code Runner** la compilación y ejecucción de mi código en cuestón de segundos a través del atajo de teclado (`Shift + Space`) como se muestra a continuación:

![Code Runner](./assets/images/coderunner.png)
![Ejemplo Code Runner](./assets/images/ejemplocoderunner.png)

Por ejemplo, al implementar una función nueva, fui validando al instante cada modificación con un solo atajo, detectando errores inmediatamente y acelerando el ciclo de prueba y error.

### IntelliJ IDEA