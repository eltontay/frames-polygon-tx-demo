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

## Deployment

You can deploy this project on your favorite hosting platform. If you choose to use Vercel, follow these steps:

1. **Deploy the Project**: You can easily deploy this project by connecting your GitHub repository to Vercel. Once deployed, grab the URL provided by Vercel.

2. **Check Your Deployment on Warpcast**: 
   - Go to the [Warpcast developer page](https://warpcast.com/~/developers/frames).
   - Input the Vercel link (e.g., `https://frames-polygon-tx-demo-navy.vercel.app/api`) to ensure your deployment is functioning correctly.

3. **Share on Warpcast**:
   - Go to [Warpcast](https://warpcast.com/), create a post, and include the Vercel link along with your description.
   - Example: "4 more days till MATIC becomes POL! I have created a frame for you to either send MATIC or spread the love ❤️ [Vercel Link]".

Voila! Your Frame is live and shared with the world.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgments

- **Dabl Club** : The space for builders to unite to create the future of Polygon.
  - **Farcaster Fridays**: Hosting events around the world. [Join events on Luma](https://lu.ma/DablClub)
  - **Telegram Group**: Stay up to date by joining the [Telegram group chat](https://t.me/dablclub) (@dablclub).
  - **Learn at Dabl Club**: [Dabl into Web3](https://learn.dabl.club) with curated courses, blogs, podcasts, and more. For noobs, experts, and everyone in between.
  - **Grow with Dabl Club**: [We offer mentors, vouchers, & partner connects](https://dabl.club/grow) to promising projects in the ecosystem.
- **Polygon Network**: For enabling fast and low-cost transactions.
  - **Polygon PoS**: [Visit the Polygon PoS website](https://polygon.technology/polygon-pos)
  - **MATIC to POL Migration**: The MATIC to POL migration is scheduled for September 4th. [Everything you need to know about the migration](https://polygon.technology/blog/save-the-date-matic-pol-migration-coming-september-4th-everything-you-need-to-know)
- **Frames API**: For providing the core transaction functionality. [Learn more about Frog API](https://frog.fm/)
- **Farcaster**: For being the platform behind Frames. [Learn more about how to build Frames](https://docs.farcaster.xyz/developers/frames/)
- **Authors** Mel , Elton