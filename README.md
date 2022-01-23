# BlockChain Smart Contracts

The goal of blockchain is to allow digital information to be recorded and distributed, but not edited.

The concept and idea of Smart Contracts was born with Nick Szabo in his paper originally published in 1997, as we can see the the link below:

- [The Idea of Smart Contracts Nick Szabo published in 1997](https://nakamotoinstitute.org/the-idea-of-smart-contracts/)

![traditionlxsmartcontracts](https://github.com/aridiosilva/SmartContractsBlockchain/blob/main/smart-vs-traditional.png)

- [Smart Contracts simply explained in this video](https://youtu.be/ZE2HxTmxfrI)

Blockchains are far more secure, inexpensive, and faster versus other technologies. Their vast advantages are compelling more and more global organizations to use smart contracts in their operations. Governments, banks and other organizations across the world are increasingly deploying them. The global smart contracts market is expected to increase the values year by year exponentially. Smart contracts have myriad applications. As a form of smart contracts law, many organizations now use them for legal processes and property law. Banks utilize smart contracts examples from basic financial services to the more complicated financial derivatives. Crowdfunding agreements, insurance premiums, and others use smart contract to expedite their transactions.

##  What are Blockchain Smart Contracts ?

(1) According to Nick Szabo in his “The Idea of Smart Contracts,” smart contracts are blockchain applications that express business logic associated with a transaction and execute on a blockchain platform. Smart contract code determines what transactions are recorded into the blockchain and the information they will contain. Through the use of smart contracts, many kinds of contractual clauses may be made partially or fully self-executing and self-enforcing. 

(2) A smart contract is a computer program or a transaction protocol which is intended to automatically execute, control or document legally relevant events and actions according to the terms of a contract or an agreement.

(3) A smart contract is code – invoked by a client application external to the blockchain network – that manages access and modifications to a set of key-value pairs in the World State via Transaction. In Hyperledger Fabric, smart contracts are packaged as chaincode. Chaincode is installed on peers and then defined and used on one or more channels.

(4) Another simple smart contract definition is that it is a group of computer codes that can self-execute when predetermined conditions are met. A blockchain or a distributed ledger holds the transaction outcomes. People typically pay for the services of a notary public or a lawyer to have their documents processed. With smart contracts, they can create, enforce, and complete a deal or agreement by themselves. These allow people to execute deals without any third party. Smart contracts don’t only establish the penalties and other obligations of an agreement like how a traditional contract does. They can carry them out automatically.  These digital contracts offer numerous potential applications in various industries. Smart contracts already work in tandem with the predicted currency of the future–bitcoins.

## Three Essential Aspects of a Smart Contract

> - First, a smart contract is a computerized agreement between two individuals. Smart contracts exist on a blockchain—a public database—which make them immutable.
> - Second, a blockchain executes a smart contract. This means the agreement can be done without relying on a third-party mediation. 
> - Third, its transactions only transpire once the agreement conditions are fulfilled. This eliminates trust issues from emerging.

## What are the Objectives of Smart Contracts ?

The objectives of smart contracts are the reduction of need in trusted intermediators, arbitrations and enforcement costs, fraud losses, as well as the reduction of malicious and accidental exceptions.

## When they First Appear ?

Smart contracts were first proposed in the early 1990s by Nick Szabo, who coined the term, using it to refer to "a set of promises, specified in digital form, including protocols within which the parties perform on these promises". In 1998, the term was used to describe objects in rights management service layer of the system The Stanford Infobus, which was a part of Stanford Digital Library Project.

## Legal Status of Smart Contracts

A smart contract does not necessarily constitute a valid binding agreement at law. Some legal academics claim that smart contracts are not legal agreements, but rather means of performing obligations deriving from other agreements such as technological means for the automation of payment obligations or obligations consisting in the transfer of tokens or cryptocurrencies. Additionally, other scholars have argued that the imperative or declarative nature of programming languages can impact the legal validity of smart contracts.

With the 2015's implementation of Ethereum, based on blockchains, "smart contract" is mostly used more specifically in the sense of general purpose computation that takes place on a blockchain or distributed ledger. The US National Institute of Standards and Technology describes a "smart contract" as a "collection of code and data (sometimes referred to as functions and state) that is deployed using cryptographically signed transactions on the blockchain network". In this interpretation, used for example by the Ethereum Foundation or IBM, a smart contract is not necessarily related to the classical concept of a contract, but can be any kind of computer program. A smart contract also can be regarded as a secured stored procedure as its execution and codified effects like the transfer of some value between parties are strictly enforced and can not be manipulated, after a transaction with specific contract details is stored into a blockchain or distributed ledger. That's because the actual execution of contracts is controlled and audited by the platform, not by any arbitrary server-side programs connecting to the platform.

In 2017, by implementing the Decree on Development of Digital Economy, Belarus has become the first-ever country to legalize smart contracts. Belarusian lawyer Denis Aleinikov is considered to be the author of a smart contract legal concept introduced by the decree.

In 2018, a US Senate report said: "While smart contracts might sound new, the concept is rooted in basic contract law. Usually, the judicial system adjudicates contractual disputes and enforces terms, but it is also common to have another arbitration method, especially for international transactions. With smart contracts, a program enforces the contract built into the code." A number of states in the US have passed legislation on the use of smart contracts, such as Arizona, Nevada, Tennessee, and Wyoming.

## Implementations of Smart Contracts

Similar to a transfer of value on a blockchain, deployment of a smart contract on a blockchain occurs by sending a transaction from a wallet for the blockchain. The transaction includes the compiled code for the smart contract as well as a special receiver address. That transaction must then be included in a block that is added to the blockchain, at which point the smart contract's code will execute to establish the initial state of the smart contract. 

Byzantine fault-tolerant algorithms secure the smart contract in a decentralized way from attempts to tamper with it. Once a smart contract is deployed, it cannot be updated.Smart contracts on a blockchain can store arbitrary state and execute arbitrary computations. 

End clients interact with a smart contract through transactions. Such transactions with a smart contract can invoke other smart contracts. These transactions might result in changing the state and sending coins from one smart contract to another or from one account to another. 

## Blockchain Platforms Supporting Smart Contracts

## Platforms list

| Platform name                          | Engine         | Contract language                                           | Live? |Origin | Inc. in     | Est.  | Pub. rel.|
|----------------------------------------|----------------|:-----------------------------------------------------------:|------:|------:|------------:|------:|----------|
| [Aeternity](https://aeternity.com/)    | HLM, FTWVM, AEVM | [Sophia, Varna, Solidity](https://github.com/aeternity/protocol/blob/master/contracts/contract_vms.md) | no | FL | Liechtenstein | 2017 | |
| [Bitcoin](https://bitcoin.org/)        | Bitcoin script |  [Ivy-lang](https://docs.ivy-lang.org), [Balzac](https://blockchain.unica.it/balzac/docs/)           | Yes   | USA     | USA       |2017.12|2017.12   |
| [Byteball](https://byteball.org)       | Byteball       |  JSON                                                       | Yes   | RU    |             |2016.12|2016.12   |
|[Cardano](https://cardanofoundation.org)| [IELE](https://iohk.io/blog/iele-a-new-virtual-machine-for-the-blockchain) |  Plutus (Haskell inspired)                                  | no    |HK       |Switzerland|2015   |
| [Corda](https://www.corda.net/)        | ?              |
| [DFINITY](https://dfinity.org/)        | EVM?           | Ethereum compatible (aka Solidity, Serpent, etc.)                                           | No |  |  |   |  |
| [EOS](https://eos.io/)                 | EVM / eWASM    |  C/C++ (compiles to WASM)                                   | Yes   |       |             |       |2018.06    
| [Ethereum](https://www.ethereum.org/)  | EVM            |  Solidity                                                   | Yes   | CA    |Switzerland  |2014.04|2015.07   |
| [Ethereum Classic](https://ethereumclassic.github.io/)| EVM |  Solidity                                              | Yes   | ^^^   | no          | ^^^   | ^^^      |
| [Exonum](https://exonum.com)           | ?              |  Rust. Java bindings TBD                                    | No    | UA    |Netherlands  |       |2017.07   |
| [hyperledger](https://hyperledger-fabric.readthedocs.io/en/release-1.3/)                            | Sandbox        | Goland, Java SDK                                         | ?     |    
| [Lisk](https://lisk.io/)               | N/A            |  Javascript
| [Nem](https://nem.io/)                 | Offchiain      |  ?                                                          | ?     |
| [Neo](https://neo.org/)                | NeoVM          |  1st batch: dotNet; 2nd: Java,Kotlin; 3rd: C,C++,GO,Py,JS (TBD)| Yes| China | China       |2014.06|2016.10   |
| [Neblio](https://nebl.io)              | ?              |  REST-API, Python,JS, .NET(C# & VB.NET), Objective-C, Java, Node.js, GO, PHP | Yes| USA | USA       |2017.01|2017.07   |
| NXT                                    | ?              |  ?                                                          | Yes   |    
| OmniLayer                              | ?              |
| [Qtum](https://qtum.org/)              | EVM            |  Solidity                                                   | Yes   |Singapore|Singapore  |2016   |2017.09   |
| quorum                                 | ?              |  ?                                                          | ?     |    
| [Radix](https://www.radixdlt.com/)     | ?              | Scrypto (Based on JavaScript/TypeScript) | Yes | UK | UK     | 2018  | |
| [Rootstock](http://www.rsk.co/)        | EVM            |  Solidity                                                   | no    |Argentina|Argentina  |2015.11|
| [Snax](https://snax.one/)                 | EVM / eWASM    |  C/C++ (compiles to WASM)                                   | no   |       |             | 2018.12 |  
| [Tezos](https://www.tezos.com)         | ?              |  Michelson                                                  | no    |
| [Ubiq](http://www.ubiqsmart.com/)      | EVM            |  Solidity                                                   | Yes   | CA    | CA ?        |       |2017.01   |
| [Universa](https://www.universa.io/)   | ?              |
| [Urbit](https://urbit.org/)            | ?              |  Hoon                                                       | Yes   |    
| [Waves](https://wavesplatform.com/)    | ?              |  _NA_                                                       | Yes   |RU     |  ?          |2016   |2016.11   | 



### 1 - Ethereum 

*Ethereum is a gold standard in the world of smart contracts and has the biggest capitalisation among other platforms. The majority of token sales happen on the Ethereum platform, using the ERC-20 token standard. There are various ERC standards and more are coming up as we speak. Implements a Turing-complete language on its blockchain, a prominent smart contract framework. Ethereum was specifically created and designed to support smart contrats. Smart Contrats can be programmed in a special programmming language called Ethereum Solidity. This language was created by Ethereum and uses a syntax that resembles JavaScript. The link to documentation site can be found [here](http://www.ethdocs.org/en/latest/introduction/web3.html#smart-contracts).*


```solidity
pragma solidity ^0.4.0;

contract SimpleStorage {
    uint storedData;
    function set(uint x) public {
        storedData = x;
    }
    function get() public constant returns (uint) {
        return storedData;
    }
}
```

### 2 - Bitcoin

*Provides a Turing-incomplete script language that allows the creation of custom smart contracts on top of Bitcoin like multisignature accounts, payment channels, escrows, time locks, atomic cross-chain trading, oracles, or multi-party lottery with no operator. Smart Contracts in Bitcoin platform it´s a lot more limited compared to Ethereum Platform.*

```solidity
pragma solidity ^0.4.24;
import "./trc20.sol";

contract ITokenDeposit is TRC20 {
    function deposit() public payable;
    function withdraw(uint) public;
}
```

```solidity
/// TRC20.sol -- API for the TRC20 token standard

// See <https://github.com/tronprotocol/tips/blob/master/tip-20.md>.

// This file likely does not meet the threshold of originality
// required for copyright to apply.  As a result, this is free and
// unencumbered software belonging to the public domain.

pragma solidity >=0.4.25;

contract TRC20Events {
    event Approval(address indexed src, address indexed guy, uint wad);
    event Transfer(address indexed src, address indexed dst, uint wad);
}

contract TRC20 is TRC20Events {
    function totalSupply() public view returns (uint);
    function balanceOf(address guy) public view returns (uint);
    function allowance(address src, address guy) public view returns (uint);

    function approve(address guy, uint wad) public returns (bool);
    function transfer(address dst, uint wad) public returns (bool);
    function transferFrom(
        address src, address dst, uint wad
    ) public returns (bool);
}
```

````solidity
pragma solidity ^0.4.24;

import "./token_deposit.sol";

contract WTRX is ITokenDeposit {
    string public name = "Wrapped TRX";
    string public symbol = "WTRX";
    uint8  public decimals = 6;

    event  Approval(address indexed src, address indexed guy, uint sad);
    event  Transfer(address indexed src, address indexed dst, uint sad);
    event  Deposit(address indexed dst, uint sad);
    event  Withdrawal(address indexed src, uint sad);

    uint256 private totalSupply_;
    mapping(address => uint)                       private  balanceOf_;
    mapping(address => mapping(address => uint))  private  allowance_;


    function() public payable {
        deposit();
    }

    function deposit() public payable {
        balanceOf_[msg.sender] += msg.value;
        totalSupply_ += msg.value;
        emit Deposit(msg.sender, msg.value);
    }

    function withdraw(uint sad) public {
        require(balanceOf_[msg.sender] >= sad, "not enough balance");
        require(totalSupply_ >= sad, "not enough totalSupply");
        balanceOf_[msg.sender] -= sad;
        msg.sender.transfer(sad);
        totalSupply_ -= sad;
        emit Withdrawal(msg.sender, sad);
    }

     function totalSupply() public view returns (uint) {
        return totalSupply_;
    }

    function balanceOf(address guy) public view returns (uint){
        return balanceOf_[guy];
    }

    function allowance(address src, address guy) public view returns (uint){
        return allowance_[src][guy];
    }

    function approve(address guy, uint sad) public returns (bool) {
        allowance_[msg.sender][guy] = sad;
        emit Approval(msg.sender, guy, sad);
        return true;
    }

    function approve(address guy) public returns (bool) {
        return approve(guy, uint(- 1));
    }

    function transfer(address dst, uint sad) public returns (bool) {
        return transferFrom(msg.sender, dst, sad);
    }

    function transferFrom(address src, address dst, uint sad)
    public
    returns (bool)
    {
        require(balanceOf_[src] >= sad, "src balance not enough");

        if (src != msg.sender && allowance_[src][msg.sender] != uint(- 1)) {
            require(allowance_[src][msg.sender] >= sad, "src allowance is not enough");
            allowance_[src][msg.sender] -= sad;
        }

        balanceOf_[src] -= sad;
        balanceOf_[dst] += sad;

        emit Transfer(src, dst, sad);

        return true;
    }
}
```` 

### 3 - Ripple (Codius)

*Ripple is a real-time gross payment system first-conceived in 2004 by Ryan Fugger and officially launched in 2012. ts goal is to eliminate the high transaction fees and processing delays of online payments by providing a frictionless experience when sending money globally with the power of blockchain technology. But Smart contract development halted in 2015.*

```javascript
{
  "source": {
    "address": "r9cZA1mLK5R5Am25ArfXFmqgNwjZgnfk59",
    "maxAmount": {
      "value": "0.01",
      "currency": "USD",
      "counterparty": "rMH4UxPrbuMa1spCBR98hLLyNJp4d8p4tM"
    }
  },
  "destination": {
    "address": "rpZc4mVfWUif9CRoHRKKcmhu1nx2xktxBo",
    "amount": {
      "value": "0.01",
      "currency": "USD",
      "counterparty": "rMH4UxPrbuMa1spCBR98hLLyNJp4d8p4tM"
    }
  }
}
```

The link for documentation site can be found [here](https://github.com/ripple/rippled).

### 4 - EOS.Io

*A blockchain platform for smart contracts.Can be use C++, Swift, JavaScript or Java to develop smart contracts using the EOSIO Platform.*

The link for documentation site can be found [here](https://developers.eos.io/welcome/latest/getting-started-guide/index)

```java
IRPCProvider rpcProvider = new EosioJavaRpcProviderImpl("https://baseurl.com/v1/");
ISerializationProvider serializationProvider = new AbiEosSerializationProviderImpl();
IABIProvider abiProvider = new ABIProviderImpl(rpcProvider, serializationProvider);
ISignatureProvider signatureProvider = new SoftKeySignatureProviderImpl();

signatureProvider.importKey(privateKeyK1EOS);
// or...
signatureProvider.importKey(privateKeyR1EOS);

TransactionSession session = new TransactionSession(
        serializationProvider,
        rpcProvider,
        abiProvider,
        signatureProvider
);

TransactionProcessor processor = session.getTransactionProcessor();

// Now the TransactionConfig can be altered, if desired
TransactionConfig transactionConfig = processor.getTransactionConfig();

// Use blocksBehind (default 3) the current head block to calculate TAPOS
transactionConfig.setUseLastIrreversible(false);
// Set the expiration time of transactions 600 seconds later than the timestamp
// of the block used to calculate TAPOS
transactionConfig.setExpiresSeconds(600);

// Update the TransactionProcessor with the config changes
processor.setTransactionConfig(transactionConfig);

String jsonData = "{\n" +
        "\"from\": \"person1\",\n" +
        "\"to\": \"person2\",\n" +
        "\"quantity\": \"10.0000 EOS\",\n" +
        "\"memo\" : \"Something\"\n" +
        "}";

List<Authorization> authorizations = new ArrayList<>();
authorizations.add(new Authorization("myaccount", "active"));
List<Action> actions = new ArrayList<>();
actions.add(new Action("eosio.token", "transfer", authorizations, jsonData));

processor.prepare(actions);

SendTransactionResponse sendTransactionResponse = processor.signAndBroadcast();

// Starting with EOSIO 2.1 actions can have return values associated with them.
// If the actions have return values they can be accessed from the response.
ArrayList<Object> actionReturnValues = sendTransactionResponse.getActionValues();

// Or
try {
    Double actionReturnValue = response.getActionValueAtIndex(index, Double.class);
} catch (IndexOutOfBoundsException outOfBoundsError) {
    // Handle out of bounds error
} catch (ClassCastException castError) {
    // Handle class casting error
}
```

### 5 - Tezos

*A blockchain platform modifying its own set of rules with minimal disruption to the network through an on-chain governance model.*

### 6 - Hyperledger Fabric (HLF)

*Call its smart contracts chaincode. HLF is an enterprise private blockchain, built with great flexibility, which makes it very useful for businesses as their business rules change after approximately 7 years. Most other blockchains are not built considering flexibility. The three most important functions are:

1) **PutState**: Create new asset or update existing one; 
1) **GetState**: Retrieve asset; 
1) **GetHistoryForKey**: Retrieve history of changes; 
1) **DelState**: Delete asset; 

Most of the chaincode (smart contracts built using HyperLedger Fabrics) is written in Golang. They also have a Java SDK for developing blockchain applications.

```golang
package main

import (
    "fmt"

    "github.com/hyperledger/fabric/core/chaincode/shim"
    "github.com/hyperledger/fabric/protos/peer"
)

// SimpleAsset implements a simple chaincode to manage an asset
type SimpleAsset struct {
}

// Init is called during chaincode instantiation to initialize any
// data. Note that chaincode upgrade also calls this function to reset
// or to migrate data.
func (t *SimpleAsset) Init(stub shim.ChaincodeStubInterface) peer.Response {
    // Get the args from the transaction proposal
    args := stub.GetStringArgs()
    if len(args) != 2 {
            return shim.Error("Incorrect arguments. Expecting a key and a value")
    }

    // Set up any variables or assets here by calling stub.PutState()

    // We store the key and the value on the ledger
    err := stub.PutState(args[0], []byte(args[1]))
    if err != nil {
            return shim.Error(fmt.Sprintf("Failed to create asset: %s", args[0]))
    }
    return shim.Success(nil)
}

// Invoke is called per transaction on the chaincode. Each transaction is
// either a 'get' or a 'set' on the asset created by Init function. The Set
// method may create a new asset by specifying a new key-value pair.
func (t *SimpleAsset) Invoke(stub shim.ChaincodeStubInterface) peer.Response {
    // Extract the function and args from the transaction proposal
    fn, args := stub.GetFunctionAndParameters()

    var result string
    var err error
    if fn == "set" {
            result, err = set(stub, args)
    } else { // assume 'get' even if fn is nil
            result, err = get(stub, args)
    }
    if err != nil {
            return shim.Error(err.Error())
    }

    // Return the result as success payload
    return shim.Success([]byte(result))
}

// Set stores the asset (both key and value) on the ledger. If the key exists,
// it will override the value with the new one
func set(stub shim.ChaincodeStubInterface, args []string) (string, error) {
    if len(args) != 2 {
            return "", fmt.Errorf("Incorrect arguments. Expecting a key and a value")
    }

    err := stub.PutState(args[0], []byte(args[1]))
    if err != nil {
            return "", fmt.Errorf("Failed to set asset: %s", args[0])
    }
    return args[1], nil
}

// Get returns the value of the specified asset key
func get(stub shim.ChaincodeStubInterface, args []string) (string, error) {
    if len(args) != 1 {
            return "", fmt.Errorf("Incorrect arguments. Expecting a key")
    }

    value, err := stub.GetState(args[0])
    if err != nil {
            return "", fmt.Errorf("Failed to get asset: %s with error: %s", args[0], err)
    }
    if value == nil {
            return "", fmt.Errorf("Asset not found: %s", args[0])
    }
    return string(value), nil
}

// main function starts up the chaincode in the container during instantiate
func main() {
    if err := shim.Start(new(SimpleAsset)); err != nil {
            fmt.Printf("Error starting SimpleAsset chaincode: %s", err)
    }
}

```

The link to documentation site can be found [here](https://hyperledger-fabric.readthedocs.io/).*

### 7 - iOlite

Is a product which focuses on the mass adoption of smart contract technology by providing an easy to use engine which is capable of understanding natural language to be compiled to smart contract code It is based on FAE (Fast adaption engine) FAE is capable of converting natural language into smart contract code.*

 
*The link for documentation site can be found [here](https://iolite.io/documentation).*

### 8 - Stellar Smart Contracts

*Stellar smart contracts (SSC) are much different from Ethereum smart contracts. They are not Turing complete and are implemented as an agreement between multiple parties and enforced by transactions. 

An SSC is expressed as compositions of transactions that are connected and executed using various constraints. Some of the constraints are: 

a) **Multi-signature** — What keys are needed to authorise a certain operation? What parties need to agree on a circumstance in order to execute the steps? 
b) **Batching/ Atomicity** — What operations must all occur together or fail? What must happen in order to force this to fail or pass? 
c) **Sequence** — In what order should a series of transactions be processed? What are the limitations and dependencies? e 
d) **Time Bounds** — When can a transaction be processed?*

```javascript
A sample code is given below:
const newKey = Stellar.Keypair.random();
const transaction = new Stellar.TransactionBuilder(ownerAccount)
    .addOperation(Stellar.Operation.createAccount({
        destination: escrowPubKey,
        startingBalance: '2.5000000'
    }))
    .build();
transaction.sign(ownerKeypair);
return StellarConfig.server.submitTransaction(transaction);
```

You can read more about stellar smart contracts in the official documentation [here](https://www.stellar.org/developers/guides/walkthroughs/stellar-smart-contracts.html). 
 
### 9 - Cardano

*Similar to Ethereum, Cardano is a smart contract platform however, Cardano offers scalability and security through layered architecture. Cardano’s approach is unique in the space itself since it is built on scientific philosophy and peer-reviewed academic research. The contact language used is Plutus.*

```plutus
add : Nat -> Nat -> Nat {
  add = \m n ->
    case m of {
      Zero -> n ;
      Suc m' -> Suc (add m' n)
    }
}
```

### NEM

*Scalability is the most critical thing about NEM’s decentralized application. While ETH does a maximum of 15 transactions per second, NEM reportedly manages hundreds of transactions per second. The NEM foundation has given security and availability a priority so entrepreneurs deal with other problems and not technical difficulties.While NEM is reportedly the faster, safer and easier technology, Ethereum provides a broader base for the creation of custom DApps.

Where Ethereum is targeting companies intend to rebuild internal networks in the next 5 to 10 years, NEM is targeting companies looking for a fast, secure, and ready to use and handle solution that’s current.

An example of NEM code is given below:

```javascript
//Include the library
var nem require(".. ./build/index.js")

/ Create an NIS endpoint object
 var endpoint - nem.model.objects.create( endpoint
// Create a common object holding key
var common - nem.model.objects.create("common
 I/Create an un-prepared transfer transaction object
var transferTransaction nem.model.objects

// Prepare the transfer transaction object
 var transactionEntity nem.model.transactions
// Serialize transfer transaction and announce
nem.model.transactions.send(common,
transactionEntity, endpoint);
```

The link to the documentation site can be found [here](https://nemproject.github.io/)

## Smart Contract Eexecution

In 1998, Szabo proposed that smart contract infrastructure can be implemented by replicated asset registries and contract execution using cryptographic hash chains and Byzantine fault-tolerant replication. Askemos implemented this approach in 2002 using Scheme (later adding SQLite) as contract script language.

One proposal for using bitcoin for replicated asset registration and contract execution is called "colored coins". Replicated titles for potentially arbitrary forms of property, along with replicated contract execution, are implemented in different projects.

As of 2015, UBS was experimenting with "smart bonds" that use the bitcoin blockchain[46] in which payment streams could hypothetically be fully automated, creating a self-paying instrument.


## Security in Smart Contracts

A blockchain-based smart contract is visible to all users of said blockchain. However, this leads to a situation where bugs, including security holes, are visible to all yet may not be quickly fixed. Such an attack, difficult to fix quickly, was successfully executed on The DAO in June 2016, draining US$50 million in Ether while developers attempted to come to a solution that would gain consensus. The DAO program had a time delay in place before the hacker could remove the funds; a hard fork of the Ethereum software was done to claw back the funds from the attacker before the time limit expired.

Issues in Ethereum smart contracts, in particular, include ambiguities and easy-but-insecure constructs in its contract language Solidity, compiler bugs, Ethereum Virtual Machine bugs, attacks on the blockchain network, the immutability of bugs and that there is no central source documenting known vulnerabilities, attacks and problematic constructs.

##Caracteristics of Smart Legal Contracts

Smart legal contracts are distinct from smart contracts. As mentioned above, a smart contract is not necessarily legally enforceable as a contract. On the other hand, a smart legal contract has all the elements of a legally enforceable contract in the jurisdiction in which it can be enforced and it can be enforced by a court or tribunal. Therefore, while every smart legal contract will contain some elements of a smart contract, not every smart contract will be a smart legal contract.

There is no formal definition of a smart legal contract in the legal industry.

A Ricardian contract is a type of smart legal contract.

## How are Smart Contracts used ?

Nowadays, businesses want to streamline their processes and accelerate current workflows. Most are using tools like marketing automation platforms to simplify their operations to the hilt.

Businesses can leverage smart contracts for these and a host of other applications. Here are some smart contract examples that digital contracts provide.

![simple to complex use](https://github.com/aridiosilva/SmartContractsBlockchain/blob/main/Smart-Contracts-Use-Cases-Simple-to-Complex.png)

> - **a) Legal Use** - *The obvious sector that would take advantage of smart contracts is the legal profession. These new digital forms of contracts will change how documents will be certified. Smart contracts offer a cost-efficient, impartial solution for people. The need for cumbersome notarization decreases.*
> - **b) Government Use** - *With the help of smart contracts, government agencies can easily enact deals to uphold democratic and legal endeavors. A city or municipal government can integrate smart contracts in its voting system. The likelihood of any election-related crimes will become impossible since votes are stored in a highly-secured distributed ledger.*
> - **c) Healthcare Use** - *Smart contracts help healthcare companies provide confidence to patients that their personal information is safe. They can enhance the insurance trial processes and offer easy access to cross-institutional data. Digital contracts allow seamless monitoring of patient interactions and easy tracking of system efficiencies. Combining smart contracts with reliable medical practice management software solutions can help elevate productivity.*
> - **d) Real Estate Use** - *Real estate firms can use smart contracts for signing deals between buyers and sellers, renters and owners, etc. One online real estate marketplace, Propy, is already among the many uses of smart contracts. Buyers can easily search and buy using the system, which offers unparalleled fairness and legality. 
To further boost productivity, it’s good to integrate digital contracts with today’s best real estate management software solutions.*
> - **e) Merchandising Use** - *Supply chains usually involve negotiations. They would stand to benefit immensely from smart contracts. Supplier and logistics firms can use smart contracts to minimize risks and automate tasks like invoicing and product releasing. The system can execute deals and manage approvals. Smart contracts can be used regardless of the type of marketplace or the things being sold.*

# How does a smart contract work?

A smart contract is a computer application that operates inside a blockchain. Two or several parties agree to the set of rules stored in the contract.

It’s like a typical application that implements some business rules. It can only use a blockchain as a database. Here are the key aspects of a smart contract:

> - **1- Identify Agreement** - *Parties engaged in the smart contract determine a shared, agreed opportunity and intended results. Possible agreements are vast, from simple business transactions and rights transfer to asset swaps*
> - **2- Set Conditions** - *Parties can decide either to initiate their digital contracts by themselves or by fulfilling certain criteria such as natural disasters or financial market movements. Other conditions that could launch smart contracts include religious occasions or important holidays.*
> - **3- Code the Business Logic** - *Like other computer programs, a smart contract is an application designed to automatically perform once the conditional parameters are reached.*
> - **4- Encryption & Blockchain Technology** - *In a blockchain, encryption is used. This provides the needed security in authenticating and verifying the messages exchanged among the involved parties.*
> - **5- Processing & Execution** - *A smart contract gets written to a block in a blockchain iteration. This occurs after reaching consensus via validation and authentication. Once the code is executed, the results are memorized for verification and compliance.*
> - **6- Network Updates** - *Every computer connected to a blockchain network automatically updates its ledgers. This demonstrates the blockchain’s new state. Upon authentication and posting, no one can alter a record in a blockchain. Only append-only actions can be done.*

# What are the benefits of Smart Contracts?

Here are some of the major benefits that smart contracts can bring to your business:

> - **Direct business relationships** - *The blockchain continues to function as prearranged. All agreed terms and conditions are accessible and visible to concerned parties. Because of its design, it’s impossible to dispute the stipulations the moment a smart contract has been determined. This makes smart contracts highly reliable.*
> - **Integrity & Trustworthiness** - *The network will sustain its integrity. The terms and conditions of smart contracts are visible and accessible to trusted parties. There’s no way to dispute the conditions of a smart contract. The parties can fully rely on the smart contract.*
> - **Speed & Security** - *Smart contracts use code and live on the internet. They execute transactions quickly. This saves time for many business processes and eliminates the need to process documents manually. Smart contracts use the same level of security as a cryptocurrency. As of today, they’re the safest way to store data on the web.*
> - **Efficient records keeping** - * Each smart contract is a digital record that can be easily stored and accessed as needed.*
> - **Paper-free** - * Smart contracts are stored digital space, securely and cost-efficiently.*> 

![Traditional-vs-Smart-Contracts](https://github.com/aridiosilva/SmartContractsBlockchain/blob/main/Traditional-vs-Smart-Contracts0003.png)

# Is a Smart Contract Legally Binding?

## Are Smart Contracts Legal?

The main concept behind smart contracts is using programs to administer the stipulations of a contract. It uses of cryptography to guarantee fraud protection, transparency, and anti-tampering. These digital contracts automatically warrant assumed legality. There’s no specific smart contract law yet. Smart contracts should be considered as software programs that can assume a contractual nature when the engaging parties decide to do so. They’re a tool to enforce legality. They’re not by themselves inherently legal instruments. 

## Three Elements of a Contract

Having said that, a legally-binding smart contract must necessarily fulfill the three elements of a traditional contract. 

> - First, a party must initiate an offer. 
> - Second, the counterparty must agree to the offered terms. 
> - Third, parties bargain on shared promises and obligations.

Simply put, like in traditional deals, smart contracts must transfer some type of value at a present or upcoming time.

## Legal basis

How are smart contracts enforced? There are existing laws that already recognize the use and legal nature of smart contracts. These tools can assure businesses of their legality and security. For instance, in USS one such law is the *Uniform Electronic Signatures Act and Electronic Signatures in Global and National Commerce Act*. This existing statute already recognizes, allows, and validates the use of electronic signatures and electronic records. This involves those that use blockchain. The law is ij USA ready. Users only need to work closely work with lawyers and use it with caution.

# How is going to use of Smart Contracts?

Smart contracts help you exchange money, property, shares, and virtually anything of value. You can all these in a problem-free and transparent way, without needing the traditionally ubiquitous middleman. Using smart contracts is simply inevitable that as technology continues to change how people conduct business as we know it. This new way of creating and executing contracts is already providing numerous advantages to existing users. It includes a very high level of security, cost and time savings, anti-tampering feature. 

# SWOT Analysis of Blockchain Technology

In a world filled with emerging technologies, the blockchain technology is arguably one of the most exciting, being labeled as ‘disruptive’ and ‘innovative’ by many. Despite often being associated abundantly with Bitcoin and other cryptocurrencies, the underlying technology, this distributed ledger, the ‘blockchain’ has been receiving attention from a variety of industries. The concept of recording transactions in a secure, stable and chronological way, has led to possible applications in many areas.

Whilst we have to admit that blockchain is still in its infancy. Many issues like unwanted centralization, slow transaction verification times and low throughput aren’t easy to solve. We have to try and find the balance between security and speed.

To help you make sense of this complicated landscape we applied a simple SWOT analysis to the blockchain and integrated our iOlite’s solutions in this analysis.

![swot analysis](https://github.com/aridiosilva/SmartContractsBlockchain/blob/main/Blockchain%20SWOT%20Analysis%20of%20BLOCKCHAIN%20TECHNOLOGY__.png)

