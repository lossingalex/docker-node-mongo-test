# docker-node-mongo-test

## Reference

Tutorial from [Docker development workflow: Node, Express, Mongo](https://medium.com/@sunnykay/docker-development-workflow-node-express-mongo-4bb3b1f7eb1e#.nl5y3gtgf)

## Developpement using composer

```
docker-compose up
```

## Build and Run docker Images

Build

```bash
docker build -t node-mongo-test:0.1 .
```

Run

```bash
> docker run -ti node-mongo-test:0.1 
Example app listening on port 3000!
# test
> curl -i http://localhost:3000/
Hello world
```

