# AgroChain

This repository hosts a Dapp (Decentralized Application) focused on Agricultural Supply Chain with integrated Micro-Finance features. The code is written in Truffle and Solidity. The underlying blockchain is a private Ethereum network established using Geth (go-ethereum), and the interactions are facilitated through the Web3 JavaScript library.
## problems to be solved
The Agricultural Supply Chain system aims to trace a farm product's journey from the farmer to the consumer. In developing countries, farmers heavily rely on bank loans, which often leads to crippling debt and unstable agricultural production. Micro-finance presents a solution to alleviate this debt burden.

In the context of the agro-market, recent incidents of farmer suicides highlight the pressing issues they face. With a growing population, there's increasing pressure on land for housing and industrial purposes, reducing available fertile land for farming. This puts a higher demand on farmers to produce more, yet they grapple with challenges such as:

1. Difficulty in securing initial investments for field setup due to high bank interest rates.
2. Struggles to obtain fair prices for their produce due to middlemen's involvement in the market.
3. Lack of access to market trends and customer preferences, with middlemen acting as intermediaries.
4. Inefficient supply chain, storage, and transportation leading to crop deterioration.

Customers, on the other hand, are concerned about the high prices of commodities and the quality of produce. They often have to buy whatever is available in the market at prices set by sellers. Unscrupulous practices like black marketing, hoarding, and adulteration further inflate prices. Despite the increasing demand for organic products, there's a lack of a robust system to trace the stages of organic cultivation and verify authenticity. The main challenge in agro-markets lies in the significant 'disconnect' between farmers and consumers.



## Our solution to the problem:
Agrochain is a blockchain-based marketplace that promotes cooperative farming between farmers and consumers. Farmers can list their crops and expected yields on a public ledger, allowing consumers to assess their credibility based on previous cultivation and supply records. This establishes a transparent and tamper-proof digital market for farm products. Through consensus, consumers can fund individual crops or fields and receive a share of the yield or profit.

Key advantages include:

1. Farmers can bypass the need for bank loans, as consumers can provide funding at zero interest.

2. Consumers have access to high-quality products at lower rates, supporting crops from their early stages of cultivation.

3. Even small-scale and household farmers can sell their products and achieve better profits.

4. A streamlined supply chain is ensured with real-time updates on immutable ledgers, allowing customers to choose specific farmers for specific products.

5. Farmers can build consumer loyalty through quality products and specific farming practices, ultimately leading to increased profits.

6. Low-income consumers can fund crops based on their needs, avoiding market price fluctuations.

7. Organic farming and quality standards are upheld through regular inspections by relevant authorities, thanks to the transparency of the immutable ledger.

8. Smart contracts provide a robust framework for resolving discrepancies arising from natural disasters, climate changes, or crop losses.

In the end, Agrochain aims to create a decentralized agro-market where farmers can easily secure funding for cultivation while having committed customers for their produce. Consumers can ensure quality products at a lower cost by investing early in crops. Both parties stand to profit and foster a loyal environment for future cooperation. The best farmers will maximize their profits, and the most successful investors (consumers) will have access to high-quality food for their homes.



![Alt text](https://github.com/nikhilvc1990/AgriChain/blob/master/screenshots/Farmer%20Registration%20Page.PNG?raw=true "Farmer Registration")

The above figure shows the registration form for the farmer in the supply chain application. The entered details are stored directly onto the blockchain. The underlying technology uses Truffle for the deployment and go-ethereum(geth) as the backend blockchain. We use the Web3 Javascript provider API to interact with the blockchain.

![Alt text](https://github.com/nikhilvc1990/AgriChain/blob/master/screenshots/Quality.PNG?raw=true "Farmer Registration")

The next page is for quality testing, here we can get the farmer details by Farmer Id. These details are stored as a structure using solidity code onto the blockchain. The Farmer details are retrieved using a special data structure called mapping by Farmer Id. 

![Alt text](https://github.com/nikhilvc1990/AgriChain/blob/master/screenshots/View%20Blocks.PNG?raw=true "Quality Testing")
This is the Quality Testing page.
Here we can see the block details where the farmer’s details are stored onto blockchain. The ‘Approve Details’ will approve the details of the farmer.

![Alt text](https://github.com/nikhilvc1990/AgriChain/blob/master/screenshots/QualityTestingProduct.PNG?raw=true "Product Testing")

Approve Details button click will redirect to this Product details page. This is also part of the quality testing where we enter the lot number, grade, price, test date and expiry date. These details are also stored in the blockchain as a structure.

![Alt text](https://github.com/nikhilvc1990/AgriChain/blob/master/screenshots/CustomerDetails.PNG?raw=true "Customer Details")

This is the customer page where the customer can check the customer details and status of the quality testing of his agriculture produce. The customer has to enter the farmer id and Lot number to see the details. These customer details are retrieved from the blockchain.

![Alt text](https://github.com/nikhilvc1990/AgriChain/blob/master/screenshots/Micro-Finance.PNG?raw=true "Micro-Finance")

The micro-finance form enables any user to fund a farmer. The funding is done by providing the farmers public id, the lot number of the product and the amount.






