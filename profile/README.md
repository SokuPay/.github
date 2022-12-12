# SokuPay
SokuPay for 2022 Magic Eden: Creator Monetization Hackathon.  
Buy NFT using QR code payment service(IoT x QR x NFT).  

![eyecatch](https://github.com/SokuPay/.github/blob/main/docs/eyecatch.png?raw=true)

## Overview
### Use case
Buy/Mint NFT at offline event space using QR code payment(SokuPay).  
And user can check mint histories(by [Coral Cube Royalty Tracking API](https://optemization.notion.site/optemization/Coral-Cube-Royalty-API-Documentation-4c37410d75ed40fe84ec212c82e33ac2) ) before buy NFT.

![payment page](https://github.com/SokuPay/.github/blob/main/docs/payment-page.png?raw=true)

### What is SokuPay?
- SokuPay aim to make profit for NFT creators and supporters in offline touch point.
- Get marketing data(User with QR payment histories. It doesn’t including personal information) when user pay via QR. That’s marketing data will be share to SokuPay DAO.
- SokuPay DAO members can use all of marketing data and reach to NFT creators/organizers.
- Members and DAO get dynamic fees(dynamic fees like Magic Eden Open Creator Protocol) when purchased NFT in SokuPay QR Payment.

## Docs
### Presentation
[Google Slides - SokuPay for 2022 Magic Eden Hackathon](https://docs.google.com/presentation/d/1mdb6xdxd8R6w7NMdYnHZXkawPnUKfFnZ2kEKPfcKn0g/edit?usp=sharing)

### Demo Video
- [YouTube - Demo1](https://youtu.be/h4S3OTznjkg)
- [YouTube - Demo2](https://youtu.be/zKCPMRjPHEY)

### Business Model
![business model](https://github.com/SokuPay/.github/blob/main/docs/business-model.png?raw=true)

### Tech
- Raspberry Pi x React
- Node x Express x TypeScript
- Solana Pay
- Coral Cube API
- QuickNode API

### System Overview
![system overview](https://github.com/SokuPay/.github/blob/main/docs/system-overview.png?raw=true)

## Source Code
- [iot](https://github.com/SokuPay/iot): (Raspberry Pi) load and show QR code to QR Device
- [frontend](https://github.com/SokuPay/frontend): (React) show QR code to Raspberr Pi
- [web3server](https://github.com/SokuPay/web3server): (Solana Pay) web3.js and business logic to frontend