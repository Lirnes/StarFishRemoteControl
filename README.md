# Starfish Remote control

This repositories contains the source code to control remotely a SSS named Starfish 990. It comes with a Grafana interface to visualize the state of the sonar.


# Requirements

 - Windows environnement.
 - Grafana installed.
 - Grafana dashboard for the Starfish imported.
 - Grafana dependencies.
	 -   [Button Panel](https://github.com/cloudspout/cloudspout-button-panel) 
	 -   [Dynamic Image Panel](https://github.com/Dalvany/dalvany-image-panel)
	 - [SQLite](https://github.com/fr-ser/grafana-sqlite-datasource) 
 - Change Grafana variable "hostIP" in the Dashboard to the IP Adress of the machine that host the Grafana server.
 - Python's module from the requirement.txt.

## Usage

To start the software, you need to launch with python StarFishScanner.py. 

    python ./StarFishScanner

Then, be hostIP the IP Adress of the host machine. You can :

 - Access the data server containing all the generated images by acceding http://hostIP:8000
 - Access the Grafana Dashboard by acceding http://hostIP:3000

Kill the program if you want to stop the servers.

From the Grafana interface
