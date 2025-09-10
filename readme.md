# Howdy

Please refer to https://github.com/spectrocloud/pack-central as a good example for Community Packs.

Please refer to https://docs.spectrocloud.com/tutorials/packs-registries/deploy-pack/ for tutorial and documentation around packs.

My internal registry for testing is at `registry.n.wcrum.dev`, for credentials, ask Will.

# Commands Ran


## Getting all Images
```
helm template . | grep image:
```

## Pushing to OCI Registry
```
oras push localhost:9100/library/spectro-packs/archive/antrea:2.4.1 antrea-2.4.1.tar.gz
oras push localhost:9100/library/spectro-packs/archive/flow-aggregator:2.4.1 flow-aggregator-2.4.1.tar.gz
oras push localhost:9100/library/spectro-packs/archive/theia:0.8.0 theia-0.8.0.tar.gz
```