# MetaMask developer documentation

This is the MetaMask developer documentation repository.
The documentation site is hosted at [`docs.metamask.io`](https://docs.metamask.io), and it's
built using [Docusaurus](https://docusaurus.io/), a static site generator purpose-built for
technical documentation.

## Build locally

Build the documentation site locally using the following steps.

### Prerequisites

- [Node.js](https://nodejs.org/) version 18+
- [Git](https://git-scm.com/)

### Steps

1. Clone the repository.

   ```bash
   git clone https://github.com/MetaMask/metamask-docs.git
   cd metamask-docs
   ```

   > **Note:** If you don't have write access to this repository, you must [fork the repository](https://docs.github.com/en/get-started/quickstart/fork-a-repo#forking-a-repository) to your personal account and clone your forked repository instead. [Add an upstream remote](https://docs.github.com/en/get-started/quickstart/fork-a-repo#configuring-git-to-sync-your-fork-with-the-upstream-repository) to be able to pull from and push to the original repository.
   >
   > ```bash
   > git clone https://github.com/<YOUR-USERNAME>/metamask-docs.git
   > cd metamask-docs
   > git remote add upstream https://github.com/MetaMask/metamask-docs.git
   > ```

2. Install dependencies.

   ```bash
   npm install
   ```

3. Start the development server.

   ```bash
   npm start
   ```

   Once the server starts, you can view the documentation at `http://localhost:3000`.

For more information on contributing to the documentation, see the [full contribution guidelines](CONTRIBUTING.md).
{
  "success": true,
  "statusCode": 200,
  "result": {
    "originChainId": 42161,
    "destinationChainId": 10,
    "receiverAddress": "0xd8dA6BF26964aF9D7eEd9e03E53415D37aA96045",
    "userAddress": "0xd8dA6BF26964aF9D7eEd9e03E53415D37aA96045",
    "input": {
      "token": {
        "chainId": 42161,
        "address": "0xaf88d065e77c8cC2239327C5EDb3A432268e5831",
        "name": "USD Coin",
        "symbol": "USDC",
        "decimals": 6,
        "logoURI": "https://assets.coingecko.com/coins/images/6319/large/usdc.png?1696506694",
        "icon": "https://assets.coingecko.com/coins/images/6319/large/usdc.png?1696506694"
      },
      "amount": "1000000",
      "priceInUsd": 1,
      "valueInUsd": 1
    },
    "destinationExec": {
      "destinationPayload": "0x",
      "destinationGasLimit": "0"
    },
    "autoRoute": {
      "userOp": "sign",
      "requestHash": "0xd7d158ed55b5d3b5e19bff46044243214ee66113271b210606b5962e769be9c6",
      "output": {
        "token": {
          "chainId": 42161,
          "address": "0xaf88d065e77c8cC2239327C5EDb3A432268e5831",
          "name": "USD Coin",
          "symbol": "USDC",
          "decimals": 6,
          "logoURI": "https://assets.coingecko.com/coins/images/6319/large/usdc.png?1696506694",
          "icon": "https://assets.coingecko.com/coins/images/6319/large/usdc.png?1696506694"
        },
        "amount": "940737",
        "priceInUsd": 1,
        "valueInUsd": 0.940737,
        "minAmountOut": "936033",
        "effectiveReceivedInUsd": 0.940737
      },
      "requestType": "SINGLE_OUTPUT_REQUEST",
      "approvalData": {
        "spenderAddress": "0x3a23F943181408EAC424116Af7b7790c94Cb97a5",
        "amount": "1000000",
        "tokenAddress": "0xaf88d065e77c8cc2239327c5edb3a432268e5831",
        "userAddress": "0xd8dA6BF26964aF9D7eEd9e03E53415D37aA96045"
      },
      "affiliateFee": {
        "token": {
          "chainId": 42161,
          "address": "0xaf88d065e77c8cC2239327C5EDb3A432268e5831",
          "name": "USD Coin",
          "symbol": "USDC",
          "decimals": 6,
          "logoURI": "https://assets.coingecko.com/coins/images/6319/large/usdc.png?1696506694",
          "icon": "https://assets.coingecko.com/coins/images/6319/large/usdc.png?1696506694"
        },
        "amount": "2585",
        "feeTakerAddress": "0xd8dA6BF26964aF9D7eEd9e03E53415D37aA96045"
      },
      "signTypedData": {
        "domain": {
          "name": "Permit2",
          "chainId": 42161,
          "verifyingContract": "0x000000000022D473030F116dDEE9F6B43aC78BA3",
          "version": "1",
          "salt": "0xabcdef"
        },
        "types": {},
        "values": {}
      },
      "gasFee": {
        "gasToken": {
          "chainId": 42161,
          "address": "0xaf88d065e77c8cC2239327C5EDb3A432268e5831",
          "name": "USD Coin",
          "symbol": "USDC",
          "decimals": 6,
          "logoURI": "https://assets.coingecko.com/coins/images/6319/large/usdc.png?1696506694",
          "icon": "https://assets.coingecko.com/coins/images/6319/large/usdc.png?1696506694"
        },
        "gasLimit": "567600",
        "gasPrice": "10000000",
        "estimatedFee": "5676000000000",
        "feeInUsd": 0.0090168936
      },
      "slippage": 0.5,
      "suggestedClientSlippage": 0.5,
      "txData": {
        "data": "0x0000019f792ebcb9000...00000",
        "to": "0x3a23F943181408EAC424116Af7b7790c94Cb97a5",
        "chainId": 42161,
        "value": "0x00"
      },
      "estimatedTime": 10,
      "routeDetails": {
        "name": "Bungee Protocol",
        "logoURI": "https://miro.medium.com/max/800/1*PN_F5yW4VMBgs_xX-fsyzQ.png",
        "routeFee": {
          "token": {
            "chainId": 42161,
            "address": "0xaf88d065e77c8cC2239327C5EDb3A432268e5831",
            "name": "USD Coin",
            "symbol": "USDC",
            "decimals": 6,
            "logoURI": "https://assets.coingecko.com/coins/images/6319/large/usdc.png?1696506694",
            "icon": "https://assets.coingecko.com/coins/images/6319/large/usdc.png?1696506694"
          },
          "amount": "2585",
          "feeInUsd": 0.002584,
          "priceInUsd": 1
        },
        "dexDetails": {
          "protocol": {
            "name": "openocean",
            "displayName": "OpenOcean",
            "icon": "https://media.socket.tech/dexes/openocean.png"
          },
          "minAmountOut": "36400217",
          "outputTokenAddress": "0xaf88d065e77c8cc2239327c5edb3a432268e5831",
          "inputTokenAddress": "0xeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeee",
          "amountOut": "36583133",
          "slippage": 0.5
        }
      },
      "refuel": {
        "input": {
          "token": {
            "chainId": 42161,
            "address": "0xaf88d065e77c8cC2239327C5EDb3A432268e5831",
            "name": "USD Coin",
            "symbol": "USDC",
            "decimals": 6,
            "logoURI": "https://assets.coingecko.com/coins/images/6319/large/usdc.png?1696506694",
            "icon": "https://assets.coingecko.com/coins/images/6319/large/usdc.png?1696506694"
          },
          "amount": "1000000"
        },
        "output": {
          "token": {
            "chainId": 42161,
            "address": "0xaf88d065e77c8cC2239327C5EDb3A432268e5831",
            "name": "USD Coin",
            "symbol": "USDC",
            "decimals": 6,
            "logoURI": "https://assets.coingecko.com/coins/images/6319/large/usdc.png?1696506694",
            "icon": "https://assets.coingecko.com/coins/images/6319/large/usdc.png?1696506694"
          },
          "amount": "1000000"
        }
      },
      "quoteId": "8d093296d3014fb588dc5e3fc359be56",
      "quoteExpiry": 1745927101,
      "rewards": {
        "rebateAmount": "10000",
        "rewardAmount": "20000",
        "totalRewardAmount": "30000",
        "totalRewardAmountInUsd": 0.03,
        "token": {
          "chainId": 42161,
          "address": "0xaf88d065e77c8cC2239327C5EDb3A432268e5831",
          "name": "USD Coin",
          "symbol": "USDC",
          "decimals": 6,
          "logoURI": "https://assets.coingecko.com/coins/images/6319/large/usdc.png?1696506694",
          "icon": "https://assets.coingecko.com/coins/images/6319/large/usdc.png?1696506694"
        },
        "isRewardEnabled": true
      }
    },
    "manualRoutes": [
      {
        "quoteId": "dbea14bb-d693-4fcb-8c8b-5c124258a96b",
        "output": {
          "token": {
            "chainId": 42161,
            "address": "0xaf88d065e77c8cC2239327C5EDb3A432268e5831",
            "name": "USD Coin",
            "symbol": "USDC",
            "decimals": 6,
            "logoURI": "https://assets.coingecko.com/coins/images/6319/large/usdc.png?1696506694",
            "icon": "https://assets.coingecko.com/coins/images/6319/large/usdc.png?1696506694"
          },
          "amount": "940737",
          "priceInUsd": 1,
          "valueInUsd": 0.940737,
          "minAmountOut": "936033",
          "effectiveReceivedInUsd": 0.940737
        },
        "affiliateFee": {
          "token": {
            "chainId": 42161,
            "address": "0xaf88d065e77c8cC2239327C5EDb3A432268e5831",
            "name": "USD Coin",
            "symbol": "USDC",
            "decimals": 6,
            "logoURI": "https://assets.coingecko.com/coins/images/6319/large/usdc.png?1696506694",
            "icon": "https://assets.coingecko.com/coins/images/6319/large/usdc.png?1696506694"
          },
          "amount": "2585",
          "feeTakerAddress": "0xd8dA6BF26964aF9D7eEd9e03E53415D37aA96045"
        },
        "approvalData": {
          "spenderAddress": "0x3a23F943181408EAC424116Af7b7790c94Cb97a5",
          "amount": "1000000",
          "tokenAddress": "0xaf88d065e77c8cc2239327c5edb3a432268e5831",
          "userAddress": "0xd8dA6BF26964aF9D7eEd9e03E53415D37aA96045"
        },
        "gasFee": {
          "gasToken": {
            "chainId": 42161,
            "address": "0xaf88d065e77c8cC2239327C5EDb3A432268e5831",
            "name": "USD Coin",
            "symbol": "USDC",
            "decimals": 6,
            "logoURI": "https://assets.coingecko.com/coins/images/6319/large/usdc.png?1696506694",
            "icon": "https://assets.coingecko.com/coins/images/6319/large/usdc.png?1696506694"
          },
          "gasLimit": "567600",
          "gasPrice": "10000000",
          "estimatedFee": "5676000000000",
          "feeInUsd": 0.0090168936
        },
        "slippage": 0.5,
        "estimatedTime": 60,
        "routeDetails": {
          "name": "Bungee Protocol",
          "logoURI": "https://miro.medium.com/max/800/1*PN_F5yW4VMBgs_xX-fsyzQ.png",
          "routeFee": {
            "token": {
              "chainId": 42161,
              "address": "0xaf88d065e77c8cC2239327C5EDb3A432268e5831",
              "name": "USD Coin",
              "symbol": "USDC",
              "decimals": 6,
              "logoURI": "https://assets.coingecko.com/coins/images/6319/large/usdc.png?1696506694",
              "icon": "https://assets.coingecko.com/coins/images/6319/large/usdc.png?1696506694"
            },
            "amount": "2585",
            "feeInUsd": 0.002584,
            "priceInUsd": 1
          },
          "dexDetails": {
            "protocol": {
              "name": "openocean",
              "displayName": "OpenOcean",
              "icon": "https://media.socket.tech/dexes/openocean.png"
            },
            "minAmountOut": "36400217",
            "outputTokenAddress": "0xaf88d065e77c8cc2239327c5edb3a432268e5831",
            "inputTokenAddress": "0xeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeee",
            "amountOut": "36583133",
            "slippage": 0.5
          }
        },
        "refuel": {
          "input": {
            "token": {
              "chainId": 42161,
              "address": "0xaf88d065e77c8cC2239327C5EDb3A432268e5831",
              "name": "USD Coin",
              "symbol": "USDC",
              "decimals": 6,
              "logoURI": "https://assets.coingecko.com/coins/images/6319/large/usdc.png?1696506694",
              "icon": "https://assets.coingecko.com/coins/images/6319/large/usdc.png?1696506694"
            },
            "amount": "1000000"
          },
          "output": {
            "token": {
              "chainId": 42161,
              "address": "0xaf88d065e77c8cC2239327C5EDb3A432268e5831",
              "name": "USD Coin",
              "symbol": "USDC",
              "decimals": 6,
              "logoURI": "https://assets.coingecko.com/coins/images/6319/large/usdc.png?1696506694",
              "icon": "https://assets.coingecko.com/coins/images/6319/large/usdc.png?1696506694"
            },
            "amount": "1000000"
          }
        }
      }
    ]
  }
}
