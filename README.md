# subgraph-rootkit
This is our subgraph, a collection of GraphQL schemas and mappings that parse the events broadcast by the Rootkit on the Ethereum blockchain.

Our smart contracts can be found in this repository https://etherscan.io/address/0xcb5f72d37685c3d5ad0bb5f982443bc8fcdf570e#code.

# Development
Before you can build, create and deploy this subgraph, you have to execute the following commands in the terminal:

$ yarn install
$ yarn prepare:mainnet
The first command installs all external dependencies, while the latter generates the subgraph.yaml file, which is required by The Graph.
the manual hot to deploy Subgraph you can find here https://colliseum2006-23245.medium.com/как-быстро-задеплоить-subgraph-пошаговый-чеклист-функций-в-power-shell-a8f4741c6288
