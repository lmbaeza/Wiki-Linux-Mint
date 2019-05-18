# Wiki Sobre Linux Mint

### Historia:


Linux mint fue desarrollado y lanzado a finales del 2006 por **Clement Lefebvre** en Francia.

Mint es una distribución GNU/Linux basada en los sistemas operativos **Debian** y **Ubuntu** con una alternativa *LMDE (Linux Mint Debian Edition)* Basada únicamente en Debian, las primeras versiones se lanzaron cada 6 meses aproximadamente hasta el 2008 que adoptó precisamente el mismo ciclo de lanzamientos que Ubuntu y eliminó su número de versiones menores antes del lanzamiento de la versión 5 “Elyssa”. Para aumentar la compatibilidad entre los 2 sistemas, Linux Mint tomó la decisión de abandonar su base de código y también cambió la forma en que construía sus lanzamientos. A partir de la versión 6, “Felicia”, cada versión ahora estaba usando completamente la última versión de Ubuntu, creada a partir de ella directamente y programada durante aproximadamente un mes después de la versión correspondiente de Ubuntu.

En 2010, Linux lanzó el LMDE independiente de otras ediciones basadas en Ubuntu, Linux Mint Debian Edition fue originalmente una versión de lanzamiento basada en Debian directamente y no estaba vinculada a los paquetes de Ubuntu o incluso a su calendario de Lanzamiento. En Mayo de 2015, el equipo de Linux Mint decidió que ya no era compatible con la versión de lanzamiento rodante originalmente de Linux Mint Debian Edition después de enero de 2016. La nueva versión de LMDE se llamó LMDE 2 “Betsy”, después de este lanzamiento todos los usuarios podían actualizarse automáticamente a las nuevas versiones de software MintTools y los nuevos entornos de escritorio incluso antes de que fueran lanzados a la edición principal de Linux Mint.

### Equipo

* **Clement Lefebvre - "Clem"** <img src="https://linuxmint.com/img/flags/png-country-4x2-fancy/res-40x30/fr.png" width="20"/>
<br/>Lider del Proyecto global y equipo de desarrollo. <br/>
<img src="https://blog.desdelinux.net/wp-content/uploads/2013/03/LXF166.feat_2013.clem-900-90-600x337.jpg" alt="Clement Lefebvre - 'Clem'" width="300"/>

* **Vincent Vermeulen** <img src="https://linuxmint.com/img/flags/png-country-4x2-fancy/res-40x30/nl.png" width="20"/><br/>
Lider del equipos de administración y moderación.<br/>

* **Oscar799** <img src="https://linuxmint.com/img/flags/png-country-4x2-fancy/res-40x30/gb.png" width="20"/><br/>
Lider del equipos de administración y moderación.<br/>

### Instalación
...
...
...

### Gestor de Paquetes
* **apt - Advanced Package Tool = apt-get + apt-cache**

Apt es un conjunto de herramientas para la gestión de paquetes de Debian también Usada en Ubuntu, ya que este depende de Debian. Esta herramienta de línea de comandos se utiliza para una integración fácil con el sistema de empaquetado dpkg que fué el primer gestor de paquetes de Debian.
	 	 	
Apt es la forma más eficiente y preferida por los administradores de software desde la línea de comandos para las distribuciones Linux basadas en Debian.

	 	 	
Apt realiza instalaciones, búsquedas de paquetes, actualizaciones y muchas otras operaciones a paquetes disponibles para su sistema. Mantener los paquetes actualizados es extremadamente importante, ya que el uso de paquetes desactualizados puede llevar a problemas de seguridad en sus sistema.

* **dpkg**

Dpkg (Debian Package) es un software de gestión de paquetes de Debian que se utiliza para instalar, eliminar paquetes .deb, en sí mismo esta es una herramienta de bajo nivel a diferencia de apt que es de más alto nivel y que internamente utiliza a dpkg. Dpkg se controla completamente a través de los parámetros de la línea de comando, que consiste en exactamente una acción y cero o más opciones. Los parámetros le indica a dpkg que debe hacer y las opciones controlan el comportamiento de la acción de alguna manera.

### Ventajas y Desventajas de usar Linux Mint

