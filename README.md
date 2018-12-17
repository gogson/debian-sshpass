# debian-sshpass
Debian docker image with curl

# Example

```
docker run gogson/debian-sshpass -p 'YOUR_PASSWORD' ssh -o "StrictHostKeyChecking=no" user@host -p PORT COMMAND
```

Will start the container and exec the given `COMMAND` on a remote SSH server.