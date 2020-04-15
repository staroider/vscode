# VS Code on Staroid ⭐️

Run VS Code on the Cloud. Fork and customize as much as you want!

### [Click here to Launch on Staroid!](https://preview.staroid.com/g/staroider/vscode)

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
