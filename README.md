# PAMIW backend


## Docker Compose

Build Image
```
docker-compose build
```

Run Image
```
docker-compose up
open http://localhost:3000
```


## Docker
Build Image
```
docker build -t pamiw .
```

Run Image
```
docker run -p 3000:80 pamiw
open http://localhost:3000
```

When adding new pip packages be sure to update your requirements.txt. These changes also requires rebuilding of the Docker image.
