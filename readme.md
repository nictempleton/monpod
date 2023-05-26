Simple podman yaml to create a pod running portainer, NPM, and Uptime Kuma. 

Future tasks: 
    All the persistent storage is currently hard coded.


To connect Portainer to podman: 
    Log into portainer and create an admin account, if needed. 
    Select Add Enviroment
    Select Docker Standalone
    Look for "Name" mid way down the page. 
        Type in a name of your choice
        Enter the IP address of the server with the port 9001 
            Example : 192.168.0.5:9001 
        Click Connect
