# Capstone Project: Video Streaming App “Netflix Clone” Deployment & Security with DevOps & DevSecOps tools

**Objective:** To implement a DevSecOps CI/CD pipeline for deploying a Netflix clone application.
It involves incorporating tools like Jenkins, Docker, and Kubernetes and security tools such as Trivy and OWASP Dependency-Check. Additionally, monitoring with Prometheus and Grafana ensures application reliability and performance, while automating the entire deployment pipeline minimizes manual effort and errors.
The successful completion of this project will provide hands-on experience in modern DevSecOps practices, focusing on secure, scalable, and automated deployments.

**Real-time Scenario:** A global video streaming service, StreamFlix, is expanding its user base and aims to provide a seamless viewing experience across different regions. As the company grows, it faces challenges in ensuring secure, scalable, and automated deployment pipelines for its web application.
The company struggles with inefficient manual deployments, lack of integrated security tools, insufficient real-time monitoring, and inconsistent container management across environments, risking vulnerabilities, performance issues, and deployment delays.
Implementing a DevSecOps CI/CD pipeline with Jenkins, Trivy, and OWASP ensures secure automation, while Prometheus and Grafana provide real-time monitoring. Docker and Kubernetes streamline deployments and enable seamless scaling, enhancing efficiency and reliability.

-------------------------------------------------------------------------------------------------------------------------

## Tools & Environment Used in this Project:

- Jenkins
- Docker
- Kubernetes
- Trivy
- Owasp
- SonalQube
- Prometheus
- Grafana

-------------------------------------------------------------------------------------------------------------------------

## High Level Project Diagram:

<img width="965" height="601" alt="image" src="https://github.com/user-attachments/assets/45b798d0-eaeb-4e84-8f55-ae08cb941a94" />

--------------------------------------------------------------------------------------------------------------------------

## High Level Tasks/Steps:

-	Prepare or fork a GitHub Repository for project related files.
-	Launch an Ubuntu EC2-Instance.
-	Install Jenkins, Docker, Trivy and create a SonarQube container.
-	Create a TMDB API Key.
-	Install Prometheus and Grafana on a new Server (EC2-machine).
-	Install the Prometheus Plugin and Integrate it with the Prometheus server.
-	Email Integration with Jenkins and Plugin setup.
-	Install Plugins like JDK, SonarQube Scanner, Nodejs and configure Sonar Server.
-	Create a Pipeline Job in Jenkins using a Declarative Pipeline.
-	Install OWASP Dependency Check Plugins and Setup.
-	Docker setup under Jenkins, Image Build and Push.
-	Deploy the Netflix-clone application in Docker using latest image.
-	Kubernetes Setup on Ubuntu machine (Master and Worker Node).
-	Deploy on Kubernetes and Access the Netflix-clone application on the browser.

  -----------------------------------------------------------------------------------------------------------------------

  ## Output Results Screenshots:

  Install and setup Jenkins server on Ubuntu EC2 Instance

  <img width="911" height="494" alt="image" src="https://github.com/user-attachments/assets/a32edb0f-2c21-4260-a3bf-0a478df7c091" />

  ------------------------------------------------------------------------------------------------------------------------

  Setup SonarQube- create a SonarQube container

  <img width="975" height="370" alt="image" src="https://github.com/user-attachments/assets/99927f32-86c4-4bc0-8305-1413b77e1814" />

-----------------------------------------------------------------------------------------------------

<img width="935" height="490" alt="image" src="https://github.com/user-attachments/assets/0c9bf739-1777-4609-947e-132d9530f153" />

--------------------------------------------------------------------------------------------------------

Install Trivy

<img width="921" height="439" alt="image" src="https://github.com/user-attachments/assets/286aa906-6473-47bc-834c-72f885a5a961" />

-------------------------------------------------------------------------------------------------------

<img width="950" height="247" alt="image" src="https://github.com/user-attachments/assets/e3adf289-b16f-49be-94fd-ed8afca85e85" />

-------------------------------------------------------------------------------------------------------

Create a TMDB API Key

<img width="963" height="590" alt="image" src="https://github.com/user-attachments/assets/f81ab0d3-ee7f-4a62-81f6-703e7bb40f95" />

---------------------------------------------------------------------------------------------------------------------------------------

<img width="962" height="502" alt="image" src="https://github.com/user-attachments/assets/0c9dce3b-08c3-44ba-b780-5215c5414848" />

-----------------------------------------------------------------------------------------------------------------------------------------

<img width="968" height="460" alt="image" src="https://github.com/user-attachments/assets/a2384686-5dd6-4c9f-a203-2b0827e875c3" />

-----------------------------------------------------------------------------------------------------------------------------------------

<img width="965" height="502" alt="image" src="https://github.com/user-attachments/assets/98f00888-a28f-4d78-b2ed-b6e73bad8c5a" />

