# frp server

## Usage

```
docker run \
  --network host \
  --restart always \
  -v `pwd`/frpc.ini:/var/lib/frp/frpc.ini:ro \
  mosluce/frpc:0.44.0
```
