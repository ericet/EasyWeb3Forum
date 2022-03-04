# Easy Web3 Forum
## 设置
* git clone https://github.com/ericet/EasyWeb3Forum
* cd EasyWeb3Forum
* npm install
* mv .env.example .env

打开.env, 在PRIVATE_KEY=那里填上钱包私钥

## 运行程序：
npx hardhat run --network matic scripts/deploy-and-seed.js

运行成功后，会显示你部署的合约，https://www.pointer.gg/tutorials/create-a-web3-forum-with-polygon/93ba1318-d91c-41bc-8d9b-a9378fea0c81 填入合约就完成了
