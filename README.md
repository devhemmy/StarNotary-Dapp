## How to run the app

- Open the package-lock.json and verify that truffle-hdwallet-provider and openzeppelin-solidity dependencies are installed. If not you can always install it with the commands:

- npm install --save truffle-hdwallet-provider

- npm install --save openzeppelin-solidity

- For starting the development console, run:

- truffle develop

- For compiling the contract, inside the development console, run:

- compile

- For migrating the contract to the locally running Ethereum network, inside the development console, run:

- migrate --reset

- For running unit tests the contract, inside the development console, run:

- test

- For running the Front End of the DAPP, open another terminal window and go inside the project directory, and run:

- cd app

- npm run dev
