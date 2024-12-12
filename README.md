# Mosquitto
ดำเนินการติดตั้ง mqtt broker

## Deploy Step
docker-compose -f CICD/DEV.yml down
docker-compose -f CICD/DEV.yml build
docker-compose -f CICD/DEV.yml up