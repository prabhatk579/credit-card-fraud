Credit card fraud analysis and classification
===

Credit card fraud is increasing with time as people become familiar with the functioning of the Automated Telle Machine (ATM). The analysis of the transactions plays a crucial role in finding the root cause of the fraudulent transactions. Classification of such transactions can help banks reduce the losses from fraudulent transactions by putting a flag for every transaction and looking into the transactions manually.

The dataset used has 11 features; Which are as follows:

- **step -** maps a unit of time in the real world. In this case, 1 step is 1 hour—a total of steps 744 (30 days of simulation).

- **type -** CASH-IN, CASH-OUT, DEBIT, PAYMENT, and TRANSFER.

- **amount -** amount of the transaction in local currency.

- **nameOrig -** customer who started the transaction

- **oldbalanceOrg -** initial balance before the transaction

- **newbalanceOrig -** new balance after the transaction

- **nameDest -** customer who is the recipient of the transaction

- **oldbalanceDest -** initial balance recipient before the transaction. Note that there is no information for customers that start with M (Merchants).

- **newbalanceDest -** new balance recipient after the transaction. Note that there is no information for customers that start with M (Merchants).

- **isFraud -** This is the transactions made by the fraudulent agents inside the simulation. In this specific dataset, the fraudulent behavior of the agents aims to profit by taking control of customers' accounts and trying to empty the funds by transferring them to another account and then cashing out of the system.

- **isFlaggedFraud -** The business model aims to control massive transfers from one account to another and flags illegal attempts. An illegal attempt in this dataset is an attempt to transfer more than 200.000 in a single transaction.
