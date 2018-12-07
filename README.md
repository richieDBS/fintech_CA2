# fintech_CA2
**DLT – CA2 – Solidity Project** 
 
**The Idea** 

A client has established a Regular Savings contract with a Life Assurer. He’s been saving on an ongoing basis and has accrued exactly €1,500, split equally between 3 sub-Wallets. The savings come from his personal account, called Cash Wallet A, which at this point contains €150,000. The amount in this Wallet is receiving no Yield. 

At this point the Life Assurance Company in question has a balance of €1,000,000 in its Capital Wallet. 
 
The client can save €150 per month using this Regular Savings Contract with the hope of reaching a Target Amount of €90,000. 
The monthly contributions are equally split into 3 different asset types, each contained in its own sub-Wallet of the Capital Wallet: 

**Sub-Wallet Type:** Equity Wallet; Property Wallet; Bonds Wallet

**Annualised Growth Rate:** 8%; 4%; 2% 
 
Upon reaching the target of €90,000 half the assets are encashed to another personal account, called a Cash Wallet B… 
…which is separate completely from both the Capital Wallet and Cash Wallet A.  

The idea here being to ‘lock in’ some of the value of the savings. 
 
- How long (in months) will it take for the Savings Contract to breach €90,000? 
- Display the Amounts in all Wallets. 
 
**The Smart Contract’s Intention**

The aim of the Smart Contract is to execute a regular transaction and move assets from one wallet to another. 
Monies are moving from Cash Wallet A into 3 Wallets:

- Equity Wallet 
- Property Wallet  
- Bonds Wallet 
 
These 3 Wallets are sub-wallets of the Life Assurance Company’s Capital Wallet. So, as these increase in value, so too does the Capital Wallet of the Life Assurance Company. Upon breaching the trigger of €90,000 between the 3 sub-wallets, half the assets of these wallets are to move to Cash Wallet B. 
 
**Inventory** 

Cash Wallet A 

Cash Wallet B 

**Capital Wallet (including sub-wallets)** 

- **Sub 1:** Equity Wallet 

- **Sub 2:** Property Wallet 

- **Sub 3:** Bond Wallet 
 
**At the Outset:**  

**Client:**

- Cash Wallet A - €150,000 

- Cash Wallet B - €0

**Life Assurance Company:**

- Capital Wallet - €1,000,000 

Included within this is: 

- Equity Wallet - €500 
- Property Wallet - €500 
- Bonds Wallet - €500 
