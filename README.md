# alpine-shadowsocks-client

To start a container, run

```sh
sudo docker run -d --restart=yes \
                -e SERVER=<your-server> \
                -e SERVER_PORT=<port> \
                -e LOCAL_PORT=1080 \
                -e PASSWORD=<your-password> \
                -p 1080:1080 alpine-shadowsocks-client
```
