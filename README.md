# Mindful Moments 📝✨

A **mental health checklist app** designed to help you stay organized and focused on your well-being. It encourages mindful practices and promotes a balanced lifestyle, helping you take small, meaningful steps towards a healthier mind.

This project is _built on [**Aptos**](https://aptosfoundation.org/)_, a blockchain that offers transaction speeds of up to 160,000 transactions per second and near-instant finality.

**Contract Address** - 0xcd7e2ed6392fb60f07010e80a48d1ca2df2f3d38b8e41e56bd4ca8ac428ceebd<br>
Or, _see it on Aptos explorer_ **[here](https://explorer.aptoslabs.com/account/0xcd7e2ed6392fb60f07010e80a48d1ca2df2f3d38b8e41e56bd4ca8ac428ceebd?network=devnet)**

<p align="center">
  <img src="https://aptosfoundation.org/brandbook/logotype/PNG/Aptos_Primary_WHT.png" height="100">
</p>


<div align="center">
	<code><img width="50" src="https://user-images.githubusercontent.com/25181517/192108891-d86b6220-e232-423a-bf5f-90903e6887c3.png" alt="Visual Studio Code" title="Visual Studio Code"/></code>
	<code><img width="50" src="https://user-images.githubusercontent.com/25181517/192158954-f88b5814-d510-4564-b285-dff7d6400dad.png" alt="HTML" title="HTML"/></code>
	<code><img width="50" src="https://user-images.githubusercontent.com/25181517/183898674-75a4a1b1-f960-4ea9-abcb-637170a00a75.png" alt="CSS" title="CSS"/></code>
	<code><img width="50" src="https://user-images.githubusercontent.com/25181517/183897015-94a058a6-b86e-4e42-a37f-bf92061753e5.png" alt="React" title="React"/></code>
	<code><img width="50" src="https://user-images.githubusercontent.com/25181517/183890598-19a0ac2d-e88a-4005-a8df-1ee36782fde1.png" alt="TypeScript" title="TypeScript"/></code>
	<code><img width="50" src="https://user-images.githubusercontent.com/25181517/186884153-99edc188-e4aa-4c84-91b0-e2df260ebc33.png" alt="Ubuntu" title="Ubuntu"/></code>
</div>

### Screenshots

<table align="center">
  <tr>
    <td align="center">
      <img src="https://github.com/user-attachments/assets/9d1502bc-c64c-4707-a616-aefee0b01f8b">
    </td>
    <td align="center">
      <img src="https://github.com/user-attachments/assets/1f4c58a4-6bfd-4640-8ce5-93b1ce4e6a93">
    </td>
  </tr>
</table>

### Running Locally 

First, we need to clone the repository and change the working directory. Then, we must set up environment variables for the project. Make sure to add ```.env``` to ```.gitignore```.

```bash
git clone [https://github.com/ayush-that/HackOn-Blocks-2024.git](https://github.com/ayush-that/my_first_aptos_dapp.git)
cd my_first_dapp/
```

Use the node version manager [(nvm)](https://www.freecodecamp.org/news/node-version-manager-nvm-install-guide/) and set up the project to use Node v16 for seamless installation. Now install the dependencies.

```node
nvm install 20
nvm use 20
npm i
```

1. **Smart Contract:** First, make sure you have Aptos CLI installed on your system. You should add ```export PATH=$PATH:~/.local/bin``` to your ```~/.bashrc```. You can install aptos-cli and compile Move with the following commands:

```bash
curl -fsSL "https://aptos.dev/scripts/install_cli.py" | python3
cd move/
aptos move compile
```
2. **Frontend:** Now, install the dependencies (node modules) and run the server locally using the following commands. Make sure you are in the root directory:

```bash
cd client/
npm install
npm start
```
