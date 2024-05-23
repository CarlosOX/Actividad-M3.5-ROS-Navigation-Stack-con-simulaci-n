# Proyecto de Navegación Autónoma del PuzzleBot

Este proyecto es una colaboración entre los siguientes estudiantes de la Universidad:

- **Salvador Santana Blanco**            A01703523
- **Anatanael Jesus Miranda Faustino**  A01769232
- **Diego Díaz Ayala**            A01770236
- **Carlos Eduardo Ortega**        A01707480


*Profesor: Juan Manuel Ledesma Rangel*

## Descripción del Proyecto

Este proyecto tiene como objetivo demostrar la capacidad del PuzzleBot para navegar de manera autónoma en un entorno simulado, evitando obstáculos y alcanzando una meta específica. La navegación se realiza utilizando ROS (Robot Operating System), Gazebo y RViz.

## Instrucciones para Ejecutar la Simulación

### Preparación del Entorno

1. **Clona el repositorio del proyecto:**
   ```bash
   git clone https://github.com/tu-equipo/nombre-del-repo.git
   cd nombre-del-repo

2. **Configura el entorno de ROS:**
   ```bash
   source /opt/ros/noetic/setup.bash
   source ~/catkin_ws/devel/setup.bash


3. **Compila el workspace:**
   ```bash
   cd ~/catkin_ws
   catkin_make

### Ejecución de la simulación

1. **Lanzar el entorno simulado en Gazebo:**
   ```bash
   roslaunch puzzlebot_gazebo puzzlebotwithlidar.launch

2. **Ejecutar el nodo de transformaciones:**
   ```bash
   rosrun puzzlebot_gazebo transforms.py

3. **Ejecutar el nodo de localización:**
   ```bash
   rosrun puzzlebot_gazebo localisation.py




