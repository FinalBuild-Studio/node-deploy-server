# node-deploy-server
A simple nodejs service to handle your project deployment via http.

### Installation
```sh
npm i
```

### How to use
```sh
SECRET={DEFINE_YOUR_SECRET_STRING_HERE} ./node-deploy-server
```

### Acceptable json schema
```json
{
  "dist": "/path/you/want/to/store",
  "owner": "CapsLock-Studio",
  "repo": "node-deploy-server",
  "tag": "XX.XX.XX",
  "command": "Command you want to execute after success"
}
```
