# **On Windows:**
1) Download and save the CuToken miner setup executable from the repo on to your local computer.
2) Double click and install the miner setup.
3) You might receive additional prompts for .NET runtime and VirtualBox if not already installed on your machine. 
Go ahead and install them by pressing next button.
4) Once the setup finishes, go ahead and launch the CuToken miner.
5) You either click "Start mining" button to immediately start mining or switch to second
tab to configure the resources you want to sell.
6) If you are running CuToken miner for the first time, you will be prompted to create a new
wallet account. Go ahead and create it. This is where your CuTokens will be shown. 
7) Make sure you remember your wallet password or secure it on a physical paper.
8) Take a backup of your wallet.dat file to another computer or USB device. Steps (7) and (8)
are important or you might lose your CuTokens.
9) Keep the CuToken miner running always to generate CuTokens in the background.

# **On Linux:**
1) To install, run the following commands in sequence to install the miner software
sudo curl -sSL getLinuxMiner.cutoken.io |sh

2) To launch and mine CuTokens, run the following commands in sequence

cd cuTokenMiner
sudo mono cuTokenMiner.exe

3) After (2), If you are running CuToken miner for the first time, you will be prompted to create a new
wallet account. Go ahead and create it. This is where your CuTokens will be shown. 
4) Make sure you remember your wallet password or secure it on a physical paper.
5) Take a backup of your wallet.dat file to another computer or USB device. 
Steps (4) and (5) are important or you might lose your CuTokens.
6) If you have already created a wallet and want to run CuToken miner even after you logout of your session, 
run the below command after quitting the CuToken miner running earlier. This will keep generating CuTokens
in the background.

nohup sudo mono cuTokenMiner.exe &

7) You can check your CuToken balance in any of the supported 
block explorers (example blockchain.info) by entering the public key from your wallet.dat file.

