# cyber_lab_gazebo

Università di Verona

[Corso di Robotica - Homework2]
AA 2017/2018<br>
Studente: [Moreno Bragaglio]

## Istruzioni

1. Recarsi nella cartella di tale progetto ed eseguire il file setup.sh tramite il comando: <br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; ./setup.sh 

2. In un nuovo terminale lanciare in seguito i comandi: <br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; export TURTLEBOT3_MODEL=waffle <br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; roslaunch turtlebot3_gazebo turtlebot3_homework2.launch

3. In un nuovo terminale lanciare in seguito i comandi: <br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; export TURTLEBOT3_MODEL=waffle <br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; roslaunch turtlebot3_navigation turtlebot3_navigation.launch map_file:=$HOME/map.yaml

4. In un nuovo terminale lanciare in seguito i comandi: <br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; export TURTLEBOT3_MODEL=waffle <br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; rosrun rviz rviz -d `rospack find turtlebot3_navigation`/rviz/turtlebot3_nav.rviz

5. Nella finestra di Rviz cliccare il tasto "2D Pose Estimate" e cliccare un punto della mappa per scegliere il punto di inizio percorso che dovrà percorrere il robot (solitamente cliccare il robot stesso per far cominciare il percorso da dove si trova)

6. Nella finestra di Rviz cliccare il tasto "2D Nav Goal" e cliccare un punto della mappa per scegliere il punto di destinazione del percorso che dovrà percorrere il robot

## Autori
Moreno Bragaglio
