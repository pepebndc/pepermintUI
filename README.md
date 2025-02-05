# Peppermint Token Deployer UI

A web-based interface for deploying various types of tokens using the Peppermint API. This tool allows you to easily deploy ERC20, ERC721, and ERC1155 tokens with different configurations.

## Features

- Support for multiple token standards:
  - ERC20 (Mintable/Burnable)
  - ERC721 (Basic, Purchasable, Royalties, Soulbound)
  - ERC1155 (Basic, Purchasable, Royalties, Soulbound)
- Secure vault-based token deployment
- Multiple blockchain support
- Easy-to-use interface
- Automatic API key management
- Support for royalties configuration

## Getting Started

1. Get your API key from [Peppermint Dashboard](https://dashboard.peppermint.tools)
2. Create a vault in the Peppermint dashboard
3. Open the token deployer interface
4. Enter your API key
5. Select your vault
6. Choose your desired token type and configure parameters
7. Deploy your token

## Token Types and Features

### ERC20

- Mintable and burnable capabilities
- Configurable decimals

### ERC721 (NFT)

- Basic implementation
- Purchasable version with pricing
- Royalties support
- Soulbound version (non-transferable)

### ERC1155 (Multi-Token)

- Basic implementation
- Purchasable version
- Royalties support
- Soulbound version

## Security

- API keys are stored locally in the browser
- Secure communication with Peppermint API
- No private keys are handled in the interface

## Requirements

- Modern web browser
- Peppermint API key
- Active vault in Peppermint dashboard
