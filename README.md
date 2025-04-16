# Foundry Smart Contracts Boiler Plate

A comprehensive boilerplate for Ethereum smart contract development using Foundry, featuring integration with OpenZeppelin and Uniswap contracts.

## Features

- 🛠️ Built with [Foundry](https://github.com/foundry-rs/foundry) - Fast, portable and modular toolkit for Ethereum application development
- 🔒 OpenZeppelin Contracts integration
  - Standard contracts
  - Upgradeable contracts
- 🔄 Uniswap Integration
  - V2 Core and Periphery
  - V3 Core and Periphery
  - V4 Core and Periphery
- 📦 Well-organized project structure
- 🧪 Comprehensive testing setup
- 🔄 Git submodules for dependency management

## Prerequisites

- [Foundry](https://github.com/foundry-rs/foundry) - Install using:
  ```bash
  curl -L https://foundry.paradigm.xyz | bash
  foundryup
  ```

## Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/Foundry-Smart-Contracts-Boiler-Plate.git
   cd Foundry-Smart-Contracts-Boiler-Plate
   ```

2. Install dependencies:
   ```bash
   git submodule update --init --recursive
   ```

3. Build the project:
   ```bash
   forge build
   ```

4. Run tests:
   ```bash
   forge test
   ```

## Project Structure

```
├── src/           # Source files
├── test/          # Test files
├── script/        # Deployment and utility scripts
├── lib/           # External dependencies
└── foundry.toml   # Foundry configuration
```

## Dependencies

- OpenZeppelin Contracts
- OpenZeppelin Contracts Upgradeable
- Uniswap V2, V3, and V4
- Forge Standard Library

## Usage

1. Create new contracts in the `src` directory
2. Write tests in the `test` directory
3. Use deployment scripts in the `script` directory

## Testing

Run tests with:
```bash
forge test
```

For more detailed test output:
```bash
forge test -vv
```

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## Acknowledgments

- [Foundry](https://github.com/foundry-rs/foundry)
- [OpenZeppelin](https://openzeppelin.com/)
- [Uniswap](https://uniswap.org/)
