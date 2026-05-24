# An Apache Tomcat 9 and PostgreSQL 15 Environment

The base Apache Tomcat image for this project is maintained here:
[Avium Labs - Tomcat Ant](https://github.com/aviumlabs/tomcat-ant-img)

**2026-05-23**
Update to Apache Tomcat 9.0.118

## Stack
- Apache Tomcat 9.0.118
- PostgreSQL 15.

## Pull Latest
In the Docker compose file, update the `app` `image` entry to the desired Apache Tomcat version.

```shell
docker compose pull
```

## Running 

Run the containers in the foreground:
```shell
docker compose up
```

Run the containers in the background:
```shell
docker compose up -d
```
