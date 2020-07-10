## *Mysql Wordpress* Application Deployment on Kubernetes Cluster

#### SECTIONS

- **[Deploying Application using Secret and no Persistent Storage](https://github.com/HemantGangwar/k8-mysql-wordpress/tree/master/wordpress_storageless)**

Steps | Command
----- | -------
Cloning Git Repository | # git clone https://github.com/HemantGangwar/k8-mysql-wordpress
Entering suitable directory | # cd k8-mysql-wordpress/wordpress_storageless
Running Commands in Sequence | # kubectl create -f secret.yml </br > # kubectl create -f mysql.yml </br > # kubectl create -f mysql-service.yml </br > # kubectl create -f wordpress.yml </br > # kubectl create -f wp-service.yml  
