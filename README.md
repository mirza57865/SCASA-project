Steps to Run Project

Pre-requisites:
Install Git, 

Docker Procedure:
Clone Git Repository (https://github.com/krssrinivas7/SCASA-project.git).
Change directory to Project Directory i.e. SCASA-project
Pull the docker image - $ docker pull krssrinivas/scasa:1
Create Container - $ docker run -d --name Scasa-KRS -p 5000:5000 krssrinivas/scasa:1
Access the application thru web -> http://publicIP:5000/
