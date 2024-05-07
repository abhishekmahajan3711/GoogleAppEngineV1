### Note Before Cloning=>
1.Install Google App Engine 
2.Do configuration using gcloud init
3.You should create project on google console and save project-id somewhere



### To clone,
Run the commands on terminal :

git clone https://github.com/abhishekmahajan3711/GoogleAppEngineV1.git

---if git is not install then install it---

cd GoogleAppEngineV1

---go in files , go to GoogleAppEngineV1 folder, go to CodeFolder, open app.yaml file, in that file paste your project-id----

python2 google_appengine/dev_appserver.py CodeFolder/app.yaml

---if python2 not found then install it---

---go to localhost:8080---
