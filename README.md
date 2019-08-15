# hello-docker-python
First steps docker with python

- Dockerfile
```
FROM python:3 
ADD {localFile} {imageFolder} 
RUN pip install pystrich  
CMD [ "python", "./hello.py" ]
```

- Build image  
```docker build -t {tagImage} . ```

- Run image  
```docker run {imageName}```

- List installed images  
``` docker images ```

- List running containers  
```docker ps ```

- List all containers  
```docker ps -a```

- Stop a running container  
```docker container stop {container-id}```




