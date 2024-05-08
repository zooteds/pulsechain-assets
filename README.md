# pulsechain-tokens

## A repository of standardised token metadata for Pulsechain open for all projects to use.

This project aims to provide a resource for developers and projects which can be be used as a substitute for other services which don't include Pulsechain data (Trustwallet etc...)

### Editing the data

Add token metadata and logo on this page: https://tokens.pls369.com/

Do no make an issue in this repository for adding or aditing token data.

### Using the data

This repository is the canonical version of the data. Secondary repositories with alternative naming and folder structure are also maintained. Instructions for integration can be found in the respective repositories.

Otterscan - https://github.com/PLS369/pulsechain-tokens-flat


** Hotlinking **
Given the data changes constantly we'd recommend hotlinking the images rather than forking this repo.
You can hotlink directly from the github like so:

https://raw.githubusercontent.com/PLS369/pulsechain-tokens-flat/main/pulsechain/0x0000000000085d4780B73119b644AE5ecd22b376.png

Depending on how you are using the data a better option is using jsDelivr - an Open Source CDN for Github. https://www.jsdelivr.com/github
It has a similar CDN as Github and offers similar speeds, but sets a might higher cache time for browsers - 30 days compared to 2 hours. For logos which are infrequently updated it would be more user friendly to have instruct their browsers to only redownload the image once a month rather than every few hours.

https://cdn.jsdelivr.net/gh/PLS369/pulsechain-tokens-flat@main/pulsechain/0x0000000000085d4780B73119b644AE5ecd22b376.png