 docker run -d --name fronttod -p 888:80 todo-front:latest
 docker build -t todo-front:latest .   
 docker build -f ./02-dockerfile/Dockerfile.dev -t mycustom-image:latest ./02-dockerfile/   