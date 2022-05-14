                 Tomcat
tomcat

sudo -i
cd /opt
yum update -y
yum insall wget unzip -y
yum install java-1.8.0-openjdk-devel -y   (1st wee need java install)
wget tomcat.zip file (go to official web site tomcat install)
unzip or tar -xvzf tomcat file
cd appache-tomcat.-.-.--
cd bin/
chmod u+x *.sh ((*means all ) (here .sh files give the executive permissions u+x)
/.startup.sh (here start the tomcat server)
cd conf/
vi tomcat.users.xml (here give the u n, pw, r )
username = -----
passwd   = -----
roles    = admin-gui,manager-gui,manager-script
vi server.xml (here change the tomcat port number )
cd webapps/
cd manager/ and cd host-manager
cd META-INF
vi context.xml(here give the comment (value) <!-- ... -->)



