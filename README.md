<img src="https://github.com/AthitSaenwaet/token-distribution/blob/main/images/logo.png" width="64" height="64">

# HAZARD Token

## Overview

### Etherscan.io

    https://etherscan.io/address/0xc8c6d4a3fe5f9b80f0dc4aa822a34bc77968749d

### Token Address

    0x3cbc42aa1c045fba5caaa572f484772099f309e0ee128fac187b8abc8c11a777

### Bscscan.com

    https://bscscan.com/token/0x27d25325d358c30cc41312fa7c24e3f1913caaa1

### Token Address

    0x27d25325d358c30cc41312fa7c24e3f1913caaa1

## HAZARD Token

The HAZARD token ERC20.sol and BEP20.sol is ERC-20, BEP2-20 standard compatible and has the following additional characteristics:

- An initial BEP-20 amount of 1,000,000,000 HAZARD tokens supply and burn 1,000,000 HAZARD for ERC-20.
- An initial ERC-20 amount of 1,000,000 HAZARD tokens supply.
- An ability to burn tokens by users to reduce total number of token supply.
- At the completion of token sale, HAZARD plans to do the following:

Burn all unallocated tokens to proportionally increase each token holder’s percentage in the overall token amount.

## HAZARD Token

We use OpenZeppelin code for SafeMath, Ownable, Burnable and StandardToken logic.

SafeMath provides arithmetic functions that throw exceptions when integer overflow occurs.
Ownable keeps track of a contract owner and permits the transfer of ownership by the current owner.
Burnable provides a burn function that decrements the balance of the burner and the total supply.
StandardToken provides an implementation of the ERC-20, BEP-20 standard.
The token contract includes the following constants:

    ERC-20

        balances[msg.sender] = 100000000000000;
        totalSupply = 100000000000000;
        name = "HAZARD";
        decimals = 8;
        symbol = "HAZARD";

    BEP-20

        _name = "HAZARD";
        _symbol = "HAZARD";
        _decimals = 18;
        _totalSupply = 1000000000000000000000000000;
        _balances[msg.sender] = _totalSupply;

The above constants indicate a maximum supply of 1,001 million tokens.

Copyright © 2019-2020 - HAZARD Company Limited. All Rights Reserved.
