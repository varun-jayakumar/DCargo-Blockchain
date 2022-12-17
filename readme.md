# DCargo-Blockchain

Dcargo is a combination of hardware and web application which have been developed to monitor cargo containers in a more reliable and secure manner by storing backup data in IPFS using an Ethereum smart contract. This ensures that the data is preserved even in the event of a database failure, making the application failsafe. The application provides a secure and efficient way to track cargo containers.

## Components of the Project

The project has three Components

![architecture](https://github.com/varun-jayakumar/DCargo-Blockchain/blob/main/screenshots/architecture.jpg?raw=true "Application Architecture")

a) NodeJS push API: Responsible for getting data from hardware and post data to Firebase and IPFS storage using Blockchain
b) Client App: Display Data from IPFS storage and Firebase
c) NodeJS Blockchain API: acts as an bridge between blockchain smartcontract and client app to retrive data

## 🚨Instructions to Run the project🚨

This project is not complete with out the Hardware setup and would not give viewable results So, I have not included the details to run it. However, below are the details to run induvidual components of the project except the Hardware

a) The client app in `Cargo-Monitoring-Client-Dapp-main` the static build files inside `Cargo-Monitoring-Client-Dapp-main/public` directory

```
npm i
npm i serve
server public/index.html
```

b) The NodeJS push API can be found under `NodeMCU_push_server-main` and `index.js` is the entry point to the API

```
npm install
node index.js
```

c) The NodeJS Blockchain API can be found under `Node-JS-API-for-Blockchain-main` and `index.js` is the entry point to the API

```
npm install
node index.js
```

Note: update API endpoints in Client App when run locally `Cargo-Monitoring-Client-Dapp-main/public/app.js`

### Any questions?

drop a mail at [jayakumar.va@northeastern.edu](mailto:jayakumar.va@northeastern.edu) 😃

Thanks for reading!

> written by Varun Jayakumar
