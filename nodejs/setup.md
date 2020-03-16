# Nodejs

### Node バージョン管理
```
# install
curl -o- https://raw.githubusercontent.com/creationix/nvm/v0.34.0/install.sh | bash

#setup bash
source ~/.bashrc

#試し
nvm list

# node install
nvm install v10.14.2
nvm use v10.14.2

# バージョン情報
nvm list
```

### Yarn
```
# install
curl -o- -L https://yarnpkg.com/install.sh | bash -s -- --version 1.13.0

# setup
source ~/.bashrc
```

### Express template
```
# install
yarn global add express-generator@4.16.0

express --view=pug ${folder-name}
```
