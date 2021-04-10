# CI/CD With Jenkins in Windows Machine
“CI/CD” is a practices of Continuous Integration (CI) and Continuous Delivery (CD).

### Before moving to CI/CD we need to install tools
    
    Jenkins
    Docker

### Jenkins Installation Guide

For Jenkins installation we need Java environment.

#### Step 1: JDK (JAVA DEVELOPMENT KIT)  and JRE (JAVA RUNTIME ENVIROMENT ) DOWNLOAD & INSTALL 

https://www.oracle.com/java/technologies/javase-jdk16-downloads.html
    
![img_2.png](doc/img_2.png)

https://www.oracle.com/in/java/technologies/javase-jre8-downloads.html

Note: Install with default settings.

![img_3.png](doc/img_3.png)



### Step 2: Set Java SDK path in Environment Variables

    copy JDK path C:\Program Files\Java\jdk-16 

* Add new Variable JAVA_HOME in User Variable and System Variable

![img.png](doc/img.png)

    Copy JAVA bin folder C:\Program Files\Java\jdk-16\bin

* Add bin path system variable path (inside environment variable)

![img_1.png](doc/img_1.png)

### Step 3: Jenkins Download & Install

https://www.jenkins.io/download/

    choose Jenkins *.***.* LTS and windows

![img_4.png](doc/img_4.png)

#### Jenkins Installations
     
Run Jenkins Windows installer and follow the steps

Installation get Service Logon Credential window need to choose Logon Type

2 Option Given
* Run Service as Local System (i choose this option)
* Run Service as local or domain user ( https://stackoverflow.com/questions/63410442/jenkins-installation-windows-10-service-logon-credentials)
    
![img_5.png](doc/img_5.png)

After Successful installation new page open in a browser at localhost:8080

then follow the steps mentions in the page. once you did all the configuration part like user creation. You will redirect to Jenkins Dashboard.

![img_7.png](doc/img_7.png)



    









