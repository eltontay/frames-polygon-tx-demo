# Frames Polygon PoS Transaction Demo

This project demonstrates how to use the Frames API to facilitate transactions on the Polygon PoS (Proof of Stake) network. The demo provides a simple interface where users can choose between sending MATIC or expressing love via a transaction-like interface.

## Getting Started

Follow these instructions to set up and run the project locally on your machine.

### Prerequisites

Ensure you have the following installed on your system:

- **Bun**: A fast all-in-one JavaScript runtime. You can install Bun by following the instructions on the official [Bun website](https://bun.sh/).
- **Git**: Version control system to clone the repository.

### Clone the Repository

First, clone this repository to your local machine using Git.

```bash
git clone https://github.com/eltontay/frames-polygon-tx-demo.git
cd frames-polygon-tx-demo
```

### Install Dependencies
Once inside the project directory, install the required dependencies:

```bash
bun install
```

### Run the Development Server
Start the development server with the following command:

```bash
bun run dev
```

### Access the Demo
After starting the development server, you can view the demo by navigating to:

```bash
http://localhost:3000/api/dev
```

This will open the interface where you can interact with the Frames API on the Polygon PoS network.

## Project Structure

Here's a brief overview of the key files and directories in the project:

- **/api**: Contains the server-side logic and API routes.
- **/ui**: Holds the UI components used in the demo.
- **index.tsx**: The main entry point for the demo application.
- **frog.config.ts**: Configuration file for the Frames API.

## How It Works

This demo provides a simple UI with two main actions:

- **Send Matic**: Initiates a transaction to send MATIC tokens on the Polygon PoS network.
- **Send Love**: Displays a message showing love was sent, simulating a non-financial transaction.

Each action transitions through different frames, demonstrating how to interact with the Frames API.

## Contributing

We welcome contributions to enhance this demo. If you'd like to contribute, please:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature/YourFeature`).
3. Commit your changes (`git commit -m 'Add new feature'`).
4. Push to the branch (`git push origin feature/YourFeature`).
5. Open a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgments

- **Frames API**: For providing the core transaction functionality.
- **Polygon Network**: For enabling fast and low-cost transactions.
