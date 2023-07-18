# CreateAToken
A Simple program written in Solidity Language.

# Description
CreateAToken is a simple token contract implemented in Solidity. The contract allows for the creation (minting) and destruction (burning) of tokens. It maintains a mapping of addresses to token balances and keeps track of the total token supply.

# Getting Started
To run this program, you can use any IDE that supports Solidity Language, for simplicity, you can use Remix Etherium IDE at https://remix.ethereum.org.

After selecting your desired IDE, make sure to compile the contract using Solidity version 0.8.18 in the Remix Etherium IDE, you can find it under the Remix Compiler(3rd icon). 

Once the code is compiled, you can move on to the Deploy Transaction(next to the Remix Compiler), After clicking deploy, you can choose different account given by the Remix IDE to use for testing.

After you choose your desired account, paste the account address inside the mint function followed by a comma and then the value you desired to mint (i.g 0x5B38Da6a701c568545dCfcB03FcB875f56beddC4, 2000), as you can see
after that go and click the mint button, this will put 2000 tokens on the 0x5B38Da6a701c568545dCfcB03FcB875f56beddC4 address, this also goes the same for the burn except instead of adding, it deducts based on the value passed.

Please note that the contract does not include any access control or security mechanisms. It is recommended to use this contract for educational or experimental purposes only.

# Author
Karl Cyil Dwight P. Abechuela

# Licence
This project is licensed under the MIT License - see the LICENSE.md file for details