------------------------------------------------------------------------------------------------------------------------------------------

Install Prometheus and Grafana on a new Server (EC2-machine)

<img width="975" height="215" alt="image" src="https://github.com/user-attachments/assets/fe9ae592-f9b4-4f5c-a5c9-d6aa13f00543" />

----------------------------------------------------------------------------------------------------------------------

<img width="936" height="518" alt="image" src="https://github.com/user-attachments/assets/abc7e45a-4ae9-4566-a0aa-e8dd802d0689" />

-----------------------------------------------------------------------------------------------------------------------

<img width="968" height="406" alt="image" src="https://github.com/user-attachments/assets/c57b2e39-96fd-4e27-9a6e-b70a09240cc4" />

-------------------------------------------------------------------------------------------------------------------------

Next, Install Node Exporter on Ubuntu EC2 machine

<img width="964" height="287" alt="image" src="https://github.com/user-attachments/assets/66e02f02-8d81-420a-a9a4-7a591474e024" />

--------------------------------------------------------------------------------------------------------------------------

<img width="947" height="345" alt="image" src="https://github.com/user-attachments/assets/99e739bd-f5d5-4ef5-bbb8-8df6473cc8a6" />

---------------------------------------------------------------------------------------------------------------------------

<img width="968" height="428" alt="image" src="https://github.com/user-attachments/assets/e44e6385-e8eb-40d1-8432-a68bf9cd959b" />

----------------------------------------------------------------------------------------------------------------------------

Next, Grafana

<img width="975" height="331" alt="image" src="https://github.com/user-attachments/assets/0e0b313a-e522-4c44-9f01-716766bd4fe4" />

-------------------------------------------------------------------------------------------------------------------------------

<img width="901" height="522" alt="image" src="https://github.com/user-attachments/assets/0191890a-f196-478a-8aa6-0166816e58e0" />

----------------------------------------------------------------------------------------------------------------------------------

<img width="947" height="269" alt="image" src="https://github.com/user-attachments/assets/92b6b7e1-e628-45d2-a67d-1644e6423ee4" />

-----------------------------------------------------------------------------------------------------------------------------------

<img width="975" height="503" alt="image" src="https://github.com/user-attachments/assets/c9aba2e8-5006-48de-b851-145e61221f47" />

-------------------------------------------------------------------------------------------------------------------------------------

Jenkins Metrics are displayed on Grafana Dashboard as graphs/meters/panels

<img width="967" height="504" alt="image" src="https://github.com/user-attachments/assets/b6a73abc-a79c-4911-a3ca-2fe662309090" />

---------------------------------------------------------------------------------------------------------------------------------------

Email Integration with Jenkins and Plugin setup

<img width="965" height="286" alt="image" src="https://github.com/user-attachments/assets/8d60a1b5-4a50-4ec1-9df1-724d3299ee3c" />

---------------------------------------------------------------------------------------------------

<img width="969" height="350" alt="image" src="https://github.com/user-attachments/assets/932203f0-198a-428c-baae-b9aa3c17a6ae" />

-----------------------------------------------------------------------------------------------------

<img width="936" height="401" alt="image" src="https://github.com/user-attachments/assets/f5a49865-df0f-4b77-bc54-956bd43b11b2" />

------------------------------------------------------------------------------------------------------

<img width="825" height="469" alt="image" src="https://github.com/user-attachments/assets/5f90ec27-aa54-41de-93a6-188f85856e0c" />

---------------------------------------------------------------------------------------------------------

Setup Email integrations settings under Jenkins

<img width="967" height="515" alt="image" src="https://github.com/user-attachments/assets/deb12738-70a2-48d4-b4c4-3c8670560649" />

-------------------------------------------------------------------------------------------------------

<img width="966" height="517" alt="image" src="https://github.com/user-attachments/assets/c7a2a292-1108-429f-8edc-4ac2fcae1673" />

-------------------------------------------------------------------------------------------------------

<img width="563" height="327" alt="image" src="https://github.com/user-attachments/assets/75becdc7-a934-4b3f-8d5e-a27e3076f2ab" />

--------------------------------------------------------------------------------------------------------

Install Plugins like JDK, SonarQube Scanner, Nodejs and configure Sonar Server

<img width="968" height="386" alt="image" src="https://github.com/user-attachments/assets/dd286670-6206-46bb-8153-da8df713b3d2" />

------------------------------------------------------------------------------------------------------------

<img width="959" height="369" alt="image" src="https://github.com/user-attachments/assets/73f325be-8242-4488-9384-21b704cc56bd" />

<img width="961" height="244" alt="image" src="https://github.com/user-attachments/assets/5e37ec11-ae37-4fb5-9b14-840abf5538b8" />

