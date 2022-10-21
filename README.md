# GOLANG GIN MYSQL JWT

## this is the web development homework

## Part.1 Prepare
1. godotenv库从**.env**文件中读取一些环境变量，保护用户信息的同时方便一些变量的配置
```bash
go get github.com/joho/godotenv
```
2. gorm，一款便捷的操作数据库的go包，但是相比于sqlx和sqlc可能性能上有一点不太行
```bash
go get -u gorm.io/gorm
go get -u gorm.io/driver/mysql
```
#### gorm中文文档
https://gorm.io/zh_CN/docs/connecting_to_the_database.html


