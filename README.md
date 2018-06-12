# docker-wordpress-adminer
Step 1. Replace password string in docker-compose.yml file with your own secret password and also change in wp-config.php file under wordpress directory.

Step 2. Run $ docker-compose up -d

Step 3. Visit localhost:8080 login to adminer, and create a database called 'wordpress'

Step 4. After Creating Database ( wordpress ) Visit localhost and install wordpress.

Step 5. To Stop all Conatiners and remove their volumes Run following command :->
            docker-compose down -v
