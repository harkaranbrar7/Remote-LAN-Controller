# Remote-LAN-Controller


How it made:

*Written in: Java
*Operating System: Microsoft Windows
*IDE = Net Beans

Requirements:
* Two or more Windows Computer (any version)
* Local connection between those computers 
* Java Support

How to Run:

Firstly, Download the newest version of java in both client and server computer. (in case you don't have it)

Newest java version is available from official Java website.
http://www.java.com/en/download/
Install Java on your both System.

>Go to the Remote LAN Controller project directory
 >Open jar directory

jar directory consists of two jar files:
					Normal System.jar
					remote_lan.jar

Run the remote_lan.jar file on the machine where you want to set up your central computer from where you want to control other systems. (client)

Run the Normal System.jar file on the other machines whom you want to control. (server)



Client: 
On Client Computer, you will see window like this:

 

Control Panel:
It consists of these elements:

Text field: It shows your IP address (if not you can type your IP)

Scan Button: This button is for scanning all Computers connected to the same network as the server.  Those devices will show in Online Devices field by IP address.

Check Server Button: This button is for checking the server computer which has a running Normal.jar file. Those devices will show in Online Servers field by IP address.

View System Button: This button is for a view and Control the specific Server computer which you were selected from Online server field.

Shutdown All Button: This button is for Shutdown all servers which are connected to Client.



This will help you to view and control all the system from your desk.
