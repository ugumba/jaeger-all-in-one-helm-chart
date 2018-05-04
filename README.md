This is a helm chart of the [Jaeger all-in-one dev setup](https://github.com/jaegertracing/jaeger-kubernetes#development-setup)

# Installation

```
helm install https://github.com/cory-klein/jaeger-all-in-one-helm-chart/raw/master/jaeger-all-in-one-0.1.0.tgz
```

If you've installed this in Docker For Desktop, then you can now reach the Jaeger UI at http://localhost:80

## Configure Port

Change the Jaeger UI port by installing like this:

```
helm install --set port=8037 https://github.com/cory-klein/jaeger-all-in-one-helm-chart/raw/master/jaeger-all-in-one-0.1.0.tgz
```
