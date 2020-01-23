# Taller 01 #
## Infraestructura como código ##

## Objetivos: ##

- Comprender las motivaciones de la automatización de infraestructura.
- Realizar de forma autónoma el aprovisionamiento automático de infraestructura.
- Diagnosticar y ejecutar de forma autónoma las acciones necesarias para lograr infraestructuras estables.

# Escenario 01

Con el fin de probar una aplicación web, se requiere montar un servidor con CentOS 8.1 y el servidor web NGINX.

## Pre Requisitos
- [virtualBox](https://www.virtualbox.org/)

## Actividades.
1. descargue la imagen [ISO de CentOS](https://wiki.centos.org/Download)
2. cree una máquina virtual en virtualbox e Instale CentOS en ella. ([Instalación estándar de centOS](https://docs.centos.org/en-US/8-docs/standard-install/))
3. Acceda a la máquina CentOS e [instale NGINX](https://www.cyberciti.biz/faq/how-to-install-and-use-nginx-on-centos-8/)
4. configure en VirtualBox una [red solo anfitrión](https://condor.depaul.edu/glancast/443class/docs/vbox_host-only_setup.html) que le permita acceder a Nginx desde la máquina local.

## Entregable
un documento en formato MarkDown (se suguiere el nombre Escenario01.MD) que contenga:
1. Nombres completos y códigos de los estudiantes.
2. Documentación y evidencias de la realización de cada una de las actividades propuestas.
3. Dificultades encontradas en el proceso.
4. Escriba en máximo 3 párrafos por qué esta forma de crear ambiente de pruebas puede ser apropiado (o inapropiado) para desplegar réplicas de este ambiente de pruebas.