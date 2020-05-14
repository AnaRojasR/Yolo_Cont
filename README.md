# Yolo_Cont
 
 Instalación de Yolo en Linux

Requisitos:

OpenCV versión >= 3.4: Este es entre muchos fue el tutorial que me sirvió  https://www.pytorials.com/how-to-install-opencv340-on-ubuntu1604/

gcc: siga los siguientes comandos
	 - sudo apt update
	 - sudo apt install build-essential  (tambien instala makefile)

	Comprueba con el siguiente comando:
	 - gcc --version

Compilar el proyecto:
	 - Abrir una terminal en la carpeta darknet-master y ejecutar el archivo Makefile con el siguiente comando:
	 	 -   make

Ejecutar YOLO con un video: escriba el siguiente comando,
	 - ./darknet detector demo cfg/coco.data cfg/yolov3.cfg yolov3.weights <video file>

	 	
