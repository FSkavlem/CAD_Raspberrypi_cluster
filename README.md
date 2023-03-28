# Raspberry Pi cluster
This raspberry pi cluster uses 80mm fans on each raspberry pi with 2x 120mm fans to move the air column horizontal. Fusion360 files located in folder.
The cluster was used to load Kubernetes on via K3s, OS run was raspberry pi lite 64 bit. THe kubernetes contains a HiveMQ MQTT broker. The top raspberrypi acts as proxy for the cluster and holds the loadbalancer. The cluster was not a high availability cluster and only one load balancer was deployed.

the RaspberryPi 3b SBC is designed by Kevin Schneider
https://www.autodesk.com/community/gallery/project/102488/raspberry-pi-3---b
![alt text](https://github.com/FSkavlem/CAD_Raspberrypi_cluster/blob/main/Pictures/Cluster.jpg?raw=true)
![alt text](https://github.com/FSkavlem/CAD_Raspberrypi_cluster/blob/main/Pictures/Fusion360.png?raw=true)
![alt text](https://github.com/FSkavlem/CAD_Raspberrypi_cluster/blob/main/Pictures/SystemDesign.png?raw=true)
