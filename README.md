# installation
java and jenkins


#JAVA INSTALLATION IN UBUNTU 

#$ sudo apt update
#$ sudo apt-get install openjdk-8-jdk -y


#JENKINS INSTALLATION

#$ 1. go to jenkins.io site
   2. click on downloads
   3. select your o/s , here i am selected ubuntu
   4. wget -q -O - https://pkg.jenkins.io/debian/jenkins.io.key | sudo apt-key add
   5. Then add the following entry in your /etc/apt/sources.list:
      deb https://pkg.jenkins.io/debian binary/
   6. sudo apt-get update
      sudo apt-get install jenkins
   7. start the jenkins server
      systemctl start jenkins
      systemctl status jenkins
   8. now goto browser and enter ip address:8080
   9. it will show the initial admin passwrd inside the node on below file
     /var/lib/jenkins/secrets/initialAdminPassword

#SONARQUBE INSTALLATION ON DIFFERENET SEREVER AND DATABASE ON AWS RDS INSTANCE

1.SONARQUBE INSTALLATION:
   1.prerequisites
     1. java 1.8 jdk and above version
     2. wget , tar , unzip 
   2. 
