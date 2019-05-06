# deploy-tomcat-mapstore
Docker based deployment of Tomcat and MapStore2

## PRE-INSTALLATION: ##
Copy your "mapstore.war" file into the build directory:
- $<INSTALL_DIR> build/

## INSTALLATION: ##
Run the following in the install directory
- $<INSTALL_DIR> docker-compose build

## RUNNING THE SERVICES: ##
Run the following in the install directory
- $<INSTALL_DIR> docker-compose up -d