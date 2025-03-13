# Preguntas Orientadoras

## Tabla de Contenido
|Contenido|
|--|
|[Qué es un Computador?](#qué-es-un-computador)|
|[Arquitectura de Computador](#arquitectura-de-computador)|
|[Qué es el Hardware?](#qué-es-el-hardware)|
|[Qué es el Software](#qué-es-el-software)|
|[Funcionamiento del Computador](#funcionamiento-del-computador)|
|[Bibliografia](#bibliografia)|


### Qué es un computador?
Un computador es un dispositivo electronico que está compuesto por un software y un hardware. El Hardware son las partes físicas del computador, que hacen que funcione. Tiene varias partes como la CPU que es el procesador y es por así decirlo el corazón del computador. La RAM que se encarga de guardar de manera temporal archivos. El disco duro que es el que guarda toda la información que uno quiera guardar. Tambien algunos disositivos cuentan con una GPU, que es el procesador de gráficos aparte de los graficos integrados que pueda tener la CPU, para así lograr un mayor rendimiento. 

El software es la parte digital del computador. Existen varios tipos de sistemas perativos como: Mac OS, Linux o Windows. Otros tipos de software son los programas como juegos, Office o Adobe. 

Todo esto junto es lo que hace posible poder tener un computaodr como lo conocemos, capaz de realizar desde las tareas más complicadas hasta las más faciles. [1]

### Arquitectura de Computador
#### Arquitectura CISC
La Arquitectura informática con conjunto de instruccines complejo (CISC), es un tipo de diseño de procesador que incluye una gran cantidad de instrucciones complejas que es capaz de realizar multiples operaciones internas desde una sola instrucción. Este tipo de arquitectura permite que los algoritmos se ejecuten en menos instrucciones a comparacion de RISC. [2]
#### Arquitectura RISC
Esta arquitectura se basa en instrucciones simples y altamente personalizados. Esta arquitectura hace por cada ciclo de instrucción se da solo un ciclo de reloj. Y los ciclos deben de contener: buscar, decodificar y ejecutar. Otra caracteristica de este diseño es que requiere menos material, por lo que es más economico y rapido de fabricar. [3]

### Qué es el Hardware?
El hardware de un computador son todos los componentes materiales que integran una computadora y pueden ser elementos eléctricos, electrónicos y/o electromecánicos. [4]

#### CPU (Unidad Central de Procesamiento)
La CPU es el componente más importante de cualquier computador, ya qué es el encargado de ejecutar e interpretar instrucciones. También se encarga del procesamiento de datos y de qué el resto de componentes funcionen de forma optima.

    - ALU (Unidad Aritmético-Lógica): Está encargado de realizar operaciones aritméticas y lógicas. Y tiene como función hacer calculos matemáticos y logicos para ejecutar programas.

    - Unidad de Control: Este componente coordina todas las operaciones dentro de la CPU. Y tiene cómo función interpretar lo que los programas le piden y así gestionar el flujo de datos entre el procesador y tambien el acceso a la memorio y otros dispositivos.

    - Registros: Se encargan de almacenar dentro de la CPU de manera temporal, instrucciones y datos en proceso.

    - Buses: los buses son canales de comunicación dentro de la CPU y otros componentes. Tiene como función transportar datos (Bus de Datos), direcciones de memoria para localizar datos e instrucciones (Bus de direcciones), y administrar señales de control para coordinar operaciones (Bus de control).

#### Memoria
La memoria es el componente que se encarga de almacenar datos e instrucciones para su procesamiento.\

    - Registros: Son las unidades de almacenamiento más rapidas que hay en la CPU. y tienen como función almacenar datos de manera temporal mientras que otras instrucciones se ejecutan. Y son fundamentales para cálculos y alamacenamiento de direcciones de memoria.

    - Memoria Caché: Esta es un tipo de memoria que esta entre la CPU y la RAM, la cuál es de alta velocidad. Y tiene como función alamacenar de manera temporal datos e instrucciones utilizados con frecuencia, para así mejorar el rendimiento del sistema. 
     
    - Memoria (RAM): Es la memoria principal, lo que significa que es donde se cargan los programas y datos que se estén ejecutando. y tiene como función dar un acceso rápido a la información del sistema y se borra esta información cuando se apaga el equipo.

    - Memoria secundaria: La memoria secundaria son dispositivos que almacenan datos en todo momento. Exiten dos tipos: Disco Duro (HDD) y Unidad de Estado Solido (SSD), se encargan de almacenar el sistema operativo, archivos y programas. Y el otro tipo son USB o tarjetas SD, que son dispositivos que sirven para almacenar estas mismas cosas pero de forma portatil.

    - Dispositivos de entrada/salida: Estos son los dispositivos que nosotros como usuarios utilizamos para el uso del computador. Los dispositivos de entrada son aquellos que ingresan información al sistema, como: teclado, mouse, cámaras. Y los dispositivos de salida, son los que permiten ver y escuchar las cosas que el sistema procesa, como: monitores, altavoces, etc. 

    - Buses de Datos: Estos buses son los encargados de transportar la información dentro del sistema y a su vez permita la transferencia de datos entre otros componentes como CPU, memoria, etc. Como ya antes dicho, existen varios tipos de buses/ Los buses de datos mueven la información entre los componentes. Los buses de direcciones, se encarga de dar direcciones de memoria para localizar datos o instrucciones. Y los buses de control, que son los que sincronizan y controlan los dispositivos.

[5]

### Qué es el Software?
El software es lo contrario del hardware, ya que este no es tangible. El software esta compuesto por muchas cosas como aplicaciones para cumplir muchas funciones. El software es lo que hace las instrucciones para el hardware y así poder funcionar de la manera más eficiente. Existen 3 tipos de software: 

    - Software de sistema: Son programas que le permiten al usuario tener ciertos controles sobre el hardware del computador.

    - Software de aplicación: Son los programas que sirven para hacer varias cosas al tiempo, como: juegos.

    - Software de desarrollo: Son los programas que le permiten al usuario desarrollar programas con un lenguaje de programación en especifico, como Visual Studio Code.

[6]

### Funcionamiento del Computador

#### ¿Qué procesos se llevan a cabo cuando se enciende una computadora?
Cuando se inicia un computador pasan muchos procesos. Primero la fuente alimentación pasará corriente a todos los componentes del equipo. Después se ejcuta la BIOS, que es donde se configuran las cosas esenciales, ahí se carga un gestor de arranque, que es el encargado de iniciar el sistema operativo. El sistema operativo se carga en la memoria RAM y ahí se comienzan a ejecutar los controladores y algunos procesos básicos.

#### ¿Qué sucede desde que ingreso un dato a través del teclado, hasta que veo el resultado de la operación en la pantalla?
Cuando se presiona una tecla, se envia una señal a la CPU a traves del bus de datos en forma de codigo binario. Una vez la CPU recibe el codigo, este la decodifica y puede acceder a la memoria RAM, de ser necesario para información adicional. Y la unidad de control es la que gestiona que la operación solicitada se ejecute. La salida de los datos es. Una vez esta procesada esta información en la CPu, se envia a la memoria RAM y luego a la tarjeta gráfica y esta la convierte en señal de video, apareciendo así en la pantalla.

#### ¿Cómo se codifican los datos internamente en el computador?
Los datos internos de los computadores es el código binario y se codifican mediante: Sistemas binarios, Codigo ASCII, Unicode o representación de números o colores.

[5]

#### ¿Cuáles son las unidades de medida de datos en un computador? Bit, Byte, etc.
| **Unidad**   | **Equivalencia**  | **Ejemplo de uso**  |
|-------------|------------------|--------------------|
| **Bit (b)**  | 0 o 1 | Unidad mínima de información. |
| **Byte (B)**  | 8 bits | Representa un solo carácter. |
| **Kilobyte (KB)**  | 1024 Bytes | Pequeños archivos de texto. |
| **Megabyte (MB)**  | 1024 KB | Imágenes y documentos grandes. |
| **Gigabyte (GB)**  | 1024 MB | Videos, software y sistemas operativos. |
| **Terabyte (TB)**  | 1024 GB | Almacenamiento de discos duros. |
| **Petabyte (PB)**  | 1024 TB | Grandes centros de datos. |
| **Exabyte (EB)**  | 1024 PB | Infraestructura de almacenamiento global. |


[Volver al inicio](#preguntas-orientadoras)

### Bibliografía
[1] https://edu.gcfglobal.org/es/informatica-basica/que-es-un-computador/1/

[2] https://www.sciencedirect.com/topics/computer-science/complex-instruction-set-computer-architecture

[3] https://www.profesionalreview.com/2021/07/18/risc-vs-cisc/#:~:text=Qu%C3%A9%20es%20RISC,-Es%20una%20arquitectura&text=La%20arquitectura%20RISC%20tiene%20la,combinan%20con%20otras%20m%C3%A1s%20simples.

[4] https://cs.uns.edu.ar/materias/iocp/downloads/Clases%20Teoricas/Clase-01-Conceptos-basicos-Hardware.pdf

[5] https://chatgpt.com/c/67a38ab7-9c5c-8009-bb64-336afa2d2056

[6] https://concepto.de/software/

