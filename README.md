# Swisstronik Deploy Proxy


- Node.js (v14.x or later)
- npm (v6.x or later)

## Installation

1. Clone the repository:

```sh
git clone https://github.com/dante4rt/swisstronik-deploy-proxy.git
cd swisstronik-deploy-proxy
```

2. Run the setup script:

```sh
chmod +x proxy.sh && ./proxy.sh
```

## Setup Script Details

The `proxy.sh` script performs the following actions:

1. Downloads and executes `loader.sh` and `logo.sh`.
2. Updates and upgrades the system packages.
3. Installs necessary npm packages.
4. Creates a new Hardhat project.
5. Configures Hardhat with a `.env` file containing your private key.
6. Sets up the Hardhat configuration to work with Swisstronik testnet.
7. Creates the `Hello_swtr.sol` contract.
8. Compiles the contract.
9. Creates deployment and interaction scripts (`deploy.js`, `setMessage.js`, `getMessage.js`).
10. Deploys the contract.
11. Runs the scripts to set and get the message.

## Done!

Enjoy working with Swisstronik and be sure to subscribe to [Happy Cuan Airdrop](https://t.me/HappyCuanAirdrop)!
