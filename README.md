# PyChain Ledger Application

Welcome to the PyChain Ledger Application! This application leverages Python and Streamlit to create a web-based user interface where users can store transaction records in a blockchain.

## Features

- **Store Transaction Records**: Users can specify a sender, a receiver, and the amount for a transaction and store this information in a block.
- **Blockchain Visualization**: Once blocks have been added, users can inspect individual blocks and see their hash values.
- **Blockchain Validation**: Check the integrity of the blockchain with a single click.

## Instructions for Testing the PyChain Ledger

### Step 1: Run the Streamlit Application
Navigate to the project's directory in your terminal and run:

streamlit run pychain.py

### Step 2: Store Transaction Records
In the Streamlit web interface:
1. Enter values for the sender, receiver, and amount.
2. Click the "Add Block" button.
3. Repeat the process to store multiple blocks in the ledger.

### Step 3: Verify the Blockchain Data
Inspect the blockchain's data in the Streamlit application, especially the block contents and hash values.

![Blockchain Details Screenshot](images/pychain_ledger)

### Step 4: Validate the Blockchain
Using the web interface, click the "Validate Chain" button to ensure the integrity of the blockchain. The application will indicate the validity of the blockchain.

![Blockchain Validation Screenshot](path_to_your_second_screenshot_here.png)


