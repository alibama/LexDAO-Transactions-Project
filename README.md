# LexDAO-Transactions-Project
The file connects to the etherscan API and pulls all transactions for a single wallet along with some minor formatting of the structured data.  In this case it is coded to pull the ethereum transactions from the LexDAO Main Wallet.




# Citations
**The primary source for this exercise was this youtube video with minor edits to the code** 
  - **Tutorial Video:** https://www.youtube.com/watch?v=x5FHbr0Em5A
    - Title: Track Ethereum Transactions and Balance Using Python)
    - Author: Tech With Tim 
  - **Etherscan API Endpoint Documentation:** https://docs.etherscan.io/api-endpoints/accounts
    - Title: Build Precise & Reliable Apps with Etherscan APIs
    - Author: Etherscan.io


# Security Considerations
These scripts use a config.py file stored locally to manage API credentials as well as a base .gitignore when pushing to the repository. You will need to create one in your local git root directory for this to work.  In most tutorials, they leave out instructions on how to properly store passwords and sensitive info like API keys.

**API Keys:** These materials were used to help with the configuration of API keys so that they are stored securely on your local drive and not pushed to the public github respositories.  It was done after the implementation of the above function.**
  -  https://www.youtube.com/watch?v=CJjSOzb0IYs&list=PLs_I47UaWbn5ufaFWD_k9TU8jRxfJGrr0
  -  https://medium.com/@jameld.pro/secure-your-api-keys-b123f30ac014
  
**.gitignore File:** This documentation helps explain what a .gitignore file is for and why it is important before pushing code to a public repository
  - https://git-scm.com/docs/gitignore
