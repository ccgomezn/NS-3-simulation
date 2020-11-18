# NS-3-simulation

Este proyecto tiene como objetiva la simulación de un sistema de redes Ad-Hoc de dos jerarquias y la optimización del mismo por medio de la tecnica Q-table de aprendizaje por refuerzo, teniendo como objetivo de optimización la cantidad de paquetes recibidos de un nodo a otro, y como variable a manipular, la ubicación de los nodos de segunda jerarquia en la simulación.


## Documentos del proyecto

En el proyecto encontrara los archivos program.cc y agent.py, el primero define la simulación y el segundo el agente inteligente en python, si desea correr estos archivos en NS-3 muevalos a la carpeta Scratch y ejecute el comandos ./waf –run program en la carpeta base de NS-3 y el comando python3 agent.py en la carpeta Scratch.

## Resultados del entrenamiento

El entrenamiento se ejecuto en tres ambientes distinos obteniendo los siguientes resultados, donde la maxima recompensa que puede alcanzar el agente es 20:

1. clusters con distancia de 1000 mts:
![Alt text](results/first_train.png?raw=true "Resultado de primer entrenamiento")

2. clusters con distancia de 1000 mts y potencia de red reducida:
![Alt text](results/second_train.png?raw=true "Resultado de segundo entrenamiento")

3. clusters con distancia de 2000 mts entre cluster 1 y 2, y 1000 mts entre cluster 2 y 3, y potencia de red reducida:
![Alt text](results/third_train.png?raw=true "Resultado de tercer entrenamiento")
