### This is a group project initiated by Ge Yu Feng and Oscar Ou. One day we talked about doing some side projects to help us learn more skills of CS (Computer Science) and CE (Computer Engineering). Welcome Liu Yi Jian!

### 1. isn't this diary style cool? we can use similar format also! :)
### 2. **everyone in the project is welcomed to edit this file!**
### 3. happy coding and good luck!
### 4. All languages welcome! Dutch, English, Chinese, Or Student, Studentin, Or...or...or...
### 5. There will be no lead person in this project. We will be working as a whole to learn new skills, develop something useful for the world, and most importantly...
### 6. Most of the communications might be appearing in this read me file, or there can be [option 1] [option 2] [option 3] (forms of communications).
### 7. Useful links will be here and there. our README.md file will be very responsive and actually it will eventually become our "documentation" for this project and maybe future projects.

##### August 20 2018, Oscar writes
1. Choosing Google Cloud (GCP) as 载体:). using the various GCP services.
2. Should we use Sprint Boot. Yes?
```
Primitive roles https://cloud.google.com/iam/docs/understanding-roles
Predefined roles 同上
Custom roles the same link as Primitive roles
```
this is cool https://docs.spring.io/spring-python/1.2.x/sphinx/html/overview.html
this is cool
http://www.jython.org/archive/22/installation.html
3. thinking how we collab. Let's go IAM.
4. Maven vs Gradle vs our so many ide options... what a nice thinking needed here. We need to understand everyone of these choices.
```
https://maven.apache.org/
https://gradle.org/
[links of ides] Can we use any of good ides, any suggestions guys?
```
5. cute things (errors):
```
1. Error: Unable to access jarfile jython_installer-2.7.1.jar
2. E: Unable to locate package pip3-python
```
solving them:
```
sudo apt-get install python3-setuptools
sudo easy_install3 pip
pip --version
```
now it looks like we are having python 3.5

6. Current Structure in that machine is something like this:
```
_in home directory, type `ls`_:
a_explaination_file  data            logs                                   solr-6.5.1
apache-nutch-2.3.1   gs-spring-boot  mongodb-linux-x86_64-ubuntu1604-3.4.7  src

- a_explaination_file, useless file, can write something in it
- data, data, should be containing data now and future
- logs, logs, should be containing logs now and future
- solr-6.5.1, that is apache solr, a very stable search engine
- apache-nutch-2.3.1, apache nutch, related to crawling data part of our project
- gs-spring-boot, spring is spring framework very useful framework
- mongodb-linux-x86_64-ubuntu1604-3.4.7, mongodb database, one of the database options can pick. Please feel free to add MySQL part installation in it if wanted
```
7. How should we do the packages management part (probably need to use a lot of thing maybe now or future, currently responsible for setting up some environments for us, these enrivonments can always be changed if you have a better solution / a nice suggestion, please feel free.
