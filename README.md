# API Autenticator JWT

## About the project

- An api for create user and products with autenticator jwt
App use Golang with Gorm

## How to run the api?

**Step 1: Clone the project, run the following commands:**

**Step 2: Create file .env in cmd/server**
	DB_DRIVER=mysql
	DB_HOST=localhost
	DB_PORT=3306
	DB_USER=root
	DB_PASSWORD=root
	DB_NAME=db_api_user_jwt
	WEB_SERVER_PORT=8000
	JWT_SECRET=secret
	JWT_EXPIRESIN=300

**Step 3: go mod tidy(at the root of the project)**
- go mod tidy

**Step 4: run api. In folder cmd/server execute;**
- go run main.go

# Link Doc(Swagger)
http://localhost:8000/docs/index.html
To generate docs, run; swag init -d cmd/server/main.go
