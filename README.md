## Introduction

Solidity is the main programming language used for writing smart contracts on various blockchain platforms, including Celo. In this challenge, you will design and implement a decentralized auction using Solidity.

## Problem Statement

Create a decentralized auction contract with the following requirements:

1. The contract should allow the contract owner to start a new auction with a set time limit.
2. It should allow bidders to place their bids during the auction time.
3. The contract should reject bids once the auction time has ended.
4. The contract should allow the contract owner to end the auction manually.
5. After the auction ends, the highest bidder should be recorded, and the bid amount should be stored.
6. Include a function that allows the highest bidder to claim the auctioned item.

## Hints

- Utilize state variables to store auction start time, duration, highest bid, highest bidder, and auction status.
- Use `msg.sender` and `msg.value` to keep track of bidders and their bids.
- `require()` function can be used to enforce rules like bid time and auction ownership.
- Implement events to log major actions such as starting the auction, placing a bid, ending the auction, and claiming the item.

## Evaluation Criteria

- **Correctness**: The contract should compile without errors and fulfill all the requirements.
- **Readability**: The contract should be well-documented, with comments explaining the code.
- **Testability**: You should also provide examples of how to test each function of the contract.

Remember, this challenge doesn't cover aspects such as security, gas optimization, and contract upgradability, which are vital considerations for a real-world auction contract on the Celo platform.

For a comprehensive understanding of Celo smart contracts and Solidity, please refer to the Celo and Solidity tutorials.

## Submission

Please reply with a link to your PR on GitHub, including your auction contract, along with any notes or comments you think are necessary to understand your design and choices. Also, provide a brief explanation about how each function of the contract should be tested.
