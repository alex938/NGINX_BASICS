# Basic Nginx Setup Example

# Init project: 
```npm init -y```

# Run it: 
```npm run start```

# Create docker: 
```docker build . -t myserver```


# Run 4 (or as many as you want):

```sudo docker run -p 1111:7777 -d myserver```

```sudo docker run -p 2222:7777 -d myserver```

```sudo docker run -p 3333:7777 -d myserver```

```sudo docker run -p 4444:7777 -d myserver```
