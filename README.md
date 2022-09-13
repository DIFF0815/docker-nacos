# docker-nacos 环境
## 开始
```shell
#配置文件
cp .env.example .env
cp docker-compose.example.yml docker-compose.yml
```
* 修改.env 里面的数据库配置（新建数据库，把目录下的nacos-mysql.sql导入数据数据库里面）
* 修改docker-compose.yml(使用默认不需要修改)

## nginx
修改nginx/conf里面的配置文件的ip为自己的ip

## 启动
`docker-compose up -d`

## 访问
地址：`http://自己的ip/nacos` 账号：nacos，密码：nacos (比如地址：http://192.168.240.120:8848/nacos)