* **Ventajas**
    * Linux Mint prioriza la Elegancia y Facilidad de uso.
    * Es una distribución muy ligera.
    * Trata de ser una interfaz amigable para los usuario que vienen de windows.
    * Mucha documentación porque toda la documentación de Ubuntu es compatible con Linux Mint
    * Muy bueno para la transición de los principiantes en linux.
    * Goza de muy buena popularidad en el último tiempo.

* **Desventajas**
    * ...

### Estructura

| Caracteristica        | Valor           |
| :------------ |:--------------|
| **Modelo de Desarrollo** | Software libre y de código abierto |
| **Versión del Kernel** | kernel Linux 4.15 |
| **Lanzamiento inicial** | 27 de agosto de 2006 |
| **Última versión estable** | 19 "Tara" 29 de junio de 2018 |
| **Tipo de núcleo** | Monolítico |
| **Interfaz gráfica predeterminada** | MATE, Cinnamon, XFCE |
| **Plataformas admitidas** | x86-64, x86 y IA-32 |
| **Sistema de gestión de paquetes** | dpkg |
| **Método de actualización** | APT |
| **Licencia** | GPL |

### Instalación:

Puede descargarse el Sistema Operativo Linux Mint de manera gratuita. Este sistema viene en un archivo ISO que necesita ser grabado en un DVD vacío o USB. El LiveDVD es entonces booteable (capaz de correr y arrancar un equipo) y provee un sistema operativo completamente funcional el cual puede probar sin afectar su PC. En términos simples, cuando ponga Linux Mint en un DVD y lo ponga en su computadora, lo puede probar sin afectar sus sistema operativo actual.

#### Descargar el ISO


