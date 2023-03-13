This container has been run from Cloud9, therefore it has this volume
Kindly use pwd to find the current directory location for the index.html page and paste it here
docker run -p 8081:80 -v /home/ec2-user/environment/docker-repo/containers/nginx:/usr/share/nginx/html nginx

Make changes to index.html file and check that these changes are reflected on the running webpage