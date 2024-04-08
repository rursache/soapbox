# soapbox
Docker container for soapbox - https://gitlab.com/soapbox-pub/soapbox

```
docker run -d \
  --name soapbox \
  --restart unless-stopped \
  -p 5000:5000 \
  -e TZ=Europe/Bucharest \
  rursache/soapbox:latest
```
