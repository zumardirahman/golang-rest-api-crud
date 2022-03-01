# Getting Started
### Running App

Create and Run MySQL Database, DBNAME : "go_rest_api_crud"

then:

    go run main.go


# Step Productions

#### Install GoLang
Official binary distributions are available at https://golang.org/dl/.

After downloading a binary release, visit https://golang.org/doc/install
for installation instructions.

    go mod init rest-api-crud

#### Install Gorilla Mux
Gorilla `mux`: For creating routes adn HTTP handlers.
    
    go get -u github.com/gorilla/mux
    

#### Install Gorm
`gorm`: An ORM tool for MySQL.
    
    go get -u gorm.io/gorm
    

#### Install MySQL Driver
`mysql`: The MySQL driver.
    
    go get -u github.com/go-sql-driver/mysql
    

#### Create Database 

MySQL Database : DBNAME "go_rest_api_crud"