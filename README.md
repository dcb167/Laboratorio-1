# LABORATORIO I</br>
## Elaborado por: Laura Rodíguez y Diana Bernal

## 1. Conceptos
### 1.1 Definición de Booteable y GRUB
+ Un Booteable es una especie de aplicación, por la cual, es posible llevar un Sistema Operativo en una USB de arranque [1].
+ GRUB se le conoce como el gestor de arranque , el cual, vuelve más sencillo el proceso de inicialización del hardware y la carga de componentes del software [2].
### 1.2 Definición de los Sistemas de Archivos Compatibles y sus Tipos
+ Se le conoce como un sistema de almacenamiento de un dispositivo de memoria, el cual, organiza la escritura, búsqueda, lectura, almacenamiento, edición y eliminación de archivos [3].</br>
Algunos de sus tipos son:</br>
+ FAT32: Formato Antiguo de Microsoft. </br> 
+ exFAT: Diseñado para dispositivos de memoria flash.</br> 
+ NTFS: Se utiliza en las versiones modernas de Windows</br>
+ HFS+: Organiza archivos y directorios en una estructura de árbol jerárquica</br>  
+ APFS: Es el sistema de archivos nativo de Apple</br> 
+ Ext2, ext3 y ext4</br>
### 1.3 Definición de las Estructuras de Particiones y sus Tipos
+ Las estructuras de particiones son aquellas en las que un disco duro fisico se divide en segmentos logicos, existen dos particones.[4]
+ MBR (Master Bood Record) Se usa para equipos o estructuras mas antiguas que se usa con el firmware BIOS
+ GPT (GUID Partition Table) Se usan para estructuras mas avanzadas.
+ Existen tres tipos de particiones. [5]
+ Partición primaria: son las divisiones básicas de un disco y se usan para instalar el sistema operativo. Tiene un límite de 4 particiones en el MBR.
+ Extendida: esta da solución al límite de particiones de la primaria y actua como un contenedor.
+ Lógica: son subdivisiones creadas dentro de las particiones extendidas. contienen diferentes tipos de sistemas de archivos y se pueden almacenar archivos personales. 

## 2. Explicación del proceso en Ventoy 
<img width="1767" height="539" alt="image" src="https://github.com/user-attachments/assets/57c1c15c-0299-4761-8e99-611560049135" /> 

<strong>Figura 1.</strong> Ingreso aL a la web y selecciono el link para para windows.

+ Se descarga Ventoy y se descomprime, luego se ejecuta como administrador.

<img width="795" height="455" alt="image" src="https://github.com/user-attachments/assets/e4f0a189-79d3-4f9d-bb8e-d25704afd913" />

<strong>Figura 2.</strong> Se eleige la memoria a la que se le va a descargar el Ventoy.
+ Seleccionamos el arranque seguro y GPT (Para equipos mas avanzados) y luego, le damos click en instalar.

<img width="417" height="116" alt="image" src="https://github.com/user-attachments/assets/91fdd7dc-b0aa-4d8e-98a5-ac6e4156274f" /> 

<strong>Figura 3.</strong> Se inician a borrar las particiones y alista la memoria para empezar a usarla con Ventoy.

<img width="362" height="139" alt="image" src="https://github.com/user-attachments/assets/24874820-6d45-403b-913a-80e5b50a95cc" />

<strong>Figura 4.</strong> Ventoy ya se instalo correctamente en la memoria.
  
<img width="781" height="311" alt="image" src="https://github.com/user-attachments/assets/99a58c7d-ec7a-43e9-8f02-da2c21eacf9c" />

<strong>Figura 5.</strong> Para colocar los sistemas operativos (S.O), solo se copian y se pegan en la memoria.

## 3. Explicación del proceso en Rufus

![WhatsApp Image 2025-09-01 at 11 29 21 PM](https://github.com/user-attachments/assets/fff9ad5b-c424-438b-9253-9d51ab52cb74)</br>

<strong>Figura 6.</strong> Ingreso al link de descarga de Rufus.

![WhatsApp Image 2025-09-01 at 11 29 30 PM](https://github.com/user-attachments/assets/37207c6d-d8dd-4eb9-b517-d963de489991)</br>

<strong>Figura 7.</strong> Selección del link de descarga de Rufus.

![WhatsApp Image 2025-09-01 at 11 29 40 PM](https://github.com/user-attachments/assets/e6893c38-d4b4-40c9-90d3-ebcff6264da8)</br>

<strong>Figura 8.</strong> Selección de la memoria en donde se desea descargar la ISO de Ubuntu.

![WhatsApp Image 2025-09-01 at 11 29 50 PM](https://github.com/user-attachments/assets/164333c1-c0f0-41c8-adc4-5f11ac820932)</br>

<strong>Figura 9.</strong> Selección del link de la ISO de Ubuntu.

![WhatsApp Image 2025-09-01 at 11 30 00 PM](https://github.com/user-attachments/assets/dd7f1971-8d98-46f8-be21-32e7532cb384)</br>

<strong>Figura 10.</strong> Visualización de que la ISO ha sido descargada en la memoria con éxito.

Lo último a realizar, es entrar a la BIOS del ordenador y seleccionar que el arranque sea por medio de USB para poder acceder al nuevo S.O Ubuntu.

## Referencias
[1] 	Anónimo, «USB booteable: qué es y los 14 mejores programas para Windows, Linux y macOS,» 23 Agosto 2019. [En línea]. Available: https://www.xataka.com/basics/usb-booteable-que-mejores-programas-para-windows-linux-macos.</br>

[2] 	M. Aleksic, «¿Qué es el gestor de arranque GRUB en Linux?,» 7 Septiembre 2023. [En línea]. Available: https://phoenixnap.com/kb/what-is-grub. [Último acceso: 1 Septiembre 2025].</br>

[3] 	Anónimo, «Sistemas de archivos: qué son y cuáles son los más importantes,» 11 Agosto 2020. [En línea]. Available: https://www.ionos.com/es-us/digitalguide/servidores/know-how/sistemas-de-archivos/. [Último acceso: 1 Septiembre 2025].</br>

[4]. GeeksforGeeks. (2025, 23 julio). Partitioning Scheme: MBR and GPT in OS. GeeksforGeeks. https://www.geeksforgeeks.org/operating-systems/partitioning-scheme-mbr-and-gpt-in-os/ 

[5]. Sevivon Studio. (2020, 21 marzo). Particiones primarias, lógicas y extendidas [Vídeo]. YouTube. https://www.youtube.com/watch?v=CSbUiK2pytE