------------------------------------------------------------------------------------------------------------------

<img width="875" height="459" alt="image" src="https://github.com/user-attachments/assets/deb27d47-de40-4d3d-8570-b962f4f9efbb" />

------------------------------------------------------------------------------------------------------------------

<img width="958" height="523" alt="image" src="https://github.com/user-attachments/assets/72ae75e4-4ea1-4732-8bd4-541ea79b6a8c" />

--------------------------------------------------------------------------------------------------------------------

In the SonarQube Dashboard, need to add a quality gate (webhook)

<img width="963" height="486" alt="image" src="https://github.com/user-attachments/assets/023f8cd5-b963-4b8c-88c5-4eec91c85739" />

-------------------------------------------------------------------------------------------------------------------

<img width="950" height="405" alt="image" src="https://github.com/user-attachments/assets/61620589-99b1-4d4b-9dab-09dfa0d81ea0" />

----------------------------------------------------------------------------------------------------------------------------

Create a Pipeline Job in Jenkins using a Declarative Pipeline

<img width="949" height="501" alt="image" src="https://github.com/user-attachments/assets/2b605613-b222-4cc7-ac41-c3bcabf1fc91" />

-----------------------------------------------------------------------------------------------------------------------

Click on Build now to check if the current pipeline job is working

<img width="729" height="445" alt="image" src="https://github.com/user-attachments/assets/0e94cfa4-d689-40b5-86e0-f67ced38d6c1" />

------------------------------------------------------------------------------------------------------------------------

<img width="968" height="338" alt="image" src="https://github.com/user-attachments/assets/953e17f5-02cd-443c-b8fd-e2f2d7213f84" />

---------------------------------------------------------------------------------------

<img width="373" height="291" alt="image" src="https://github.com/user-attachments/assets/d569d4cc-98e0-4c29-a3dd-897fcc59bb30" />

---------------------------------------------------------------------------------------------------

Install OWASP Dependency Check Plugins and Setup in Jenkins

<img width="940" height="511" alt="image" src="https://github.com/user-attachments/assets/88018670-0fad-4592-b212-4d1a28f67730" />

------------------------------------------------------------------------------------------------------------

<img width="945" height="467" alt="image" src="https://github.com/user-attachments/assets/3486e1bc-be80-4f9a-b5d2-19b7aef8c694" />

--------------------------------------------------------------------------------------------------------

<img width="962" height="217" alt="image" src="https://github.com/user-attachments/assets/a18648c8-4b14-4889-a9db-f6ef99b50829" />

---------------------------------------------------------------------------------------------------------------

Docker setup under Jenkins, Image Build and Push

<img width="468" height="474" alt="image" src="https://github.com/user-attachments/assets/17dc17a1-7a39-4aa0-9c50-18f19826a9d7" />

------------------------------------------------------------------------------------------------------------------

<img width="958" height="292" alt="image" src="https://github.com/user-attachments/assets/5aba6b96-e7d4-456a-8686-bd6ac622b147" />

--------------------------------------------------------------------------------------------------------------------

After sometime, the job build got completed successfully.

The docker Image was build, tagged and pushed to docker hub properly.

The Trivy Image scan was also completed successfully. PFB the Screenshot:

<img width="481" height="332" alt="image" src="https://github.com/user-attachments/assets/87b375e8-0fea-4608-aa12-f485d1659a61" />


Docker Hub Repository:

<img width="963" height="452" alt="image" src="https://github.com/user-attachments/assets/e05be4d5-b8b7-415f-9947-8ce55f5629e6" />

------------------------------------------------------------------------------------------------------------------

<img width="966" height="206" alt="image" src="https://github.com/user-attachments/assets/0e33a60e-5a5c-4e39-a67c-d9fda0769e32" />

-------------------------------------------------------------------------------------------------------------------

Deploy the Netflix-clone application in Docker using latest image

<img width="617" height="527" alt="image" src="https://github.com/user-attachments/assets/e90c8e1a-dff2-4250-80b3-4c176966117a" />

------------------------------------------------------------------------------------------------------------------

The “netflix” container is running successfully and is mapped with port 8081 of the ubuntu EC2 machine

<img width="969" height="216" alt="image" src="https://github.com/user-attachments/assets/2eac1590-eddf-4be5-bf77-d8b37cf7c4cd" />

-----------------------------------------------------------------------------------------------------------------

Next, access the Netflix-clone application (running in container) on the browser using below URL: http://3.89.122.32:8081

The Netflix-clone Application is getting opened properly on the browser

<img width="884" height="524" alt="image" src="https://github.com/user-attachments/assets/b9724d76-f0b0-4bc2-b0c4-c419ab065dfe" />

---------------------------------------------------------------------------------------------------------------------

Kubernetes Setup on Ubuntu machine (Master and Worker Node)

