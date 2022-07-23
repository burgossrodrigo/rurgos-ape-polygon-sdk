# QuickSwap SDK

This repository has been forked from [UniswapV2](https://github.com/Uniswap/uniswap-sdk)
It was updated from @burgossrodrigo to solve the init_code_hash issue and a couple other things.

## Running tests

To run the tests, follow these steps. You must have at least node v10 and [yarn](https://yarnpkg.com/) installed.

First clone the repository:

```sh
git clone https://github.com/QuickSwap/QuickSwap-sdk.git
```

Move into the quickswap-sdk working directory

```sh
cd QuickSwap-sdk/
```

Install dependencies

```sh
yarn install
```

Run tests

```sh
yarn test
```

You should see output like the following:

```sh

> tsdx test

 PASS  test/constants.test.ts
  ● Console

    console.log test/constants.test.ts:10
      0x96e8ac4277198ff8b6f785478aa9a39f403cb768dd02cbee326c3e7da348845f

 PASS  test/token.test.ts
 PASS  test/router.test.ts
 PASS  test/fraction.test.ts
 PASS  test/miscellaneous.test.ts
 PASS  test/trade.test.ts
 PASS  test/entities.test.ts
 PASS  test/route.test.ts
 PASS  test/pair.test.ts (5.081s)

Test Suites: 1 skipped, 9 passed, 9 of 10 total
Tests:       3 skipped, 124 passed, 127 total
Snapshots:   0 total
Time:        7.246s
Ran all test suites.
```
