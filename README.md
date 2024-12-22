# T3rn Bridge Bot

T3rn Bridge Bot is an automated multi-chain bridge script that simplifies and automates the process of bridging assets across multiple blockchain test networks such as Arbitrum Sepolia, OP Sepolia, Blast Sepolia, and Base Sepolia.

---

## Features

- **Multi-Chain Auto Bridging**: Automates the bridging process across supported networks.
- **Real-Time Transaction Notifications**: Displays transaction details like hash, amount bridged, and success count in real-time.
- **Network Color Coding**: Each network is color-coded for better clarity.
- **Network Connectivity Check**: Verifies connection to the network before initiating transactions.
- **Error Handling**: Provides error messages for failed gas estimations or transactions.

---

## Requirements

- Python 3.7 or higher
- Dependencies listed in `requirements.txt`

---

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/vinskasenda/TirnBot.git
    cd TirnBot
    ```

2. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```

3. Configure your bot:
    - Replace the private keys, addresses, and labels in the `setup.py` file with your own.
    - Set the network RPC configurations in `set_rpc.py`.
    - Update bridge data in `data.py` to match your requirements.

---

## Usage

1. Run the bot:
    ```bash
    python3 t3rn_bridge.py
    ```

2. Follow the on-screen instructions to select the network or execute bridging across all networks.

---

## Notes

- Ensure sufficient funds are available in each wallet for gas fees and transactions.
- The bot can be interrupted safely using `Ctrl + C`.

---

## Join the Community

- Join Telegram: [ZeroDropDAO](https://t.me/ZeroDropDAO)

---

## Contributing

Pull requests are welcome. For major changes, please open an issue to discuss what you would like to change.

---

## License

This project is licensed under the MIT License.
