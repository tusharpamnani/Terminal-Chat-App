# Rust TCP Client-Server Communication

This repository contains a simple implementation of a TCP client-server communication in Rust. The communication involves sending and receiving messages between a server and multiple clients.

## Getting Started

### Prerequisites

- Rust programming language: [Install Rust](https://www.rust-lang.org/tools/install)

### Running the Server

1. Clone the repository:

    ```bash
    git clone https://github.com/tusharpamnani/Terminal-Chat-App.git
    cd Terminal-Chat-App
    ```

2. Build and run the server:

    ```bash
    cargo run --bin server
    ```

### Running the Client

1. Open a new terminal window.

2. Clone the repository (if not done already):

    ```bash
    git clone https://github.com/tusharpamnani/Terminal-Chat-App.git
    cd Terminal-Chat-App
    ```

3. Build and run the client:

    ```bash
    cargo run --bin client
    ```

## Usage

- The server listens for incoming connections on `127.0.0.1:6000`.
- Multiple clients can connect to the server simultaneously.
- Type messages in the client terminal and press Enter to send them to the server.
- Type `:quit` in the client terminal to exit the client.
- The server displays received messages from clients in its terminal.

## Contributing

Feel free to contribute by submitting issues or pull requests.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
