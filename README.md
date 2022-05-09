# Blockchain_Wallet

This Python application is a simulation to recruit, to hire and to pay fintech professionals via Blockchain. Streamlit dashboard allows for a user-friendly web interface. It utilizes 3 components: Python, Streamlit, and Ganache.

Integrating `finTech_finder.py` and `crypto_wallet.py` will automate the tasks associated with generating a digital wallet, accessing Ethereum account balances, and signing and sending transactions via a personal Ethereum blockchain called Ganache.

The Wallet will allow to conduct human resource transactions and to pay via a personal Ethernet Blockchain, account address and Ether.

Features include:

* Complete script for easy transaction. 
* Userfriendly interface Streamlit application
* Integration of defined functions in `crypto_wallet.py

To do these, complete the following steps:

1. In the terminal, run the Streamlit application by
using `streamlit run fintech_finder.py`. This will open a web browser
at `localhost:8501`.

2. Verify Ethereum address and balance to confirm total wage afforability.


3. Select a Person and Number of Hours needed for work. This will
   calculate the `Total Wage in Ether`.

4. Click `Send Transaction`

5. To confirm transaction, go to Ganache. Here, the transcations
    are detailed.

## Technologies

This application incorportates the following required dependancies to run:


### Import the required libraries and dependencies for Python

`fintech_finder.py`
- import streamlit as st
- from dataclasses import dataclass
- from typing import Any, List
- from web3 import Web3
- w3 = Web3(Web3.HTTPProvider('HTTP://127.0.0.1:7545'))

`crypto_wallet.py
- import os
- import requests
- from dotenv import load_dotenv
- load_dotenv()
- from bip44 import Wallet
- from web3 import Account
- from web3 import middleware
- from web3.gas_strategies.time_based import medium_gas_price_strategy


## Installation Guide

The following installation must be performed before running the program. It include:

pip intall streamlit


## Usage

To run this application, create a clone on the local desktop. Then, initiate your conda environment.
In Terminal command line, type `streamlit run fintech_finder.py`. This will open a web browser.

Below is a validated and verified transaction example:

Send Transaction and Validated Transaction Hash on Streamlite:
<img width="1088" alt="transaction" src="https://user-images.githubusercontent.com/93550651/167327057-a57dad10-426f-4f12-abda-5e795e4237a0.png">

Ganache Transactions Verified:
<img width="1023" alt="Ganache_verify" src="https://user-images.githubusercontent.com/93550651/167327076-5c07e7eb-77d8-45a1-aac4-e69df3e6bed6.png">

Ganache Transaction Receipt:
<img width="1116" alt="Ganache_receipt" src="https://user-images.githubusercontent.com/93550651/167327095-2061af95-0101-4588-86c0-8e9581dd78f9.png">

Ganache Block Hash:
<img width="1106" alt="Block3_Hash" src="https://user-images.githubusercontent.com/93550651/167327130-623b8695-b2f0-46e0-8ae3-13b11a42f180.png">


## Contributors

Contributor: John Batarse  

Email: jbatarse@hotmail.com

LinkedIn: [Find me on LinkedIn](<https://www.linkedin.com/in/john-a-batarse-760a26116/>)


## License

Trilogy Education LLC. and UC Berkeley
