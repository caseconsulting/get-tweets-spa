# get-tweets

1. [Caution](#caution)
1. [Installation](#installation)
1. [Server](#server)

## Caution

Ensure that you read the [API Docs](https://dev.twitter.com/docs), most importantly the [rate limiting and black listing](https://dev.twitter.com/rest/public/rate-limiting).

## Installation

Copy the repo.

```bash
mkdir -p ~/GitHub/caseconsulting && cd $_
git clone git@github.com:caseconsulting/get-tweets-spa.git
cd get-tweets-spa
```

Install packages.

```bash
yarn install
```

Create an .env file. See the [sample](env.example) for more information.

```bash
cp env.example .env
vim .env
```


## Server

```bash
yarn start
```
