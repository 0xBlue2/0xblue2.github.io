This is my attempt at a course about blockchain CTFs. There is a lot of good information out there, but I think it'll help to put a lot of it one place.

## Where's the name come from?
The name(and general format) is ripped straight from one of the greatest ctf courses, [Nightmare](https://guyinatuxedo.github.io/).

## How much of it is done?
Very little! You can check the github for commit history, but I'm starting this pretty late into 2023. If you have any advice/corrections/chall you think I should add, let me know. It realistically won't be done for at least a year+, both because I'm lazy and know very little about most of this.

## What does it cover?
I'll likely update this as I update this blog(and actually get good at some of this stuff), but I hope to eventually cover:
- Ethereum
  - reentrancy, over/underflow, `private` storage
- Solana
  - blocking others from making a specific transaction via address collisions, improperly checking input
- Algorand
  - (I haven't yet seen any challs, but it's pretty cool and different from both eth and solana)
  - improperly handing certain txn(transaction) types
    - I think having `exit(1)` as an entire contract lets anyone delete the contract bc it doesn't refuse `delete` txns
    - ^ still havem't actually tested this
  - blocking people from making a txn by filling storage limits
    - haven't tried this either, but fingers crossed
- Creating your own Blockchain challs
  - there currently(as of 2023) isn't a single overarching chall frameeowrk(there's one for solana, but I personally don't like only being able to interact one txn at a time + no sdk)
  - how to set up your chain's choice of node/validator/etc, how to prevent players from making certain rpc calls, how to ensure player's can pay txn fees, checking the chall contract off state to give players a flag
