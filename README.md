1. Create the project directory and initialize Go modules:
mkdir student-management-system
cd student-management-system
go mod init student-management-system

2. To create two floder
mkdir backend
mkdir frontend

3.Install MongoDB driver and other necessary packages:
go get go.mongodb.org/mongo-driver/mongo
go get github.com/gorilla/mux  # For routing
go get github.com/dgrijalva/jwt-go  # For authentication (JWT)
go get github.com/joho/godotenv  # For loading environment variables

3.Run the Server :
go run main.go

4 Frontend :
student management system frontend is developed by javascript,html,css

