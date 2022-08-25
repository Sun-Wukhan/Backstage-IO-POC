# [Backstage](https://backstage.io)

This is your newly scaffolded Backstage App, Good Luck!

To start the app, run:

```sh
yarn install
yarn dev
```

yarn install --frozen-lockfile
yarn tsc   
yarn build 

yarn --cwd packages/backend start
sudo npm install -g js-yaml   

nvm install 14.17.0  
yarn add --cwd packages/backend pg
yarn add --cwd packages/backend better-sqlite3  

docker image build . -f packages/backend/Dockerfile --tag backstage

docker run -it -p 7007:7007 backstage
