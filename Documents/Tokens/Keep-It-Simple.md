# Keep-It-Simple

<a rel="license" href="http://creativecommons.org/licenses/by/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by/4.0/88x31.png" /></a><br /><span xmlns:dct="http://purl.org/dc/terms/" href="http://purl.org/dc/dcmitype/Text" property="dct:title" rel="dct:type">Non Fungible Token Design</span> by <a xmlns:cc="http://creativecommons.org/ns#" href="https://github.com/Quality-Assurance-DAO" property="cc:attributionName" rel="cc:attributionURL">Stephen Whitenstall</a> is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by/4.0/">Creative Commons Attribution 4.0 International License</a>.

<img src="/Documents/Binary/Keep it Simple.gif" align="center" width="1000">

<hr>

# Contributions

There are many types of contribution to NFT-DAO. There are **Audited Contributions**. Contributions that must be reported (e.g., to a funder).There are **Tracked Contributions**. Contributions that NFT-DAO can quantify (e.g., through GitHub).There are **Voted contributions**. Contributions that members vote on.

1. **Audited Contributions**. 
1. **Tracked Contributions**. 
1. **Voted contributions**. 

These types of value : Audited, Tracked and Voted Contributions. Are recorded in a **Contributions ledger** in metadata, either on a side chain or in IPFS.

# One Token

There is One Token. For example : **The NFT-DAO Token**. The NFT-DAO Token is convertible to **Fungible** (e.g. burnt), **Swaps**, (e.g. other tokens) and **Votes** (e.g., Governance Rights).

1. **Fungible** (e.g. burnt)
2. **Swaps**, (e.g. other tokens)
3. **Votes** (e.g., Governance Rights).

# Plutus Smart Contract

The 3 contribution states (Audited, Tracked, Voted) are recorded in a **Plutus Smart Contract**. Haskell logic matches JSON Metadata of each Contribution type to an NFT-DAO Token state (Fungible, Swaps, Votes). The NFT-DAO Token is minted in these contextual states.

# Roadmap / Priorities

## Complexity of Smart Contract

The complexity of each Smart Contract rendition of contribution states increases from Audited, through Swaps, to Votes.

### Simple : Audited / Fungible

The simplest smart contract only depends upon data that is volunteered by the DAO (**Audited**) and results in the minting of a simple Token that is Fungible.

**Example** : A simple Art Token (NFT) with arbitrary metadata attached that is only bought or sold.

### Intermediate : Tracked / Swaps

An intermediate smart contract depends upon data that is tracked by the DAO (**Tracked**) and results in the minting of a Token that can be swapped for other tokens (as well as being fungible).

**Example** : A Swaps Token (NFT) with metadata sourced from tracked data (e.g. JSON frameworks) that may be traded with other Swaps Tokens

### Complex : Voted / Votes

A complex set of contracts that depends upon a voting system (**Voted**) designed using Game Theory which results in the minting of a Token that can be used for participation in governance of a DAO.

**Example** : No LIVE examples.




