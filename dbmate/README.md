## Create a database
dbmate --url "postgres://postgres:abc@localhost:5432/<db_name>?sslmode=disable" create

## Create new migration file
dbmate new <name> //example dbmate new initial

## Run migrations up
dbmate --url "postgres://postgres:abc@localhost:5432/<db_name>?sslmode=disable" up
