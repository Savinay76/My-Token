# My-Token
Overview

MyToken is a simple ERC-20 compatible token built on Ethereum for learning purposes.

Token Details

→ Name: MyToken
→ Symbol: MTK
→ Decimals: 18
→ Total Supply: 1,000,000 MTK

Features

→ Standard ERC-20 implementation
→ Transfer tokens between addresses
→ Approve and transferFrom functionality
→ Event emission for transparency
→ Balance tracking

How to Deploy

→ Open RemixIDE
→ Create new file MyToken.sol
→ Paste the contract code
→ Compile with Solidity 0.8.x
→ Deploy with desired total supply

How to Use
Check Balance

→ balanceOf(address account) → returns uint256

Transfer Tokens

→ transfer(address to, uint256 amount) → returns bool

Approve Spending

→ approve(address spender, uint256 amount) → returns bool

Transfer on Behalf

→ transferFrom(address from, address to, uint256 amount) → returns bool