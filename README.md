# Kobo-Nickel-Menu-Configuration
### My perssonal Kobo &amp; Nickel Menu configuration

Recientemente compre un lector Kobo y lo primero que quise hacer fue ver si podia agregarle atajos y configuraciones que me facilitaran algunas cosas. 

Sigo experiemtando pero dentro de lo destacado está quitar el logo de Gandhi al encenderlo, ver estadisticas de libros ya terminados, capacidad de exportar notas, instalar Nickel Menu y activar los archivos compartidos con Google Docs y Dropox.

## Archivo Kobo ereader
  Conceta tu Kobo y dirigete a la carpeta oculta /.kobo/Kobo busca el archivo Kobo ereader.

  Edita las caracteristicas del archivo, aqui algunas de las opciones de configuración https://wiki.mobileread.com/wiki/Kobo_Configuration_Options
  
  Mucho de lo que yo usé como guie se encuentra en este blog https://kobo.lectoreselectronicos.com/subweb/configuracion.html

  Mis modificaciones personales pueden verse dentro de del archivo con el mismo nombre en este repositorio

## Eliminar el logo al encender
  Al encender el sispositivo aparece durannte unos segundos el logo de la librería en donde lo compre. No queria que apareciera así que descibri que puedes eliminarlo al camiviar el nombre de la variable afiliado.
  
  En la carpata /.kobo abre el archivo afilite y remplaza el texto por:

    [General]
    affiliate=Kobo
  
## Configuración de Nickel menu
  Nickel menu es un menu de opciones adicinales que ya se encuentran dentro del frimware de Kobo pero no son tan accesibles o estan ocultas. Es como un acceso directo o un atajo.
  
  Para inastalar Nickel menu sigan las instrucciones para agregar Nickel Menu https://pgaskin.net/NickelMenu/

  Una vez instalado dirigete a la carpeta oculta /.adds/nm y crea un archivo de texto (no importa el nombre ni extensión)
  En ese nueve archivo puedes configurar el menu a tu conveniencia pero dejo el mio.
  
  NOTA: yo edite el icono y nombre de mi menu así que tienes que agregar un archivo png llamado ".icon.png" en esa misma carpeta

### Menu principal
Dentro de mis atajos principales añadi:

La opcion de apagar y reiniciar (para no tener que usar los botones)

Un atajo a las estadisticas.

Un atajo a un juego que se encuentra al activar el modo desarrollador

Activar el modo Screanshots (al activar este modo las Screanshots se toman al presionar el boton de apagado, tienes que desactivarlo para poder volver a usar ese boton).

<img width="300" height=auto alt="screen_001" src="https://github.com/user-attachments/assets/e44baa85-0b6f-403f-8e89-0a1e2968e9d6" />

### Menu de lectura
Estando dentro de la lectura añadi: 

La opcion de activar el modo oscuro

Activar el Modo Screnshots

<img width="300" height=auto alt="screen_002" src="https://github.com/user-attachments/assets/06131105-2809-4fb0-9230-859277be9cad" />
<img width="300" height=auto alt="screen_003" src="https://github.com/user-attachments/assets/f2dc0cbe-d929-4cd7-9942-a98bad3d4be8" />


### Menu de biblioteca
Dentro del menú de la biblioteca añadi la opcion de concectarme por Drive y DopBox.

Kobo Libra Coulor tinene Drive y DropBox dentro de su configuracion por Default, sin embarog esta no esta en Kobo Libra 2. Para poder activarla es necesario hacer unas modificaciones dentro del archivo /.kobo/Kobo/Kobo ereader.

<img width="300" height=auto alt="screen_004" src="https://github.com/user-attachments/assets/a5ae2cc3-1aa8-417f-b497-71de7e21d480" />
<img width="300" height=auto alt="screen_005" src="https://github.com/user-attachments/assets/c85c73e3-bb0d-4e95-928d-c718863ba6a2" />

