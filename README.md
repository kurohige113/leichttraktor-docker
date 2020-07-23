# leichttraktor-docker
leichttraktor-docker is simple php container.

# How to start

1. start container
```
docker-compose up -d
```

2. make html
```
docker exec -it web bash
touch index.html
```

3. browse localhost

you can see the website.

4. close container

```
docker-compose down
```

# Overall view
```
.
├── leichttraktor
│   └── ...
└── leichttraktor-docker   <- here
    ├── README.md
    ├── docker-compose.yml
    └── php
        ├── Dockerfile
        └── php.ini
```
