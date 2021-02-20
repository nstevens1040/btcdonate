# btcdonate
**Webpage for Bitcoin donations**  

The actual github-pages website is here --> [https://nstevens1040.github.io/btcdonate](https://nstevens1040.github.io/btcdonate)  

The webpage is integrated with [https://coinpayments.com](https://coinpayments.com) for payment processing and exchange rate retrieval.  

API calls are handled by my webserver. This amounts to retrieving the exchange rate as well as the donate button callback that sets up the transaction and returns the link to [coinpayments.com](coinpayments.com)  
## Features
   - The exchange rate is live and updates every 5 seconds.  
   - Typing a Bitcoin amount automatically calculates the dollar amount.  
   - Typing in a dollar amount automatically calculates the Bitcoin amount.  
