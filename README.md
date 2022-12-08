# msw_lgu_lte
sparrow 보드에 lidar센서를 장착하여 거리를 측정하는 미션 소프트웨어

## Install dependencies
### MQTT-broker
```
$ wget http://repo.mosquitto.org/debian/mosquitto-repo.gpg.key
$ sudo apt-key add mosquitto-repo.gpg.key
$ cd /etc/apt/sources.list.d/
$ sudo wget http://repo.mosquitto.org/debian/mosquitto-buster.list 
$ sudo apt-get update
$ sudo apt-get install -y mosquitto
```
### nodejs Library
```
$ npm install

