# VS Code on Staroid ⭐️

Run VS Code on the Cloud. Fork and customize as much as you want!

[![Run](https://staroid.com/api/run/button.svg)](https://staroid.com/api/run)

## Branch

| Branch |  Code-server version|
| ------ | --------------- |
| Master | latest          |

This project packages pre-built [code-server](https://hub.docker.com/r/codercom/code-server) docker image and run on [Staroid](https://staroid.com).

## Development

Run locally with [skaffold](https://skaffold.dev) command.

```
$ skaffold dev --port-forward
```

and browse `http://localhost:8080`
