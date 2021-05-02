# Unicly uToken Info

## Overview

By adding your uToken info on this repository, your uToken dashboard page will show your uToken's custom logo and appraisal link.

#### What is an appraisal?

A uToken collection appraisal is a PDF report (by a third party auditor) that estimates the value of the collection.

## How to add token

**Adding a uToken checklist**:
- [ ] Fork the Github repository
- [ ] Create folder with name of token smartcontact address in lowercase `uTokens/<token_smartcontract_address>/`.
- [ ] Tell your designer that token image must be in SVG format, with max file size of 100kB.
- [ ] Upload your logo with file named `logo.svg` to previously created folder with smartcontract address, and if you done all correctly your path should look like this. `uTokens/0x3d9233f15bb93c78a4f07b5c5f7a018630217cb3/logo.svg`
- [ ] Upload your appraisal with file named `appraisal.pdf` to previously created folder with smartcontract address, and if you done all correctly your path should look like this. `uTokens/0x3d9233f15bb93c78a4f07b5c5f7a018630217cb3/appraisal.pdf`
- [ ] Upload your metadata, including description and social media links. The file should be named `info.json`, and the path should look like this: `uTokens/0x3d9233f15bb93c78a4f07b5c5f7a018630217cb3/info.json`. Here is an example of a correctly formatted info.json:
```
{
  "description": "Genesis Unicly Collection by 0xLeia. More Unicly branded NFTs to be added later. This is NOT the UNIC token.",
  "telegram": "t.me/LeiaFisherOne",
  "twitter": "twitter.com/0xLeia",
  "medium": "https://medium.com/@0xleia",
  "discord": "discord.com/invite/uniclyNFT"
}
```
- [ ] Create a pull request to the main repo

## Disclaimer
Anyone can submit new assets to this repository. However, this does not mean that we are in direct partnership with all of or any of these projects.

We will reject uTokens that are deemed as scam or fraudulent after careful review. The Unicly community reserves the right to change the terms of asset submissions at any time due to changing market conditions, risk of fraud, or any other factors we deem relevant.
