# Wallet API

The as-of-yet unnamed wallet API will be a Go abstraction of a wallet for a given cryptocoin. It should abstract these operations:
* creating a new address
* checking the balance of a given address
* injecting a transaction to the network
* checking the status of a transaction

The wallet API will provide a Go binding, a REST API and a command line interface.

It will initially support Bitcoin and Skycoin. Support for additional cryptocoins can be implemented in Go.

## Terminology

briancaine note:

  so, I added this section in case we might want to clarify any terminology.

  I'm guessing we're using standard terminology but

  maybe we might need to (for technical reasons) clarify what we mean

  (ie, like, does a transaction include fees or not? do we want to clarify that somewhere?)

  if not, then we can just delete this section

## Go

### Library API

briancaine note: here's where we document the library interface

### Cryptocoin API

briancaine note: here's where we document implementing the specifics for a wallet for a given cryptocoin

## REST API

briancaine note: as above... where I'd document the rest API, including samples

## CLI

briancaine note: self explanatory
