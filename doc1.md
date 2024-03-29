## create porject Directory ./gin_one

```sh
mkdir gine_one
cd gine_one
go mod init gine_one
```

## install CompileDaemon

```sh
go get github.com/githubnemo/CompileDaemon
# installing it when i wanna used it as a command will go to ~/go folder as executable 
go install github.com/githubnemo/CompileDaemon
```
## install dotenv package

```sh
go get github.com/joho/godotenv
```

## install Gin Framework

```sh
go get -u github.com/gin-gonic/gin
```

## install GORM stands for Go ORM => Object Relational Mapping

```sh
go get -u gorm.io/gorm
```

## install GORM DRIVER FOR THE USED DATABASE (sqlite,postgres,mysql,...)
```sh
go get -u gorm.io/driver/postgres
```
## now create the structure of Project

```sh
-gine_one
    -initializers
        -database.go
        -loadEnvVariables.go
    -migrate
        -migrate.go
    -models
        -postModel.go
    -.env
    -go.mod
    -go.sum
    main.go
```



