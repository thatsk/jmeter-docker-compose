# jmeter-docker-compose
jmeter-docker-compose for alpine
#For Finding IP's Of Slave machine
Just Run the command bash.sh
#For running Docker-compose
docker-compose up -d
#For scaling Slave machine
docker-compose scale slave=5
#For scale down slave machines
docker-compose scale slave=2
#for Stopping
docker-compose down
