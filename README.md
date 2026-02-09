# Cyber Security

## 6702041510237 

-Plengpin Cheerapat 
- email : s6702041510237@email.kmutnb.ac.th

## Environment
cp env.example .env

## Running service

### Database

```sh
docker compose -f db.yaml up -d
```
### ADMIN
```sh
docker compose -f admin.yaml up -d
```
### APP
```sh
docker compose -f app.yaml up -d
```