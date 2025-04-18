# java-maven-jenkins-job
# Hello Java Maven with Jenkins
This project demonstrates a simple Java application built using **Maven**, and the CI process is handled using **Jenkins**.
## 🛠 Project Overview
- A basic Java "Hello World" program.
- Built using **Apache Maven**.
- Jenkins automates the build process.
## 📁 Project Structure
hello-java-maven/ ├── pom.xml └── src/ └── main/ └── java/ └── HelloWorld.java
markdown
Copy
Edit
## ⚙️ Jenkins Setup
1. **Create a new Freestyle project** in Jenkins.
2. In the **Source Code Management** section:
   - Select Git.
   - Add your GitHub repo URL.
3. In the **Build** section:
   - Add build step: `mvn clean package`
4. Apply and Save.
## 📸 Screenshots
1. Jenkins Dashboard with job
2. Job Configuration page
3. Successful Build Console Output
4. Workspace showing target folder
5. Java program output (optional)
![image alt](https://github.com/jaswanthBavi/java-maven-jenkins-job/blob/f50bbdfa76e6d75d21752abdd775d00eb7449d95/Screenshot%202025-04-18%20160859.png)
![image alt](https://github.com/jaswanthBavi/java-maven-jenkins-job/blob/f50bbdfa76e6d75d21752abdd775d00eb7449d95/Screenshot%202025-04-18%20161154.png)
![image alt](https://github.com/jaswanthBavi/java-maven-jenkins-job/blob/f50bbdfa76e6d75d21752abdd775d00eb7449d95/Screenshot%202025-04-18%20162022.png)
![image alt](https://github.com/jaswanthBavi/java-maven-jenkins-job/blob/f50bbdfa76e6d75d21752abdd775d00eb7449d95/Screenshot%202025-04-18%20162113.png)
![image alt](https://github.com/jaswanthBavi/java-maven-jenkins-job/blob/f50bbdfa76e6d75d21752abdd775d00eb7449d95/Screenshot%202025-04-18%20162325.png)
![image alt](https://github.com/jaswanthBavi/java-maven-jenkins-job/blob/f50bbdfa76e6d75d21752abdd775d00eb7449d95/Screenshot%202025-04-18%20162347.png)
![image alt](https://github.com/jaswanthBavi/java-maven-jenkins-job/blob/f50bbdfa76e6d75d21752abdd775d00eb7449d95/Screenshot%202025-04-18%20162411.png)
![image alt](https://github.com/jaswanthBavi/java-maven-jenkins-job/blob/f50bbdfa76e6d75d21752abdd775d00eb7449d95/Screenshot%202025-04-18%20162617.png)
