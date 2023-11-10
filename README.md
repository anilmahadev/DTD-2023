# DTD-2023
Dallas Training Day Slide and Code for Oracle Containers with Docker

Demo Scripts DALLAS TRAINING DAY 2023


Non-Persistent version

docker run -d -p 1521:1521 -e ORACLE_PASSWORD=<your password> gvenzl/oracle-free 

Persistent version

docker run -d -p 1521:1521 -e ORACLE_PASSWORD=<your password> -v oracle-volume:/opt/oracle/oradata gvenzl/oracle-free

Make modifications

docker commit <container-ID>  <New Image Name>
