# jmeter-docker-compose<br>
jmeter-docker-compose for alpine<br>
<b>Just execute the command to enter into jmeter-client<b><br>
docker exec -it master /bin/bash<br>
<b>Then Run jmeter script<b><br>
jmeter -n -t jmeter-docker-compose.jmx -R172.19.0.16,172.19.0.15<br>
<b>For Finding IP's Of Slave machine</b><br>
Just Run the command bash.sh<br>
<b>For running Docker-compose</b><br>
docker-compose up -d<br>
<b>For scaling Slave machine</b><br>
docker-compose scale slave=5<br>
<b>For scale down slave machines</b><br>
docker-compose scale slave=2<br>
<b>for Stopping</b><br>
docker-compose down<br>
