# Oasis Assets Info

## Overview
Oasis token repository is a comprehensive, up-to-date collection of information about several thousands (!) of crypto tokens.

[Oasis](https://wonderwall.finance) uses token logos from this source, alongside a number of other projects.

The repository contains token info from several blockchains.
For every token a logo and optional additional information is available (such data is not available on-chain).

Such a large collection can be maintained only through a community effort, so _feel free to add your token_.

<center><img src='https://wonderwall.finance/150x150.png' height="100"></center>

## How to add token

Please note that __brand new tokens are not accepted__,
the projects have to be sound, with information available, and __non-minimal circulation__.

### Quick starter

Here is a quick starter summary for the most common use case.

**Adding an ERC20/BEP20 token checklist**:
- [ ] Make sure your smartcontract has more than 1,000 address holders and at least 2000 transactions, otherwise you will be rejected
- [ ] Fork the Github repository
- [ ] Create folder with name of token smartcontact address in **checksum format**, with mixed lowercase and uppercase letters, such as `0xd9c99510a5e3145359d91fe9caf92dd5d68b603a`. Non-checksum addresses (e.g. all lowercase) are considered invalid. `bsc/assets/<token_smartcontract_address>/`.
- [ ] Tell your designer that token image must be in PNG format, recommended size 256x256px, max. 512x512px, with max file size of 100kB, please, optimize your image with service called [tinypng](https://tinypng.com/).
- [ ] Upload your logo with file named `logo.png` to previously created folder with smartcontract address, and if you done all correctly your path should look like this. `bsc/assets/0xd9c99510a5e3145359d91fe9caf92dd5d68b603a/logo.png`
- [ ] Create `info.json` file with info about the token/project
- [ ] Create a pull request to the main repo

## Disclaimer
Oasis team allows anyone to submit new assets to this repository. However, this does not mean that we are in direct partnership with all of the projects.

Oasis team will reject projects that are deemed as scam or fraudulent after careful review.
Oasis team reserves the right to change the terms of asset submissions at any time due to changing market conditions, risk of fraud, or any other factors we deem relevant.
