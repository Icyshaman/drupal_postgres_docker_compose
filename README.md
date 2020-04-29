# drupal_postgres_docker_compose
>**Requirements**:
* docker : https://docs.docker.com/get-docker/
* docker-compose program : https://docs.docker.com/compose/install/

>**How to use**:
* Save docker-compose.yml to a directory.
* Open terminal to that specific directory.
* Start **docker service**.
* Execute **docker-clone up**, this will enable the drupal and postgres service.
* To use drupal go to **host ip address:8080** using browser.
* At the time of setting up database select **database type** as **PostgreSQL**.
* **Database name** is **postgres**.
* **Database username** is **postgres**.
* **Database password** is by default set as **password**, to change it change the value of **POSTGRES_PASSWORD** in docker-compose.yml.
* In **Advanced Options** set **Host** as **postgres**.
* If some error occurs with message **could not connect to server: no route to host** then stop the **firewall service**.
* To stop the service execute **docker-clone stop**. (Data will stored persistently)
