翔泳社 Spring徹底入門のサンプルアプリケーションをカスタマイズ。
* Spring Bootのバージョンを1.5.7へ変更
* PostgreSQLのDDL・DMLをMySQLに対応させた。



PostgreSQLモードで起動

```
java -jar target/mrs-0.0.1-SNAPSHOT.jar   --spring.profiles.active=postgresql
```

MySQLモードで起動

```
java -jar target/mrs-0.0.1-SNAPSHOT.jar   --spring.profiles.active=mysql
```
