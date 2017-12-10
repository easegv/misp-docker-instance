
# Configuring MySQL container

```
(in mysql console from database root user)
> USE mysql;
> UPDATE user SET host='%' WHERE host='localhost';
> FLUSH PRIVILEGES;
```

# Running the image
Use the docker-compose file provided as example.
