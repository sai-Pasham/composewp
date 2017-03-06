# composewp


docker-compose up -d

http://localhost:8000/

NOTE : it will take couple of minutes for WP to come up, do not get restless

https://docs.docker.com/compose/wordpress/#build-the-project

Shutdown/Clean up
</BR>
<code>docker-compose down</code> will remove the containers and default network, but preserve your wordpress database. 
</BR>
<code>docker-compose down --volumes</code> will remove the containers, default network, and the wordpress database.
