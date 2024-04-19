# Setup

Set node version

```bash
nvm install && nvm use
```

Install dependencies for both sub projects

```bash
cd client/
npm i
cd ../
cd server/
npm i
```

# Spinning up a local mongo

```bash
docker run --name todo-list -p 27017:27017 -d mongo:latest
```

# How To run Server

```bash
cd server/
yarn build
yarn start
```

# How to run Client

```bash
cd client/
yarn start
```