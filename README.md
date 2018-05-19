Bitcore-Ulord Library
=======

[![NPM Package](https://img.shields.io/npm/v/bitcore-lib-ulord.svg?style=flat-square)](https://www.npmjs.org/package/bitcore-lib-ulord)
[![Build Status](https://img.shields.io/travis/UlordChain/bitcore-lib-ulord.svg?branch=master&style=flat-square)](https://travis-ci.org/UlordChain/bitcore-lib-ulord)
[![Coverage Status](https://img.shields.io/coveralls/UlordChain/bitcore-lib-ulord.svg?style=flat-square)](https://coveralls.io/github/UlordChain/bitcore-lib-ulord?branch=master)

A pure and powerful JavaScript Ulord library.

## Principles

Ulord is a powerful new peer-to-peer platform for the next generation of financial technology. The decentralized nature of the Ulord network allows for highly resilient ulord infrastructure, and the developer community needs reliable, open-source tools to implement ulord apps and services.

## Get Started

```
git clone https://github.com/UlordChain/bitcore-lib-ulord.git
```

## Documentation

The complete docs are hosted here: [bitcore documentation](http://bitcore.io/guide/). There's also a [bitcore API reference](http://bitcore.io/api/) available generated from the JSDocs of the project, where you'll find low-level details on each bitcore utility.

- [Read the Developer Guide](http://bitcore.io/guide/)
- [Read the API Reference](http://bitcore.io/api/)

To get community assistance and ask for help with implementation questions, please use our [community forums](https://forum.bitcore.io/).

## Examples

* [Generate a random address](https://github.com/UlordChain/bitcore-lib-ulord/blob/master/docs/examples.md#generate-a-random-address)
* [Generate a address from a SHA256 hash](https://github.com/UlordChain/bitcore-lib-ulord/blob/master/docs/examples.md#generate-a-address-from-a-sha256-hash)
* [Import an address via WIF](https://github.com/UlordChain/bitcore-lib-ulord/blob/master/docs/examples.md#import-an-address-via-wif)
* [Create a Transaction](https://github.com/UlordChain/bitcore-lib-ulord/blob/master/docs/examples.md#create-a-transaction)
* [Sign a Ulord message](https://github.com/UlordChain/bitcore-lib-ulord/blob/master/docs/examples.md#sign-a-bitcoin-message)
* [Verify a Ulord message](https://github.com/UlordChain/bitcore-lib-ulord/blob/master/docs/examples.md#verify-a-bitcoin-message)
* [Create an OP RETURN transaction](https://github.com/UlordChain/bitcore-lib-ulord/blob/master/docs/examples.md#create-an-op-return-transaction)
* [Create a 2-of-3 multisig P2SH address](https://github.com/UlordChain/bitcore-lib-ulord/blob/master/docs/examples.md#create-a-2-of-3-multisig-p2sh-address)
* [Spend from a 2-of-2 multisig P2SH address](https://github.com/UlordChain/bitcore-lib-ulord/blob/master/docs/examples.md#spend-from-a-2-of-2-multisig-p2sh-address)


## Security

We're using Bitcore in production, as are [many others](http://bitcore.io#projects), but please use common sense when doing anything related to finances! We take no responsibility for your implementation decisions.

If you find a security issue, please email security@bitpay.com.


## Building the Browser Bundle

To build a bitcore-lib-ulord full bundle for the browser:

```sh
gulp browser
```

This will generate files named `bitcore-lib-ulord.js` and `bitcore-lib-ulord.min.js`.

You can also use our pre-generated files, provided for each release along with a PGP signature by one of the project's maintainers. To get them, checkout a release commit (for example, https://github.com/UlordChain/bitcore-lib-ulord/commit/e33b6e3ba6a1e5830a079e02d949fce69ea33546 for v0.12.6).

To verify signatures, use the following PGP keys:
- @braydonf: https://pgp.mit.edu/pks/lookup?op=get&search=0x9BBF07CAC07A276D `D909 EFE6 70B5 F6CC 89A3 607A 9BBF 07CA C07A 276D`
- @gabegattis: https://pgp.mit.edu/pks/lookup?op=get&search=0x441430987182732C `F3EA 8E28 29B4 EC93 88CB  B0AA 4414 3098 7182 732C`
- @kleetus: https://pgp.mit.edu/pks/lookup?op=get&search=0x33195D27EF6BDB7F `F8B0 891C C459 C197 65C2 5043 3319 5D27 EF6B DB7F`
- @matiu: https://pgp.mit.edu/pks/lookup?op=get&search=0x9EDE6DE4DE531FAC `25CE ED88 A1B1 0CD1 12CD  4121 9EDE 6DE4 DE53 1FAC`


## Development & Tests

```sh
git clone https://github.com/UlordChain/bitcore-lib-ulord
cd bitcore-lib-ulord
npm install
```

Run all the tests:

```sh
gulp test
```

You can also run just the Node.js tests with `gulp test:node`, just the browser tests with `gulp test:browser`
or create a test coverage report (you can open `coverage/lcov-report/index.html` to visualize it) with `gulp coverage`.

## License

Code released under [the MIT license](https://github.com/UlordChain/bitcore-lib-ulord/blob/master/LICENSE).

Copyright 2013-2015 BitPay, Inc. Bitcore is a trademark maintained by BitPay, Inc.
Copyright 2016 The Ulord Foundation, Inc.
