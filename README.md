# Augur

Augur is a decentralized oracle and peer to peer protocol for prediction markets. Augur is free, public, open source software, portions of which are licensed under the General Public License \(GPL\) and portions of which are licensed under the Massachusetts Institute of Technology \(MIT\) license. Augur is a set of smart contracts written in Solidity that can be deployed to the Ethereum blockchain.

Augur is a protocol, freely available for anyone to use however they please. Augur is accessible through a desktop client app, similar to interacting with an Ethereum or Bitcoin node. Users of the Augur protocol must themselves ensure that the actions they are performing are compliant with the laws in all applicable jurisdictions and must acknowledge that others’ use of the Augur protocol may not be compliant. Users of the Augur protocol do so at their own risk.



## Development Guides

Clone Augur's Monorepo.

* `git clone https://github.com/AugurProject/augur.git`

Then, install the packages using Yarn -- installation _must_ be done via `yarn` and not `npm` since Augur utilizes the Yarn Workspace funcitonality for monorepo support.

* `yarn`

## Make commands

| Command | Purpose |
| :--- | :--- |
| `make build-typescript` | Build all everything but the UI and contracts once |
| `make watch-typescript` | Build everything but the UI and contracts continuously |
| `make build-ui` | Build the UI once |
| `make watch-ui` | Build the UI continuously |
| `make build-contracts` | Build the solidity contracts |
| `make test` | Run the typescript tests. |
| `make build-clean` | Remove JUST typescript build artifacts |
| `make clean` | Remove everything that isn't currently being tracked by git \(node\_modules, build aretifacts, etc.\) |
| `make docker-all` | Run all the needed dockers to run the UI in dev mode |
| `make ipfs-publish` | Publish augur-ui to dnslink for IPFS |
| `make ipfs-pin` | Publish augur-ui to IPFS, pinned in your local node |

## Repository Typescript build commands

NOTE: Run `yarn` at the base of the repository to install dependencies before running any of the following.

| Command | Purpose |
| :--- | :--- |
| `yarn build` | Build all everything but the UI once |
| `yarn build:watch` | Build everything but the UI continuously |
| `yarn build:clean` | Remove JUST typescript build artifacts |
| `yarn clean` | Remove everything that isn't currently being tracked by git \(node\_modules, build aretifacts, etc.\) |
| `yarn docker:all` | Run all the needed dockers to run the UI in dev mode |


