# Recruto test app


## Lauch container
### 1. Install requirements
- Docker
- Docker compose (optional)

### 2. Clone repository
```bash
git clone https://github.com/username/recruto.git
cd recruto
```

### 3. Build and launch container
```bash
docker build -t recruto .
docker run -d -p 5050:5050 --name recruto_app recruto
```

### 4. Check in browser
```bash
http://localhost:5050
http://localhost:5050/?name={YOUR_NAME}&message={YOUR_MESSAGE}
```