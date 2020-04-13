# elk
Supporting Repo for ELK installation Youtube video
```
git clone https://github.com/soufianem370/elk.git
cd elk/docker
```
## elastic search parametres VM.max
```
sudo sysctl -w vm.max_map_count=262144
```
rename docker-compose-v7.1.1.yml  with docker-compose and edit docker-compose for use the latest version 

```
mv docker-compose-v7.1.1.yml docker-compose.yml
```

