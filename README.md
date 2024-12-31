![luminara logo](./luminara.jpeg)
# Namada Ecosystem -- Community Run Resources

This repo contains a directory of community run Namada resources -- rpcs, indexers, interfaces, monitoring tools, and more!

You can view the directory in json format inside the `user-and-dev-tools` directory, or you can check out the auto-generated gitbook: https://luminara-hub.gitbook.io/namada-ecosystem.

## Getting your tool listed
If you're operating some Namada-related infra or have another resource you'd like to make available in this directory, please follow these steps:
1. Fork this repo, and make sure it's current with the latest changes by clicking the 'Sync Fork' button in GitHub (inside your fork).
2. Add your tool(s) by editing the appropriate json file(s) in your fork, inside the `user-and-dev-tools` directory. If your tool is for mainnet, please add it to the the `mainnet` directory, and if your tool is for the
`housefire-alpaca` testnet, please add it to the `testnet` directory.  

**IMPORTANT NOTE:** please edit the json files inside `mainnet/testnet` only -- you don't need to touch anything inside the `gitbook` directory. The gitbook `.md` files are auto-generated from the json after each update. When your PR is merged into the main repo, they will automatically update to reflect your additions.  

3. Once you've added your tools to the json file(s), make a PR to this repo.  

That's it! If you have any questions, please don't hesitate to reach out in the #housefire-canary-net or #mainnet-coordination channels in the Namada Discord server.
