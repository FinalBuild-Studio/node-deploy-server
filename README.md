# node-deploy-server ![node-requirement](https://img.shields.io/badge/Nodejs-7.x.x-green.svg)
Lightweight cross platform self-hosted deployment server solution. Make deployment easier! 🚀

### Requirement
Node.js >= **7.0.0**

### Installation
```sh
npm install
```

### How to use
```sh
SECRET={DEFINE_YOUR_SECRET_STRING_HERE} ./node-deploy-server
```

### Windows Users
```sh
set SECRET={DEFINE_YOUR_SECRET_STRING_HERE}

node ./node-deploy-server --harmony-async-await
```

### For those who do not want to set ENV in shell
Modify `.env.exmple` to `.env` and changing to property setting.

### Acceptable incoming json schema
```json
{
  "dist": "/path/you/want/to/store",
  "owner": "CapsLock-Studio",
  "repo": "node-deploy-server",
  "tag": "XX.XX.XX",
  "command": [
    "Command you want to execute after success"
  ],
  "ignore": [
    "/folder/you/do/not/want/to/copy"
  ]
}
```
