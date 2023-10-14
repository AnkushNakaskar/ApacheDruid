## Apache Druid
* This document explains the installation of apache druid
* Steps are as below :
  * First visit link : https://druid.apache.org/docs/latest/tutorials/docker/
  * Clone druid repo : https://github.com/apache/druid
    * active version is 27.0.0
    * run ```docker-compose -f distribution/docker/docker-compose.yml up ```
    * Once it is up and running , you can cross check the link : http://localhost:8888/unified-console.html
   
  * If you face any error related to port bind, you cna refer the terminal_output in repo
