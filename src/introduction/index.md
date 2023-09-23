# Introduction

I honestly know very little about this, but here's my interpretation of some web3 terms:
- `blockhain` - a bunch of computers run similar software that lets them:
  - send transactions
  - coordinate the results of those transactions(making sure no one's lying/everyone agrees on what happened)
  - execute smart contract code <-- fun stuff here
 
- `transaction` - anything that changes the state of the blockchain(or what the computers agreed upon)
  - sending cryptocurrency(ETH on ethereum, SOL on solana, etc)
  - calling smart contract code(either through another smart contract, or through off-chain client code)
  - deploying smart contracts

- `smart contract` - the code executed by blockchain computers
  - usually has to compiled to some kind of bytecode beforehand
 
## So, what does this mean for an apsiring web3 ctfer?
Usually, your main goal will be to:
- get some number of cryptocurrency, or
- change some variable of a smart contract(ex: setting `iSSolved` to `true`)

One of the really cool things about these types of challs is that they're(usually) pretty open-handed in how you can approach them. You can write off-chain code(in nodejs, rust, python, etc) to solve the challenge, deploy a smart contract to exploit the target contract when it's deployed, or make a helper smart contract to work with your off-chain code. I'm pretty sure there's some other approaches I'm missing here, which is even cooler! However, there are some downsides

## What's the catch?
There's a _lot_ of programming, like an ass-ton. Being comfortable with programming in general(or even better, a specific language), will be a huge help. Other than that, there's also a bunch of setup you have to do just to get started, which can also suck. If you're okay with that(or even _enjoy_ it, you sick bastard), you're in luck!

## Now what?
Continue on!

<todo: make next chapter + first project's files>
