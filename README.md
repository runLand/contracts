# contracts
智能合约

使用ERC721构建兼容EVM的NFT智能合约

借助openzeppelin的一些库，可以构建更为安全的智能合约，
可以使用AZkui的ERC721A实现批量铸造更节省GAS的智能合约  
通过返回tokenURL(云服务、或者IPFs)来返回每个NFT的数据

ipfs去中心化的文件服务器使用特点是永久存储
可以使用一些ipfs服务商的的工具如pinta（收费）、https://nft.storage/等上传NFT资产
云服务可以使用云服务商例如亚马逊、阿里云等

hashlips_art_engine 工具使用，用于快速构建JSON文件，构造符合MetaData的JSON、如控制稀有度、生成各个对应属性

构建Web前端用于交互智能合约，前端可以使用各中框架React、vue、甚至静态HTML.  
唯一需要注意的事需要了解与智能合约交互需要了解钱包知识如何调用钱包用、发送交易  
可以使用web3modal库

.sol编写使用 https://remix.ethereum.org/  
验证合约：ETHscan、单文件直接验证、多文件（依赖库的智能合约）使用flatten混入成单文件在构建  
flatten: 用来混入依赖  
hardat:部署、测试智能合约库  
