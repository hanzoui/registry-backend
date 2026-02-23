# Generate Hanzo Studio Node Pack Information

Execute the following command. You can adjust `CUSTOM_NODE_URL` and `CUSTOM_NODE_NAME`.

```bash
docker compose run node-pack-extact \
    --build \
    -e CUSTOM_NODE_URL=https://storage.googleapis.com/comfy-registry/altkeyproject/hanzo-studio-dream-project/1.0.6/node.tar.gz \
    -e CUSTOM_NODE_NAME=hanzo-studio-dream-project \
    hanzo-studio-dream-project-nodepack.json
```

The command will produce `hanzo-studio-dream-project-nodepack.json` under [`output`](./output/) directory.
