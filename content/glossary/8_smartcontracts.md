---
date: '2025-05-08T12:00:59+05:30'
draft: false
title: 'Smart Contracts'
weight: 8
url: /glossary/smartcontract
tags: ["smartcontract", "web3", "blockchain", "dex", "uinswap", "solidity", "cryptography"]
highlight_name: true
description: "Explanation of smart contract, what is it and how it works"
---

Smart contracts are pieces of code stored on a blockchain that let users interact with them through transactions. They manage data, like a user’s token balance, and include access controls to decide who can update or change that data.

Smart contracts are widely used to create new tokens on blockchains like Ethereum and Solana. A token smart contract typically includes a balance mapping (e.g., User address => User token balance) and functions to update this mapping, such as transferring tokens.

You can design a smart contract to store any kind of data and set whatever restrictions you want. For example, in a token smart contract, if you want to reduce a user’s balance, you need their digital signature. Without it, the balance stays untouched!

This ensures the data in the smart contract can’t be altered unless it follows the coded rules, making smart contracts super secure and great for building trust.

### Use Cases of Smart Contracts

- #### Voting
Smart contracts can ensure fair voting by enforcing rules, like allowing only one vote per user address and restricting voting to a set of approved addresses. Since the code enforcing these rules lives on the blockchain, there’s no way to bypass them.

- #### Certificate Storage
Smart contracts can securely store certificates, like birth certificates or college degrees. Once stored, no one can modify them, ensuring their authenticity. At the same time, anyone who needs to verify a certificate can request it from the blockchain. The smart contract includes functions to add new certificates, fetch existing ones, and more.