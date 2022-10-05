# LocalHuahua
An instant, zero-config Huahua blockchain.

```bash
docker run -it --rm -p 9091:9091 -p 26657:26657 -p 1317:1317 -p 5000:5000 \
  --name localhuahua ghcr.io/scrtlabs/localhuahua
```

Full docs: https://docs.scrt.network/docs/development/local-huahua

# Source

You can trace everything from `build-localhuahua` in [`Makefile`](https://github.com/ChihuahuaChain/chihuahua/blob/master/Makefile), but the gist of it is in [`bootstrap_init_no_stop.sh`](https://github.com/ChihuahuaChain/chihuahua/blob/master/deployment/docker/devimage/bootstrap_init_no_stop.sh).