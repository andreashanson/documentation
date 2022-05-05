## Run postgres container
```docker run -e POSTGRES_PASSWORD=abc -p 5432:5432 --rm  postgres```

## Enter the container
```docker exec -it <container_id> psql -U postgres```

## Run migrations on it
```dbmate --url "postgres://postgres:abc@localhost:5432/postgres?sslmode=disable" up```

