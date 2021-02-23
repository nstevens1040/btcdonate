# btcdonate
**Webpage for Bitcoin donations**  

The actual github-pages website is here --> [https://nstevens1040.github.io/btcdonate](https://nstevens1040.github.io/btcdonate)  

The webpage calls api endpoints **/ticker** and **/q/getreceivedbyaddress** hosted on [https://blockchain.info](https://blockchain.info) for exchange rate retrieval and for detecting a change in my Bitcoin balance, respectively.  

My P2SH Bitcoin receiving address is hard coded into the webpage.  

## Features
   - The exchange rate is live and updates every 5 seconds.  
   - Typing a Bitcoin amount automatically calculates the dollar amount.  
   - Typing in a dollar amount automatically calculates the Bitcoin amount.  