<img width="830" height="258" alt="image" src="https://github.com/user-attachments/assets/7180fa4d-e021-4036-bdce-8185805671eb" />

----------------------------------------------------------------------------------------------------------------------

Under Jenkins- install Kubernetes Plugins

<img width="921" height="475" alt="image" src="https://github.com/user-attachments/assets/af9128cc-a410-46b6-813a-e7117666c1d6" />

-----------------------------------------------------------------------------------------------------------------------

<img width="962" height="488" alt="image" src="https://github.com/user-attachments/assets/8e6440ee-bc97-4859-9236-af677a2693b7" />

-----------------------------------------------------------------------------------------------------------------------

Deploy Netflix clone app in Kubernetes cluster and Access the Netflix-clone application on the browser.

Run the fully integrated Jenkins Pipeline Script to deploy app and run security scans.

the Job build was completed with SUCCESS message. The complete Pipeline with all the stages got Passed:

<img width="570" height="451" alt="image" src="https://github.com/user-attachments/assets/9b9abb9a-a612-4a89-8101-c4325ee76407" />

--------------------------------------------------------------------------------------

<img width="577" height="490" alt="image" src="https://github.com/user-attachments/assets/ea0b42ae-49f1-4a33-93b4-95a82ee859dd" />

----------------------------------------------------------------------------------------

Email Notification sent with SUCCESS msg and Trivy Scan logs attached:

<img width="712" height="490" alt="image" src="https://github.com/user-attachments/assets/ea9c222f-eb19-422b-b664-e0f18abb7cf7" />

-------------------------------------------------------------------------------------------------------

OWASP Dependency Check Results:

<img width="962" height="493" alt="image" src="https://github.com/user-attachments/assets/19fe4d11-d2bb-48bc-9a24-57e7aedd11e0" />

----------------------------------------------------------------------------------------------------------

<img width="943" height="539" alt="image" src="https://github.com/user-attachments/assets/4b8acbf6-06b7-45a2-b5e4-9044f4a9e731" />

--------------------------------------------------------------------------------------------------------------

SonarQube – Quality Gate Status:

<img width="961" height="585" alt="image" src="https://github.com/user-attachments/assets/100c34c0-25c1-4a73-89ad-41499544eb95" />



<img width="961" height="300" alt="image" src="https://github.com/user-attachments/assets/9e483b5c-07e7-4140-a3d8-5e29f02b77fc" />


--------------------------------------------------------------------------------------------------------------

**Trivy File System Scan:**


<img width="937" height="561" alt="image" src="https://github.com/user-attachments/assets/eaa9fb46-dcc5-4508-af31-13c99e9984cf" />



**Trivy Image Scan:**


<img width="962" height="438" alt="image" src="https://github.com/user-attachments/assets/098529f8-64fc-4f3d-ad41-82cad72a1d26" />

----------------------------------------------------------------------------------------------------------------------------------

Monitor & Visualize System Metrics of Jenkins Machine on Grafana Dashboard via Prometheus Data source:

<img width="975" height="509" alt="image" src="https://github.com/user-attachments/assets/5a7e5541-dd53-4bf9-9221-c7a8ba55357a" />

-----------------------------------------------------------------------------------------------------------------------------------

Monitor & Visualize System Metrics of Kubernetes-Master Node on Grafana Dashboard via Prometheus Data source:

<img width="975" height="504" alt="image" src="https://github.com/user-attachments/assets/6a010105-e0b5-4e35-9b30-0c12dad32bd0" />

------------------------------------------------------------------------------------------------------------------------------------

Monitor & Visualize System Metrics of Kubernetes-Worker Node on Grafana Dashboard via Prometheus Data source:

<img width="975" height="509" alt="image" src="https://github.com/user-attachments/assets/723e9a94-c503-4969-a465-8c568d0a142e" />

-----------------------------------------------------------------------------------------------------------------------------------

Netflix-clone Application Deployed & Running on Kubernetes Cluster:

http://54.145.47.178:30007

<img width="975" height="589" alt="image" src="https://github.com/user-attachments/assets/0ea5d7e6-708a-4b31-897d-5b831da34d00" />

-----------------------------------------------------------------------------------------------------------------------------------

**Hence, The Project implemented a DevSecOps CI/CD pipeline for deploying a Netflix clone application, by incorporating tools like Jenkins, Docker, and Kubernetes for automated deployment.
Security tools like SonarQube, Trivy and Owasp dependency check were used for Source Code Analysis, File system scan & image scan and Dependencies check for any vulnerabilities. Additionally for Monitoring of system metrics – Prometheus was used and to visualize metrics on Dashboards/graphs/panels – Grafana was used.
The Project has been completed successfully with modern DevSecOps practices to ensure secure, scalable, and automated deployments.**


