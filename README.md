# NOTAS
## 1. TÉRMINOS
### 1.1 Software
- Programas de ordenador, la documentación asociada y la configuración de datos que se necesita para hacer que estos programas operen de manera correcta.
- Programas digitales, conjunto de instrucciones o datos usados para decirle a la computadora que realizar.

### 1.2 Ingeniería de software
- Es una disciplina de ingeniería que comprende todos los aspectos de la producción de software desde las etapas iniciales de la especificación del sistema, pasando por la gestión de proyectos de software y el desarrollo de herramientas, métodos y teorías de apoyo a la producción de software hasta el mantenimiento de éste después de que se utiliza.
- Es una disciplina que aplica el uso de estructuras, herramientas y técnicas para la producción de software durante todo el ciclo del desarrollo del software.

### 1.3 Proceso de software
- Un conjunto de actividades y resultados asociados que produce un producto de software, cuya meta es el desarrollo o evolución del software.
- Conjunto de actividades para hacer un software.

### 1.4 Git:
- Es un software de control de versiones el cual rastrea el historial de cambios conforme las personas y los equipos colaboran juntos en los proyectos. Conforme los desarrolladores hacen cambios al proyecto, cualquier versión anterior de este puede recuperarse en cualquier momento.
- Es un software de control de versiones diseñado para guardar el rastro de la evolución del software con todos sus cambios.

### 1.5 Programación
- Es la actividad mediante la cual las personas le entregan a una computadora un conjunto de instrucciones (programas) para que, al ejecutarlas, ésta pueda resolver un problema.
- Es un conjunto de instrucciones que se le da a una computadora para realizar una tarea específica.

### 1.6 Lenguaje de programación
- Lenguaje artificial que se utiliza para expresar programas de ordenador.
- Es un lenguaje que permite a los programadores comunicarse con las máquinas.

### 1.7 Compilador
- Es un programa que toma como entrada un programa escrito en un lenguaje fuente y lo transforma en un programa escrito en lenguaje máquina. Puede realizarse de dos formas: por interpretación o por compilación
- Es el tradutor entre el lenguaje de programación que se usa y el lenguaje binario de la máquina.

## 2. CICLO DE VIDA/DESARROLLO DE SOFTWARE
### 2.1 Planificación
Se define cuál es le problema a tratar, posibles soluciones y el modo en el que se hará
### 2.2 Análisis
Se contemplan los recursos que se tienen y se plantea la mejor solución.
### 2.3 Diseño
Esquema de la mejor solución y organizar la arquitectura del software.
### 2.4 Implementación
Ejecutar la solución.
### 2.5 Prueba
Verificar que funcione el producto correctamente en los dispositivos que se vayan a utilizar.
### 2.6 Mantenimiento
Probar que siga vivo y en buen funcionamiento el código.

## 3. DOCUMENTO DE ESPECIFICACIÓN DE REQUISITOS DE SOFTWARE
### 3.1 INTRODUCCIÓN
Definir el próposito del documento y para quién va dirigido.

#### 3.1.1 Alcance:
Ennumeran los objetivos general y comerciales dle producto, así como lo beneficios.
#### 3.1.2 Valor:
Se presenta que beneficios se busca que el público encuentre en el producto.
#### 3.1.3 Público objetivo:
A quién esta destinado el producto.
#### 3.1.4 Uso previsto:
De que manera se espera que el público objetivo utilize el producto y con qué fin.
#### 3.1.5 Descripción general:
Un resumen de las funciones y características del producto, así como de los puntos antes mencionados.

## 4. COMANDOS
### 4.1 Git init
- Inicializa un repositorio nuevo de Git y comienza a supervisar el directorio existente. Este agrega una subcarpeta oculta dentro del directorio existente que hospeda la estructura de datos interna que se requiere para el control de versiones.
- Este comando crea un nuevo repositorio de Git.

### 4.2 Git config
- Es una función útil que sirve para definir valores de configuración de Git a nivel de un proyecto global o local. Estos niveles de configuración se corresponden con archivos de texto .gitconfig. Al ejecutar git config, se modificará un archivo de texto de configuración.
- Permite configurar y establecer algunos datos o valores (como el nombre y correo electrónico) que luego serán utilizados por otros comandos de Git.

### 4.3 Git add
- Almacena provisionalmente un cambio. Git rastrea los cambios que se hacen a la base de código de un desarrollador, pero es necesario probarlos y tomar una captura de pantalla de ellos para incluirla en el historial del proeycto. Este comando realiza pruebas, la primera parte de este proceso de dos pasos. Cualquier cambio que se pruebe, se convertirá en parte de la siguiente captura de pantalla y también del historial del proyecto. Las pruebas y confirmaciones por separado otorgan a los desarrolladores el control completo sobre el historial y sobre el proyecto sin cambiar la forma en la que codifican y trabajan.
- Se utiliza para subir/añadir un cambio a la rama.

