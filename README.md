# LABORATORIO DOCKER COMPOSE

pasos para ejecutar proyecto

1. construye las imagenes basado en el contenido de la carpeta py1/ py2/ py3/, entras a cada carpeta y ejecutaras el siguiente comando en cada una 

py1: '''
    docker build -t img1 .
     '''
py2: '''
    docker build -t img2 .
     '''
py3: '''
    docker build -t img3 .
     '''

2. despues retrocederas a la carpeta DockerMain/ y ejecutaras el siguiente comando
    '''
    docker-compose up
    '''