RUN the following command for docker-compose

=> `docker-compose up`

- creates images & containers specified in the docker-compose.yaml file

=> `docker-compose down --rmi all -v`

- removes all the images, containers and volumes generated by the docker-compose.yaml. To breakdown;
- --rmi all => flag that removes all the images created by the docker-compose.yaml.
  We can specify the images we want to delete instead of 'all'
- -v => flag that removes all the volumes created by the docker- compose.yaml.
