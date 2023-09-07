## Proof of concept template for Immunefi's Bug Bounty

### Prerequisites:
- Prepared SGX environment (SGX SDK + SGX PSW)

### Steps:
1. Compile latest version of swisstronikd from master branch
2. Using command swisstronikd testnet init-config —chain-id swisstronik_1291-1
3. Start local testnet using sudo docker-compose -f local-network.yml up inside directory with cloned repo
