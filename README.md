# trabajoswing1
FUNDAMENTOS DE PROGRAMACIÓN I I Trabajo Java Swing

Curso 2022/2023 1

Clases, objetos y métodos

Deseamos crear un programa que nos permita simular la gestión de los contendores que llegan
al puerto de Valencia.

En el puerto de Valencia los barcos mercantes descargan contenedores que se almacenan en
hubs de 10 filas y 12 columnas tal y como indica la figura.

Hub de contenedores

La información asociada a un contenedor es la siguiente:
  - Número identificador del contenedor (int).
  - Peso del contenedor (int).
  - País de procedencia.
  - Si ha sido inspeccionado por el control de aduanas o no.
  - Prioridad (1,2,3).
  - Descripción del contenido (cadena de máximo 100 caracteres).
  - Nombre de la empresa que envía el contenedor (cadena máximo 20 caracteres).
  - Nombre de la empresa que recibe el contenedor (cadena máximo 20 caracteres).
El hub se organiza de la siguiente forma: la primera columna se dedica a apilar los
contenedores de prioridad 1, la segunda columna a almacenar los contenedores de proridad 2
y el resto de las columnas de dedica a almacenar los contenedores de prioridad 3.

Para que el programa sea plenamente operativo, debe implementarse, al menos, lo que se
indica a continuación:
  - Definición de las clases necesarias. (HECHO/Diego)
  - Constructores necesarios para cada una de las clases. (HECHO/Diego)
  - getters y setters. (HECHO/Diego)
  - Método toString que devuelva un plano del hub.(HECHO/Alberto)
  - Método para apilar un contendor en el hub atendiendo a su prioridad. (HECHO/Diego,Alberto)
  - Método para desapilar un contenedor del hub de una columna concreta. (HECHO/Alberto)
  - Método para mostrar todos los datos de un contendor a partir de su número de identificación. Si dicho contenedor no está en el hub, se indicará mediante un mensaje. (HECHO/Marcos)
  - Método para calcular la cantidad de contenedores procedentes de un determinado país. (HECHO/Marcos)


NOTA: Todas las clases se almacenarán en un paquete llamado PaqNombre_de_tu_grupo
(por ejemplo, PaqC01) y habrá que decidir la visibilidad de los métodos y atributos de las
clases