El archivo que necesita descargar es una fichero ISO para grabarla en un DVD o USB. Hay dos maneras de descargar este archivo, por la página oficial [Download](https://linuxmint.com/download.php). Una vez que su descarga haya finalizado, puede asegurarse de que su archivo ISO no esté corrupto revisado su firma con el MD5.

#### Iniciar desde el LiveDVD

Ponga el DVD en el lector y reinicia el computador, debería ver la siguiente pantalla:

![Linux Mint - Instalación](https://i.ibb.co/xjfCVxx/01-Instalar-Linux-Mint.png)


Si no ve esta pantalla y su computadora inicia normalmente, probablemente se deba a que su BIOS no está programada para iniciar desde un DVD. Reinicie el computador y presione F1, F2, Suprimir o Escape (o la que sea la tecla que le permite entrar a la configuración de la BIOS) y cambie la configuración de la BIOS para instruir a su computadora que inicie desde la unidad de DVD.

#### Instalar Linux Mint en su Disco Duro
Desde la pantalla de inicio, elija la opción por defecto “Start Linux Mint” (“Iniciar Linux Mint”) y presione «Enter».

![Linux Mint - Instalación](https://i.ibb.co/4Tznz5P/02-Instalar-Linux-Mint-17-1.png)

Si experimenta problemas y el sistema no consigue iniciar, intente con la opción “Start Linux Mint in Compatibility Mode” (Iniciar Linux Mint en Modo de Compatibilidad”) desde el menú de arranque.

Después de un momento, el sistema debería cargar el DVD y se le presentará el escritorio:

En este punto, Linux Mint no está instalado en su computadora, sólo está corriendo desde el DVD, el sistema que tiene en frente suyo, sin embargo, es casi exactamente igual al que tendrá en su computadora cuando la instalación haya terminado.
Diviértase con él, explore y vea si le gusta. Tenga en mente que cuando se ejecuta desde el DVD Linux Mint es significativamente más lento que cuando lo hace al ser instalado en un disco duro, esto se debe a que tiene que leer datos desde la unidad de DVD, que es un medio más lento que el disco Duro.
Cuando esté listo, haga doble-click en el icono del escritorio que pone “Install Linux Mint” (“Instalar Linux Mint”).

![Linux Mint - Instalación](https://i.ibb.co/5YpLTXr/03-Linux-Mint-Language.png)

Elija el lenguaje que quiere utilizar y presione el botón “Continuar”.

En la siguiente pantalla, asegúrese de esta conectado a una fuente de alimentación (si está utilizando un ordenador portátil), que esté conectado a Internet y de que tenga suficiente espacio en el disco para instalar el sistema. Una vez verificado, presiones el botón “Continuar”: 

![Linux Mint - Instalación](https://i.ibb.co/M8T5dmN/04-Tipo.png)

En la pantalla que le sigue, usted puede asignarle todo su disco a Linux Mint o instalarlo junto con otros sistemas operativos, del mismo modo (aunque de manera alternativa), usted puede, así mismo, decidir particionar y asignar su disco de forma manual.

* Si usted decide utilizar el disco completo, su contenido será borrado y Linux Mint será instalado como el único sistema operativo en su computadora. En esta opción le permite añadir las opciones de: 

    * Cifrar las particiones en la que se va instalar Linux Mint.
    * Usar LVM la nueva instalación de Linux Mint.

* Si escoge instalarlo junto a otros sistemas operativos, el instalador utilizará el espacio vacío en otras particiones para crear una nueva partición para instalar Linux Mint. Se le preguntará cuánto espacio quiere asignar a Linux Mint, seguido de lo cual, el instalador encogera una partición y asignará el espacio automáticamente. Después de la instalación, su computadora le mostrará una pantalla en la que podrá decidir qué sistema operativo iniciar. 

* Si escoge especificar las particiones manualmente, un editor de particiones aparecerá, dándole control total sobre el particionamiento de su disco. Esto es recomendado sólo para usuarios avanzados que entienden cómo funciona el particionamiento bajo Linux. Es importante tener en cuenta que Linux Mint requiere una partición de al menos 9GB y que el espacio recomendado para el SWAP es de al menos 1.5 veces la cantidad de RAM que posee la computadora.

Elija la opción que mejor satisfaga sus necesidades y luego haga click en “Continuar”:

![Linux Mint - Instalación](https://i.ibb.co/vhJHhtc/05-Particiones.png)

La siguiente pantalla le pide confirmar. Cuando esté listo, presione el botón “instalar Ahora” para comenzar la instalación.
En este punto, la instalación está ocurriendo de forma desatendida mientras el instalador le pregunta sus datos:

![Linux Mint - Instalación](https://i.ibb.co/sR3yCbL/06-Zona-Horaria.png)

Escoja su ubicación en el mapa al hacer click en la ciudad que está más cerca suyo, el propósito de esto es identificar su “Zona de Tiempo”. Asegúrese de que la fecha que aparece es correcta y presione “Continuar”.

![Linux Mint - Instalación](https://i.ibb.co/zhWq1JJ/07-Teclado.png)

Ahora es tiempo de seleccionar su distribución de teclado. Si no está seguro respecto al cuál es exactamente, puede seleccionar una opción tentadora y luego utilizar la casilla de texto que hay en el fondo para comenzar a escribir y verificar que todas las teclas funcionan correctamente. Algunas distribuciones de teclado varían sólo con respecto a los acentos, números y signos de puntuación, así que asegúrese de probar estas funciones también.

Cuando esté listo, presione “Continuar”.

Introduzca su nombre real, su nombre de usuario y una contraseña, cada vez que inicie Linux Mint usted utilizará su cuenta con este nombre de usuario y contraseña. Una vez Linux Mint esté instalado usted podrá definir otras cuentas, en caso de que más personas vayan a utilizar esa computadora.

![Linux Mint - Instalación](https://i.ibb.co/pyWRzBJ/08-Usuario.png)

El instalador tal vez detecte otros sistemas operativos en su computadora y le pregunte si quiere migrar parte de su información personal. Por lo general, esto le permite migrar marcadores, favoritos, contactos y otras clases de información personal de los otros sistemas operativos que tenga instalados en su computadora hacia su nueva instalación de Linux Mint. Cuando esté listo, haga click en el botón de “Adelante”. 

![Linux Mint - Instalación](https://i.ibb.co/NTPvv5q/09-Inicio.png)

La instalación debería durar 10 y 15 minutos.

Un vez haya terminado la instalación presione el botón de “Reiniciar Ahora” y el entorno de LiveDVD se apagará.
Cuando se le pida, saque el DVD de la unidad, cierre la unidad y presiones «Enter».
Su computadora ahora está lista para Iniciar Linux Mint desde el disco duro.



### Bibliografía

...