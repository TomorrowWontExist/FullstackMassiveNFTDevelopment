# Full Stack NFT Collection Development A-Z Dummy Edition | No Coding or Crypto Knowledge Required
#TWEFamily #TBCToken #TWEToken #TWELottery #TomorrowWontExist #TWECryptoDev #ScrawnyViking

***This Instrucitonal Video includes Polygon/Matic And ETH Mainnet + Rinkby Testnet***

Instructional Walkthrough video of how to create and launch your own 10k NFT collection! From Scratch on a computer that has nothing installed. We are going back to very core of everything and climbing out together while holding hands on this adventure. I highly recommend pausing frequently until you catch up. If you hit a snag, come to telegram and people will be more than happy to help!

Follow along for a Streamlined Dummy version A-Z how to make your art into a randomly generated Massive NFT Collection, without any code or crypto knowledge! - Because this is free, I pray that everyone who watches this and launches their own NFT collection, please send me one! And also buy a Twee the Bee NFT!!! https://tomorrowwontexist.github.io/tbcnft/

Donation Wallet - Owner of TheBeeCollaborative | Just in case...
0x2608A324Ab6ad00Ca5b498DA6EF7E61E1F3417AD

Join the TheBeeCollaborative Community @TBCToken in Telegram https://t.me/TBCToken

Look at ValuableNoteCleanVersion.md inside MintingStationDApp for copy/pasteable tips

Please Like Subscribe and Comment on the video, it HELPS SO MUCH!!


Before You begin your journey and follow along with the video... 
Download/Install everything you see here in this order, and then open Node.js
<p/>
How to install node.js https://nodejs.org/en/download/<p/>
How to install https://code.visualstudio.com/download<p/>
How to install .Git https://git-scm.com/downloads<p/>
How to install Ganache https://www.trufflesuite.com/ganache<p/>
How to install IPFS Desktop https://ipfs.io/#install<p/>
<p/>
If you haven't already, make an account @ github.com and make sure MetaMask is installed and you're logged into the Wallet you plan on having bee the Owner of your NFT Collection.
Lastly, have your IPFS Desktop open and running, Github Account created and open, and open a tab with https://remix.ethereum.org<p/>
Need to be logged in to your Wallet with Metamask.io and have Rinkby Test Ethereum, you can get it here https://faucet.rinkeby.io/ - Tweet your wallet address, copy the tweet link and paste it in the Address box at the website. Click 18.75 ETH / 3 days

You now have the perfect Wire Frame for what we are about to accomplish. // Some things we did and are about to do, may overlap eachother... I'm just creating fail proofs and safety nets by doing things twice, in order to cover all possibilities in the case that u get an unknown error.<p/>
<p/>
Are you ready? ... run the next command to begin your EPIC adventure... <p/>
<p/>
git clone https://github.com/TomorrowWontExist/FullstackMassiveNFTDevelopment.git<p/>
<p/>
Once it's done downloading, we need to make sure we're working on the correct $dir ending with FullstackMassiveNFTDevelopment\ArtGeneratorByHashLips <p/>
It will look something like this... <p/>
D:\FullstackMassiveNFTDevelopment\ArtGeneratorByHashLips // Alteranively, you can right click ArtGeneratorByHashLips on the explorer tab (ctrl-shift-e) and copy path, then type<p/>
cd (paste)  // example .. <p/>
<p/>
cd D:\FullstackMassiveNFTDevelopment\ArtGeneratorByHashLips<p/>
<p/>
Now run these commands<p/> *IMPORTANT* If you get any error, that's okay keep moving to the next command... this tutorial is designed to trump anything that could arise. MAKE SURE you download everything above before going past this point! If you rush this process, you will turn 1 hour into 20. Please follow explicitly and I GUARANTEE that you will have your NFT Collection launched Live on Mainnet, Matic, and/or Rinkby Testnet. Unless you're on Mac, you're going to have some variables unknown to a 31 year Windows PC owner. 
<p/>
npm install -g npm<p/>
npm install<p/>
npm upgrade <p/>
npm install --global yarn<p/>
yarn --version    // to make sure it's installed<p/>
yarn add all<p/>
node index.js     // You should now see 10 NFT's being created<p/>
set-ExecutionPolicy -ExecutionPolicy Unrestricted // only if u get error for access<p/>
git clone https://github.com/ipfs/go-ipfs.git<p/><p/>
npm install -g ipfs<p/>
jsipfs daemon or ipfs daemon // Depends on which path your PC chose to isntall it in<p/>
<p/>
So it works... Now the fun part begins! Start by replacing the folders with your artwork, and then renaming the .pngs in the code. Careful! 1 typo (capitalization matters) and the code may break. Always test the code by running (node index.js) and make sure it still prints 10 NFTs (before you do too much work)

In the video we are going to skip ahead and complete the Full Stack Development and have all NFT's Live on Opensea.io through a Minting Station (Front end Dapp), and deployed on solidity with ERC721 smart contract. We will do Everything from A-Z and have a fully finished Production on Rinkby Testnet. Then I will show you exactly how to convert your Testnet Production onto Mainnet in just a few easy lines of code. By the end of this video, we will have deployed and successfully launched everything! At the end, we will circle back and I'll show you exactly how to swap out my Bee project with your Artwork. 
<p/>
***We're going to create an entire new project from Scratch right here, right now! *Grab a drink*

Time to grab the Minting Station Repo!

git clone https://github.com/TomorrowWontExist/MintingStationDApp.git