---
sidebar_position: 1
---

# Account

DecentralChain uses an account-based model. Each transaction is created on behalf of an account, all assets and data are associated with an account. An account has a pair of cryptographically bound keys: a private key that the account uses to sign transactions, and a public key that allows anyone to verify the signature. 

To create an account, store keys, and sign transactions, you can use [Decentral.Exchange](http://decentral.exchange/).

## Account Keys

Unlike centralized applications, users do not have usernames and passwords on the blockchain. User identification and validation of their actions are performed using a cryptographically bound key pair:

* The private key is used to sign transactions or orders.
* The public key allows the verification of the digital signature.

Each transaction contains the public key of the sender’s account. The sender generates a digital signature of the transaction using the account’s private key. The signature and the sender’s public key are used to verify the authenticity of the transaction’s data and to check that the signature of the transaction matches the public key.

DecentralChain uses an asymmetric cryptographic system based on the elliptic curve Curve25519-ED25519 with X25519 keys. The guideline for generating keys and signatures is given in the cryptographic practical details article. The private and public keys are  byte arrays. In UIs, the keys are displayed as base58 encoded strings. Base58-encoded keys can be of different lengths, the maximum length is  characters.

## Secret (Seed) Phrase


## Creating an Account


## Backup Seed Phrase


## Log in to Account


## Forgot Password


## Address


## Get Personal Address


## Alias


### Alias Requirements


### Create Alias


### View Aliases


## Account Balance


### Account Balance in DecentralCoin


### View Account Balance


### How to buy DecentralCoins


## Account Data Storage


### View Account Data


### Add, Modify, Delete Entries


## dApp and Smart Account

