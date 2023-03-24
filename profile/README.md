# 🧱 SentryChain

Welcome to SentryChain, an easy-to-use tool for auditing smart contracts.

SentryChain combines the features of three popular security audit tools: Slither, Mythril, and Securify.

## 🔧 Tools

### [Slither](https://github.com/crytic/slither) 👀

Slither is a static analysis tool that can detect a wide range of security vulnerabilities in smart contracts.

It has a simple command-line interface and can be easily integrated into a development workflow.

### [Mythril](https://github.com/ConsenSys/mythril) 🔍

Mythril is a symbolic execution tool that can detect complex security vulnerabilities in smart contracts.

It can be used to identify vulnerabilities such as reentrancy attacks and can be integrated with other tools such as Slither.

### [Securify](https://github.com/eth-sri/securify2) 🔒

Securify is an automated security scanner that can identify a wide range of security vulnerabilities in smart contracts.

It has a user-friendly web interface and can be easily integrated into a development workflow.

## 💡 Features

SentryChain combines the features of Slither, Mythril, and Securify to create a comprehensive smart contract audit tool
that can detect a wide range of security vulnerabilities, including both simple and complex issues.

For example, we use Slither to quickly identify common vulnerabilities such as uninitialized variables,
and then Mythril to perform a more thorough analysis and detect more complex issues such as reentrancy attacks.
Finally, we use Securify to scan the code for any additional vulnerabilities and provide a user-friendly report of the results.

## 🚀 Getting Started

To get started with SentryChain, you will need to install the three underlying audit tools, Slither, Mythril, and Securify.

You can then install SentryChain using pip:

```
pip install sentrychain
```

Once installed, you can use SentryChain to audit your smart contracts:

```
sentrychain audit <contract_file>
```

## 🤝 Contributions

We welcome contributions to SentryChain. If you would like to contribute, please fork the repository and submit a pull request.

## 📝 License

SentryChain is released under the MIT License.
