## oracles
### chainlink
- [vrf](https://docs.chain.link/docs/chainlink-vrf/)
- [polygon matic datafeeds](https://docs.chain.link/docs/matic-addresses/)
- 
## contracts
### open zeppelin
- [contract wizard](https://docs.openzeppelin.com/contracts/4.x/wizard)
- [erc-1155 docs](https://docs.openzeppelin.com/contracts/3.x/erc1155)

## metadata
### varcel
used to host metadata
- [varcel](https://vercel.com/dashboard)

### hardhat
- [compiler version error](https://backbencher.dev/articles/solved-error-hh606-solidity-version-pragma-statement)

# UI
### svg
- [w3schools SVG Intro](https://www.w3schools.com/graphics/svg_intro.asp)

## React
#### Styles
- [antd](https://ant.design/components/list/)

# Contract Code
## Solidity
#### encode / decode
- [base64 encode/decode](https://www.digitalocean.com/community/tutorials/how-to-encode-and-decode-strings-with-base64-in-javascript)

#### Arrays
- [how-to-create-a-dynamic-memory-array-in-solidity](https://stackoverflow.com/questions/66914403/how-to-create-a-dynamic-memory-array-in-solidity)
- [solidity-by-example-array](https://solidity-by-example.org/array/)

#### Events
[solidity by example - events](https://solidity-by-example.org/events/)

```
this_hash=0x23232323204576656e74730a5b736f6c6964697479206279206578616d706c65202d206576656e74735d2868747470733a2f2f736f6c69646974792d62792d6578616d706c652e6f72672f6576656e74732f290a0a6060600a746869735f686173680a6060600a2d205b7468726d207374636b7863686e67206320383635385d2868747470733a2f2f657468657265756d2e737461636b65786368616e67652e636f6d2f7175657374696f6e732f383635382f776861742d646f65732d7468652d696e64657865642d6b6579776f72642d646f290a3e74686520696e6465786564206b6579776f7264206973206f6e6c792072656c6576616e7420746f206c6f67676564206576656e74730a46726f6d205b436f6e747261637473202d204576656e74733a5d28687474703a2f2f736f6c69646974792e72656164746865646f63732e696f2f656e2f6c61746573742f636f6e7472616374732e68746d6c236576656e747329200a557020746f20746872656520706172616d65746572732063616e2072656365697665207468652061747472696275746520696e64657865642077686963682077696c6c20636175736520746865207265737065637469766520617267756d656e747320746f20626520736561726368656420666f723a20497420697320706f737369626c6520746f2066696c74657220666f722073706563696669632076616c756573206f6620696e646578656420617267756d656e747320696e20746865207573657220696e746572666163652e0a
```
- [thrm stckxchng c 8658](https://ethereum.stackexchange.com/questions/8658/what-does-the-indexed-keyword-do)
>the indexed keyword is only relevant to logged events
From [Contracts - Events:](http://solidity.readthedocs.io/en/latest/contracts.html#events) 
Up to three parameters can receive the attribute indexed which will cause the respective arguments to be searched for: It is possible to filter for specific values of indexed arguments in the user interface.

#### types
- [string concat](https://dev.to/hannudaniel/concatenate-two-strings-on-the-blockchain-using-solidity-smart-contracts-new-feature-in-v0812-549g)

#### Operators
- https://www.tutorialspoint.com/solidity/solidity_operators.htm

#### Comments
```
///@title  Dev Notes - EVM Programing
///@author quantumtekh.eth
///@notice reference of learnings along the way to learning and developing ethereum dapps

//@dev solidity supported doxygen style tags for comments
/*
// Tag      Description                                 Context
//@title    Title that describes the contract.          Contract, Interfaces
//@author   Author Name                                 Contract, Interfaces, Functions
//@notice   Explination of functionality.               Contract, Interfaces, Functions
//@dev      Any extra details                           Contract, Interfaces, Functions
//@param    parameter type followed by parameter name   Functions
//@return   return value of a function                  Functions

//not supported:
//@source   source of [some] content                    Contract, Interfaces, Functions
//@ref      reference to [some] content                 Contract, Interfaces, Functions
*/
//@Source https://jeancvllr.medium.com/solidity-tutorial-all-about-comments-bc31c729975a
//@ref    [Doxygen Manual](https://www.doxygen.nl/manual/index.html)

/*
///@title
///@author
///@notice
///@dev   
///@param 
///@return
///@source
///@ref   
*/

```
#### Links 
- [solidity-tutorial-all-about-comments](https://jeancvllr.medium.com/solidity-tutorial-all-about-comments-bc31c729975a)
- [Doxygen Manual](https://www.doxygen.nl/manual/index.html)
