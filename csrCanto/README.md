![png logo](https://user-images.githubusercontent.com/132018856/235363871-51cf3241-f2dc-4498-910f-594133662bce.png)

# $csrCANTO token

$csrCANTO is a wrapped token, similar to $WCANTO, with the exception of being registered to the [Turnstile](https://docs.canto.io/evm-development/contract-secured-revenue) contract and the use of a accounting and distribution mechanisms to award CSR accrued to tokenholders.

## Links

- [Application](https://csrcanto.xyz)
- [Docs](https://csrcanto.gitbook.io/csrcanto/)
- [Twitter](https://twitter.com/csrCANTO)
- [Discord](https://discord.com/invite/yTjpt9MNDZ)
- [Contract](https://tuber.build/address/0xe73191C7D3a47E45780c76cB82AE091815F4C8F9/contracts#address-tabs)

## Description

The main purpose of CsrCanto is to be able to issue an ERC-20 standard wrapped $CANTO that would leverage the Contract Secured Revenue mechanism in order to distribute a portion of the gas fees spent by the network to the token holders.
All logic is entirely on-chain for transparency and security in order to function as a public good within the ecosystem


We have tailored ideas from 3 different ERCs to the Turnstile contract mechanism for CSR distribution:

1. [ERC-1726: Dividend-Paying Token Standard](https://github.com/ethereum/EIPs/issues/1726)

2. [ERC-1843 - Claims Token Standard](https://github.com/ethereum/EIPs/issues/1843)

Based on the same principles than ERC-1726, but with a different naming system. The _Calculation of the available funds_ and the _Example_ sections have been used to tune the automated tests for our CSR friendly implementation 🙂

<img width="821" alt="Screenshot 2023-05-08 at 00 09 43" src="https://user-images.githubusercontent.com/132018856/236707090-2555145f-2dab-46eb-84d1-12d723e32244.png">

3. [ERC-2222 - Funds Distribution Standard](https://github.com/ethereum/EIPs/issues/2222)

> This EIP is based on and supercedes EIP1726 and EIP1843.

## More about $csrCANTO

- Contract address: [0xe73191C7D3a47E45780c76cB82AE091815F4C8F9](https://tuber.build/address/0xe73191C7D3a47E45780c76cB82AE091815F4C8F9/contracts#address-tabs)
- Contract repo: [sources](https://github.com/csrCANTO/hardhat)

## Core Contributors

<table align="center">
  <tr align="center">
    <td>
        <img height="120" src="https://user-images.githubusercontent.com/132018856/236650125-50256756-94da-44a8-baf9-55df882523a8.jpg" /><br />
        Abraxas
    </td>
    <td>
        <img height="120" src="https://user-images.githubusercontent.com/132018856/236650130-bcd9d8b7-e48a-4096-acd1-ca2b09ac54ea.jpg" /><br />
        Bob - Software engineer
    </td>
  </tr>
</table>
