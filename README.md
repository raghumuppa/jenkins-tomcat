# Sample Hello World Project

Integrating Jenkins Container with Tomcat Container

# For integrating both the containers just follow the docker-compose file 

<pre>docker-compose up -d</pre>

# For integrating two servers follow the below steps

Prepare you jenkins server and then tomcat server


|	Jenkins		|	Tomcat		|
|-----------|-----------|
| * Maven Integration	| * Create user with	|
| * GitHub Plugin	|   required access	|
| * Create Credentials 	| * Tomcat Should run on| 
| * Project URL (git)	|   port 8080		|


For Installing Tomcat on Ubuntu-18.04

<pre>apt-get update && apt-get install -y tomcat9 tomcat9-docs tomcat9-examples tomcat9-admin</pre>

For Installing Jenkins on Ubuntu-18.04

<pre>wget -q -O - https://pkg.jenkins.io/debian/jenkins.io.key | sudo apt-key add -</pre>

Then add the following entry in your /etc/apt/sources.list:

<pre>deb https://pkg.jenkins.io/debian binary/
sudo apt-get update
sudo apt-get install jenkins
</pre>

Note: Make sure Java 8 or Java 11 installed 


