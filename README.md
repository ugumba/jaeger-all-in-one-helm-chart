This is a helm chart of the [Jaeger all-in-one dev setup](https://github.com/jaegertracing/jaeger-kubernetes#development-setup)

# Installation

```
git clone <this repo>
cd <this repo>
helm install .
```

If you've installed this in Docker For Desktop, then you can now reach the Jaeger UI at http://localhost:80

## Configure Port

Change the Jaeger UI port by installing like this:

```
helm install --set port=8037
```
