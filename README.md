
##### 準備
----
```
docker pull mysql
```

##### 環境変数
----
+ ref: https://hub.docker.com/_/mysql/
```
vi env.txt
```

##### 起動
----
```
docker run -itd -P --name some-mysql --env-file env.txt mysql
```
