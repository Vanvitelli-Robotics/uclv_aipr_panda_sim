# Simulatore Cinematico del Robot Panda

[![N|Solid](https://www.unicampania.it/doc/img/logo_vanvitelli.jpg)](https://www.ingegneria.unicampania.it/roboticslab)

Simulatore cinematico del robot Panda per il corso di Programmazione dei Robot.

## Install


- Installare i questo pacchetto e le dipendenze
Nella cartella src del ros workspace
```bash
git clone https://github.com/Vanvitelli-Robotics/uclv_aipr_panda_sim.git 
sudo apt update && rosdep install -r --from-paths . --ignore-src --rosdistro $ROS_DISTRO -y
```

## Avviare il simulatore

Avviare il simulatore con:
```bash
ros2 launch uclv_aipr_panda_sim demo.launch.py
```

Controllate i topic di comando e misura dalla rete ros
```bash
rqt_graph
```

## Esempio con CLIK e generatori di traiettoria

Un esempio di utilizzo con algoritmo CLIK e generatori di traiettoria è disponibile al seguente [link](https://github.com/Vanvitelli-Robotics/uclv_aipr_panda_clik_demo.git).

## License

GNU General Public License v3.0