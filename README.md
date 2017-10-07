### jenkins in docker

#### Pull image
```bash
docker pull huitseeker/jenkins[:TAG]
```

#### Run container
```bash
docker run -d --name jenkins -p 8888:8080 -p 50000:50000 <image ID>
```
