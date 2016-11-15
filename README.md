# node-deploy-server
Lightweight cross platform self-hosted deployment server solution. Make deployment easier! 🚀

### Requirement
Node.js >= 7.0.0

### Installation
```sh
npm install
```

### How to use
```sh
SECRET={DEFINE_YOUR_SECRET_STRING_HERE} ./node-deploy-server
```

### Acceptable incoming json schema
```json
{
  "dist": "/path/you/want/to/store",
  "owner": "CapsLock-Studio",
  "repo": "node-deploy-server",
  "tag": "XX.XX.XX",
  "command": "Command you want to execute after success"
}
```
