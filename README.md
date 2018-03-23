# Swarm-sample

## Usage

```
$ git clone https://github.com/kurouw/registry-example.git

$ cd registry-example

$ docker-compose up -d

$ cd ../

$ cd fluentd

$ docker build  --tag localhost:5000/kuro/fluentd

$ docker push localhost:5000/kuro/fluentd

$ cd ../

$ fish init.fish

$ fish start.fish
```