### 4.4 Git commit
- Guarda la instantánea del historial del proyecto y completa el proceso de seguimiento de los cambios. En resumen, una confirmación funciona tal como el tomar una fotografía. Todo lo que se haya almacenado provisionalmente con git add pasará a formar parte de la instantánea con git commit.
- Se utiliza para comfirmar los cambios que añadiste previamente a la rama.

### 4.5 Git push
- Actualiza el repositorio remoto con las confirmaciones realizadas localmente en una rama.
- Este comando lleva los cambios confirmados hacia el repositorio y los sube/guarda.

### 4.6 Git pull
- Actualiza la línea de desarrollo local con actualizaciones de sus contrapartes remotas. Los desarrolladores utilizan este comando si un compañero de equipo hizo confirmaciones en una rama en un repositorio remoto y quieren reflejarlos en su ambiente local.
- Se utiliza para que los cambios que se hayan realizado en el repositorio remoto puedan ser actualizados en un ambiente local de un determinado dispositivo.

### 4.7 Git checkout
- En términos de Git, "checkout" (extraer) es el acto de cambiar entre diferentes versiones de una entidad objetivo. El comando git checkout opera sobre tres entidades distintas: archivos, confirmaciones y ramas. Este comando cambia entre ramas o restaura los archivos del árbol de trabajo.
- Este comando te permite volver a una versión anterior de un commit o momento en el tiempo del historial de las versiones de tu programa.

### 4.8 Git branch
- Muestra las ramas en las que se trabaja localmente.
- Al correr este comando se muestra una lista de los branches/ramas en las que se trabaja localmente.

### 4.9 Github
- GitHub hospeda repositorios de Git y proporciona a los desarrolladores las herramientas para generar un código mejor mediante características de línea de comandos, propuestas (debates en hilo), solicitudes de cambio, revisión de código, etc. Es una plataforma de desarrollo colaborativo que aloja proyectos en la nube utilizando el sistema de control de versiones llamado Git. Ayuda a los desarrolladores a almacenar y administrar el código llevando un registro de cambios.
- Es una plataforma de control de versiones que facilita la administración y almacenamiento de un código en un repositorio a través de un registro de cambios.

### 4.10 Github pages
- GitHub Pages es un servicio de alojamiento de sitio estático que toma archivos HTML, CSS y JavaScript directamente desde un repositorio en GitHub, opcionalmente ejecuta los archivos a través de un proceso de complilación y publica un sitio web.
- Es un servicio que permite a los usuarios de Github a alojar sitios web estáticos de manera gratuita y directamente desde sus repositorios.

### 4.11 Wiki
- Las wikis son parte de los repositorios Git, de manera que puedes hacer cambios localmente y subirlos a tu repositorio mediante un flujo de trabajo de Git. Cada repositorio en GitHub.com viene equipado con una sección para alojar documentación, llamada wiki. Puede utilizar la wiki de su repositorio para compartir contenido extenso sobre su proyecto, como cómo usarlo, cómo lo diseñó o sus principios básicos. Un archivo README indica rápidamente qué puede hacer su proyecto, mientras que puede usar una wiki para proporcionar documentación adicional.
- Es un espacio/sección dentro del repositorio para alojar, crear y editar documentación donde podrás proporcionar información adicional sobre el código y el proyecto en general.

## 5. EJEMPLO DE DOCUMENTO DE ESPECIFICACIÓN DE REQUISITOS DE SOFTWARE
### 5.1 INTRODUCCIÓN
#### 5.1.1 Alcance del producto:
- Objetivo general: Crear una página sencilla de accesos directos a sus mejores productos o servicios para 
- Objetivos Específicos:
    - Establecer las métricas a evaluar 
    - Componer los reportes de métricas
    - Componer su página estilo Linktree.
- Metas:
    - Una página web estilo Linktree
    - Reportes mensuales de las métricas de la página.

#### 5.1.2 Valor del producto
- Mayor alcance al público.
- Información detallada de sus productos y servicios, con fácil acceso al usuario.

#### 5.1.3 Público objetivo
Jóvenes y mujeres adultas entre 18 a 35 años que buscan una vida saludable.

#### 5.1.4 Uso previsto
El público objetivo tendrá mayor comodidad y fácil acceso a los productos que más les gusta comprar al cliente final.

## 6. DIAGRAMA DE GANTT

## 7. DISEÑO LINKTREE


