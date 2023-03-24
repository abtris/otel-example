# Example using OTEL with Go

- Grafana/Tempo for observability

- <https://grafana.com/blog/2021/04/13/how-to-send-traces-to-grafana-clouds-tempo-service-with-opentelemetry-collector/>

- <https://grafana.com/docs/tempo/latest/getting-started/example-demo-app/>

## Run

## Prerequistities

- [m1 macs] make own version of 2 docker-images not compatible with ARM

```sh
git clone git@github.com:grafana/xk6-client-tracing.git
cd xk6-client-tracing
make docker
```

```sh
git clone git@github.com:mingrammer/flog.git
cd flog
docker build -t mingrammer/flog .
```

## Use

```sh
docker-compose up
```

## Destroy

```sh
docker-compose down
```
