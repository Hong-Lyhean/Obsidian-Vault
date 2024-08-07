List installed Node.js versions
``` bash
nvm list
```

Install new version, can replace it with specific version too like: 22.5.0
``` bash
nvm install 22
```

Change Node.js or npm version
``` bash
nvm use 14.17.3
```

Make specific version to default version 
``` bash
nvm alias default 14
```

Uninstall Node.js and npm
``` bash
nvm uninstall v14.17.3
```

(Optional) Remove npm cache If you want to clean up npm cache files associated with the removed version
``` bash
npm cache clean --force
```

