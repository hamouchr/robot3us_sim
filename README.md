## robot3us_sim

### Lancement avec le bb8

1. Lancer le simulateur Gazebo : par exemple BB8, empty world

2. Créer une instance du robot 3 ultrasonics (robot3us) : roslaunch robot3us_sim spawn_robot.launch

3. Visualiser le robot dans rviz : roslaunch robot3us_sim rviz.launch

### Lancement avec un monde séparé

Utiliser les scripts .sh se trouvant dans le dossier scripts ( à copier à la racine de votre compte)

#### avec le monde world1 
./run_robot_in_world.sh world1

#### avec le monde world2 
./run_robot_in_world.sh world2

#### avec le monde world3 
./run_robot_in_world.sh world3

### Possibilité de chargeer le monde seul sans le robot

Par exemple : ./load_world.sh world1

### crééer une instance du robot dans un monde préalablement chargé

./spawn_robot.sh



