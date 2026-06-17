# Doscker-Task
Task Description:  Install docker on EC2 and explore the docker commands (docker images, containers, volumes, network)

Step 1 : Installed Docker in EC2
<img width="1631" height="715" alt="image" src="https://github.com/user-attachments/assets/ac6f5891-0c49-4197-af26-0a24f1b8d62f" />

Step 2: Give Docker Access to Ubuntu User
<img width="1615" height="758" alt="image" src="https://github.com/user-attachments/assets/e7cb9a6f-4c5b-450c-a4d5-1424889fecac" />

Step 3 : Pull an Image / List Images / Remove an Image / Inspect Image
<img width="1620" height="701" alt="image" src="https://github.com/user-attachments/assets/c48d3011-828a-4298-8cb2-fdd4a3f04e99" />

Step 4 : Create Dockerfile Build Dockerfile Run Container
<img width="1838" height="717" alt="image" src="https://github.com/user-attachments/assets/b1564038-b52a-4205-9156-6b823ae7c32c" />
<img width="1277" height="202" alt="image" src="https://github.com/user-attachments/assets/df46632b-1c67-4647-9a60-7c7e333c9fc0" />
<img width="1881" height="963" alt="image" src="https://github.com/user-attachments/assets/2a611799-97a4-42da-ab6c-3ebec87d1925" />

Step 5 : View All Containers / Stop Container / Start Container / Restart Container / Remove Container / Inspect Container / View Container Logs
<img width="1900" height="437" alt="image" src="https://github.com/user-attachments/assets/b9db666f-538b-4f28-b289-8334b7e5d502" />

Step 6 : Using docker volume to persist container data
Run Temporary Ubuntu Container > Create file inside container > Exit container > Remove container > Run new container and check for file which shows Container storage is ephemeral/temporary 
<img width="1612" height="392" alt="image" src="https://github.com/user-attachments/assets/dcbbb718-7af8-4936-9771-2482413f8db2" />
<img width="1890" height="707" alt="image" src="https://github.com/user-attachments/assets/4cb5bd6e-10c7-4a79-a020-f9cdcb53e766" />
Create volume > Run container using volume > Create Persistent file > remove container > Run New Container Using Same Volume > Check file it still exists because data 
is stored in docker volume
<img width="1773" height="595" alt="image" src="https://github.com/user-attachments/assets/d762ae1d-875a-43e6-8a1c-ab23ef70aba3" />

Step 7 : Use Docker network to communicate between two containers
Create Custom docker network > Run first container(Container runs in background and terminal attached to it) > Run second container bind to same network 
<img width="1688" height="402" alt="image" src="https://github.com/user-attachments/assets/167746bd-4ef8-49ef-8417-3d56aac285e9" />
 Enter app1 container install ping utility and ping container 2
<img width="1842" height="672" alt="image" src="https://github.com/user-attachments/assets/6331e769-225d-4bd9-bed4-26d42cf122c3" />
<img width="1845" height="697" alt="image" src="https://github.com/user-attachments/assets/b3e80005-e531-416d-82cb-c299ce69cb33" />
<img width="1861" height="186" alt="image" src="https://github.com/user-attachments/assets/03da06a8-d793-482e-b816-73ac987da36d" />

