**XUnionacy**,is built using [React.js](https://reactjs.org/) and [Typescript](https://www.typescriptlang.org/).

## Goals
To bridge the limitations of microfinance
To expand the scalability of mobile money transactions
## User Interface
peer-to-peer trading interface
Mobile money wallet
rest-api
## Functionality
multiversX node **wallet-connect** is inherited by default
bitcoin LNnode **wallet-connect** for p2p trades
**UGMD** stable coin [in-wallet minting] liquidity pool
**sats-GMD** converter 
**mobile-money-wallet** for deposit, withdraw, transfer, merchant, 


## Milestones
Integrate all the mobile money payments and microfinances into one system
## Software Design Specifications
All the boilerplates we for the entire project is pull from MultiversX dapp template inheriting the core design
See [Unionacy](https://unionacy.wordpress.com/) for more details.

## Requirements

- Node.js version 16.20.0+
- Npm version 8.19.4+

## Getting Started

The dapp is a client side only project and is built using the [Create React App](https://create-react-app.dev) scripts.

### Instalation and running

### Step 1. Install modules

From a terminal, navigate to the project folder and run:

```bash
yarn install
```

### Step 2. Running in development mode

In the project folder run:

```bash
yarn start:devnet
yarn start:testnet
yarn start:mainnet
```

This will start the React app in development mode, using the configs found in the `vite.config.ts` file.
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.\
You will also see any lint errors in the console.

### Step 3. Build for testing and production use

A build of the app is necessary to deploy for testing purposes or for production use.
To build the project run:

```bash
yarn build:devnet
yarn build:testnet
yarn build:mainnet
```

## Roadmap

See the [open issues](https://github.com/multiversx/xunionacy/issues) for a list of proposed features (and known issues).

## Contributing

Contributions are what make the open source community such an amazing place to be learn, inspire, and create. Any contributions you make are **greatly appreciated**.

One can contribute by creating _pull requests_, or by opening _issues_ for discovered bugs or desired features.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request
