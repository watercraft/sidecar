# sidecar
A Golang Proxy Example for the Side-Car Authentication Pattern

Reference: https://reintech.io/blog/creating-simple-proxy-server-with-go
```
export SIDECAR_PORT=8081
export SIDECAR_SERVICE_ENDPOINT=localhost:8080
go run sidecar.go
