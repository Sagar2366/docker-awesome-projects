### Weather Application using React and Openweather API

Project structure:

```
.
├── public
├── src
├── Dockerfile
├── package-lock.json
├── package.json
└── README.md
```

## Deploy with Docker

```
$ git clone https://github.com/Sagar2366/docker-awesome-projects.git
$ cd docker-awesome-projects/project3
$ docker build -t weather .
$ docker run -itd -p 3000:3000 weather
$ docker save -o weather.tar weather
$ ls -al
$ docker rmi -f weather
$ docker images | grep -i weather
$ docker load -i weather.tar
$ docker images | grep -i weather
```

# Output:
![Output](./output.png)