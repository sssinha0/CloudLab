# CloudLab



















#Question 6
command for run docker 
sudo docker run hello-world  //check docker install properly or not
docker --version             //chekc the version of docker
sudo systemctl status docker //check the staus of docker engine 
sudo docker images           //give all the docker image list
sudo docker search ubuntu    //search on the docker hub to get the image file 
sudo docker create --name shashisinha-ubuntu -it ubuntu bash    //create new ubuntu image name as shashisinha-ubuntu
sudo docker start shashisinha-ubuntu  //start the image
sudo docker attach shashisinha-ubuntu  //get inside the new install ubuntu docker image
sudo docker logs shashisinha-ubuntu  //get log of the ubntu image


