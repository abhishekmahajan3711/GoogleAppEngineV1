### Note Before Cloning=>
1.Install Google App Engine 

2.Do configuration using gcloud init

3.You should create project on google console and save project-id somewhere

4.Then do cloning acoording to given following steps



### To clone,
Run the commands on terminal :

git clone https://github.com/abhishekmahajan3711/GoogleAppEngineV1.git

---if git is not install then install it---

cd GoogleAppEngineV1

---go in files , go to GoogleAppEngineV1 folder, go to CodeFolder, open app.yaml file, in that file paste your project-id----

python2 google_appengine/dev_appserver.py CodeFolder/app.yaml

---if python2 not found then install it---

---go to localhost:8080---



































### OwnCloud using Docker Commands

sudo su -
apt-get install docker -y
apt-get install docker.io -y
service docker start
dcoker --version

------now on google search for "install docker compose", click "Overview of Installing Docker Compose",scroll down and you will see "install the Compose standalone" and click on it, now run that twp installation commands (first command is => curl -SL https://github.com/docker/compose/releases/download/v2.27.0/docker-compose-linux-x86_64 -o /usr/local/bin/docker-compose    .... second command is => sudo ln -s /usr/local/bin/docker-compose /usr/bin/docker-compose   ) ------

chmod -R 777 /usr/local/bin/docker-compose /usr/bin/docker-compose

------now on google search for "installing owncloud using docker" , click on "Installing with Docker- OwnCloud Documentation", scroll down you will see "Docker Compose", ther are 3 points , do/perform that 3 points ------

ifconfig

------if "ifconfig" not found ,then install it ------
------you will see 192.something , copy that ip address and paste it in .env file inplace of "localhost"------

cd /home/abhishek/owncloud-docker-server
docker-compose up -d

------now go in browser and go to "localhost:8080" and sign in by username: admin and password:admin , in phone you can put ip address 192.something:8080---------
