# NFT creation using Moralis - https://github.com/Omprakash228/NFT-Moralis
1. Created a local dApp server by following the instructions in 
https://moralis.io/how-to-set-up-a-self-hosted-web3-server/

2. Added the AppId and ServerUrl of the local dApp server in the client application

3. Since the parserAPI doesn't work with self hosted server, made changes to the login method in logic.js
![Alt text](/login_change.png?raw=true "Optional Title")

4. Similarly Moralis.File() method doesn't work with self hosted servers, so updated the upload method in logic.js
![Alt text](/upload_change.png?raw=true "Optional Title")

5. Installed the dependencies using the command
`yarn install`

6. Built the client application using the command
`yarn build`

7. Run the application using 
`yarn dev`

8. Once the application started, connected the application to my metamask account and uploaded an image to mint as nft
![Alt text](/working_result.png?raw=true "Optional Title")

9. Checked my opensea testnet account and could confirm the created NFT
![Alt text](/nft_result.png?raw=true "Optional Title")