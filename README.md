# P2P BTC Node ⚡

Node application for Node Runners

⚠️**Beta software**

## How run?

**Pre Requisite**

- Nostr-js
- Lightning-js
- Node.js
- NPM
- Git
- Lightning Node (LND)

**Step 1**

Create a new directory for your project and navigate to it in your terminal. Then, initialize a new Node.js project by running the following command:

```npm
npm init -y
```

**Step 2**

Install dependencies

Install the required packages, nostr-js and lightning, by running the following command:

```npm
npm install nostr-js lightning
```

**Step 3**

Make sure to replace the placeholders **(localhost:10009, /path/to/tls.cert, and /path/to/admin.macaroon)** in the **lnd** configuration with the appropriate values for your Lightning Network node.

**Step 4**

Start the application

Save the changes to app.js, and in your terminal, run the following command to start the application:

```node.js
node app.js
```
Now, your Node application is up and running, and it will listen for incoming messages via Nostr. You can customize the processMessage function to handle the received messages and interact with the Lightning Network using the lnd instance.

## Roadmap

- [ ] FOSS
- [ ] LDK
- [ ] CLN
- [ ] Eclair
- [x] Alpha Software
