# CI/CD With Jenkins in Windows Machine
“CI/CD” is a practices of Continuous Integration (CI) and Continuous Delivery (CD).

### Before moving to CI/CD we need to install tools
    
    Jenkins
    Docker

### Jenkins Installation Guide

For Jenkins installation we need Java environment.

#### Step 1: JDK (JAVA DEVELOPMENT KIT)  and JRE (JAVA RUNTIME ENVIROMENT ) DOWNLOAD & INSTALL 

https://www.oracle.com/java/technologies/javase-jdk16-downloads.html
    
![img_2.png](img_2.png)

https://www.oracle.com/in/java/technologies/javase-jre8-downloads.html

![img_3.png](img_3.png)

    Note: While installation no need to change anything. let it be install default setting

### Step 2: Set Java SDK path in Environment Variables

    copy JDK path C:\Program Files\Java\jdk-16 
    add new Variable JAVA_HOME in User Variable and System Variable

![img.png](img.png)

    Copy JAVA bin folder C:\Program Files\Java\jdk-16\bin
	add bin path system variable path (inside enviroment variable)

![img_1.png](img_1.png)

### Step 3: Jenkins Download & Install

https://www.jenkins.io/download/

    choose Jenkins *.***.* LTS and windows

![img_4.png](img_4.png)

#### Jenkins Installations
     
    Run Jenkins windows installer and follow the steps
    
    While installtion get Service Logon Credential winodw need to choose Logon Type
    2 Option Given
        * Run Service as Local System (i choose this option)
        * Run Service as local or domain user (follow https://stackoverflow.com/questions/63410442/jenkins-installation-windows-10-service-logon-credentials)
    
![img_5.png](img_5.png)

    After Successful installtion new page open in browser at localhost:8080

    then follow the steps mentions in the page. once you done all the confguration part like user creation. you will redirect to jenkins Dashboard.

![img_7.png](img_7.png)



    









