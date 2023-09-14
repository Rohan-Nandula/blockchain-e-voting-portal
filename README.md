# blockchain-e-voting-portal
An E-voting portal using Blockchain technologies and Frameworks including Smart Contracts, Truffle, Ganache etc. It leverages the security offered by blockchain to ensure safe voting systems.
 
Steps to execute the application in a local setup:

Installing Xampp Server: 
1. To download and install Xampp, visit the official website of Xampp and download for your respective windows configuration. Below is the XAMPP installation page.
 
2. Once the download is complete, run the exe for installing Xampp. Now click on install.
3. You can see Xampp installing at this point. 
4. When it finishes, you can see a screen that says the setup was successful. 
5. Once after setup, open the Xampp panel and start Apache and MySQL. Below is the XAMPP Control Panel.
 
6. Goto PhpMyAdmin from localhost://phpMyAdmin which will be the database. 
7. Create tables in the database with the schema. Below is the XAMPP Database.
 
8. The Xampp downloaded folder by default contains htdocs folder. Make sure all the code files related to theproject are there in this folder. 
9. Run the files from localhost://htdocs/ through browser.

MetaMask: 
1. Metamask is a browser add-on (browser extension) that manages a user’s Ethereum wallet by storing their private key on their browser’s data store and the seed phrase encrypted with their password. 
2. It is a non-custodial wallet, meaning, the user has full access and responsibility their private key. Once lost, the user can no longer control the savings or restore access to it.
3. After installation part, execute the code files from the browser. This file will run with the
help of xampp server and metamask extension. The blockchain history will be available at
polygonscan.com with the inserted id.


Node and Ganache installation:
1. Download node in your system from “nodejs.org/download”. 
2. Upon downloading it, install node using the node installation wizard. And then check the version of node in the terminal using the “node -version” command. Similarly, download and install the Node Package Manager (NPM) from “npmjs.com” and then check its version.
3. Then install the following packages using “npm i”
 
Truffle installation:
1. Install “Truffle” to compile and run our application using command “npm install -g truffle”.
2. To check its version, type “truffle version”.
3. Now to run the application, enter the 3 commands in sequence:
	a. truffle compile – to compile the application.
	b. truffle migrate –reset – to migrate a fresh image of the application to the blockchain.
	c. npm run dev – to start the application in localhost
4. In a web browser, type http://localhost:<port> to start the application.
