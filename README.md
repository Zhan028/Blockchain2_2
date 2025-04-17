# Solana Hello World
This project demonstrates how to build, deploy, and interact with a simple Solana smart contract using Rust. It's a basic "Hello World" program running on Solana's Devnet.

## **Prerequisites**
* [Rust](https://www.rust-lang.org/)
* [Solana CLI](https://solana.com/ru/docs/intro/installation)
* Git
* RustRover

## **Install Solana CLI**
Solana CLI was installed using the official installation script:

```bash
sh -c "$(curl -sSfL https://release.solana.com/stable/install)"
```

![Изображение WhatsApp 2025-04-11 в 22 41 00_740ac06b](https://github.com/user-attachments/assets/a26b886a-9b7b-47e6-890a-6d0fe3c2c39c)


## **Hello World Example**
*Project structure:*
![img.png](photo/img4.png)

## **Build the Program**
Built the smart contract with:

```bash
cargo build-bpf
```

*Build successful:*

![img.png](photo/img2.png)


## **Configure Devnet and Deploy**
Set Solana to use Devnet:

```bash
solana config set --url https://api.devnet.solana.com
```

Deployed the program with:

```bash
solana program deploy dist/program/helloworld.so
```

![Uploading image.png…]()



## **Wallet & Program Info**
Wallet address:
![img.png](photo/img3.png)


## **Resources**
* [Solana Docs](https://solana.com/docs)
* [Solana CLI](https://docs.solana.com/cli)
* [Solana Hello World Example](https://github.com/solana-labs/example-helloworld)

## **Authors**
Moldabek Zhanbatyr

Nadir Shugay

Dias Makhatov# Blockchain2_2
