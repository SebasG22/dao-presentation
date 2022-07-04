---
fonts:
  # basically the text
  sans: "Lato Light"
  # use with `font-serif` css class from windicss
  serif: "Roboto Condensed"
  # for code blocks, inline code, etc.
  mono: "Fira Code"
theme: ./
layout: intro
header: "Strategic Insight"
text: "Beyond the Basics Web 3.0"
---

---
layout: fact
---


## Heard about Blockchain/Web3 but never understood the hype?

This is an overview to to explore it and their usage with DAO.

<!-- Zero technical knowledge needed. -->

---
layout: statement
---

<div class="text-left">
<h1 class="inline-block text-7xl">D</h1><span class="inline-block text-4xl">ecentralized</span>
 </div>

<div class="text-left"> 
<h1 class="inline-block text-7xl">A</h1><span class="inline-block text-4xl">utonomous</span>
</div>

<div class="text-left">
<h1 class="inline-block text-7xl">O</h1><span class="inline-block text-4xl">rganization</span>
</div>

 <!-- Any group that is governed by a transparent set of rules found on a blockchain or smart contract. -->

---
layout: fact
---

# Is Bitcoin a DAO ?

 Any group that is governed by a transparent set of rules found on a blockchain or smart contract.

<!-- Because some people say miners could choose whetever upgrade their software -->

---
layout: fact
---

## What is DAO ?

A DAO is community of people with a shared bank account. 

Decisions around how than bank account is used are made by voting on different proporsal that members created.

<!-- When a proposal gets enough votes,it is executed on-chain! -->

---
layout: bullets
---

# What is the problem ?

- Trust centrality
- Transparency
- Given power to all the members 

**Benefit:** An organization operated exclusively through code

<!-- this solves an age-old problem of trust
centrality and transparency and giving
the power to the users of different
protocols and applications instead of
everything happening behind closed doors 

# Principles

- Inmutable
- Transparent
- Decentralized

-->
---
layout: image-right
image: eth-logo.svg
---

## Architecture Tools

### Voting Mechanism

<p class="text-xs font-semibold">How do I participate - How do I engage with this DAO? How do I help make decisions</p>

Tokenizing Voting Power:
- ERC20 Token
- Non Fungible Token (NFT)

<!-- When you tokenize the voting power -> Deepest pocket

Whoever got the deepest pockets has the most money gets to pick changes so if it (Changes benefit)

This does seems as an improvement of our current work 

NFT -> Interesting -->



---
layout: image-right
image: solidity-logo.png 
---

## How to build a DAO

###  Code Solutions (Etherium)

- Solidity (.sol) 

```sol

// SPDX-License-Identifier: GPL-3.0

pragma solidity >=0.7.0 <0.9.0;

contract Storage {

    uint256 number;

    function store(uint256 num) public {
        number = num;
    }

    function retrieve() public view returns (uint256){
        return number;
    }
}
```

---
layout: 3-images
imageLeft: aragon-dao-logo.png
imageTopRight: colony-dao-logo.png
imageBottomRight: dao-stack-logo.jpeg
---
<!-- - Aragon 
- Dao Stack
- Colony
- Dao Haus 
No code solution -> https://aragon.org/
https://daostack.io/
https://colony.io/
https://daohaus.club/ -->
---
layout: image-right
image: thirdweb-features.png
---

## How to build a DAO

### Third web

It is a complete development framework that allows you to easily build powerful web3 functionality into your applications.

- **Deploy** smart contracts to the blockchain easily with a single click or a one-line command.

- **Build** applications to interact with the blockchain in your favorite languages by using our powerful SDKs, APIs, and frontend libraries.

- **Manage** your contract settings, team permissions, revenue streams, and analytics through our intuitive dashboards.

---
layout: image-right
image: bunny.jpg
---

## What we will built ?

- Create an NFT Collection 
- Use a NFT (ERC721) to be part of our DAO

- Create the bunny token (ERC20) to manage our DAO 
- Airdrop some tokens

- Create the DAO / Treasury
- Setup the voting mechanism

---
layout: image-right
image: thirdweb-features-2.png
---
# What we need ?

- Account Wallet with funds
  - We will be working with the ethereum test network (rinkeby)
- Basic knowledge in JS
  - We will run some scripts to generate the DAO
- Basic knowledge in React/React Hooks
  - We will create a dApp to interact with the proposals on the DAO

---
layout: section
---

# Retrieving data from Blockchain

<!-- - Web 2
  - API Rest
  - GraphQL

- Web 3
  - GraphQL (The Graph) -->

---
