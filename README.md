**Jenkins CICD pipeline ||Developer|| Github|| Jenkins || Ansible || Webserver ||**

Jenkins Installation 

**Make a shell scripting with the name "vim jenkins_innnstall.sh"**
---------------------------------------------------------------------------------------
sudo apt install openjdk-11-jdk
curl -fsSL https://pkg.jenkins.io/debian-stable/jenkins.io-2023.key | sudo tee \
  /usr/share/keyrings/jenkins-keyring.asc > /dev/null
echo deb [signed-by=/usr/share/keyrings/jenkins-keyring.asc] \
  https://pkg.jenkins.io/debian-stable binary/ | sudo tee \
  /etc/apt/sources.list.d/jenkins.list > /dev/null
sudo apt-get update
sudo apt-get install jenkins
sudo systemctl enable jenkins
----------------------------------------------------------------------------------------
> sudo sh jenkins_install.sh
