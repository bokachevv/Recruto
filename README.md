# Recruto test app

## Option 1. Launch container with DockerHub
```bash
docker run -d -p 5050:5050 ibokachev/recruto
```

## Option 2. Launch container with GitClone
### 1. Clone repository
```bash
git clone https://github.com/username/recruto.git
cd recruto
```

### 2. Build and launch container
```bash
docker build -t recruto .
docker run -d -p 5050:5050 --name recruto_app recruto
```

## Check in browser
```bash
http://localhost:5050
http://localhost:5050/?name={YOUR_NAME}&message={YOUR_MESSAGE}
```

## Remove files
```bash
docker stop recruto_app #stop container
docker rm recruto_app #remove container
docker rmi recruto #remove image
```