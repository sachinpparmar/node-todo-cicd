# node-todo-cicd

Run these commands:


`sudo apt install nodejs`


`sudo apt install npm`


`npm install`

`node app.js`

or Run by docker compose

test

-------------------------------------------------------
-----------------------------------------------------
notes node-todo
https://docs.google.com/document/d/1qos4eUfY4vZojjnZLSGw8D3A46Yy2r42uiZPyPxL17A/edit

-------------------------------------------------------------------------------------------------------------------------
-------------------------------------------------------------------------------------------------------------------------

       sudo apt update
      sudo apt update
      sudo apt  install docker.io -y
      sudo apt install docker-compose -y
      docker
      docker-compose-v
      docker-compose -v
      sudo apt update
      sudo apt install openjdk-11-jre -y
      curl -fsSL https://pkg.jenkins.io/debian-stable/jenkins.io-2023.key | sudo tee   /usr/share/keyrings/jenkins-keyring.asc > /dev/null
      echo deb [signed-by=/usr/share/keyrings/jenkins-keyring.asc]   https://pkg.jenkins.io/debian-stable binary/ | sudo tee   /etc/apt/sources.list.d/jenkins.list/dev/null
      sudo apt-get update
      sudo apt-get install jenkins -y
      jenkins
      sudo apt-get update
      sudo apt-get install jenkins -y
     jenkins
    sudo apt-get install jenkins -y
     sudo systemctl start jenkins
    sudo systemctl status jenkins
    cat /var/lib/jenkins/secrets/initialAdminPassword
      sudo cat /var/lib/jenkins/secrets/initialAdminPassword
  
  cd /var/lib/jenkins/workspace/todo-node-app     (we will go after run the job on jenkins)
  
  sudo apt install nodejs
  sudo apt install npm
  
  sudo apt install npm


  npm install

  node app.js      (for run the app we run this command)
  
  ## we will run this app using dockerfile  
  ## so write dockerfile
  
  FROM node:12.2.0-alpine
WORKDIR app
COPY . .
RUN npm install
EXPOSE 8000
CMD ["node","app.js"]

docker build . -t node-app
sudo usermod -a -G docker $USER
docker run -d --name node-todo-app -p 8000:8000 todo-node-app


 sudo usermod -a -G docker jenkins
  systemctl restart jenkins
  sudo systemctl restart jenkins
   systemctl status jenkins

