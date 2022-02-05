# Wealth Bear Token List
## Overview
<p><img src="https://wealthbear.app/assets/img/github-header.png"></p>

The Wealth Bear Token List is a list of Binance Smart Chain tokens that are available in the Wealth Bear Wallet app.

## How to add your token

### Quick starter

**Adding an BEP20 token checklist**:
- [ ] Fork the App-Token-List repository.
- [ ] Create a folder and make the name equivalent to the token contract address in checksum format `assets/<token_contract_address>/`.
- [ ] *** MAKE SURE THE FOLDER NAME IS IN CHECKSUM FORMAT *** https://ethsum.netlify.app/ .
- [ ] Token image must be in PNG format with extension ending in `.png`. Avoid transparent backgrounds, recommended image size is 256px x 256px max.
- [ ] Add your logo file named `logo.png` to the previously created folder. If done correctly your path should look like this. `assets/0x1234567461d3f8Db7496581774Bd869C83D51c93/logo.png`.
- [ ] Edit the tokenlist.json file. Add your token info in the format shown below.
- [ ] Create a PR to be added to the list.

Please do take a moment to look at an existing project to view how best to integrate into our list.

#### Tokenlist JSON Format
```
},
{
    "name": "Wealth Bear",
    "symbol": "WLTH",
    "contract_address": "0x98C09FA6DaEbeCaf24FB4DF1C7c1AdE0dC0d8155",
    "decimals": 18,
    "logo_url": "https://raw.githubusercontent.com/wealth-token/App-Token-List/master/assets/0x98C09FA6DaEbeCaf24FB4DF1C7c1AdE0dC0d8155/logo.png"
},
```

The logo_url value should match `https://raw.githubusercontent.com/wealth-token/App-Token-List/master/assets/checksum_address/logo.png` to match the folder your submitted.

Make sure there is a comma separating your JSON entry from the next. If you add your entry to the end of the list, do not add a trailing comma.

## Disclaimer
* Wealth Bear allows anyone to submit new assets to this repository. However, this does not mean that we are in partnership with the projects.
* Wealth Bear will reject projects that are deemed as scam or fraudulent after careful review.
* Wealth Bear reserves the right to reject any project for any reason from listing on this platform.
