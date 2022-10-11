<p align="center">
  <a href="https://chainide.com">
    <img width="200" src="https://d1hofj2ah5bgy9.cloudfront.net/cell-evolution-logo.svg">
  </a>
</p>

<h1 align="center">Cell Evolution</h1>

<div align="center">

Cell Evolution is the first decentralized sandbox business strategy game based on blockchain, in which all players act as a cell group. In this group, we need to balance our overall adaptability, survivability and reproduction. When the direction of our cell population is out of balance, we will fail to evolve as a whole. This is not just a game, but also a real social group experiment. You play a primitive cell here, and countless you will determine our common destiny. Next, start the evolutionary journey!

</div>

## ⏬ Install git
```
apk add git
```

## ⏬ Download Source Code

```bash
git clone https://github.com/WhiteMatrixTech/cell-evolution-all.git
```

## 📦 Install Dependency

```bash
cd cell-evolution-all
git checkout conflux
```

```bash
yarn
```

## set the privatekey of deploy account

open file `packages/cell-evolution-contracts/.env` , set the privateKey

```
PRIVATE_KEY=XXX
```

## 💻 Compile contract
```
yarn compile:contract
```

## 💻 Depoly Contract
```
yarn deploy:contract
```

## 💻 Package SDK
```
yarn build:sdk
```

## 🧿 Start the Front-end
```
yarn start:webapp
```
