# `TradeSaga` 📜✨

Welcome to `TradeSaga`, your personal, decentralized file vault built on the **Internet Computer**. This application is your own on-chain saga, allowing you to securely upload, store, and manage your digital files in a robust, unstoppable environment.

`TradeSaga` leverages the power of the Internet Computer to provide a truly serverless file storage solution where you, and only you, control your data.

-----

## ✨ Key Features

  * **Decentralized File Storage:** Upload any file from your local machine and store it securely on the Internet Computer's blockchain.
  * **Robust Chunking Mechanism:** Large files are automatically split into smaller chunks on the client side before being uploaded to the canister. This ensures reliable transfer and storage of files of any size.
  * **Secure Authentication:** Integrates with **Internet Identity** for a secure, cryptographic login, ensuring that only you can access and manage your files.
  * **Complete File Management:** A simple and intuitive interface allows you to easily list your uploaded files, download them back to your machine, or delete them permanently from your vault.

-----

## 🛠️ Technology Stack

  * **Backend:** **Motoko**
  * **Frontend:** **React** & **JavaScript** (with **Tailwind CSS**)
  * **Platform:** **Internet Computer (ICP)**
  * **Authentication:** **Internet Identity**

-----

## 🚀 Running the Project Locally

To run and test the project on your local machine, follow these steps.

1.  **Start the local replica:** This command starts the local Internet Computer replica in the background.

    ```bash
    dfx start --background
    ```

2.  **Deploy the canisters:** This command deploys your canisters to the local replica and generates the necessary interface bindings.

    ```bash
    dfx deploy
    ```

Once the job completes, your application will be available at `http://localhost:4943?canisterId={asset_canister_id}`.