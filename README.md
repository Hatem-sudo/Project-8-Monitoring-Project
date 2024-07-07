# Project-8-Monitoring-Project
## Monotoring Project 

![Capture1](https://user-images.githubusercontent.com/74002629/185382955-28d67f00-8b19-4caa-8dd2-048cea6c0b74.PNG)

#### Project Description
-. Monotoring Project with prometheus and Grafana 
-. See project Performans 
Tools :-
1.Node-Exporter.
2.Prometheus.
3.Grafana.
4.Docker.
5.Linux.

#### Step 1 - Node-Exporter.
1. Open node-Exporter offical website.
2. Checkout the newly Virison of Node-Exporter as a Docker image.
3. Run Docker image of Node-Exporter as a container with Docker compose Becuse we have many of Volume and commands.

![pull node and prom](https://github.com/Hatem-sudo/Project-8-Monitoring-Project/assets/113099054/d10fac78-f55f-432b-a16a-eda1d9a660fe)

#### Step 2 - Download and Install Prometheus.

1.Login prometheus server.
2.Download Prometheus image from Docker-Hub.
3.Instal Prometheus and Run the Container.

![pull node and prom](https://github.com/Hatem-sudo/Project-8-Monitoring-Project/assets/113099054/d10fac78-f55f-432b-a16a-eda1d9a660fe)
  
#### Step 3 – Download and Install Grafana.


1.Go to Docker-Hub to download Grafana Image.
2.Install Grafana with as a container and run it.
3.Cheak Network Ips

![pull grafana](https://github.com/Hatem-sudo/Project-8-Monitoring-Project/assets/113099054/232c0ca4-f186-4a64-b48b-f6cb91cc461e)


#### Step 6 - Edit Prometheus file.
1. Open Prometheus file configration.
2. Select the file to add target to collect information with static configs with yaml sentax.
3. Put the IP of machine or Docker container.
4. Make a new configration file to be easy to acces it with comand line.
![catpremthyml](https://github.com/Hatem-sudo/Project-8-Monitoring-Project/assets/113099054/2c5f7344-7b63-44cd-a827-2da91b7abf61)



#### Step 7 – Creat Connection with all.

1. Now creat Node-Exporter to collect monotoring information from the server.
2. make Prometheus to listen to Node-Exporter by configration file 

![dpcker cpmpose](https://github.com/Hatem-sudo/Project-8-Monitoring-Project/assets/113099054/fea3ce12-597d-4241-9613-4b64e4b840b7)

#### Step 8 - Grafana logs.
1. we can go to mountpoint to manage storgae to this path to see data and make volume from container 
2.Make DataSource in grafana to copy the logs from Prometheus to Grafana
3.Edite dahshebord to handel your details.

![grafana logs](https://github.com/Hatem-sudo/Project-8-Monitoring-Project/assets/113099054/d049d4cc-aed4-4e26-be77-00680adb5493)

### Project Done 


![nodeexporter](https://github.com/Hatem-sudo/Project-8-Monitoring-Project/assets/113099054/e789cb1f-2036-4b65-a5b6-a4899a1940a0)


![promethus](https://github.com/Hatem-sudo/Project-8-Monitoring-Project/assets/113099054/a5261557-41da-4455-9cfd-eddca733ec2c)

![Grafana](https://github.com/Hatem-sudo/Project-8-Monitoring-Project/assets/113099054/f3dc08ef-361c-4daa-8bd0-5c6f04460a34)


