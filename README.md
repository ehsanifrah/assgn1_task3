# Assignment 1 - Task-3

### create docker volume
![create docker volume](image.png)

### create container using image and mount vol
![nginx image](image-4.png)

### "nginx" default page is accessible on your host machine at http://localhost:8080.
![nginx page is accessible](image-2.png)

### create html file
![html file](image-3.png)

### copy index.html file to volume
![copy file](image-14.png)

### http://localhost:8080/index.html.
![html file](image-5.png)

### stop and remove container
![Alt text](image-6.png)

### new Docker container using the "httpd" image
![httpd image](image-7.png)

### create about.html file
![about file](image-8.png)

### copy about.html file to volume
![copy file to container's volume](image-9.png)

### http://localhost:8081/about.html.
![Alt text](image-10.png)

### stop and remove container
![Alt text](image-11.png)

### Verify Files
i have run inspect command to verify it
![Alt text](image-13.png)
but you can only verify files using command in linux, in mac and windows either you create new container to verify or use docker desktop to verify it.
![docker volume](image-12.png)

### Remove Volume
![remove vol](image-15.png)
