## Create a database
dbmate --url "postgres://postgres:abc@localhost:5432/<db_name>?sslmode=disable" create

## Create new migration file
dbmate new <migration_name> //example dbmate new initial

## Run migrations up
dbmate --url "postgres://postgres:abc@localhost:5432/<db_name>?sslmode=disable" up
dbmate --url "postgres://postgres:abc@localhost:5432/<db_name>?search_path=<schema>&sslmode=disable" up

## Run migrations down
dbmate --url "postgres://postgres:abc@localhost:5432/<db_name>?sslmode=disable" down
