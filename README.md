# Decentralized Talent-Connect

To run the application in devleopment mode,

After cloning the repository

1. Install Ganache and Truffle globally

```bash
npm i -g ganache truffle
```

2. Change directory into the client, and install required dependencies

```bash
cd client
```

```bash
npm i
```

3. Inside a terminal, run ganache

```bash
ganache
```

4. Set up Metamask extension in your browser.

5. Set up truffle network config. In truffle-config.js in /truffle, under networks, make sure the host and port matches the host and port being listened by ganache.

6. Add this network in Metamask and switch to this network

7. From repository's root directory, change directory into truffle and deploy the smart contracts.

```bash
cd truffle
```

```bash
truffle migrate
```

8. From the terminal running Ganache, copy the private key of a user, and import the user into metamask.

9. Now inside client directory, start the frontent application

```bash
npm run dev
```

The React-Frontend for the application should be running at your 127.0.0.1 (i.e., localhost) port 5173 (or the port mentioned in the terminal after running) i.e., 127.0.0.1:5173/ 
