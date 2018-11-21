# GitLab_docker_compose_deploy
deploy a local gitlab server with docker-compose using official GitLab Docker image 

# run 
docker-compose up -d

# volumes
docker运行后会将gitlab元数据及docker日志挂载到本项目下的volumes/路径下来达到本地持久化的目的
