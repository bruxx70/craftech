﻿# craftech-nginx
para ejecutar la prueba se necesitaria:
en la plataforma github setear sus credenciales de dockerhub. En caso contrario si necesitan les doy permisos como colaborador, pero no tengo mas minutos de uso para actions.
Esta implementacion es simlemente el CI, para el CD se deberia generar una conexion a su maquina que permita el eliminado de la imagen, y levantar de nuevo el docker compose up. 
A su vez sería mucho mejor generar una solución con ArgoCD con conexion directa a los repositorios que permita el delivery de la implementacion.
El motivo de uso de github action fue porque era uno de los requerimientos para el puesto, desde el punto de vista de organizacion de trabajo, me facilitaba el uso de la condicion paths para obtener cada cambio del index.html y a su vez no necesito configuraciones extras como jenkins.
Utilicé docker compose por facilidad de uso en ambiente local.
