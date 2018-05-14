# Hyperledger
MyMedBlock Hyperledger Education Project

IBM Hyperledger Resources 
 - Setting up Development Resources Mac OS
 1. Install Node Version Manager -->  - curl -o- https://raw.githubusercontent.com/creationix/nvm/v0.33.0/install.sh | bash
 2. Install XCode 
 3. Paste --> touch .bash_profile  in terminal 
 4. Rerun orginal curl command (step 1.)
 5. Check that nvm is installed use --> nvm —-version in terminal
 6. Install Node --> latest version --> nvm install --lts in terminal 
 7. Switch to --> nvm use --lts in terminal
 8. Check Node --> node --version
 
 Installing Docker https://docs.docker.com/docker-for-mac/install/
 
 Installing Visual Studio for Mac https://code.visualstudio.com 
 1. Launch VSCode and then press the “Extensions” button on the vertical left toolbar. Type composer into the search bar and then press the Install button next to the Hyperleger Composer extension. Once the install completes you need to press the Reload button to activate the extension.

Install CLI tools for Composer developers
 1. Essential Tool --> npm install -g composer-cli in terminal
 2. REST Server Utility --> npm install -g composer-rest-server
 3. Application Asset Generator -- npm install -g generator-hyperledger-composer 
 4. Yeoman --> npm install -g yo
 
 Playground for building and testing Business Networks 
 npm install -g composer-playground
 
Set up IDE
Browser app can be used to work on your Business Network code, most users will prefer to work in an IDE. VSCode has a Composer extension is available.

Install VSCode from this URL: https://code.visualstudio.com/download

Open VSCode, go to Extensions, then search for and install the Hyperledger Composer extension from the Marketplace.

A local Hyperledger Fabric runtime to deploy your business networks
In a directory, we are assumming ~/fabric-dev-servers), get the .tar.gz file that contains the tools to install Hyperledger Fabric:

--> In terminal:  mkdir ~/fabric-dev-servers && cd ~/fabric-dev-servers

curl -O https://raw.githubusercontent.com/hyperledger/composer-tools/master/packages/fabric-dev-servers/fabric-dev-servers.tar.gz
tar -xvf fabric-dev-servers.tar.gz 

Hyperledger Fabric Runtime
cd ~/fabric-dev-servers
./downloadFabric.sh

Scripts 

~/fabric-dev-servers  <--- List of Scripts 

    cd ~/fabric-dev-servers
    ./startFabric.sh
    ./createPeerAdminCard.sh  <--- Start Script Creates Peer Admin Card
    
    
    run ~/fabric-dev-servers/stopFabric.sh and then ~/fabric-dev-servers/teardownFabric.sh  <--- When Ending Dev Session 
    
   Start Web Playground 
   
       composer-playground <--run 



 
