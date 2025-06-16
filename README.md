# Solana Wallet Private Key Finder: Recover and Manage Your SOL Keys

**SolanaChecker** is a robust tool designed to interact with the Solana blockchain. It offers a suite of features for checking wallet status and managing your digital assets. A key function is the ability to find your Solana wallet private key from your seed phrase.

<p align="left">
    <img src="/renders/frame.webp" />
</p>

## Program Features, Including Private Key Recovery

1.  **Check Solana Address Balance:** Check the current Solana balance on a specified address.

<p align="left">
    <img src="/renders/plan.webp" />
</p>

2.  **Check Solana Tokens for Fraud:** Assess token security based on characteristics.

<p align="left">
    <img src="/renders/over.webp" />
</p>

3.  **Track Solana Addresses:** Receive notifications.

4.  **Wallet Data from Mnemonic Phrase (Private Key Recovery):** *This is a central feature: Recover and manage your private keys.* Extract the private key, address, and balance of a Solana wallet using the mnemonic phrase (seed phrase).

<p align="left">
    <img src="/renders/flip.webp" />
</p>

5.  **Generate a Single Solana Wallet:** Generate new wallets.

<p align="left">
    <img src="/renders/prior.webp" />
</p>

6.  **Generation Solana Wallets and Check Balance (for Research):** Brute-force.

<p align="left">
    <img src="/renders/transparent.webp" />
</p>

## Setting Up Telegram

Configure Telegram.

## Getting Started: Download or Build

Download or build the project.

## Building the Project

Building the project from source for security reasons.

### Installing Dependencies Using vcpkg:

1.  Install **vcpkg** if you haven’t already.
2.  Add to your system PATH.
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

4.  Build.

### Building via Visual Studio:

1.  Open the solution in Visual Studio.
2.  Make sure **vcpkg** is correctly integrated.
3.  Click **Build** -> **Build Solution**.
4.  The executable will be in the `bin` folder.

### Building with Another C++ Compiler:

1.  Ensure all dependencies are installed via **vcpkg**.
2.  Compile using (example):

    ```bash
    g++ -o solanachecker main.cpp -lssl -lcrypto -lsodium -lcryptopp -std=c++17
    ```

## Command Line: Finding Your Private Key

1.  **-s / -search**: Brute-force.
2.  **-t / -track (ADDRESS)**: Track.
3.  **-g / -gen (NUMBER)**: Generate.
4.  **-m / -mnemonic (MNEMONIC)**: *Use this to find your private key. Carefully protect the mnemonic you provide.*
5.  **-b / -balance (ADDRESS)**: Check balance.

## Notes

-   Use responsibly.
-   Protect your data.

## License

This project is licensed under the [MIT License](/LICENSE).

Update:  16 June 2025 Sitemap URLs