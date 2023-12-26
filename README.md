# MyBlockchain
### A blockchain made from scratch using javascript
The blockchain created has various features like:
- There is self adjusting difficulty level to control the mining rate
- There is a broadcast facility to broadcast the block created to all the nodes
- There is a syncing feature that allows a newly added node to have access to all the previously mined blocks
- There is also a verification feature to check whether the block coming from the node/miner is valid or not
- It is based on the **Publish-Subscribe** Model
- It uses **Postman app** to write data onto the blocks
- There is also a feature which will automatically select the longest chain adhering to the primary feature of a blockchain
### Steps to run this project
Step 1: Clone this project using `git clone https://github.com/Rahul1227/MyBlockchain.git`<br>
Step 2: Install all the dependencies:
- `npm init -y` 
- `npm i hex-to-binary@1.0.1 --save`
- `npm i express --save`
- `npm i nodemon --save-dev`
- `npm i body-parser --save`
- `npm i redis@2.8.0`
- `npm i cross-env@5.2.0 --save-dev`
- `npm i request@2.88.0 --save`<br>
Step 3: Download Postman app and set up it to write onto the blockchain<br>
Step 4: Download Redis zip folder from `https://github.com/microsoftarchive/redis/releases` , extract it and run redis-server in the background<br>
Step 5: Run the blockchain with the command  `npm run dev` and peer nodes using `npm run dev-peer`<br>
![VScode](https://github.com/Rahul1227/MyBlockchain/blob/master/Images/VscodeTwoNodes.png)

Step 6: Open Postman app and provide the data in the json format to the blockchain<br>
![postman](https://github.com/Rahul1227/MyBlockchain/blob/master/Images/Postman.png)
Step 7: Get the blocks info from `http://localhost:3000/api/blocks`
![blocks](https://github.com/Rahul1227/MyBlockchain/blob/master/Images/Blocks_info.png)

