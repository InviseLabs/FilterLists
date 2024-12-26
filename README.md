# FilterLists  
Curated and custom modified adblock filterlists by Invise Labs, created for several unique purposes, such as whitelisting important domains that lists you add might clock, or lists blocking coinmining. These lists are often curated and merged from other lists to create the best experience possible. piHole, AdGuard, and other adblockers have performance issues when importing too many lists. We are aiming to create merged lists for specific categories. 
<br>
<br>
### WhiteList.txt: Safe Whitelisting for different common services and apps.
Here we attempt to unblock and whitelist domains that are safe and requried for many common apps and services without allowing telemetry.

### BlockCoin.txt: Blocks Coin Mining
We have fohnd that many sites using JS-based coin mining craft it to use only 5 to 20% CPU, so that the mining operation remaims undetected. We have found no real way to detect these occurrences, thus we propose that coin mining be blocked by default in the future. Those wishing to utilize mining could either explicitly disable the blocking or allow that local IP.  

BlockCoin.txt is merged from the following lists:  
https://github.com/black7375/MineBlockFilter/blob/master/MinerBlocker.txt  
https://github.com/hoshsadiq/adblock-nocoin-list/blob/master/nocoin.txt  
https://gist.github.com/jordan-wright/95af062378e9a7436b94f893d195bcd2#file-cryptocurrency_mining_list-txt 
https://gitlab.com/ZeroDot1/CoinBlockerLists/raw/master/list.txt

<br>
<b>HOSTS Only</b>
https://raw.githubusercontent.com/hoshsadiq/adblock-nocoin-list/master/hosts.txt  
<br>
Possible tool to crawl web and generate most lists and blockable elements:<br>
https://github.com/sou-predictable/Crypto-Census


#### Invise Labs Team:

Check and add these sources:

No Miners - https://github.com/Shaa3/nominers

Mining Blocker - http://mining-blocker.com/

NoMiner - https://mybrowseraddon.com/block-miners.html

Coin-Blocker - https://github.com/Brandon-T/Coin-Blocker (Will Added.)

MinerBlock - https://addons.mozilla.org/en-US/firefox/addon/minerblock-no-coin-miners/

No Coin - https://github.com/keraf/NoCoin

CoinBlock - https://addons.mozilla.org/en-US/firefox/addon/coinblock/

AntiMiner - https://addons.mozilla.org/en-US/firefox/addon/antiminer-1-coin-minerblock/
