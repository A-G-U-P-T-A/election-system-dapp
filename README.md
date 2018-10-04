# Election System Dapp

# Step 0. Dependencies
Install these prerequisites to follow along with the tutorial. See free video tutorial or a full explanation of each prerequisite.

NPM: https://nodejs.org

Truffle: https://github.com/trufflesuite/truffle

Ganache: http://truffleframework.com/ganache/

Metamask: https://metamask.io/

# Step 1. Clone the project
~$ git clone https://github.com/A-G-U-P-T-A/election-system-dapp.git

# Step 2. Install dependencies
~$ cd election

~$ npm install

# Step 3. Start Ganache
Open the Ganache GUI client that you downloaded and installed. This will start your local blockchain instance. See video tutorials for full explanation.

# Step 4. Compile & Deploy Election Smart Contract
~$ truffle migrate --reset You must migrate the election smart contract each time your restart ganache.

# Step 5. Configure Metamask
See video tutorials for full explanation of these steps:

Unlock Metamask
Connect metamask to your local Etherum blockchain provided by Ganache.
Import an account provided by ganache using private keys.

# Step 6. Run the Front End Application
~$ npm run dev Visit this URL in your browser: http://localhost:3000
